# STDAN-CVPRW-2022 (Keep Update)

This is the official Pytorch implementation of _Space-Time Video Super-Resolution Using Deformable Attention Network_.

(The code is coming soon)

## Dependencies

- Python 3.8.0 (Recommend to use Anaconda)
- PyTorch == 1.8.0
- CUDA == 10.1
- [Deformable Convolution v2](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Deformable_ConvNets_V2_More_Deformable_Better_Results_CVPR_2019_paper.pdf), we use [Detectron2's implementation](https://github.com/facebookresearch/detectron2/tree/main/detectron2/layers/csrc/deformable) in the network.

## Installation

1. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
   
2. Compile the deformable attention and convolution:
   ```
   cd YOUR_PATH/STDAN/codes/models/modules/DCNv2_latest
   bash make.sh
   ```

## Testing

   


## Acknowledgments
Our code is inspired by [Zooming Slow-Mo](https://github.com/Mukosame/Zooming-Slow-Mo-CVPR-2020) and [Detectron2](https://github.com/facebookresearch/detectron2)

