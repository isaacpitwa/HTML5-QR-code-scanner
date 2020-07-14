# HTML5 QR code scanner
QR Code is a very common technique of encoding information as images. Its a very common used in physical stores for identifying products like bar code is used.

The javascript library available at [mebjas/html5-qrcode](mebjas/html5-qrcode) on Github allows users to add a QR code scanner in their web applications. It works cross-platform and across different devices like PC, Mac or smartphones.

It uses the stream from the camera and try to decode frames at a certain frequency (configurable) and notify the caller about results via callbacks. Requesting camera permissions in browsers usually results in a permission dialog popup to users for requesting permissions and can only be used if the user grants them.