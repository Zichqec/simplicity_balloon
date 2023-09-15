A simple balloon template. Replace this readme with your readme (or remove it if you don't want a readme), and please make sure you add a craftman and replace the name/directory of the balloon in the descript.txt and install.txt files!

Find documentation for all the various balloon settings here: https://ukagakadreamteam.github.io/ukadoc/manual/descript_balloon.html

A couple notes about this balloon template. I've included all the stuff I typically want when making a balloon, but some of the stuff I like to add isn't totally necessary.

You can omit the cursor.font.color and cursor.pen.color settings if you would like. I sometimes make them match the anchor color, that way when you hover over menu choices, they highlight in the same color as the anchor. But many of my balloons don't do this, and simply show the underline when choices are hovered over. If you want the latter, then just erase those two settings.

The font disable color can be omitted if SSP generates a nice one for your balloon. In the case of this template, it was too light to read, so I added a custom one. You should try commenting out the disable.font.color settings though after you add your images/regular font color, and see if it looks ok by default.

The onlinemarker interval setting is relatively recent (at the time of writing) and it's not at all necessary. But if you'd like to make an online animation that's a bit smoother, then there's the setting. You can erase it if you just want to use the default speed.

This template makes use of negative numbers for its coordinates, so that it's very easy to create new sizes for the balloon. I have a guide here that talks about that: https://ukagaka.zichqec.com/guide/negative_coordinates_in_balloons
Basically, negative X coordinates are relative to the right, and negative Y coordinates are relative to the bottom. If you plan ahead and make your balloon's borders always the same distance from the edges of the canvas, you won't need to fuss with individual settings files to place your arrows and such. It simplifies things a lot and can save you hours of tedious work depending on the complexity of your balloon.


Simplicity Balloon v1.0.0
Made by Zichqec https://ukagaka.zichqec.com/
You are free to use this to create any balloons you like, no need to credit me! But if you'd like to find more by me, including more templates like this, find me at the link above.