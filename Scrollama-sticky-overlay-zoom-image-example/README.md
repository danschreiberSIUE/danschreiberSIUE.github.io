This scrollytelling example is a sticky overlap with a sticky image and going through the steps will zoom in and out of parts of the picture.

Example of non-D3 scrollytelling from scrollama.js, pared down from the original documentation examples.

Look at https://jsoma.github.io/simplified-scrollama-scrollytelling/

A lot of work needs to be done to figure out how to properly pan and zoom the image, including
how to center the zoomed area within the circle that is centered on the screen.

The issue is that in CSS when you zoom, it doesn't respect the translate coordinates, even with a new origin, it enlarges the entire image, which then moves the center of what you want displayed.

I wonder if requiring a specific size for an image might help with some of this?
