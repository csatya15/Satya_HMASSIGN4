Student Id: 700769823 Student Name: Satya Bhaskar Chaliki


**Basic GAN for MNIST Digit Generation**

 Description
This project implements a simple Generative Adversarial Network (GAN) using PyTorch to generate handwritten digits similar to those in the MNIST dataset. It includes a generator and discriminator network, a training loop with alternating updates, and visual outputs at different training stages.

 Requirements
Python 3.x

PyTorch

torchvision

matplotlib

Install dependencies using:

bash
Copy
Edit
pip install torch torchvision matplotlib

 Outputs
Generated image samples saved at:

samples/epoch_0.png

samples/epoch_50.png

samples/epoch_100.png

Loss comparison plot:

samples/loss_plot.png


 Deliverables
 Generated image samples (Epochs 0, 50, 100)

Loss plot of generator vs discriminator over time

 
**Data Poisoning Simulation on a Sentiment Classifier**

 Description
This project demonstrates a data poisoning attack on a sentiment classifier using scikit-learn. It flips sentiment labels for sentences containing a targeted entity (e.g., "UC Berkeley") in the training data to simulate malicious data injection.

 Requirements
Python 3.x

scikit-learn

matplotlib

numpy

Install dependencies using:

bash
Copy
Edit
pip install scikit-learn matplotlib numpy
 Components
Simple dataset with labeled positive/negative movie review sentences.

Naive Bayes sentiment classifier trained on clean and poisoned data.

Accuracy and confusion matrix comparison before and after poisoning.

 Outputs
Accuracy before and after poisoning (printed in console)

Confusion matrix plots displayed for both models.
 Deliverables
 Confusion matrix before and after poisoning

 Printed accuracy values for comparison

 Explanation of how label flipping degrades model performance
