# PhysioNet - Digitization of ECG Images

What [physio-seg model](https://www.kaggle.com/models/wasupandceacar/physio-seg-public/PyTorch/net3_009_4200/1) actually outputs

The `net3_009_4200.pt` checkpoint is a 4-class semantic segmentation model, trained with:
* CrossEntropyLoss
* Softmax over channels
* Not independent sigmoid channels

The 4 classes are roughly:
* background
* grid
* ECG trace
* noise/artifacts
