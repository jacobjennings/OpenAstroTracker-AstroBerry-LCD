# OpenAstroTracker-AstroBerry-LCD
An enclosure for the MKS Gen_L and a raspberry pi for use with the OpenAstroTracker.

![ss 1](ss1.png?raw=true)
![ss 2](ss2.png?raw=true)

(just sharing my design, not affiliated with OAT)

The f360 design is highly parameterized and should hopefully be easy to customize or extend for your own needs. Please feel free to send pull requests with changes, variants, or build photos!

## Print & build

Print the base in its normal position. You should not need supports. 

Print the lid with the flat side (top side) against the print bed (you'll have to flip it from its orientation in the STL.)

The heatset inserts required are M3xD4.6xL6.0, the same inserts specified for the OpenAstroTracker build if you used the heatset option.

The heatset insert holes can be adjusted globally by changing the user parameters in the f360 workspace, so you can use a different size, or
just change it to fit a screw directly if you wish.

A standard 80mm computer fan will fit on top if you want to use it.

The holes on the sides are just big enough to fit a cigarette lighter plug through which is what I use for powering the whole thing. They are 23mm sized for a rubber wiring gasket you can get from aliexpress etc. though it's not really necessary.

I use a 12v power source combined with a 12v->5v buck converter from amazon to power the MKS and the pi (directly to the pins). 

I suggest using a long-ish ribbon cable for the LCD so you can set the lid aside easily.

There are spots for heated inserts on the bottom for feet if you want to add some.
