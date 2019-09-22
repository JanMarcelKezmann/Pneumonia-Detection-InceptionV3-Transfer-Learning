# Pneumonia Detection using the InceptionV3 Network

## About

<p>The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).</p>

<p>Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.</p>

<p>For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.</p>

## Dataset

<p>The for the network used dataset was downloaded from <a href="https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia">Kaggle</a>
<p>The original dataset can be found <a href="https://data.mendeley.com/datasets/rscbjbr9sj/2">here</a>

## Local Installation

### Clone the repo (or simply download it)
```shell
git clone https://github.com/JanMarcelKezmann/Pneumonia-Detection-InceptionV3-Transfer-Learning.git
```

### Install requirements
##### (go into the new folder)

```shell
pip install -r requirements.txt
```

### Run with JupyterNotebook or JupyterLab
<p>Just open the .ipynb code in a Notebook of your choice and run it.</p>

## Results

<p>Training the model with a on the imagenet dataset pretrained InceptionV3 model gives the follwing scores:</p>

- Accuracy: 0.7131
- F1 Score: 0.7954
- Precision Score: 0.7175
- Recall Score: 0.8923

<p>Way better results gives us the untrained IncpetionV3 model</p>
<p>Here we got the following results</p>
<p>Accuracy: 0.8413</p>
<p>F1 Score: 0.8871</p>
<p>Precision Score: 0.7988</p>
<p>Recall Score: 0.9974</p>



## Acknowledgements
<p>My work was partially inspired by <a href="https://www.kaggle.com/aakashnain/beating-everything-with-depthwise-convolution">this</a> Kaggle Kernel and <a href="">this</a> Github Repository.</p>
