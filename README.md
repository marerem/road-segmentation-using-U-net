# road-segmentation-using-U-net

Our best result was achieved with *accuracy=0.945* and *F1-score=0.895*. \
Result link on the competition platform: https://www.aicrowd.com/challenges/epfl-ml-road-segmentation/submissions/207397 \
**`Team`**: **MQU**

**`TeamMembers`**: **Mariia Eremina**, **Qiming Sun**, **Ulysse Widmer**

# Quickstart
For data upload: follow the link : https://www.aicrowd.com/challenges/epfl-ml-road-segmentation/dataset_files. Before running the code make sure that you download train and test datasets to the directory ```data/```. You should have such folder structure:
```
data/
  test_set_images/
  training/
    groundtruth/
    images/
```
OR use to download the google drive with already uploaded data the corresponding folders and put it on your google drive in MyDrive section: https://drive.google.com/drive/folders/1sETvpSVuvLm1zewQdSBcWdmoLIns5NTB?usp=share_link

The stored weights(best model and models with tuning hyperparameters) of it We saved the best models weights and parameters on in ```data/saved_models``` folder.

You can reproduce these results by following the instructions in project_2.ipynb 

### **`project_2.ipynb `**
Contains all the implementation of model architecture, results visualizations, and all the explanations on how we put everything together and how to run it.
