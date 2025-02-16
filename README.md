#  Mini-Challenge_W25

- **School:** University of Michigan-Flint
- **Course:** Ethics and Bias in AI 
- **Semester:** Winter 2025
- **Lecturer:** Prof. Rania Khalsi 

## About the Challenge
This is a class task assigned to the students of Ethics and Bias in (ARI 515). It was carried out by team members of the class. 
The mini-challenge is about bridging the bias in cancer image dataset which in turn is used to build a machine learning model that will perform optimally across different skin colors. In this challenge the dataset is gotten from open-source, which goes through series of preprocessing to obtain resized greyscale images with contours. The results are then run through a sample machine learning algorithm and adjusted to give a positive accuracy.

## Background

Cancer image datasets are crucial for developing and training machine learning models aimed at early detection, diagnosis, and treatment planning. However, these datasets often suffer from biases that can significantly impact the performance and generalizability of the models. One common source of bias is the underrepresentation of certain demographic groups, such as racial minorities, older adults, or individuals from low-income regions. This lack of diversity can lead to models that perform well on the majority population but fail to accurately diagnose or predict outcomes for underrepresented groups. Additionally, the quality and resolution of images can vary based on the equipment used, which may differ across healthcare facilities, further introducing bias into the dataset.

Another significant source of bias in cancer image datasets is the annotation process, which often relies on human experts to label the images. Variations in expertise, subjective interpretations, and even fatigue can lead to inconsistent or inaccurate annotations. Moreover, the selection of images for inclusion in the dataset may be influenced by the researchers' or clinicians' preferences, leading to a skewed representation of certain types of cancer or stages of the disease. These biases can propagate through the machine learning pipeline, resulting in models that may not be reliable or equitable across different populations or clinical settings. Addressing these biases requires a concerted effort to ensure diversity in dataset collection, standardization of imaging protocols, and rigorous validation processes to create more robust and fair models.

Most cancer dataset have very little or no data for people of color. Therefore, the skin color images may be the best in training a model to test data of different races. This mini-challenge focuses on the solving the bias by using contours of the cancer images to classify the dataset.

## Methodology


### Tools & Technologies
- Jupyter Notebook
- 


### Procedure

- **Data Processing:** This step involves downloading open source data on cancer images and preprocessing the data. The pre-processing includes grayscaling, making images the same size, getting rid of null values, balancing if need-be, and blurring/cropping images to ONLY include the lesion.

- **Contours & Binarization:** After preprocessing the dataset to include only grayscale images with lesion, this next step figures out the contours frOm the grayscale images.
  
- **Algorithm Comparison:** This step is where the finished dataset is run through a sample machine learning algorithm, then the dataset is adjusted as needed to ensure results are positive. The results are then compared between unprocessed, preprocessed, and contour datasets.
  
- **Github Organization & Presentation:** The results from the previous step are compiled for presentation.

## Discussion (Observations)


## Conclusion





## Contributors


## External resources
- https://challenge.isic-archive.com/data/
- https://drive.google.com/drive/folders/1LEGEXY7pqHgJAWipZUu_xp6qKVCF1z3D
