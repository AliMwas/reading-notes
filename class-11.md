# Audio, Video, Images

**HTML Images Syntax**
The HTML < img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The < img> tag creates a holding space for the referenced image.

The < img> tag is empty, it contains attributes only, and does not have a closing tag.

The < img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image


**The src Attribute**
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

**The alt Attribute**
The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader). The value of the alt attribute should describe the image

**size images in CSS**
You can control the size of an image using the width and height properties in CSS, just like you can for any other box. 
Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.
You might think that your site is likely to have images of all different sizes, but a lot of sites use the same sized image across many of their pages. 
![htm&css](https://images.tynker.com/blog/wp-content/uploads/20190226100225/02-25-2018-html-css-announcement-blog.png)

**HTML5 video and audio**
The < video> and < audio> elements allow us to embed video and audio into web pages. As we showed in Video and audio content,
The HTML5 DOM has methods, properties, and events for the < audio> and < video> elements.

HTML Audio/Video Methods
Method	Description
addTextTrack()	Adds a new text track to the audio/video
canPlayType()	Checks if the browser can play the specified audio/video type
load()	Re-loads the audio/video element
play()	Starts playing the audio/video
pause()	Pauses the currently playing audio/video




