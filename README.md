# Handwritten_digit_recognition_using_CNN
Handwritten Digit Recognition Using CNN

Introduction:
This project focuses on using Convolutional Neural Networks (CNNs) to automatically recognize handwritten digits from images. By training on datasets like MNIST and EMNIST, the system can classify digits (0–9) with high accuracy, supporting applications in digitized forms, automated postal systems, banking (cheque processing), and educational tools.

Keywords:
Deep Learning, CNN, Handwritten Digit Recognition, Image Classification, MNIST, EMNIST

Literature Review:
CNNs have become the state-of-the-art approach for image recognition tasks due to their ability to automatically learn spatial hierarchies and features from images. LeCun et al. (1998) demonstrated the success of CNNs on the MNIST dataset for handwritten digit classification. More recent studies show that deeper architectures with multiple convolutional and pooling layers can achieve accuracies above 99% on MNIST and its variants, including EMNIST. Data augmentation and dropout techniques are commonly used to reduce overfitting and improve generalization.

Application Survey:
Accurate handwritten digit recognition has practical applications in:

Banking: Automated cheque processing and digit extraction.

Postal Services: Sorting letters based on zip codes.

Education: Digit recognition in student answer sheets or exams.

Form Digitization: Converting handwritten forms into digital data for storage and analysis.

Methodology:

Data Collection: Used MNIST and EMNIST datasets containing tens of thousands of handwritten digit images.

Preprocessing: Normalized pixel values, reshaped images to fit CNN input, and encoded labels for classification.

Model Architecture: Implemented a CNN with convolutional layers for feature extraction, pooling layers for dimensionality reduction, and dense layers with softmax activation for classification.

Training: Trained the model using categorical cross-entropy loss and Adam optimizer, with early stopping to prevent overfitting.

Evaluation: Evaluated model performance using accuracy, confusion matrix, and loss curves on validation and test sets.

Results and Discussion:

Achieved an accuracy of ~99% on MNIST and ~95–97% on EMNIST digits.

CNN successfully captured complex patterns of handwritten digits, including variations in stroke thickness and orientation.

Model generalizes well to unseen digit samples and handles noisy or imperfect handwritten inputs.

Conclusion:
The CNN-based handwritten digit recognition system demonstrates the power of deep learning for automated image classification tasks. It provides a reliable and scalable solution for digit recognition and can be extended to other handwriting-based tasks or more complex datasets.

References:

LeCun, Y., Bottou, L., Bengio, Y., & Haffner, P. (1998). “Gradient-based learning applied to document recognition,” Proceedings of the IEEE.

Cireșan, D. C., Meier, U., & Schmidhuber, J. (2012). “Multi-column deep neural networks for image classification,” IEEE Conference on Computer Vision and Pattern Recognition.

MNIST Dataset: http://yann.lecun.com/exdb/mnist/

EMNIST Dataset: https://www.nist.gov/itl/products-and-services/emnist-dataset
