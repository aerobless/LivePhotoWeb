# LivePhotoWeb

How to display Apple Live Photos on a website. Please be aware that this is just a silly hack. It currently only works in Desktop browsers, though I'm looking into making it work on mobile too. 

###How does it work
1. Copy Live Photos from your iPhone with "Image Capture" (OS X), they consist of a IMG\_123.JPG and IMG\_123.MOV.
2. Convert the IMG\_123.MOV to IMG\_123.MP4 with [Handbreak](https://handbrake.fr/).
3. Embed the image and video like in the index.html example in this repo. You're done :).

###[Demo](http://w1nter.com/apps/LiveViewer/)
While you click the image, the video will play in a loop until you release the mouse button or move the cursor away. This only works on desktop browser atm, due to the problems listed below.

###Problems with Mobile
+ iOS on iPhone doesn't allow video to be played inline.
+ iOS and Android interprete clicking the image as long press

##License (MIT)
> Copyright (c) 2015 Theo Winter

> Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

> The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.