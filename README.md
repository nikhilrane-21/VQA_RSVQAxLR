# VQA_RSVQAxLR
python 3.7.15, skip-thoughts, 

## DataSet:
Download the RSVQA low resolution Dataset from https://zenodo.org/record/6344334#.Y572D9JByC0

## Training the models
The files regarding the model are put in the VQA_model folder.
The architecture is defined in models/model.py, and you can use train.py to launch a training.

You will need, in addition to the packages found in requirements.txt, to install skipthoughts:
`
    git clone https://github.com/Cadene/skip-thoughts.torch.git
    cd skip-thoughts.torch/pytorch
    python setup.py install
`
Available here:
https://github.com/Cadene/skip-thoughts.torch/tree/master/pytorch


## How To:

`pip install -r requirements.txt`

Go to VQA_model directory
`python train.py`

For Testing model
`python computeStats.py`


# References
[1] Lobry, Sylvain, et al. "RSVQA: Visual question answering for remote sensing data." IEEE Transactions on Geoscience and Remote Sensing 58.12 (2020): 8555-8566.
