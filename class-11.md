# image
The `<image>` css data type represents a two-dimensional image.
Syntax
The `<image>` data type can be represented with any of the following:
* An image denoted by the url() data type
* A `<gradient>` data type
* A part of the webpage, defined by the element () function
* An image, image fragment or solid patch of color, defined by the image ()function
* A blending of two or more images defined by the cross-fadel function.
* A selection of images chosen based on resolution defined by the image-set() function.Description
CSS can handle the following kinds of images:
* Images with intrinsic dimensions (a natural size), like a JPEG, PNG, or other raster format .
* Images with multiple intrinsic dimensions, existing in multiple versions inside a single file, like some .ico formats. (In this case, the intrinsic dimensions will be those of the image largest in area and the aspect ratio most similar to the containing box.)
* Images with no intrinsic dimensions but with an intrinsic aspect ratio between its width and height, like an SVG or other vector format .
* Images with neither intrinsic dimensions, nor an intrinsic aspect ratio, like a CSS gradient.

CSS determines an object's concrete size using (1) its intrinsic dimensions; (2) its specified size, defined by CSS properties like width, hight  or background-size; and (3) its default size, determined by the kind of property the image is used with:
IMAGE ROLLOVERS & SPRITES
Using CSS, it is possible to create a link or button that changes to a second style when a user moves their mouse over it (known as a rollover) and a third style when they click on it. This is achieved by setting a background image for the link or button that has three different styles of the same button (but only allows enough space to show one of them at a time). You can see the image we are using in this example on the right. It actually features two buttons on the one image. When the user moves their mouse over the element, or clicks on it, the position of the background image is moved to show the relevant image.
Background Images

background-image: The background image property allows you to place an image behind any HTML element. This page may be the whole or just a part of it. By default, the background image will repeat to fill the entire square.
Repeating Images, background-repeat and background-attachment :
1. repeat : The background image is repeated both horizontally and vertically (the default way it is shown if the background-repeat property isn’t used). 
2. repeat-x : The image is repeated horizontally only. 
3. repeat-y : The image is repeated vertically only. 
4. no-repeat : The image is only shown once 
5. fixed :The background image stays in the same position on the page. 
6. scroll : The background image moves up and down as the user scrolls up and down the page. 
aligning Images Using css
* There are two ways to align img:
1. The float property is added to the class that was created to represent the size of the image.
2. New classes are created with names such as align-left or align-right to align the images to the left or right of the page.These class names are used in addition to classes that indicate the size of the image.
img.align-left { float: left; margin-right: 10px;} img.align-right { float: right; margin-left: 10px;} img.medium { width: 250px; height: 250px;}