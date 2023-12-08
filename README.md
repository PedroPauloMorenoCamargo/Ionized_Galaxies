# Galactic Vision Library

Welcome to the Galactic Vision Library, a Python tool designed by undergraduate students from INSPER as the culmination of our computer vision course. This library is crafted to assist individuals in the scientific exploration of ionized galaxies, offering essential tools for the analysis of chemical elements within images.

## About Us

We are a team of enthusiastic undergraduate students from INSPER, driven by the desire to showcase our achievements in the field of computer vision. This GitHub page serves as a platform for those passionate about the subject to explore our work and join us in the fascinating world of computer vision.

## Objective

Our project's objective is to create a specialized Python library for the analysis of ionized galaxies. Tailored to support scientific research, the library facilitates a thorough investigation, enabling scientists to identify the types and locations of chemical elements within an input image, ultimately enhancing the clarity of their research.

The library employs a passband filter on the input image, among other steps, to generate an output image highlighting the studied regions through encirclement. For detailed information on the library's functionalities, please visit the procedure page.

## What does the library do?

Our Python library is designed to assist individuals immersed in scientific pursuits. It addresses the common issue of losing code during exploration, offering a free and accessible solution. The pipeline involves converting an image to grayscale, applying a Fourier transform, implementing a pass-band filter, and filtering the original image for the specified band. This process enables the focused study of specific elements, such as hydrogen, by adjusting the band frequency.

Subsequently, the masked image undergoes an inverse Fourier transformation, followed by the application of a Sobel filter to delineate the contours of the studied element. Skeletonization consolidates these contours into a singular curve. Ultimately, the contour is juxtaposed with the original image, enabling a more nuanced examination of galaxies or other relevant contexts. This comprehensive approach enhances the ability to study and understand complex images, providing a valuable tool for scientific exploration.
