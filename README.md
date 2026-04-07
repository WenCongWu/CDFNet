# CDFNet: Cross-Dimension Fusion Network with Dual Feature Enhancement for Multimodal Object Detection
This is an official PyTorch implementation for our CDFNet. Our paper has been accepted by **Expert Systems With Applications** in 2026. The paper will be published soon.

### 1. Dependences
 Create a conda virtual environment and activate it.
 1) conda create --name MOD python=3.9
 2) conda activate MOD
 3) pip install -r requirements.txt

### 2. Datasets download
Download these datasets and create a dataset folder to hold them.
1) FLIR dataset: [FLIR](https://drive.google.com/file/d/1o9lchkdQcPaYqqEa_d_6l3QewyfkDTCx/view?usp=drive_link)
2) LLVIP dataset: [LLVIP](https://drive.google.com/file/d/1Bl1_D1T2x4JLu4__VbBjn6WJ3-T1Z99W/view?usp=drive_link)
3) M3FD dataset: [M3FD](https://drive.google.com/file/d/1FSfAQQ80UvwE7mXKDAxZZnabUrsM9HHD/view?usp=drive_link)

### 3. Pretrained weights
Download our CDFNet weights and create a weights folder to hold them.
1) FLIR dataset: [CDFNet_FLIR.pt](https://drive.google.com/file/d/1b0Bzo3k9kh_Bd5jMsDOCUhpYnU-eiQzj/view?usp=drive_link), [CDFNet-s_FLIR.pt](https://drive.google.com/file/d/135MCsvTspEsFx9FWlphjdWUu9x_CbR5L/view?usp=drive_link)
2) LLVIP dataset: [CDFNet_LLVIP.pt](https://drive.google.com/file/d/1GX4fd5MML73t8SknVjB0FOw9afwvDN5b/view?usp=drive_link), [CDFNet-s_LLVIP.pt](https://drive.google.com/file/d/13fBWugKyWNotUG2JBm7bkrqHilKNt3V5/view?usp=drive_link)
3) M3FD dataset: [CDFNet_M3FD.pt](https://drive.google.com/file/d/1vDZKli96vcD3qVcjMjB5U-7iQKqLNY5N/view?usp=drive_link), [CDFNet-s_M3FD.pt](https://drive.google.com/file/d/1Rp8DfUsl7lCOHNsYupjl_coim5TDTiuQ/view?usp=drive_link)

### 4. Training our CDFNet
Dataset path, GPU, batch size, etc., need to be modified according to different situations.
```
python train.py
```

### 5. Test our CDFNet

```
python test.py
```

### 6. Citation
If you find CDFNet helpful for your research, please consider citing our work.
```BibTex
@article{Wu2026,
  title={CDFNet: Cross-Dimension Fusion Network with Dual Feature Enhancement for Multimodal Object Detection}, 
  author={Wencong Wu and Xiuwei Zhang and Hanlin Yin and Haorui Zeng and Chenxu Wei and Lei Yu and Yanning Zhang},
  journal={Expert Systems With Applications},
  year={2026}
}
```

