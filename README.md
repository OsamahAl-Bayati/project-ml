# Audio Classification Using CNNs and Spectrogram

This project is an Audio Classifier using PyTorch and torchaudio. The model is designed to classify environmental sounds into one of the 10 classes from the UrbanSound8K dataset.

### Prerequisites
Before you proceed, make sure you have the following installed on your system:

1. Python 3.6 or later
2. pip
3. Jupyter Notebook or Jupyter Lab

### Installing
1. Clone this repository:
```
git clone https://github.com/OsamahAl-Bayati/project-ml.git
cd project-ml
```
2. Create and activate a virtual environment (optional, but recommended):
```
python -m venv venv
source venv/bin/activate  # for Linux/macOS
.\venv\Scripts\activate  # for Windows
```

3. Install the required packages:
```
pip install -r requirements.txt
```
4. Download the [UrbanSound8K dataset](https://urbansounddataset.weebly.com/urbansound8k.html) and extract it into the project folder. The folder structure should look like this:

```
project-ml/
    audio-classification.ipynb
    UrbanSound8K/
        audio/
            fold1/
            fold2/
            ...
        metadata/
            UrbanSound8K.csv
```
### Running the Project
1. Start Jupyter Notebook or Jupyter Lab:

```
jupyter notebook  # or jupyter lab
```
2. Open the .ipynb notebook and run the cells one by one, following the instructions in the notebook.

### Training and Inference
The .ipynb notebook contains code to train and validate the model on the UrbanSound8K dataset. The training process takes a few minutes to complete. After training, the notebook will also demonstrate how to perform inference on the validation dataset and calculate the overall accuracy of the model.
