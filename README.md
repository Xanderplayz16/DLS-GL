# DLS-GL
DLS-GL is a port of Digital Logic Sim to the web.
There actually is not any code difference of code to Digital Logic Sim, so no source code is here.
https://xanderplayz16.github.io/DLS-GL/index.html
# To build yourself
Go to file/build settings and set the build to use WebGL.

Go to edit/project settings/player/publishing settings and set the Decompression fallback checkbox to checked. // This fixes some things.

Now go to file/build settings/WebGL/ and set your settings. I personally build for speed and I use ETC2 in the build above. // When built for speed, the files are 42 megabytes.

Now just press build, select a directory and wait for it to build. // Double-clicking the HTML file will not work, you need to host a web server. If you have python installed, you can open the command prompt, CD to the directory that you selected earlier, and run the command python -m http.server. Now you can open 127.0.0.1:8000 in your web browser.
