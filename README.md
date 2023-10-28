## Fall2023_IDS706 Mini Project 9: Cloud-Hosted Notebook Data Manipulation
### by Jiayi Zhou [![CI](https://github.com/nogibjj/Fall2023_IDS706_MiniProject9_JiayiZhou/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/Fall2023_IDS706_MiniProject9_JiayiZhou/actions/workflows/cicd.yml)

### Purpose
This is for class data engineering mini project 9. It set up a cloud-hosted Jupyter Notebook--google colab and perform data manipulation tasks on a sample dataset.

### Requirements
* Set up a cloud-hosted Jupyter Notebook (e.g., Google Colab)
* Perform data manipulation tasks on a sample dataset

### Deliverables
* [Link to the cloud-hosted notebook](https://colab.research.google.com/drive/1v_s1vSYI0yUTzbqbyeQR78eZgR5ULWhn)
* [Document demonstrating the tasks performed](https://github.com/nogibjj/Fall2023_IDS706_MiniProject9_JiayiZhou/blob/main/DataManipulation.md)

### Functionality
In the Jupyter Notebook, the following tasks are performed using a dataset about drug use by age from the [National Survey on Drug Use and Health](https://www.icpsr.umich.edu/web/ICPSR/studies/34933) provided by the Substance Abuse and Mental Health Data Archive:

1. **Loading the Dataset**: The notebook loads the dataset.

2. **Data Exploration**:
   - It prints the head of the dataset.
   - It prints the tail of the dataset.
   - It displays the columns of the dataset.
   - It provides information about the shape (number of rows and columns) of the dataset.

3. **Summary Statistics**: Descriptive summary statistics of the dataset are generated.

4. **Data Visualization**:
   - Two bar plots are created to visualize the age distribution for alcohol use.
   - Two bar plots are created to visualize the age distribution for marijuana use.

5. **Data Filtering**: The observations related to individuals under the age of 18 are filtered.

6. **Data Sorting**: The dataset is sorted based on the percentage of alcohol use in the group.

### Steps
I cloned the project template created by Professor Noah Gift and modified the template. Based on the template from professor, I made the following changes:
1. Remove the old jupyter notebook template
2. Creat a new juptyter notebook on google colab
3. Perform data manipulation in the jupyter notebook
4. Link the google colab to Github
