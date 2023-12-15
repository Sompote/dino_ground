
# Ground dino finetune

This project was developed to train ground dino with addtional class.

## Deployment

To deploy this project run

1. Use the  file finetun_dino_vast.ipynb and run to install open ground Dino

2. at command promnpt run
apt install libgl1-mesa-glx

export CUDA_HOME=/path/to/cuda-11.3


2. Copy all of file in config/ to config folder in open ground dino

3. Copy data to train into fig/ folder 

4. run !python main.py  --output_dir dino_data  --c config/cfg_odvg.py  --dataset config/datasets_od.json  --pretrain_model_path /content/drive/MyDrive/dino_data/groundingdino_swint_ogc.pth  to train model

5. The train model weight is in --output_dir dino_data 
