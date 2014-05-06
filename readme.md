# Canvas2image #
a tool of saving or converting canvas to images. It allow also to saveAsImage
with filename defined by you! No longer meaningless browser default 
filenames that may scare some people.

## Demo ##
[canvas2image](http://mbochynski.github.com/proj/canvas2image/index.html)

## Code ##
you can just use it like this
		
    Canvas2Image.saveAsImage(canvasObj, width, height, type, filename)
    Canvas2Image.saveAsPNG(canvasObj, width, height, filename)
    Canvas2Image.saveAsJPEG(canvasObj, width, height, filename)
    Canvas2Image.saveAsGIF(canvasObj, width, height, filename)
    Canvas2Image.saveAsBMP(canvasObj, width, height, filename)
		filename should be a string without extension
    
    Canvas2Image.convertToImage(canvasObj, width, height, type)
    Canvas2Image.convertToPNG(canvasObj, widht, height)
    Canvas2Image.convertToJPEG(canvasObj, widht, height)
    Canvas2Image.convertToGIF(canvasObj, widht, height)
    Canvas2Image.convertToBMP(canvasObj, widht, height)

## Supported browsers ##

I have tested this new feature (custom filename) with following browsers:
Opera 12.16 1860 NOK
Google Chrome 34.0.1847.132 OK
Mozilla Firefox 29.0 OK

More (IE) will be tested soon.

NOK => everything seems to be working but saved with browser default filename
OK => everything seems to be working fine
