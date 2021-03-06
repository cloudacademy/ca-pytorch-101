# Cloud Academy Course
## Pytorch 101 

## Setting Up the Google Colab Environment

The Google Colab is a product from Google Research which allows
> anybody to write and execute arbitrary python code through the browser, and is especially well suited to machine learning, data analysis and education. More technically, Colab is a hosted Jupyter notebook service that requires no setup to use, while providing free access to computing resources including GPUs.

For more information, please visit the following [link](https://research.google.com/colaboratory/faq.html).

Here, we provide a short tutorial on how to upload the data on that environemnt via Google drive, and then use the Google colab to run your analysis.
Please, note that we assume you have a google account to access to this Google product.

### 1. Open a Google Colab session

From your favourite browser, open a new colab notebook via the following [link](https://colab.research.google.com)

### 2. Mount your drive on colab

We assume you have placed the data into the `My Drive` folder. If so, connecting your drive to a google machine is pretty easy, using the python google library: just run the following code snippet

```python
from google.colab import drive
drive.mount('/content/drive')
```
After an authorisation check, you will be able to interact with your drive content either from the file browser side panel (easier) or using command-line utilities.

### 3. Clone the GitHub Repository on your Drive
I suggest to create a folder inside your drive. For example, call it `ca.webinars`. Then, in any colab notebook cell, type the following commands
```python
%cd '/content/drive/My Drive/ca.pytorch101'
```
and then clone the following repository:
```python
!git clone https://github.com/cloudacademy/ca-pytorch-101.git
```

### 4. Open the template .ipynb file from your drive
Now, you have to navigate inside the Google Drive folder where the repo has been cloned. Once there, you just need to open, say, the file `'Pytorch101_Lecture01.ipynb'` with Google Colab. And that's it! :smile:


## Instructor info
This course is held by Andrea Giussani, Data Scientist at Cloud Academy.
You can reach him out wither at [:email:](andrea.giussani@cloudacademy.com) or on [Linkedin](https://it.linkedin.com/in/andrea-giussani-764816148?trk=public_profile_samename_mini-profile_title), and you can follow him on his [:rocket: blog](https://andreagiussani.github.io/the-long-beard-blog/).

