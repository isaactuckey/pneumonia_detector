# Deep Learning-based Pneumonia Detector Using Chest X-Ray Images

The chest x-ray dataset can be downloaded here: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

To prep the dataset, anything that is not a .jpeg is removed from all folders. You will need to update the path variables to point to the correct local train, val, and test folders organized like this:

```bash
├── train
│   ├── NORMAL
│   └── PNEUMONIA
├── val
│   ├── NORMAL
│   └── PNEUMONIA
├── test
│   ├── NORMAL
│   └── PNEUMONIA
```

The notebook resnet18.ipynb has all the necessary code to recreate the results. In a clean Python 3.12 environment, install the requirements with:

```pip install -r requirements.txt```

and run all cells.

*Note: Weights and Balances is used for logging results which requires an online account with an API key to utilize.*

