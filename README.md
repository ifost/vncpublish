# vncpublish
Greg wrote vncpublish because he wanted a client-less readonly VNC-viewer. It lets you publish a VNC server as plain HTML pages (no 
JavaScript even) -- just images and a wrapper page which refreshes the images every few seconds. It is useful for keeping on an intranet 
to monitor pesky server applications which report errors to a desktop. It is also useful for delivering presentations over the web to 
staff at large corporations who aren't allowed to install any kind of viewer plugin. And with a few tweaks and a bit of planning, it 
would probably be the most scalable screen sharing solution, since each screenshot is chopped into small parts which can be more easily 
cached in a proxy server. Requires: expect, ImageMagick or GraphicsMagick, md5sum and sftp.
