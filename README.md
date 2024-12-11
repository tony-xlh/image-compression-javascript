# image-compression-javascript

A demo compressing images with JavaScript.

It can compress images via the following aspects:

* Resolution
* Color conversion
* Image format
* Image quality

It can run a batch test to get an idea of how those aspects can impact the final size.

[Online demo](https://tony-xlh.github.io/image-compression-javascript/)

## Color Conversion Modes Supported

* Grayscale
* Black & white with a 50% threshold

## Image Formats Supported

* PNG
* JPEG
* WebP
* FAX4 (CCITT-4)
* JBIG2
* JP2000
* LZX

The latter four are mainly used for PDF. We use [Dynamsoft Document Viewer](https://www.dynamsoft.com/document-viewer/docs/introduction/index.html) to get the image compressed in the four types.
