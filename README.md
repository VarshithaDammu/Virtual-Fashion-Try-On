# Virtual-Fashion-Try-On
In the online fashion retail industry, customers often face uncertainty when purchasing clothes due to the inability to try them on virtually. This leads to reduced customer satisfaction and increased return rates. To address this challenge, a Virtual Try-On system is proposed to digitally simulate how clothes would look on a person without physically wearing them.
The goal of this project is to build a machine learning-based Virtual Try-On application that allows users to visualize how a selected clothing item would appear when worn. By leveraging computer vision techniques, image processing, and similarity-based recommendations, this system enhances the online shopping experience by making it more interactive, personalized, and confidence-driven.
This project is a web-based Virtual Try-On application that allows users to upload an image of themselves and a clothing item (like a shirt or dress), and then see a visual overlay of the selected clothing on their photo.

The main objectives of this project are:
To simulate a virtual dressing experience using basic image processing.
To recommend similar clothes based on visual features using deep learning.
To use Flask as the backend for web interaction.

Technologies Used:
Frameworks & Libraries: Flask, OpenCV, TensorFlow (Keras), PyTorch, NumPy
Deep Learning Models:
VGG16: For feature extraction to recommend similar clothing items.
DeepLabV3+: For potential segmentation of clothing and background (currently loaded but not actively used).

