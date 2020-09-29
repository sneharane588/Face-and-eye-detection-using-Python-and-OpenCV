# Face-and-eye-detection-using-Python-and-OpenCV

Here I've performed basic face detection and Eye detection using Haar Feature-based Cascade Classifiers.

<b>Object Detection using Haar feature-based cascade classifiers</b> is an effective object detection method proposed by <b>Paul Viola and Michael Jones</b> in their paper, “Rapid Object Detection using a Boosted Cascade of Simple Features” in 2001. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images.

haar_features

Initially, the algorithm needs a lot of positive images (images of faces) and negative images (images without faces) to train the classifier. Then we need to extract features from it. For this, haar features shown in below image are used. They are just like our convolutional kernel. Each feature is a single value obtained by subtracting sum of pixels under white rectangle from sum of pixels under black rectangle.

optimized-face-eye-detect

So this is a simple intuitive explanation of how <b>Viola-Jones face detection</b> works.
