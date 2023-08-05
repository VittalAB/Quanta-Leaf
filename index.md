# Web App White Paper (QuantaLeaf): Disease Diagnosis and Recommendation System ⚙

## 1. Introduction to Disease

In today's world, timely and accurate disease diagnosis is crucial for effective management of yield in agriculture. This white paper presents a web application that leverages advanced AI algorithms and a comprehensive dataset collection to offer a reliable disease diagnosis and recommendation system for Late Leaf Spot and Rust in Groundnut which causes 70% of yield loss. Thus it becomes very crucial to identify the disease at early stages.

## 2. AI Algorithm 🤖

The heart of our web app lies in its sophisticated AI algorithm. Using machine learning and deep learning techniques, our algorithm analyzes leaf image and extracts valuable insights. It can identify patterns, anomalies, and trends in image data, aiding farmers and researchers in making informed decisions.

## 2.1 Phases  

--> Image Classification
--> Severity Quantification
--> Recommendation Algorithm 

## 2.1.1 Image Classification 

In this phase, our major goal is to classify the input image into three classes, such as LLS, rust, and Healthy. For image classification, we have employed keras model trained over with 2000 images.

![Image Classification](https://github.com/VittalAB/Quanta-Leaf-/assets/59869004/a7a29148-0d4b-470d-9b1e-3e2d7a662921)

Above figure shows the image classification 

## 2.1.2 Severity Quantification 

In this phase we quantify the diesase and find out the percentage of infected area and also count how many instances are there in a leaf i.e. how many spots are present in one leaf based on which the disease score would be finalized. Here we have employed object detection mechanism to identify the spots and count and color based analyisis to quantify the percentage of leaf infected. For object detetcion we have used Faster-RCNN algorithm.

![Object Detection Algorithm](https://github.com/VittalAB/Quanta-Leaf-/assets/59869004/1cca4ecf-8224-4568-b553-deb5780cc021)

<p align="center">
  <img src="https://github.com/VittalAB/Quanta-Leaf-/assets/59869004/bf59bcb1-1af9-46a3-8eec-08e237cd8074" />
</p>

## 2.1.3 Recommendation System 

This phase comprises all of the above-mentioned steps, It starts with taking the input image, classifying the disease, quantifying the disease, and recommending the fungicide based on the infection intensity and weather conditions, This would help to understand the yield of the crop and measures to be taken to prevent more loss. Our tool recommends the right quantity of fungicide based on the severity of the disease, thus preventing excessive usage of the fungicide.

![Workflow of the System ](https://github.com/VittalAB/Quanta-Leaf-/assets/59869004/1aa96619-8375-4b62-a249-fbaf96d9c315)


## 3. Dataset Collection

Accurate disease diagnosis depends on diverse and high-quality datasets. Our web app has undergone an extensive dataset collection process, compiling anonymized leaf images and healthy leaf images which were collected in UAS Dharwad under concerned authorities. It consists of 3000 images in total. The dataset was used for training out AI model.

## 4. Conclusion

Finally we can conclude that our model was able to classify and identify the disease with 99% of accuracy and recommends fungicde quantity based on severity and weather based preediction which provides real time insights and predicts the future infection rate.


<p align="center">
  <img src="https://github.com/VittalAB/Quanta-Leaf-/assets/59869004/e7e34a65-6e39-452d-a7e8-55e393350847" />
</p>

### <i> For more details and a deeper understanding of our web app's capabilities, we are planning to release android version of the same and host our web tool soon. </i> 😊✌


