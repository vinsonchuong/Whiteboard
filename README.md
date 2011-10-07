# Whiteboard
Whiteboard is a collaborative workspace, providing a drawing surface and
text chat to multiple simultaneous users.

The drawing surface is built using HTML5 canvas. The overall user interface is powered by
[jQuery](http://jquery.com),
[jQuery UI](http://jqueryui.com),
[jQuery miniColors](http://abeautifulsite.net/blog/2011/02/jquery-minicolors-a-color-selector-for-input-controls/),
[fileinput](http://plugins.jquery.com/project/fileinput),
[spinner](http://www.jqueryin.com/projects/spinner-jquery-preloader-plugin/), and
[jquery.event.drag](http://threedubmedia.com/code/event/drag).
Client and server communication for the chat and canvas is powered by [Socket.IO](http://socket.io/).
File serving is powered by [Express](http://expressjs.com). Data sanitization is powered by
[node-validator](https://github.com/chriso/node-validator).

## Usage


## Issues
* To allow the canvas to be updated simultaneously by multiple users, pen strokes are
drawn as two-point paths, which prevents stroke opacity from displaying as expected.

## Licensing
jQuery, jQuery UI, jQuery miniColors, fileinput, Spinner, jquery.event.drag, Socket.IO, Express,
and node-validator (included dependencies of this project) and their included dependencies
are licensed under their own respective terms, which are listed in the relevant subdirectories.

All other code and assets are licensed under the MIT License as follows:

    Copyright (c) 2011 Vinson Chuong

    Permission is hereby granted, free of charge, to any person obtaining a copy of
    this software and associated documentation files (the "Software"), to deal in
    the Software without restriction, including without limitation the rights to
    use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is furnished
    to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
    FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
    COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
    IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
    CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
