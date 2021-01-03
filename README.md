# HTMLCSS
Id: this is unique through out the file i.e multiple sections can not have same ID.
class: multiple sections can have same class.

1) Difference between div and span
-> Div ::
     div is a block level Element. i.e the element is displyed on the next  new line.
   Span :: 
     span id inline element. i.e it does not add content to new line. it continues in the same line.

    
HTML5 Semantic Tags:::

1) <header> :: includes header elements of website like logo, login/logout, search, name
2) <footer> :: includes footer element
3) <nav> :: Used for navigation
4) <main> :: wrap the main content of page in main tag
5) <section> :: 
6) <article> :: multiple blogs or read more buttons
7) <aside> :: contains side bar contents


CSS using ID selector or Class ?
 Id needs to be unique through out the page so we can not reuse the same css.
 We can have multiple html tags or elements with same class in a page.
 So, it is preferred to use class selector while applying css.


CSS Units
  There are 2 types of css units 
    1> Absolute Units
        * cm (Centi meter)
        * mm (milli meter)
        * in (inches)
        * px (Pixels 1px = 1/96 of 1 in) this unit is most frequently used.
        * pt (points 1pt = 1/72 of 1 in)
        * pc (picas picas 1pc = 12pt)
      
    2> Relative units
        * % (with respect to parent element)
        * em (with respect to font-size or padding,margin etc of parent element)
        * rem (with respect to root element)
        * vw (with respect to 1% of voewport width)
        * vh (with respect to 1% of viewport height)


Different ways of specifying color in css?
  1> color name
      ex: color : black; //adviced not to use directly
  2> RGB color format
      ex: rgb(0,0,0) //represents black
          rgb(255,255,255) // represents white
          rgb(255,0,0) // red
          rgb(0,255,0) // green
          rgb(0,0,255) // blue
  3> Hexa values
      ex: color : #ffffff //white 
          color : #000000 or #000 // black
      (in hexa values if same character is repeated 6 times then we can give it only 3 times also. both will represent same color . i.e #ffffff and #fff both are white)

what are the 3 properties of border property?
  when we define css border property we need to specify 3 property values those are 
      border-width
      border-style
      border-color
  ex: border : 3px solid red;
      border : border-width border-style border-color;


* if we want the backgound of image to be transparent then the format of image should be .png

Margin and Padding
  margin :  
    * it is space outside the border
    * in browser dev tool when we hover over an element margin is shown in light orange color
  padding : 
    * it is the space inside border
    * in browser dev tool when we hover over an element padding is shown in light green color.

* If we provide padding without setting box-sizing property, then the padding is added to the box size,
  i.e, if we have a box size as 500 and padding as 120 then the box size will be increased by 120px on all sides . now box-width = 120 + 500 + 120.

  To avoid increasing of box size we need to set box-sizing : border-box.


  FLOAT:
    when we use float on any element after that element we need to clear the float. 
    Ex: we have 3 divs on 2nd div we use float property. if we dont clear the float after div2 and directly display div3 then div3 will be overlapping with div2 floats. so after div2 we need to clear float.


We can not use margin:auto to dispaly inline elements at center.
we can use margin:auto only when the element is block level element

We can not use width and margin-bottom while using display:inline. these properties will be ignored.

By Default position will be static

POSTION VALUES
STATIC : not effetced by top,left,right,bottom (TLRB)values

RELATIVE : TLRB values cause element to be moved from its nprmal position

ABSOLUTE: Positioned relative to its parent element that is positioned relative

FIXED: Positioned relative to the viewport

STICKY: Positioned based on scroll position


class css takes the higher precedence that the direct element css

Padding can not have -ve values. if given then also there will be no effect of those values.