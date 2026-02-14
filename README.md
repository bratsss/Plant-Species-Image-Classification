PLANTS SPECIES IMAGE CLASSIFICATION

A. Project Overview
● Brief description of the project
  -This project aims to create an image classification system that can automatically classify different plant species using digital images. The system employs machine learning or deep learning algorithms to analyze visual characteristics such as leaf shape, color, texture, and patterns. The system is trained on a dataset of plant images, and it learns to classify the plants correctly based on their visual characteristics.
  
● Purpose of the image classification model
  -The primary function of the image classification model is to serve as a fast, accurate, and automated means of plant species identification.The image classification model can be used to support plant education, agricultural monitoring, biodiversity research, and environmental awareness by making plant identification more accessible and efficient.


Answer the following questions based on your experience:
1. How did the number of images per class affect your model’s accuracy?
   - Classes with more images generally performed better because the model had more examples to learn the unique features of each plant. On the other hand, species with fewer images sometimes caused the model to misclassify, as it couldn’t fully capture their variations in shape, color, or lighting conditions.
     
2.. Which plant species were most commonly misclassified and why?
   - Some of the most commonly misclassified species were Spring Onion and Onion, because their leaves and overall appearance look very similar, especially when the bulb is not visible.

3. How did changing the epochs, batch size, or learning rate affect the training results?
   -Increasing epochs helped improve accuracy at first, but too many caused overfitting. Smaller batch sizes made learning more detailed but slower. A balanced learning rate was important — too high made training unstable, while too low made it very slow.
   
4. What challenges did you encounter during dataset collection and labeling?
   -Some plants like Barley, Sugarbeet, and Cotton were hard to find enough clear images for. Many photos had different angles, lighting, and backgrounds. Labeling was also tricky because some plants looked very similar.
   
5. If you were to improve your model, what specific changes would you make and why?
   -I would collect more images, especially for similar-looking plants. I’d also use data augmentation and try a stronger pre-trained model. These changes would help reduce confusion and improve overall accuracy.

