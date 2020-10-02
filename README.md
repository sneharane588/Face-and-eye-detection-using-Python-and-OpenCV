# Face-and-eye-detection-using-Python-and-OpenCV

Here I've performed basic face detection and Eye detection using Haar Feature-based Cascade Classifiers.

![optimized-face-eye-detect](https://user-images.githubusercontent.com/19407823/94596795-44638200-02aa-11eb-834b-08eada896078.gif)

<b>Object Detection using Haar feature-based cascade classifiers</b> is an effective object detection method proposed by <b>Paul Viola and Michael Jones</b> in their paper, “Rapid Object Detection using a Boosted Cascade of Simple Features” in 2001. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images.

Initially, the algorithm needs a lot of positive images (images of faces) and negative images (images without faces) to train the classifier. Then we need to extract features from it. For this, haar features shown in below image are used. They are just like our convolutional kernel. Each feature is a single value obtained by subtracting sum of pixels under white rectangle from sum of pixels under black rectangle.

![haar_features](https://user-images.githubusercontent.com/19407823/94596804-488f9f80-02aa-11eb-898d-891a20d39c01.jpg)

So this is a simple intuitive explanation of how <b>Viola-Jones face detection</b> works.
