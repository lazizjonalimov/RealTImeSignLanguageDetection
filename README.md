# **Real Time Sign Language Detection**

## **Overview**
This project is aimed to help deaf people communicate through hand signs. It is a machine learning model that uses **TensorFlow** and **OpenCV**, and **Computer Vision** to recognize human hand signs. The model is trained on a dataset of hand sign images, and can be used to classify new images of hand signs.

## **Requirements**
**Python 3.x**\
**TensorFlow 2.x**\
**OpenCV**
**Numpy**

## **Usage**
1. Clone the repository: \
`git clone https://github.com/username RealTImeSignLanguageDetection.git`
2. Install the required packages:\
`pip install -r requirements.txt`
3. Train the model:\
`python training.py`
4. Test the model:\
`python tests.py`


## **Dataset**
The model is trained on a dataset of hand sign images, containing different hand signs for each letter of the alphabet. The dataset was obtained from the ASL Alphabet dataset.

## **Model Architecture**
The model is a convolutional neural network (CNN) architecture, which is known to be effective in image classification tasks. The model is trained using the <a href="https://teachablemachine.withgoogle.com/train">Teachable Machinee</a> and categorical cross-entropy loss function.

## **Results**
The model achieves a high accuracy on the test set. The model can be further optimized by using more data, fine-tuning the hyperparameters or using Transfer Learning.

## **Conclusion**
The model is a proof of concept that demonstrates the potential of machine learning to help deaf people communicate through hand signs. This project can be further developed and integrated into an application to help deaf people communicate more easily.

## **Contribution**
Any contribution will be appreciated, please feel free to open an issue or make a pull request.

## **Authors**
Iskandar Kholmatov\
Lazizjon Alimov\
Maarij Mohi Uddin\
Sadwal Patel
