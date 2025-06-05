In these practical sessions, we . To be more specific: 

- In `2-a: Transfer Learning` section, we implemented a transfer learning framework using the entire VGG16 network—except for its last two layers—with pretrained weights on ImageNet. We combined this with several downstream architectures, including a linear SVC and a fully connected layer (with and without propagating the gradients to the rest of the network), to perform a classification task on the 15 Scene dataset, then conducted an analysis of the test results to evaluate and compare the performance of the different configurations.
- In `2-b: Visualization` section, we applied three techniques—Saliency Map, Adversarial Example, and Class Visualization—to study the behavior of convolutional neural networks, specifically how the network processes the image to produce predictions. 
- In `2-c: Domain Adaptation` section, we implemented one of these techniques. The model will be trained on the MNIST and MNIST-M datasets.
- In `2-de: Generative Adversarial Networks` section, 
