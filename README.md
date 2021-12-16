# VRDL_HW3



## Requirements

```
# install it from a local clone:
git clone https://github.com/facebookresearch/detectron2.git
python -m pip install -e detectron2

# (Optional) install opencv for visualizing img
pip install opencv-python
```

## Project Structure

you have to change the data to Coco format

```
content/
    dataset
    ├── coco
    │   ├── annotations         
    │   │    ├ train.json
    │   │    ├ val.json        
    │   │    ├ test_img_ids.json      
    │   ├── train 
    │   │    ├ TCGA-18-5592-01Z-00-DX1.png
    │   │    ├ ...
    │   ├── val 
    │   │    ├ TCGA-B0-5711-01Z-00-DX1.png
    │   │    ├ ...
    │   ├── test
    │   │    ├ TCGA-50-5931-01Z-00-DX1.png
    │   │    ├ ...
```

## Training
https://github.com/ray980215/VRDL_HW3/blob/main/hw3.ipynb

## Inference
https://github.com/ray980215/VRDL_HW3/blob/main/inference.ipynb


## Pre-trained Models

You can download my model weights here:
https://drive.google.com/file/d/1I4QioghvOK9ZbL5xtm7Gc4Me4A1v5Hfg/view?usp=sharing


## Results

my model achieves the following performance : mAP = 0.23084

## References
[Detectron2](https://github.com/facebookresearch/detectron2)
