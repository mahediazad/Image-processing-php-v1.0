Image procession in php
=======================
Convert image from one type to another and other operation in php

#uses:
* Image resize
$imageConvert = new ImageProcessing();
$imageConvert->imageResize('image source', 'store in new image', 'image width', 'image height');


* Convert to thumb
$imageConvert = new ImageProcessing();
$imageConvert->img2Thumb('image source', 'store in new image', 'image width', 'image height', 'image extension');

* Convert to jpg image
$imageConvert = new ImageProcessing();
$imageConvert->imgConvert2JPG('image source', 'store in new image');