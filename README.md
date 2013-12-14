SvgBackdrops
============
Shows the use of css3 + png + svg to do textured scalable backdrops with small file sizes

It consists of:

plain colour background
alpha transparant css3 gradient to provide the highlight
svg to provide the sharp foreground (the owls)
alpha png to provide the texture

When served through a properly configured web server the svg will be gzip 
compressed from 17k to ~6k giving a total download size of ~22k the majority
of which is the png
