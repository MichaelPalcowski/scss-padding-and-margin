# scss-padding-and-margin
SCSS function to add padding and margin based on a class.  Supports individual properties, vertical and horizontal properties, and all properties at once.  
Classes are built based on the pixel value you provide when using them.  

Format :
Classes are set using the format of {property}-{sides}-{size}

Properties for {property}: 
<p>m - for classes that set margin</p>
<p>p - for classes that set padding</p>

Sides for {sides}: 

<p>t - for classes that set margin/padding-top</p>
<p>r - for classes that set margin/padding-right</p>
<p>b - for classes that set margin/padding-bottom</p>
<p>l - for classes that set margin/padding-left</p>
<p>t - for classes that set margin/padding-top</p>
<p>blank - for classes that set margin/padding on all 4 sides of {property}</p>

Size for {size}:

<p>{size} is set using a numerical value between 1 and 300.  The range can be adjusted by changing the second value in the @for rule.</p>
<p>Setting {size} will add that pixel value of margin/padding on the {sides} specificed in the class. </p>


Reponsive 
Info coming later
