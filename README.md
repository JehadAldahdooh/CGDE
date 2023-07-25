# Mining drug-target interactions from biomedical literature using chemical and gene descriptions based ensemble transformer model

## Installation

To set up the project environment, you can use `pip3` to install the required packages. Run the following commands to install the necessary dependencies:

```
pip3 install -U scikit-learn
pip3 install bioc==1.3.6
pip3 install omegaconf==2.1.1
pip3 install torchtext==0.10.0
pip3 install transformers==4.8.0
pip3 install hydra
pip3 install hydra.core==1.1.0
pip3 install wandb==0.10.33
pip3 install segtok
```

## Training
To train the model, run the following command:

```
python3 -m drugprot.train
```