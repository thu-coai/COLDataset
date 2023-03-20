# COLDataset
The official repository of the paper: COLD: A Benchmark for Chinese Offensive Language Detection

中文冒犯语言检测数据集

Paper link: https://arxiv.org/abs/2201.06025

Detector: We release the version of [roberta-base-cold](https://huggingface.co/thu-coai/roberta-base-cold?text=%E4%BD%A0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%82%BB) in Huggingface.

# News
Our paper has been accepted by EMNLP 2022!

# Info
COLDataset contains 37,480 comments with binary offensive labels and covers diverse topics of race, gender, and region. 
To gain further insights into the data types and characteristics, we annotate the test set at a fine-grained level with four categories: attacking individuals, attacking groups, anti-bias and other non-offensive.

the labels in train.csv and dev.csv:

* label 0: safe, 
* label 1: offensive

fine-grained-label in test.csv:

* 0: safe (other-Non-offen)
* 1: attack individual
* 2: attack group
* 3: safe (anti-bias)

# Citing
Please kindly cite our paper if this paper and the dataset are helpful.
```
  @article{deng2022cold,
  title="Cold: A benchmark for chinese offensive language detection",
  author= "Deng, Jiawen and Zhou, Jingyan and Sun, Hao and Mi, Fei and Huang, Minlie",
  booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing",
  month = dec,
  year = "2022",
  address = "Abu Dhabi, United Arab Emirates",
  publisher = "Association for Computational Linguistics",
  url = "https://aclanthology.org/2022.emnlp-main.796",
  pages = "11580--11599"
}
```

