# Circle-Detector
In many image processing applications, we are looking for a specific shape within an image (such as the outline of a car in traffic images). In this project, the desired shape is a circle that is insensitive to rotation. One of the applications of circle detection is the identification of relatively round cells in microscopic images.
\n
In this project, two different approaches are used for circle detection:
\n
a) In this case, the radius of the circle is known in advance. We are only looking for circles with the specified dimensions, and even if the image contains circles with different dimensions, they should not be detected.
\n
b) The radius of the circle is unknown, and we are searching for the detection of all circles present in the image.
\n
In case (a), commonly an image of the target pattern (in this case, a circle) is taken into account, and the locations of matches are determined using the correlation criterion. Simply put, the correlation value determines which parts of the image exhibit a high similarity to the desired pattern. For case (b), a method called "Gradient Vector Pairings" is used, which will be explained further.
\n
This project consists of four sections: three sections related to finding circles with a known radius (direct correlation method, correlation using DFT, and correlation on derivative images), and one section focused on finding circles with an unknown radius.
