# BrainAbnormalityCategorization

In the past decade, developments in the field of medical analysis and imagery have been exponential. Logical approaches to intricate problems have played a significant role in the larger picture: medical diagnosis and treatment. This paper discusses the detection of brain abnormalities, casualties, and complex analysis of medical imagery such as Magnetic Resonance Images and X-rays in a more focused spectrum. The most common occurring brain disorders today stem from brain abnormalities. The general practice is to have a neurologist analyse many patient images, which becomes extremely tedious and inefficient. In this work, we propose an abnormality detection workflow revolving around advanced machine learning techniques to study the brain's medical images (X-rays/MRIs).
With more than 700 unlabelled patient images, we would label and pre-process these images (resizing, orientation, grayscale, and noise removal). Then, further classifying the images into 'brain' and 'not brain' using a neural network-based classifier framework. Further with the annotated photos of the different parts of the brain in required forms like bounding boxes and polygons. With these concrete brain images and a convoluted neural network architecture, we will classify the brain images; 'Normal' and 'Abnormal.' These predictions will be based on the learning from training data. The further steps in classification include modifications to improve accuracies and training on larger datasets to get a better fit.

<img width="296" alt="Screenshot 2021-12-04 at 11 46 16 AM" src="https://user-images.githubusercontent.com/52413705/144699862-544dd197-77e2-439d-a71b-0d49567ea037.png">

For this project we trained and test several Deep Learning Models to attain the following results:

Model | ANN | CNN | CNN (Augmentation Layer) | VGG16 | AlexNet
--- | --- | --- | --- |--- |--- 
Accuracy | 0.8077 | 0.9231 | 0.8077 | 0.6154 | 0.6923

After a thorough analysis we were able to interpret that CNN model was performing the best.
