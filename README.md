# Document Scanner


[![Watch Video](https://github.com/murtazahassan/Document-Scanner/blob/master/Documnet%20Scanner.jpg)](https://youtu.be/ON_JubFRw8M)

A simple document scanner using opencv and how we can save these images by pressing just a button on the keyboard. It is simple and covers the core principals of opencv. 

The saved image is named after 'myImage0' with very high resolution.Although I applied it to only one image the code supports multi documents scanner.

The pipeline of the image is as follows:

OriginalImage    ->   GrayScaleImage  ->      EdgeDetector  ->     ContoursDetection  ->     SelectionOf BiggestContour  ->      Warp Prespective(Colored Image)  ->    Adaptive Thresholding(Scanned Document)   ->>>>>      Additional functonality of saving the document to a folder by clicking 's' on keyboard

