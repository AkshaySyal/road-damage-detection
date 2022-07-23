# road-damage-detection

Project Summary:
https://docs.google.com/presentation/d/1dL3Bf2k0vpAjC-U0t5CSXYb-prx6U18TjcBDnpEHOZA/edit?usp=sharing

Model Weights:
https://drive.google.com/drive/folders/1hXjR42tEJUU_hWdnw2VP0ajvNVj-J4PT?usp=sharing

## 1st step
Cloned this github repo: https://github.com/WongKinYiu/yolor

## 2nd step
Performed data preparation, cleaning and train-test split

## 3rd step
Command used to train the algorithm: python train.py --batch-size 4 --img 640 640 --data custom.yaml --cfg cfg/yolor_p6_custom.cfg --weights yolor_p6.pt --device 0 --name yolor_p6 --hyp hyp.scratch.1280.yaml --epochs 30
