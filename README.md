# OmniStyleGAN
OmniStyleGAN for Style-Guided Image-to-Image Translation

## Training networks


`python main.py --mode train --num_domains 3 --w_hpf 0 \
               --lambda_reg 1 --lambda_sty 1 --lambda_ds 2 --lambda_cyc 1 \
               --train_img_dir data/afhq/train \
               --val_img_dir data/afhq/val`
