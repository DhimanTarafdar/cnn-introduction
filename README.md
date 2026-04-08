# CNN Introduction 

এই notebook-এ আমি Convolutional Neural Network (CNN)-এর basic থেকে core concept পর্যন্ত step-by-step শিখেছি এবং বুঝেছি।
এটা মূলত আমার learning journey-এর একটা অংশ যেখানে আমি image processing এবং deep learning-এর foundation তৈরি করছি।

---

## এই Notebook-এ যা যা শিখেছি

### Image Basics

* Image আসলে pixel-এর grid (matrix)
* Grayscale vs RGB image
* Image shape: (H, W, C)

---

### CNN (Convolutional Neural Network)

* CNN কী এবং কেন ব্যবহার করা হয়
* কেন CNN normal neural network থেকে ভালো image data handle করতে পারে

---

### Convolution Operation

* Filter / Kernel কীভাবে কাজ করে
* কীভাবে image-এর উপর sliding করে feature বের করে
* Feature Map তৈরি হওয়া

---

### Important Concepts

####  Stride

* Filter কত step করে move করবে

####  Padding

* Output size control করার জন্য border-এ pixel add করা

---

### Activation Function

* ReLU (Rectified Linear Unit)
* কেন non-linearity দরকার

---

### Pooling Layer

* Max Pooling / Average Pooling
* কেন dimension reduce করা হয়
* গুরুত্বপূর্ণ feature retain করা

---

### Feature Extraction

* CNN কীভাবে ধাপে ধাপে edge → shape → object চিনে

---

### Flatten & Fully Connected Layer

* 2D feature map → 1D vector (Flatten)
* Fully Connected Layer দিয়ে final prediction

---

