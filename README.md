# typography
hosted link:https://manuhegde198924.github.io/typography/
we have learnt:
 margin/padding
- height/width
- background-color
- border
- font-size
- font-weight
- text-align
- In this article, we will explain the difference between CSS padding and margin.

Margin: It is the space around an element. Margins are used to move an element up or down on a page as well as left or right. Margin is completely transparent, and it does not have any background color. It clears the area around the element. Each side of the element has a margin size you can change individually. In creating the gap, the margin pushes adjacent elements away.

Padding: It is the space between the element and the related content inside it. It determines how elements look and sit within a container. It also shows the container background around the element in it. Padding can be affected by background colors as it clears the area around the content. To create the gap, it either grows the element size or shrinks the content inside. By default, the size of the element increases.

When to use Margin and Padding?

    When you are adjusting the layout of your design, you will need to determine whether to adjust the margins or the padding. If the width of your page is fixed, centering an element horizontally is very simple, just assign the value margin: auto. You would also use the margin to set the distance between nearby elements.
    You would change the padding if you want to create the space between the element and the edge of the container, or border.

Note: Margins are used to add spaces between an image and the description of that image.
The font-weight property of the CSS is used to set the weight or thickness of the font being used with the HTML Text. The font-weight applied will depend on font-family used and the browser. For instance, some font-family is available only in specific weights.

Syntax:

font-weight: normal|bold|lighter|bolder|number|initial|inherit|unset;

Property Values:

    normal: This is the default font-weight & defines the normal font-weight. It is equal to the number value 400.
    bold: This defines the bold font-weight, it is equal to the number value 700.
    lighter: This makes the font-weight one level lighter than the parent element, considering the available font weights of the font family.
    bolder: This makes the font-weight one level heavier than the parent element, considering the available font weights of the font family.
    number: This sets the font-weight according to the number specified. The number can range between 1 to 1000. If the exact weight is unavailable, a suitable weight is applied.
    

CSS Padding is used if we want to create a space between an element and the edge of the container or the border. It is also useful in the requirement of changing the size of the element. 


The background-color property in CSS is used to specify the background color of an element. The background covers the total size of the element with padding and border but excludes margin. It makes the text so easy to read for the user. 

Syntax:

element {
    background-color property
}

Default value : It has a default value i.e. transparent.

Property Values:

    color: It defines the background color value or color codes. For example: A color name can be given as: “green” or HEX value as “#5570f0” or RGB value as “rgb(25, 255, 2)”.

Syntax:

element {
    background-color: color_name;
}

border:
The border property in CSS is used to style the border of an element. This property is a combination of three other properties border-width, border-style, and border-color as can be used as a shorthand notation for these three properties. It sets or returns the border-width, border-style, border-color Properties. 

Syntax: 

border = "width style color|initial|inherit"

Default Value: Its default value is initial.

Property Values: 

    width: This value specifies the weight or the width of the border.
    style: This value specifies a style for the border, that is whether the border will be dotted, dashed, solid etc.
    color: This value specifies the color of the border.
    The font-size property in CSS is used to set the font size of text in HTML document.

Syntax:  

font-size: medium|xx-small|x-small|small|large|x-large
           |xx-large|smaller|larger|length|initial|inherit;

Default Value: medium

Property Values: 

    absolute-size: The absolute-size is used to set the font size absolutely. The default value of absolute-size is medium. The list of absolute-size properties are xx-small, x-small, small, medium, large, x-large, xx-large.
    relative-size: It contains two values smaller and larger. The font-size is smaller or larger depends on the parent element. 
    length: This property is used to set the font-size in length. The length can be in the form of px, cm etc. 
    global: This property contains three types of values such as initial | inherit | unset.
    The text-align property in CSS is used to specify the horizontal alignment of text in an element ie., it is used to set the alignment of the content horizontally, inside a block element or table-cell box.

Syntax:

text-align: left|right|center|justify|initial|inherit;

Default Value : left if direction is ltr, and right if direction is rtl

Property Value:

    left: It is used to set the text-alignment into left. This is the default property.
    right: It is used to set the text-alignment to right.
    center: It is used to set the text-alignment into the center.
    justify: It is used to spreads the words into the complete line i.e., by stretching the content of an element.
    initial: It is used to set an element’s CSS property to its default value.
    inherit: It is used to inherit a property to an element from its parent element property value.
    
