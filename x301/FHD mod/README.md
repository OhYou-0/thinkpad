This mod uses the pre-existing LVDS to eDP bridge adapter cable thing for the T420/T430 (not s models, they use a flat flex for lvds)
I have tested this on a x301 and an x300. There is no reason it should not also work on a t400s. I may update this with other thinkpads it might work on. It does not work on a T400
You are limited to 1080p 16:9 panels, but you are not necesarily limited to the supported panels of the mod. Please consult schematics or ask around what works on the t420 as it should also work here
The n140hcg-gq2 should fit in the lid of the x301, I will find out tomorrow. I think others have tested it with the adapter before so it should probably work.

This mod chip that you receive can plug directly into the x301 as it uses the came connector. But it is wired completely differently and it will damage your thinkpad, the mod chip, and the lcd.
To be more clear, if you just take it out of the package and plug it in and turn on the laptop, you will directly short the backlight and blow the fuse, You will send 5v to a lvds - pin on the mod chip and panel. 
This mod will change the kit so that it no longer works on a T420 or T430, if you attempt to use it on one after this, you are dumb

The process to rewire the plug is very straightforward and requires very little soldering skills. It is more of a test of your fine motor skills. 
A quick summary of the work:

13 red 42awg shielded strand wires

16 blue 44awg shielded strand wires

of the red wires, 4 need the pin gender reversed

of the blue wires, 6 need the pin gender reversed

wire to pin alignment must be perfect and there must not be excess solder left on the pin

great care must be taken to not damage the connector so that it properly functions in pin retention and separation.

it is critical that you do not damage or otherwise modify the length of any blue wire. 

General steps of the process:
1:
disconnect the lvds cable from the mod chip (input) and entirely remove the wire wrap.
with great care, remove the metal top of the connector.

2:
take a picture of your connector as reference and ensure it is exactly the same as example picture 001.jpg
take this time to orient your cable and find pin 1, take note that all the odd pins are long, and all the short pins are even.

3:
take small tweezer tools and attempt to tear off the top ground strap. Mine came off easily, but you need to be very careful not to damage the cable. 
it may be better to use soldering iron to more easily remove the strap but you risk letting the wires come with it or becoming unorgainzed

4:
use a new razor blade or xacto knife and carefuly pry out all the pins from the connector 
you should now just have the wires and pins all as one unit

5:
use your reference picture or 001.jpg and desolder one wire at a time. I started with the right side, pin38, and did all th reds first
separate the individual wire, reterminate it if needed, and reinsert it into the plug in the correct position.
you just simply heat the strap and the hlue at the same time and the wire should pop free, be careful not to hit the pin with the iron or it could become damaged or unsoldered.
some wires you can reorder, such as vbl20, to terminate wires in a different spot that would otherwise need to have the pin changed.
pin 6 (lvds cable) can go in any ground position on the plug, I used 40
simply leave out the extra pins, they do nothing and make the cable harder to insert which isnt what you want.

6:
you do not need to attemt to reuse the ground strap, simply bridge the shielding with a solder blob.
do not go too thick or the connector wont assemble correctly
do not go too hot or you risk burning through the insulation
bridging the red group is unnessesary but could help you maintain pin separation 

7:
verify that every pin is correctly installed on the plug side, the gold end should be in the small rectangle of the plug and not in the insertion zone surrounding the island. 
it should be visible in the rectangle but if one has become bent, it may not, but it will probably be fine.

8: 
reassemble the plug before testing, otherwise all the pins will fall out when you insert it and probably break.
although you can insert it with the shield off if you are careful and help the pins stay down as you push it on.

9:
optionally, disassemble the original cable, and cut the wires off for the webcam and thinklight, you will have to strip the insulation and solder them to all the extra pins, then terminate them in the plug. 

10:
re-wrap the cable. route the cable into the lid, as there is no room for the mod chip in the chassis. 
