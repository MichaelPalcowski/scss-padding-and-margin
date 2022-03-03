# scss-padding-and-margin
SCSS function to add padding and margin based on a class.  Supports individual properties, vertical and horizontal properties, and all properties at once.  
Classes are built based on the pixel value you provide when using them.  

Format :
Classes are set using the format of {property}-{sides}-{size}

Properties for {property}: 
m - for classes that set margin
p - for classes that set padding

Sides for {sides}: 

t - for classes that set margin/padding-top
r - for classes that set margin/padding-right
b - for classes that set margin/padding-bottom
l - for classes that set margin/padding-left
t - for classes that set margin/padding-top
blank - for classes that set margin/padding on all 4 sides of {property}

Size for {size}:

{size} is set using a numerical value between 1 and 300.  The range can be adjusted by changing the second value in the @for rule.
Setting {size} will add that pixel value of margin/padding on the {sides} specificed in the class. 


Reponsive 
Info coming later
