first, get the colors
=====================

simple way:
-----------

use 

    red = pixels[0]

and so on  

alternative way:
----------------

use list unpacking:

red, green, blue = pixels

next, rescale the colors
========================
if x is (say) between 0 and 100, then x / 100 is between 0 and 1