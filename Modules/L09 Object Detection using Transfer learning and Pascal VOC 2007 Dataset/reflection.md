# L09 Object Detection using Transfer Learning and Pascal VOC 2007 Dataset

This assignment provided a hands-on introduction to the exciting world of object detection! I used the SSD MobileNet V2 model and the Pascal VOC 2007 dataset to learn how to identify and locate multiple objects within images.

**Object Detection vs. Image Classification:**

Unlike image classification, which assigns a single label to an entire image, object detection goes further by:

* **Identifying Multiple Objects:**  Recognizing various objects present in an image.
* **Localization:**  Pinpointing the location of each object using bounding boxes.

**Why SSD MobileNet V2?**

I chose the SSD MobileNet V2 model for this task because it strikes a good balance between:

* **Speed:** It's designed for efficient inference, making it suitable for real-time applications.
* **Computational Efficiency:**  It requires fewer resources, which is beneficial for deployment on devices with limited processing power.

**Key Learnings:**

* **Filtering Images:** I learned how to filter the Pascal VOC 2007 dataset to focus on specific object classes of interest.
* **Confidence Thresholds:** I experimented with adjusting confidence thresholds to control the sensitivity of object detection.
* **Real-World Scenarios:** I tested the model on real-world images to evaluate its performance in practical situations.

**Challenges and Observations:**

* **Small Object Detection:** The model struggled to accurately detect smaller objects within images.
* **Complex and Overlapping Objects:**  Objects with complex shapes or those that overlapped with each other also posed challenges for the model.

This project provided valuable experience in applying object detection techniques and highlighted the importance of model selection and parameter tuning for achieving optimal performance.
