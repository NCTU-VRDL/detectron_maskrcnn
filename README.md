Detectron2 is Facebook AI Research's next generation library
that provides state-of-the-art detection and segmentation algorithms.
It is the successor of
[Detectron](https://github.com/facebookresearch/Detectron/)
and [maskrcnn-benchmark](https://github.com/facebookresearch/maskrcnn-benchmark/).
It supports a number of computer vision research projects and production applications in Facebook.

<div align="center">
  <img src="https://user-images.githubusercontent.com/1381301/66535560-d3422200-eace-11e9-9123-5535d469db19.png"/>
</div>

## Download pre-traine weights
```bash
wget https://dl.fbaipublicfiles.com/detectron2/COCO-InstanceSegmentation/mask_rcnn_R_50_FPN_3x/137849600/model_final_f10217.pkl
```
## Installation

See [installation instructions](https://detectron2.readthedocs.io/tutorials/install.html).

## Colab
[https://drive.google.com/drive/folders/1-njpOJC79PyZlIyCV8OFIag8l6P_UeNd](https://drive.google.com/drive/folders/1-njpOJC79PyZlIyCV8OFIag8l6P_UeNd)

### Exercise1:
Familiar with the segmentation data format. Open the [exercise1_dataformat.ipynb](https://github.com/NCTU-VRDL/detectron_maskrcnn/blob/master/exercise1_dataformat.ipynb)

### Exercise2:
Mask R-CNN model inference. Open the [exercise2_inference.ipynb](https://github.com/NCTU-VRDL/detectron_maskrcnn/blob/master/exercise2_inference.ipynb)

### Exercise3:
Mask R-CNN model training. Open the [exercise3_training.ipynb](https://github.com/NCTU-VRDL/detectron_maskrcnn/blob/master/exercise3_training.ipynb)

### Exercise4:
See other Mask R-CNN model based applications. Open the [exercise4_applications.ipynb](https://github.com/NCTU-VRDL/detectron_maskrcnn/blob/master/exercise4_applications.ipynb)

## Getting Started

See [Getting Started with Detectron2](https://detectron2.readthedocs.io/tutorials/getting_started.html),
and the [Colab Notebook](https://colab.research.google.com/drive/16jcaJoc6bCFAQ96jDe2HwtXj7BMD_-m5)
to learn about basic usage.

Learn more at our [documentation](https://detectron2.readthedocs.org).
And see [projects/](projects/) for some projects that are built on top of detectron2.

## Model Zoo and Baselines

We provide a large set of baseline results and trained models available for download in the [Detectron2 Model Zoo](MODEL_ZOO.md).

## License

Detectron2 is released under the [Apache 2.0 license](LICENSE).

## Citing Detectron2

If you use Detectron2 in your research or wish to refer to the baseline results published in the [Model Zoo](MODEL_ZOO.md), please use the following BibTeX entry.

```BibTeX
@misc{wu2019detectron2,
  author =       {Yuxin Wu and Alexander Kirillov and Francisco Massa and
                  Wan-Yen Lo and Ross Girshick},
  title =        {Detectron2},
  howpublished = {\url{https://github.com/facebookresearch/detectron2}},
  year =         {2019}
}
```
