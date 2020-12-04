<!--
Shawdows to elements with CSS3.

Instructions: Double click to paste this code in your .css file and apply this div <div class="name"> </div> to your text (name=darkshadow|lightshadow|innershadow, etc.). 
Values for box-shawdow are: horizontal offset, vertical offset, blur radius and shawdow color.
Also, include the call to the .css file between the <head> and </head> tags. Example: <link rel="stylesheet" type="text/css" href="css/myelements.css"/> 
-->
.darkshadow
{
   background-color: #ddd;
   width: 300px;
   padding: 10px;
   
   box-shadow: 10px 10px 15px #000;
   -webkit-box-shadow: 10px 10px 15px #000;
   -moz-box-shadow: 10px 10px 15px #000;
}

.lightshadow
{  
   background-color: #999;
   width: 200px;
   padding: 10px;
   color: #fff;
   
   box-shadow: 4px 4px 2px #ffc;
   -webkit-box-shadow: 4px 4px 2px #ffc;
   -moz-box-shadow: 4px 4px 2px #ffc;
} 

.innershadow
{  
   background-color: #fff;
   width: 200px;
   padding: 10px;

   -moz-box-shadow: inset 0 0 1em gold;
   -webkit-box-shadow: inset 0 0 1em gold;
   box-shadow: inset 0 0 1em gold;
}

## Welcome to my site

<div class="darkshadow">Hello, World!</div>