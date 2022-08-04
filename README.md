# Basic VSR

## Inference

1. `pyinit`
2. Install pytorch
3. `pip install basicsr`
4. `python scripts/download_pretrained_models.py BasicVSR`
5. `python scripts/download_pretrained_models.py flownet`
6. `python inference/inference_basicvsr.py --input_path "/home/markhuang/Data/frames/Solo_sm" --save_path "/home/markhuang/Data/solo_out_2" --model_path experiments/pretrained_models/BasicVSR/BasicVSR_REDS4-543c8261.pth`

## Training
