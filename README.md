# Perceptual Loss

## Train
* python style.py train --dataset ~/CocoDataset/ --style-image images/style-images/vincent.jpg --save-model-dir models/ --epochs 2 --cuda 1

## Inference
* python style.py eval --content-image images/content-images/resized.jpg --model models/epoch_2_Sun_Sep_19_03\:30\:19_2021_100000.0_10000000000.0.model --output-image images/output-images/resized.jpg --cuda 1
* python style.py eval --content-image images/content-images/PEI-8715.jpg --content-scale 10 --model models/epoch_2_Sun_Sep_19_03\:30\:19_2021_100000.0_10000000000.0.model --output-image images/output-images/PEI-8715.jpg --cuda 1