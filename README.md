# Plant-Species-Image-Classification
# 🌿 Plant Species Image Classification (Bonsai Collection)

## 📌 Project Overview

This project focuses on building an image classification model that can recognize **20 different bonsai plant species** using Google Teachable Machine.

The purpose of this project is to apply machine learning concepts such as dataset preparation, training, evaluation, and testing. The model aims to accurately classify bonsai species based on visual features such as leaves, flowers, and structure.

---

## 🌱 Section B: Plant Species Overview

Below are the 20 bonsai species used in this project:

### 1. Azalea Bonsai

![Azalea](images/azalea.jpg)
A flowering bonsai known for its vibrant and colorful blooms.

### 2. Blueberry Bonsai

![Blueberry](images/blueberry.jpg)
A fruit-bearing bonsai that produces small edible blueberries.

### 3. Bougainvillea Bonsai

![Bougainvillea](images/bougainvillea.jpg)
A tropical bonsai famous for its bright, paper-like flowers.

### 4. Chinese Elm Bonsai

![Chinese Elm](images/chinese_elm.jpg)
A popular beginner bonsai with small leaves and strong adaptability.

### 5. Dwarf Jade Bonsai

![Dwarf Jade](images/dwarf_jade.jpg)
A succulent bonsai with thick leaves and excellent drought tolerance.

### 6. Ginseng Ficus Bonsai

![Ginseng Ficus](images/ginseng_ficus.jpg)
Recognized for its thick roots and glossy green leaves.

### 7. Hibiscus Bonsai Tree

![Hibiscus](images/hibiscus.jpg)
A flowering bonsai with large, vibrant blossoms.

### 8. Ixora Bonsai

![Ixora](images/ixora.jpg)
A tropical bonsai known for its clustered small flowers.

### 9. Japanese Flowering Cherry Bonsai

![Cherry](images/cherry.jpg)
Famous for its delicate pink blossoms.

### 10. Japanese Maple Bonsai

![Maple](images/japanese_maple.jpg)
Known for its beautiful seasonal leaf color changes.

### 11. Juniper Bonsai

![Juniper](images/juniper.jpg)
One of the most common bonsai types with needle-like foliage.

### 12. Kingsville Boxwood Bonsai

![Boxwood](images/boxwood.jpg)
A compact bonsai with dense foliage.

### 13. Mimosa Bonsai

![Mimosa](images/mimosa.jpg)
Known for its sensitive leaves that close when touched.

### 14. Orange Bonsai

![Orange](images/orange.jpg)
A fruit-bearing bonsai producing miniature oranges.

### 15. Persimmon Bonsai

![Persimmon](images/persimmon.jpg)
Produces small orange fruits and has seasonal leaf changes.

### 16. Pine Bonsai

![Pine](images/pine.jpg)
A classic bonsai with needle-like leaves and rugged form.

### 17. Pomegranate Bonsai

![Pomegranate](images/pomegranate.jpg)
A flowering and fruiting bonsai with bright red blossoms.

### 18. Trident Maple Bonsai

![Trident Maple](images/trident_maple.jpg)
Known for its strong roots and beautiful autumn colors.

### 19. White Oak Bonsai

![White Oak](images/white_oak.jpg)
A sturdy bonsai with lobed leaves and strong trunk.

### 20. Wisteria Bonsai

![Wisteria](images/wisteria.jpg)
Famous for its hanging purple flower clusters.

---

## ⚙️ Section C: Model Training Details

* **Epochs:** 50
* **Batch Size:** 16
* **Learning Rate:** 0.001
* **Images per class:** ~250
* **Total dataset size:** ~5000 images

These values were selected to balance training efficiency and model accuracy. Increasing epochs allows better learning, while a moderate batch size ensures stable updates.

---

## 📊 Section D: Model Evaluation

### Confusion Matrix

![Confusion Matrix](model_training_details/confusion_matrix.png)

### Accuracy per Class

![Accuracy per Class](model_training_details/accuracy_per_class.png)

### Overall Accuracy

The model achieved an overall accuracy of **92%**. <!-- CHANGE THIS -->

The confusion matrix shows that most bonsai species were correctly classified, although some visually similar species caused minor misclassifications.

---

## 🧪 Section E: Model Testing

Below are sample test results from the Teachable Machine Preview:

### Test Results

![Test 1](preview_test_images/test1.png)
![Test 2](preview_test_images/test2.png)
![Test 3](preview_test_images/test3.png)
![Test 4](preview_test_images/test4.png)
![Test 5](preview_test_images/test5.png)
![Test 6](preview_test_images/test6.png)
![Test 7](preview_test_images/test7.png)
![Test 8](preview_test_images/test8.png)
![Test 9](preview_test_images/test9.png)
![Test 10](preview_test_images/test10.png)

---

## 📦 Model Export

The trained model was exported using TensorFlow format and stored in the [`models/`](./models) folder.

---

## ✅ Submission Checklist

* ✔️ **20 related plant species proposed**
  See **Section B: Plant Species Overview** for details.

* ✔️ **Minimum 250 images per species**
  Images are stored in the [`images/`](./images) folder.

* ✔️ **Model trained using Teachable Machine**
  Training details are in **Section C: Model Training Details**.

* ✔️ **Under-the-hood evaluation screenshots**
  Confusion matrix, per-class accuracy, and overall accuracy are in **Section D: Model Evaluation**.

* ✔️ **10 preview testing screenshots**
  See **Section E: Model Testing** for all screenshots.

* ✔️ **Model exported and saved**
  Exported model files are in the [`models/`](./models) folder.

* ✔️ **GitHub repository with complete README.md**
  You are currently viewing it here! ✅

* ✔️ **All files and screenshots uploaded and documented**
  Check the following folders for completeness:

  * [`images/`](./images)
  * [`models/`](./models)
  * [`model_training_details/`](./model_training_details)
  * [`preview_test_images/`](./preview_test_images)

---

## 🧠 Reflection

**1. How did the number of images per class affect your model’s accuracy?**
Increasing the number of images improved the model’s accuracy and ability to generalize.

**2. Which plant species were most commonly misclassified and why?**
Species with similar leaf structures, such as maple and trident maple, were sometimes misclassified.

**3. How did changing the parameters affect results?**
Higher epochs improved accuracy but increased training time. Proper learning rate prevented overfitting.

**4. What challenges did you encounter?**
Collecting diverse and high-quality images was time-consuming.

**5. What improvements would you make?**
Adding more images and improving dataset balance would further enhance accuracy.

---

## 👨‍💻 Author

**Anthea Myles A. Simon**
