# Breast Cancer Tumor Classification

Built a convolutional neural network to classify the malignant or benign tumor and its severity.

## Summery

Cancer is massive public health problem around the world. According to the International Agency for Research on Cancer (IARC) 27 million of new cases are expected to occur until 2030. Among the cancer types, breast cancer is second most common for women, excluding skin cancer.

Despite significant progress reached by diagnostic imaging technologies, the final breast cancer diagnosis, including grading and staging, continues being done by pathologists applying visual inspection of histological samples under the microscope. Recent advances in image processing and machine learning techniques allow to build CAD systems that assist pathologists to be more productive, objective and consistent in diagnosis. The main challenge of such system in dealing with inherent complexity of histopathological images. In this effort, I try to create a model using convolutional neural network (CNN) to improve on existing model.


## Data

The Breast Cancer Histopathological Image Classification [(BreakHis)](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/) is  composed of 7,909 microscopic images of breast tumor tissue collected from 82 patients using different magnifying factors (40X, 100X, 200X, and 400X). 

It contains 2,480  benign and 5,429 malignant samples (700X460 pixels, 3-channel RGB, 8-bit depth in each channel, PNG format).

Both breast tumors benign and malignant can be sorted into different types based on the way the tumoral cells look under the microscope. Various types/subtypes of breast tumors can have different prognoses and treatment implications. 
The dataset currently contains four histological distinct types of benign breast tumors: adenosis (A), fibroadenoma (F), phyllodes tumor (PT), and tubular adenona (TA);  and four malignant tumors (breast cancer): carcinoma (DC), lobular carcinoma (LC), mucinous carcinoma (MC) and papillary carcinoma (PC).



## Built With

The models run and test on p2-xlarge nodes from [AWS Amazon](https://aws.amazon.com/). 

I use [Keras](https://keras.io/) API for this project. 
Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation. 


