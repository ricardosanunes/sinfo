# SINFO - YOLOv7 Object Detection Workshop
Welcome! In this workshop, we'll guide you through the process of training YOLOv7 to detect a new object.  

## Prerequisites
The current code implementation requires a GPU. Make sure you have at least one available before running the code.  

## Getting Started
To begin, follow these steps:  
1) Clone this repo:  
   `git clone https://github.com/ricardosanunes/sinfo.git`
2) Perform the steps in the notebook:  
   `presentation.ipynb`

## Datasets
The implementation will have two datasets with photos of the new object:
- Bad dataset: contains less images, only from a few angles and mostly with the same background 
- Good dataset: includes more images from different angles and backgrounds 

To train the model with your own images, you must label them. For that, we recommend using [label-studio](https://labelstud.io/).  

### Label-studio Setup
To use [label-studio](https://labelstud.io/) on your own images, it is recommended to create a python enviroment.  
For that purpose, follow these steps:
1) Create environment named 'labelling':  
   `python -m venv labelling`
2) Activate the environment:  
   `source labelling/Scripts/activate`
3) Install label-studio:  
   `python -m pip install label-studio`
4) Start the server:  
   `label-studio`

For alternative installation methods, refer to the label-studio documentation [here](https://labelstud.io/guide/install).  
To deactivate the environment, run: `deactivate`.  
To remove the environment named 'labelling', run: `rm -rf labelling`.
