## UTF_8_Glyph_All_Future_Character_models
# Update
This system starts with the initial UTF-8 code 11111110, and then the rest of the codes are 10xxxxxx, where those "xxxxxx" are the bits of data that allow the floating point values to be calculated.
<br>
Once the bytes starting with "10" run out, no further curves need be drawn in the square meant for that glyph on the page.
<br>
The curves are written using the "Parametric" method because that allows for the most unique symbols imaginable. The sine function (plus a constant, quadratic and cubic parameter) is all that is needed to approximate arbitrary curves within the 100 x 100 square of space with a reasonable degree of precision, and, if it isn't, there is a second sine function, or the minimum and maximum value of t can be changed right before that curve, while a secondary curve later (using a different starting t value) (that starts at the spot where the previous curve ended) can create the impression of a single curve that does the complicated stuff that one curve was unable to do. 
