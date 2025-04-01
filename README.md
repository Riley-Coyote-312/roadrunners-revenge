# roadrunners-revenge
Flipper Zero app for tracking USDA fc2 animal tracking tags

Background:

This project allows direction location using the CC1101 radio in the flipper zero radio using phase detection. This is done by tuning slightly above and below the target frequency and then reading the RSSI. This can then be used to algorithmically determine approximate direction. 

Note that reflections way confuse the direction finder if you are near structures. Also this approach is not immune to interference on the band. This can be refined in later revisions by rewriting the core subghz code to run faster. 

This will read any fc2 type tag operating in the 434 Mhz band (primarily used to coyote monitoring in my locale but used for other animals as well).


Instructions: 

Drag roadrunners_revenge.fap into your SD Card/apps/ folder using qFlipper

To start tracking press down arrow.
The app will search for an active tag within range. If found it will display the tag and start tracking.
