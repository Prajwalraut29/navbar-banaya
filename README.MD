# selector 
<h1>selector in CSS  </h1>
<h2 class="brf">  name selector 
class selector 
id selector 
universal selector

 
 #  css formatting 
   1) color
   2) font family -> try to add two more more font family deu to unexpected error
   3) font size ->unit of font size is pixel 
   * default value of font size is 16px
   * formula of coverting em to pixel 
   em = pixel/16
    em (2)= 32 /16
    4) font style -> styling like italic
    5) font weight -> weight or thickness of text
    like bold,meduim,large,semi bold, extrabold
    6)

    # css box model
    /* p{
    color: rgb(0, 255, 166);
    font-size: 1.25em;
    font-family: cursive;
    font-style: italic;
    font-weight: 900;
  background-color: black;
         width: 200px;
         height: 190px;
         border-radius: 20px;
         border: 5px dotted rgb(255, 0, 200);
         padding: 50px;
         margin: 50px;
         margin-top: 100px;
         margin-bottom: 80px;
} */
    * all html element can be considered as boxes 
    * the box model represent the design and layout of webapage 
    # 1) width & height 
    * it consists of widht height border padding and content & properties
    * properties work on left right top bottom
* widht & height -> widht is form left to right & height is top to bottom 
* both are specified with px & default px is 20pixel

# 2) padding 
* specifies the amount of space between content area and the border 
* padding is space between piture and frame surrounded the picture
* we can apply padding multiple sides 
* if you defined 4 four value it mean top bottom right left

# 3) Border 
* border is line that surrounds as element like a frame around a painting or picture 
* we can modify the corners of an element using border-raduis property
* border: 2px solid red;

# 4) margin
*  margin refer to space directly outside of the border box
* it specifies the amount of space betwn the border and outside edge of the element 
* the margin property also lets you center content 
* margin:5px;

# 5) positioning and layout-positions elements
1) static positions 
2) fixed positions
3) absolute positions
4) relative positions

# 1) static positions
syntax = position : static ;
* its work on natural flow of page & it is the default value  but when an element is deliberately set to static
* element follow natural flow of page 

# 2) fixed positions
 syntax = position : fiexd;
 * when position has a fixed it means that element will not remain int the natural flow of the page & stays in one place
   
   # 3) absolute positionig
   * all element on the page will ignore the element with position: absolute and act like it is not present on the page 
   * int other words it takes it out of the normal flow of the page and position it according to values it is given 


   # 6 z-index
* when elements are positioned outside the normal , they overlap other elements
* the z-index property specifies the stack order of an elelment in order for it to be placed in front of or behind others
* it uses number values and the higher the number 
* the greater the authority it has

# 7 media queries 
* media queries are used in responsive design, it changes the presentation of content based on diff viweport sizes

syntax :
@media(max-width:600px){
  body{
  color : red
  }
}
@media(max-width:500px) {
  body{
    background-color: gray;
    font-size: 16px;
  }
  
}

# animation
1) animation-duration : define the how long an animation should take to complete

2) animation delay : specifies the delay for the start of the animation

3) animation-iteration-count: specifies how many times an animation should run, the value can even be infinite

some properties of animation
 ease :   start slow then fast end slow 
 linear : same speed start and end 
 ease-in
 ease-out 
 ease-in-out
 cubic-bezier


 # flexbox
 * flexbox is a more effcient way to layout , align and distribute space among items in a container even if thier sizes are unknown 
 * it is acitived by selecting the type,class,id and giving it the property 
   

  *  flexbox - flex-direction
  it defines which direction the container wants to stack the flex items  
  ans it had default direction row vice

 *  syntax
  .container{
  display: flex;
  flex-direction: row;
}

* flexbox - flex-wrap
flex-wrap property defines whether the flex items should wrap or not 
i.e wehter to stop elements from overflowing outside of thier container

syntax: 
.container{
  display: flex;
 flex-wrap: wrap;
}

* flexbox - justify-content 
* justify-content property is used to align items, 
this moves the flex items to justify , right to left aligned (all horizontally / main axis)
* it has a lot of values like the space-between,flex-start,flex-start,flex-end,flex-around and center and default it set to flex- start

* flexbox - align items
* the property is used to align itens vertically or along the cross / x axis ont the current line.
think of it as the justify-content version for the cross-axis 
* its default value is stretch which makes elements fill up the entire cross axis  
syntax :
.container{
  display: flex; 
 height: 800px;
align-items: flex-end;
}














# click on version control system
# initialize repository 
# commit the message -> first commit 
# link of repo
# add name of your 
# then add push to github
# push to github ->>auto add url 