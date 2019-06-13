# Maps-in-Tikz

This is a more detail explanation of how to create maps using Tikz.

1. Download InkScape. 

https://inkscape.org/

2. Download the map with the SVG extension you want to want to convert to Tikz.

For example:

https://commons.wikimedia.org/wiki/File:Flag-map_of_Norway_%2B.svg

3. Download SVG2Tikz

https://github.com/kjellmf/svg2tikz

4. Copy the following files available in SVG2Tikz

tikz_extport.py file 
tikz_export_effect.inx 
tikz_export_output.inx 
to 
the inkscape/share/extensions directory

5. Open the SVG map in Inkscape and go to Save as, if everything is right there is going to be an option (the last one) saying Tikz Code

6. Add to the already existed options Crop and Verbose.

7. Open the file in a LaTeX editor

