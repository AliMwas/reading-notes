
# Images, Color, Text

HTML Images Syntax
The HTML < img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The < img> tag creates a holding space for the referenced image.

The < img> tag is empty, it contains attributes only, and does not have a closing tag.

The < img> tag has two required attributes:

* src - Specifies the path to the image

The src Attribute
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.


* alt - Specifies an alternate text for the image

The alt Attribute
The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:


## color
The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

rgb values
These express colors in terms of how much red, green, and blue are used to make it up. For example: rgb(120,130,90)

hex codes
These are six-digit codes that represent the amount of red, green, and blue in a color, preceded by a pound or hash # sign. For example: #ee5e60
color names
There are 147 predefined color names that are recognized by browsers. For example green

## Text

**Text Color**
The color property is used to set the color of the text. The color is specified by:

a color name - like "red"
a HEX value - like "#ff0000"
an RGB value - like "rgb(255,0,0)"
Look at CSS Color Values for a complete list of possible color values.

The default text color for a page is defined in the body selector.

**Text Alignment**
The text-align property is used to set the horizontal alignment of a text.

A text can be left or right aligned, centered, or justified.

The following example shows center aligned, and left and right aligned text (left alignment is default if text direction is left-to-right, and right alignment is default if text direction is right-to-left):

**Text Decoration**
The text-decoration property is used to set or remove decorations from text.

The value text-decoration: none; is often used to remove underlines from links:

![text](https://i.stack.imgur.com/R3rg7.png)

## JPEG, PNG, GIF

**JPEG** is a lossy compression specification that uses human perception. It can achieve a compression ratio of 1:10 without any noticeable quality difference. In addition, compression artifacts become more prominent. Because JPEG compression works by averaging the colors of nearby pixels (see Discrete Cosine Transform), JPEG images are best suited for photos and paintings of natural scenes with smooth color and intensity changes. However, if the image contains text or lines and requires strong contrast between adjacent pixels to highlight the correct shape, this lossy compression technique will not produce good results.

**PNG** is a lossless image format that uses DEFLATE compression. No data will be lost during the compression process and no compression artifacts will be introduced into the image. For this reason, PNG images will maintain higher quality and look sharper than JPEG images, and will also take up more disk space. This makes it unsuitable for storing or transferring high-resolution digital photos, but it's a great choice for images with sharp edges, text, logos, and shapes.

**GIF** is also a lossless image format that uses the LZW compression algorithm. In the early days, I was more favored by simple website graphics than PNG, because support for PNG continues to grow. Since all major devices now support PNG, and PNG compression is about 5 to 25 times faster than GIF compression, GIF images are now primarily used only when the image contains animation.