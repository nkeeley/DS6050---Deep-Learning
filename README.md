# DS6050 - Deep Learning

Language types: Python

This repository contains the assignments and projects related to a Deep Learning course. Topics included the architectures of Convolutional Neural Networks (CNNs), construction of CNNs from scratch and via Tensorflow Keras, the creation of recurrent neural networks, the application of transfer learning, and the detection of GAN-generated satellite images. Note: To facilitate efficiency, all assignments contained varying degrees of templated material provided by the professor. Also, all assignment were run in GoogleCollabPro to reduce runtime duration/RAM maxout.

### ngk3pf_assignment_1_ann(2).ipynb

In this assignment, I was tasked with building a neural network from "scratch" using native Python functions to solve the XOR problem. I then compared this models performance, after hyperparameter tuning, against a neural network produced through TensorFlow Keras. With tuning, my model eventually outperformed the TensorFlow Keras model.

### ngk3pf_assignment_2(1).ipynb

In this assignment, I applied transfer learning by using several ImageNet-ready, Convolutional Neural Networks (CNNs) to solve an image classification problem.

### ngk3pf_assignment_3(2)

In this assignment, we were given a template of a recurrent neural network and asked to adjust/fill-in specific portions of the code. The network was able to receive sheet music of popular tunes and reproduce music outputs that made "sense." Given the size of the file, it is not available here. However, you may access a similar template at MIT's site: https://github.com/aamini/introtodeeplearning/. My own file is located in the "SY_Q3/DL" folder of my Dropbox, or via Jupyter Notebook.

### Final Project: Detecting GAN-generated Fake Satellite Imagery

- Description: For our final project, my team decided to tackle a growing problem in the intelligence community of GAN-generated fake satellite imagery. Using a pre-processed GAN dataset, as well as real satellite images of Seattle, we tested the performance of a newly developed neural network family within the human facial imagery community called "Meso" nets.  I downloaded this data and made it processable by our anticipated neural network architectures, as well as replicated these Meso networks, as described by Afchar, et al.. Ultimately, our team compared their performance against Google's Inception network, and also investigated the activation maximizations of each network's layer filters to determine what each network "sees" when it evaluates fake vs. real satellite images.

- Associated files: "DL_FinalProject_Consolidated_FINAL.ipynb" contains the code for this project. "DL_FinalProject_Deepfake sat imagery_Report_FINAL.docx" is the final writeup for our project, and contains details on the data, methods, and results of our project.
