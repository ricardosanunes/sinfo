# sinfo
Welcome! In this workshop, we'll present to you how to train YOLOv7 to detect a new object.  
  
To complete this workshop, follow the steps:  
1) Clone this repo:  
   `git clone https://github.com/ricardosanunes/sinfo.git`
2) Perform the steps in the notebook:  
   `presentation.ipynb`

<br/><br/>
The implementation will have two datasets with photos of the new object:
- Good dataset: plenty images from different angles and backgrounds
- Bad dataset: fewer images, only from a few angles and mostly with the same background  

To train the model with your own images, you must label them. For that, we recommend using [label-studio](https://labelstud.io/).  

---
### Label-studio
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

For other installation types consult label-studio documentation [here](https://labelstud.io/guide/install).  
To deactivate the environment run: `deactivate`.  
To remove the environment named 'labelling' run: `rm -rf labelling`.
