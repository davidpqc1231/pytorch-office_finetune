# PyTorch-Office_Finetune

A PyTorch implementation for fine-tuning AlexNet and ResNet on Office dataset.

## Environment

- Python 3.6
- PyTorch 0.4.0

## Result

|                |   A-W   |   A-D   |
| :------------: | :-----: | :-----: |
| this(alexnet)  | 0.5874  |         |
| this(resnet50) | 0.7597  |         |

## Note

- alexnet pretrained model is converted from caffe pretrained model, can be download [here]()
- LRN layer is officially supported now

## links

- similar problem: <https://discuss.pytorch.org/t/pytorch-alexnet-not-as-good-as-original-alexnet-implementation/16680>
- wjd
- <https://www.qin.ee/2018/06/25/da-office/>