# XNAS

**XNAS** is an effective, modular, and flexible neural architecture search (NAS) codebase, which aims to provide a common framework and baselines for the NAS community.

This project is now supported by PengCheng Lab.

## Installation

```bash
git clone https://git.openi.org.cn/PCL_AutoML/XNAS
cd XNAS
# set root path
export PYTHONPATH=$PYTHONPATH:/Path/to/XNAS
```



## NAS--Projects Capabilities

We currently have the following algorithms implemented in our repository, and the links in the table below will take you to our algorithm documentation, the official project repository, and our readthedocs website.

You can click on **this link** to go to our readthedocs website.

You can click on the hyperlinks below to go to the algorithm details page, where our algorithm documentation will contain a brief introduction to the algorithm, performance tests of the algorithm, how to run the code, and other information.

```markdown
|                Algorithms                | Our Link | Our Doc | Official Link |
|:----------------------------------------:|:--------:|:-------:|:-------------:|
|                   DARTS                  |          |         |    `Github`   |
|                  PCDARTS                 |          |         |               |
|                  PDARTS                  |          |         |               |
|                    SNG                   |          |         |               |
|                   ASNG                   |          |         |               |
|                  MDENAS                  |          |         |               |
|                  DDPNAS                  |          |         |               |
|                  MIGONAS                 |          |         |               |
|                GridSearch                |          |         |               |
|                   DrNAS                  |          |         |               |
|                   TENAS                  |          |         |               |
|                  RMINAS                  |          |         |               |
|                  DROPNAS                 |          |         |               |
| Performance comparison of all algorithms |          |         |               |
```

## Directory Tree

https://blog.csdn.net/weixin_47148731/article/details/123830637

## BibTex

```bash
@inproceedings{zheng2022rminas,
  title={Neural Architecture Search with Representation Mutual Information},
  author={Xiawu Zheng, Xiang Fei, Lei Zhang, Chenglin Wu, Fei Chao, Jianzhuang Liu, Wei Zeng, Yonghong Tian, Rongrong Ji},
  journal={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2022}
}
@article{zheng2021migo,
  title={MIGO-NAS: Towards fast and generalizable neural architecture search},
  author={Zheng, Xiawu and Ji, Rongrong and Chen, Yuhang and Wang, Qiang and Zhang, Baochang and Chen, Jie and Ye, Qixiang and Huang, Feiyue and Tian, Yonghong},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
  year={2021},
  publisher={IEEE}
}
@inproceedings{zheng2020rethinking,
  title={Rethinking performance estimation in neural architecture search},
  author={Zheng, Xiawu and Ji, Rongrong and Wang, Qiang and Ye, Qixiang and Li, Zhenguo and Tian, Yonghong and Tian, Qi},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={11356--11365},
  year={2020}
}
```