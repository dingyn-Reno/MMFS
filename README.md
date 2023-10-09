# MMFS
Fine-grained Action Analysis: A Multi-modality and Multi-task Dataset of Figure Skating.

pdf：https://arxiv.org/abs/2307.02730

![image]([https://github.com/dingyn-Reno/MMFS/edit/main/MDRGCN.png](https://github.com/dingyn-Reno/MMFS/blob/main/MDRGCN.png))

## Abstract

The fine-grained action analysis of the existing action datasets is challenged by insufficient action categories, low fine granularities, limited modalities, and tasks. In this paper, we propose a Multi-modality and Multi-task dataset of Figure Skating (MMFS) which was collected from the World Figure Skating Championships. MMFS, which possesses action recognition and action quality assessment, captures RGB, skeleton, and is collected the score of actions from 11671 clips with 256 categories including spatial and temporal labels. The key contributions of our dataset fall into three aspects as follows. (1) Independently spatial and temporal categories are first proposed to further explore fine-grained action recognition and quality assessment. (2) MMFS first introduces the skeleton modality for complex fine-grained action quality assessment. (3) Our multi-modality and multi-task dataset encourage more action analysis models. To benchmark our dataset, we adopt RGB-based and skeleton-based baseline methods for action recognition and action quality assessment.

## Dataset Download

Skeleton dataset link：https://drive.google.com/file/d/1X3ffZ05hp3CAhScFEv-B7jhIcQne8awc/view?usp=share_link

The RGB video may cause copyright issues. If RGB videos are needed, please contact Prof.Shenglan-Liu：liusl@dlut.edu.cn

## 相关工作

以下为本人所做的和滑冰数据集相关的识别和动作质量评估新方法。

2M-AF: A Strong Multi-Modality Framework For Human Action Quality Assessment with Self-supervised Representation Learning. ICLR, under review

Multi-Dimensional Refinement Graph Convolutional Network with Robust Decouple Loss for Fine-Grained Skeleton-Based Action Recognition. TNNLS, under review
pdf：https://arxiv.org/abs/2306.15321
github：https://github.com/dingyn-Reno/MDR-GCN

## Citation

If you find our work useful in your research, please consider citing:

@misc{liu2023finegrained,
      title={Fine-grained Action Analysis: A Multi-modality and Multi-task Dataset of Figure Skating}, 
      author={Sheng-Lan Liu and Yu-Ning Ding and Si-Fan Zhang and Wen-Yue Chen and Ning Zhou and Hao Liu and Gui-Hong Lao},
      year={2023},
      eprint={2307.02730},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
