---
layout: post
title: Pixelation Programs
description: Developed programs in MATLAB and Python to pixelate images using two different methods. Included user input for output image pixel size with error checks for invalid inputs.
skills:
  - Images Processing
  - MATLAB
  - Python

main-image: /pixcomp.png
---

---

## MATLAB (school project)


Wrote a MATLAB function that takes as inputs image colors and desired pixel block length. The function generates errors for improper inputs, such as non-integer pixel block length. If the function does not return an error, it instead returns data which can be written to an image as a pixelated version of the input image. This was achieved by averaging together colors of n-by-n pixel blocks for the entire image, where n is the pixel block length input.



In the example below, 10-by-10 pixel blocks were used for the output image.

{% include image-gallery.html images="ornament.jpg, pixelatedornament.png" height="400" %}

---

## Python (2025, post-graduation)


Wrote Python code using the Pillow image processing library to take an image as input and output a pixelated version of the input image as a new file. Running the program brings up a UI prompting the user to specify the number of pixel blocks long and tall the image should be. Length and width can be different values. Code includes warnings and errors for improper inputs. This code achieves picelation by shrinking the input image and stretching it back to original size.



In the example below, the output image is 80 pixel blocks tall and 40 pixel blocks wide.

{% include image-gallery.html images="ornament.jpg, pixorn.png" height="400" %}

<br>
