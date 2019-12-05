**COMPUTER VISION SYSTEM FOR SELF-DRIVING-CARS**

A self-driving car, also known as an autonomous vehicle (AV), connected and autonomous vehicle (CAV), driverless car, robo-car, or robotic car, is a vehicle that is capable of sensing its environment and moving safely with little or no human input. (for more - check - [WIKI](https://en.wikipedia.org/wiki/Self-driving_car))

The **computer vision system** for **self driving cars** has a very wide range of methods and functionality for full performance. What is given specifically in this system? a simple implementation of one of the systems of computer vision, with the help of which, while driving, the car will be able to **find and identify lanes of road traffic**, thereby building for itself a path along the road.

**STEP-BY-STEP**

First, we determine the dimension of the photo:
![Size (X and Y)](https://sun9-17.userapi.com/c854428/v854428154/192090/F0cBbsJaqTY.jpg)

Second, we defined the zone of interest:

![After various filters and transformations, we get what we need - road markings](https://sun9-43.userapi.com/c854428/v854428154/1920b5/fze2dgVUql8.jpg)

Step three - If we bring the picture closer, we will understand that it has such a form that our stripes will be marked with a value of 255, while everything else will be zeros. We mark our marked area with lines for identification.

![Result](https://sun9-44.userapi.com/c854428/v854428409/195fbb/yyZIKv2yTrc.jpg)

Let us look at the operation of the algorithm with other pictures, as well as with video (the previous example showed the identification of lines on roads in the city of Tver, Russia)

Step five - we improve the algorithm, set the angular coefficient (pi / 180 degrees), we also use the straight line formula for the coordinate system:

![Formula for lines](https://d321jvp1es5c6w.cloudfront.net/sites/default/files/imce-user-gen/a1m4l8image6.jpg)


**VIDEO**
<a href="https://j.gifs.com/q7pmBD.gif"><img src="https://j.gifs.com/q7pmBD.gif" title="Real time detection"/></a>
