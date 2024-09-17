---
layout: post
categories: update
title: Resize Images
date: 2024-09-17 00:00:00 -0400
# author: name (optional)
---
Showing that images can be resized and how to arange them with ```<br>```

![image 1]( /images/test-example-2.png ){: width="250" }
![image 2]( /images/test-example-2.png ){: width="100" }

![image 3]( /images/test-example-2.png ){: width="300" }

Also, layout.
If you don't leave blank line between things, they will try to appear on the same line. (first two images.)
Even if you leave a blank line, the two things will be touching. (first image touching third image.)<br>
<br>

---
<br>

![image 2]( /images/test-example-2.png ){: width="100" }
![image 2]( /images/test-example-2.png ){: width="100" }
![image 2]( /images/test-example-2.png ){: width="100" }

This (above) is slightly different from this (below).

![image 2]( /images/test-example-2.png ){: width="100" }![image 2]( /images/test-example-2.png ){: width="100" }![image 2]( /images/test-example-2.png ){: width="100" }

<br>

---
<br>

To avoid this, use ```<br>```, which means new line.

![image 1]( /images/test-example-2.png ){: width="250" } This ```<br>``` moves image 2 to the next line.<br>
![image 2]( /images/test-example-2.png ){: width="100" } This ```<br>``` moves what ever is after it down a line.<br>
This line and ```<br>```'s after it adds an extra line, making some white space between image 2 and 3.<br><br>
![image 3]( /images/test-example-2.png ){: width="300" }
<br><br>

---

So if I have some text.
















Leave a bunch of white space.


















These lines will appear just next to each other.

<br>

So if I want space.
<br><br><br><br><br><br><br><br><br><br>
A bunch of ```<br>``` will do the trick.