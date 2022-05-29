# KWS_Quizon
Transformer keyword spotting project. To be submitted as requirement 03 for EE298 Second Sem 2021-2022.


## Requirements
```
pip install pytorch-lightning --upgrade
pip install torchmetrics --upgrade
pip install torch
pip install sys
pip install librosa
pip install argparse
pip install numpy
pip install wandb
pip install einops
pip install torchmetrics
pip install torchaudio
pip install torchvision
```
## Training 
Run train.py to train the transformer model. The output file "model_scripted_final.pt"

## Inference

RUn kws-infer.py to use the "model_scripted_final_87%.pt" for keyword spotting using your own voice. Please change --checkpoint from get_args() to change the pt file to be used for inference.

