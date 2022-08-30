## Multiclass Segmentation using UNet for autonomous cars
1. The notebook `unet-keras` contains the code for the segmenation model build in `keras` deep learning library.
2. The data used for the multiclass segmentation was obtained from the `Cityscapes` dataset. The dataset can be found [here](https://www.cityscapes-dataset.com/).
3. The training was performed on `Google Colab`.
4. The original dataset contains 30 classes, which were cut down to 8 for the purpose of training this model, due to lack of efficient resources for training.
5. The selected classes for training include:
    - road
    - sidewalk
    - person
    - car
    - truck
    - bus
    - sky
    - ground
