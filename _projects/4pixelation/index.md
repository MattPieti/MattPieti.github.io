---
layout: post
title: Image Pixelation via Spatial Averaging and Resampling
description: Developed programs in MATLAB and Python to pixelate images using two different methods. Included user input for output image pixel size with error checks for invalid inputs.
skills:
  - Image Processing
  - MATLAB
  - Python
  - Algorithm Design & Comparison
  - Input Validation & Error Handling

main-image: /pixcomp.png
---

---

## MATLAB (school project)


Wrote a MATLAB function that takes as inputs image colors and desired pixel block length. The function generates errors for improper inputs, such as non-integer pixel block length. If the function does not return an error, it instead returns data which can be written to an image as a pixelated version of the input image. This was achieved by averaging together colors of n-by-n pixel blocks for the entire image, where n is the pixel block length input.



In the example below, 10-by-10 pixel blocks were used for the output image.

{% include image-gallery.html images="ornament.jpg, pixelatedornament.png" height="400" %}
<span style="font-size: 10px">Image "Costume Ornament with PRofile Portrait" from the National Gallery of Art: https://www.nga.gov/artworks/46288-costume-ornament-profile-portrait</span>  

---

## Python (2025, post-graduation)


Wrote Python code using the Pillow image processing library to take an image as input and output a pixelated version of the input image as a new file. Running the program brings up a UI prompting the user to specify the number of pixel blocks long and tall the image should be. Length and width can be different values. Code includes warnings and errors for improper inputs. This code achieves pixelation by shrinking the input image and stretching it back to original size. This independent version of the project was a self-directed exercise in revisiting and re-evaluating prior work.



In the example below, the output image is 80 pixel blocks tall and 40 pixel blocks wide. These example values result in a more "intense" pixelation than the example values used above in the MATLAB program.

{% include image-gallery.html images="ornament.jpg, pixorn.png" height="400" %}

---

## Key Takeaways


This project demonstrates my ability to reason about algorithms and translate technical concepts across programming environments. Two ideas were reinforced:


* Different strategies can produce similar results with different computational tradeoffs
* Input validation and boundary handling significantly affect robustness

<br>
