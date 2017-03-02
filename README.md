# Web Worker Multi Window Example
This example sets up a dedicated worker in each window that is opened and 
sets up communication directly between the web worker in the primary window
and each web worker in the secondary window.

This allows for high data throughput between the workers without putting any
load on the main window js that relies on the UI.

There is also logic in there to close all windows when the primary window is 
closed.

Note: to run this demo you will need to host the files in your own web server
as the example will not work by just opening the html file in the browser.
