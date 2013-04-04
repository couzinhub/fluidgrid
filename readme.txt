/*  -------------------------------------------

    ===========================================
                     FLUIDGRID
                         *
    = = = = = = = = = = = = = = = = = = = = = = 
              &copy; 2011, Hubert Florin 
                couzin.hub@gmail.com  
             Released under MIT LICENSE
    
    Permission is hereby granted, free of charge, to 
    any person obtaining a copy of this software and 
    associated documentation files (the "Software"), 
    to deal in the Software without restriction, including 
    without limitation the rights to use, copy, modify, 
    merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom 
    the Software is furnished to do so, subject to the 
    following conditions:
    
    The above copyright notice and this permission notice 
    shall be included in all copies or substantial portions 
    of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF 
    ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED 
    TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A 
    PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL 
    THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, 
    DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF 
    CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN 
    CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS 
    IN THE SOFTWARE.
    
    
    THIS SOFTWARE IS UNDER DEVELOPMENT, USE FOR TESTING, 
    PREVIEW, OR DON'T USE AT ALL !
                
    ------------------------------------------- */    


FLUIDGRID is a CSS ONLY grid system. You can use it to create
Layouts in your websites in seconds, by just using a set of 
classes.

FLUIDGRID can use as many columns as you want, and with 
whatever gutter width you need. It is based on percentages, and
therefor can adapt to any width, even fluid width.

FLUIDGRID has been created with SASS, meaning that the CSS
is created automatically by running a SASS script on fluidgrid.scss
Just define the number of columns and the width of the gutters
and run SASS. This will create a stylesheet that will set all 
the styles of your grid.

All the class example given below are uppercase, but this is only
for highlighting purposes. When writing your code, use lowercases.

FLUIDGRID uses classes to give dimensions to elements of your
markup. If you have a 12 columns grid, by just giving an element
of your page the class 'SPAN-6' will give that element half
of the layout's width. A 'SPAN-3' will be a quarter, 'SPAN-12' or
'SPAN-FULL' will take the full width.

The only rule to remember is to give to the FIRST ELEMENT of a 
row the class ALPHA, and the LAST ELEMENT of a row the class OMEGA.

You can also move elements on the grid by using the extra class
PUSH and PULL to move your elements on the grid. For example,
the class PUSH-3 will move your elements 3 columns to the right, 
where the class PULL-3 will move it 3 columns to the left.

You can also use the class SUFFIX or PREFIX to create padding
on the right or left of your elements. For example, the class
SUFFIX-3 will add he equivalent of 3 columns of padding to the
right of the elements, pushing the following elements of the same 
row to the right.

You can refer to the attached example for a more complete example 
of how FLUIDGRID works, and how to use it.
