
# Introduction
In this work, propose a novel disentangled contrastive learning framework for social Recommendations to model heterogeneous behavior patterns of users in item domain and social domain.

# Environment 
`pip install -r requirements.txt`

# Dataset
 We conduct experiments on two datasets: Ciao and Douban.

# Command
`cd code && python main.py`


*NOTE*:
1. The setting of hyperparameters could be found in the file of *code/main.py*.
2. The optimal hyperparameters could refer to the logs in fold of  *logs of optimal hyperparameters*.
3. If you find our work helpful, please cite: [Disentangled Contrastive Learning for Social Recommendation](https://dl.acm.org/doi/abs/10.1145/3511808.3557583)
```
@inproceedings{wu2022DcRec,
  author = {Wu, Jiahao and Fan, Wenqi and Chen, Jingfan and Liu, Shengcai and Li, Qing and Tang, Ke},
  title = {Disentangled Contrastive Learning for Social Recommendation},
  year = {2022},
  publisher = {ACM},
  booktitle = {Proc. of CIKM'2022}
}


