# Midterm Object Detection Challenge

This midterm project pushed my object detection skills to the next level! I tackled the challenge of enhancing an object detection model using the Pascal VOC 2007 dataset.

**Why Not CIFAR-10?**

I initially considered using the CIFAR-10 dataset, but I realized its limitations for object detection:

* **Limited Object Variety:** CIFAR-10 only contains 10 object classes, which is not representative of real-world scenarios.
* **Small Image Size:** The small image size in CIFAR-10 (32x32 pixels) makes it difficult to accurately detect and localize objects.

**Pascal VOC 2007 - A Better Choice:**

The Pascal VOC 2007 dataset provided a more suitable challenge with:

* **Diverse Object Classes:** It includes 20 object classes, offering a wider range of objects for detection.
* **Larger Image Size:** The larger image size allows for more accurate object detection and localization.

**My Approach:**

* **Preprocessing:** I applied various preprocessing techniques to the dataset, including:
    * **Resizing:** Adjusting image dimensions to match the model's input requirements.
    * **Augmentation:**  Increasing dataset diversity by applying transformations like rotations, flips, and crops.
    * **Normalization:** Scaling pixel values to a standard range.
* **Model Selection:** I chose the **SSD MobileNet V2** model for its speed and efficiency, making it suitable for real-time applications.
* **Addressing Overfitting:** I implemented techniques to prevent overfitting, such as:
    * **Dropout:** Randomly dropping out neurons during training to improve generalization.
    * **Class Weight Adjustment:**  Balancing the influence of different classes to improve learning on imbalanced datasets.

**Results:**

By carefully tuning the model and addressing overfitting, I achieved:

* **Training Accuracy:** ~60%
* **AUC (Area Under the Curve):** 78.8%

**Key Takeaways:**

This project reinforced the importance of:

* **Dataset Selection:** Choosing the right dataset is crucial for training effective object detection models.
* **Model Tuning:**  Fine-tuning model parameters and addressing overfitting are essential for achieving good performance.
* **Preprocessing:**  Proper preprocessing techniques can significantly improve the quality of the training data and model accuracy.
