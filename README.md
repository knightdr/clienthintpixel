Client hint pixel
===============

Using css media queries and an image pixel to pass client hints such as min-width, min-resolution, etc. to a server.


What is this?
---------------

This is a simple experiment to see if valuable information about the capabilities of a device/browser can be passed to the server using css and an image with query parameters.
Then evaluate if this works and is any better than current solutions.


Questions
---------------

* Can this be used for responsive images?
* Will the media queries trigger the clinthintpixel.gif request before the first inline image is requested?
* Is this 'better' than using javascript?
* Is this faster than using javascript?
* Is this smaller than using javascript?
* Can we get/control the information better than javascript?
* Is this any better than other RESS techniques? (May need to provide links to these techniques)
* Is cacheing of clinthintpixel.gif an issue? If it is, are there solutions?
* Is making an image request for each feature your testing for a 'bad' idea?
* Am I missing anything?


I'm looking for feedback
---------------

Please create an issue if you know the answer to any of the questions above.

Update: Adaptive-Images by Matt Wilcox
---------------

Besides the javascript cookie method he also outlines a css solution that is very, very close to what this experiement is doing. 
He does list caveats for the css method that you can checkout out in the instructions. https://github.com/MattWilcox/Adaptive-Images/blob/master/instructions.htm

See GitHub project: https://github.com/MattWilcox/Adaptive-Images
