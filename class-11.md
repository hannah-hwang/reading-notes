# Read: Class 11 Audio, Video, Images

## Video and Audio Content

1. Since the early 2000's, the ability to use video and audio on the web has evolved from technologies such as Flash and Silverlight, which had issues with security and accessibility, to the HTML elements \<video> and \<audio>, which can be controlled by JavaScript APIs.
2. The *src* attribute is the source which contains the link to the video you want embedded in your webpage. The *controls* attribute is applied using JavaScript APIs and refers to the video contols (volume control, pausing/playing the video, etc.).
3. It is important to have *fallback content* inside the \<video> element because it is what is displayed if the video is not supported by the browser. A direct link to the original video can be displayed here.
4. Not really a story (not at all actually;;;), but \<video> and /<audio> work in similar ways, and they can work together for accessibility purposes. For example, providing a video containing text tracks for an audio file for people with auditory impairments.

## Grid

1. Grid layout is different from Flex in that grid can be used to align elements into multiple rows and columns, while flex is one dimensional and can only control one row or column at a time.
2. *Grid container* is the element where the grid display is applied, and where all of the items will be contained. *Grid item* is the content stored in the grid container. *Grid line* refers to the horizontal and vertical lines that make up the layout of the grid.

## Responsive Images

1. Developers should make images responsive because otherwise, users may waste bandwidth by downloading an image that is to large for the screen they're using. Repsponsive images also take into the account which resolution is best for specific devices.
2. The *srcset* attribute defines they set of images the browser can choose between. The set includes the same image with different sizes and resolutions. The *sizes* attribute defines a set of media conditions and indicates what image size would be best for the screen size. It provides the size of the viewport width. So the browser will get the device width, match it with media condition on the sizes list that is true, get the size of the area designated for the image, then load the image from the srcset that matches that size.
3. *Srcset* is more helpful for responive images that CSS or JavaScript because it will load the image required for the page before the original image loads.
