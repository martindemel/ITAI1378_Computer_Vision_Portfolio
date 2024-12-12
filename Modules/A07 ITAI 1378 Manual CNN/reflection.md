# A07 ITAI 1378 Manual CNN

In this team project, we delved into the fundamental concept of convolution in Convolutional Neural Networks (CNNs) through a hands-on, manual exploration.

**Our Approach:**

1. **Image Representation:** We started with two 8x8 grids representing simple images: a rectangle and a square.
2. **Filter Design:** We designed 3x3 filters specifically to detect vertical and horizontal edges within the images.
3. **Manual Convolution:**  We simulated the convolution operation by sliding these filters across the 8x8 grids. For each position:
    * We performed element-wise multiplication between the filter and the corresponding section of the grid.
    * We summed the results of the multiplication to obtain a single value.
4. **Feature Maps:**  The resulting values from each filter position were used to create new grids (feature maps) that highlighted the detected features, such as edges and corners.

**Key Takeaways:**

* This manual process provided a clear and intuitive understanding of how convolution operations work within CNNs to extract features from images.
* We gained a deeper appreciation for the role of filters in identifying specific patterns and features.
* By visualizing the feature maps, we could see how the convolution process transforms the input image into a representation that emphasizes important visual characteristics.
