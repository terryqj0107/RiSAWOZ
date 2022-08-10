# RiSAWOZ Home Page
Please refer to the homepage of [RiSAWOZ](https://terryqj0107.github.io/RiSAWOZ_webpage/) for more detailed introduction.

# RiSAWOZ
Datasets and codes for the paper "RiSAWOZ: A Large-Scale Multi-Domain Wizard-of-Oz Dataset with Rich Semantic Annotations for Task-Oriented Dialogue Modeling". (EMNLP 2020)

You can get the source codes and models of the five benchmark tasks from Google Drive (URL: https://drive.google.com/drive/folders/1LFEY2h0WGikOG1-fMAAnF0NkR8zpyoTG?usp=sharing) or BaiduNetDisk (URL: https://pan.baidu.com/s/1BQImRCvnnP_nQzXVM1CTZQ), the password for BaiduNetDisk is 73jl.



## Abstract
In order to alleviate the shortage of multi-domain data and to capture discourse phenomena for task-oriented dialogue modeling, we propose RiSAWOZ, a large-scale multi-domain Chinese Wizard-of-Oz dataset with Rich Semantic Annotations. RiSAWOZ contains 11.2K human-to-human (H2H) multi-turn semantically annotated dialogues, with more than 150K utterances spanning over 12 domains, which is larger than all previous annotated H2H conversational datasets. Both single- and multi-domain dialogues are constructed, accounting for 65% and 35%, respectively. Each dialogue is labeled with comprehensive dialogue annotations, including dialogue goal in the form of natural language description, domain, dialogue states and acts at both the user and system side. In addition to traditional dialogue annotations, we especially provide linguistic annotations on discourse phenomena, e.g., ellipsis and coreference, in dialogues, which are useful for dialogue coreference and ellipsis resolution tasks. Apart from the fully annotated dataset, we also present a detailed description of the data collection procedure, statistics and analysis of the dataset. A series of benchmark models and results are reported, including natural language understanding (intent detection & slot filling), dialogue state tracking and dialogue context-to-text generation, as well as coreference and ellipsis resolution, which facilitate the baseline comparison for future research on this corpus.

## Data License
We make the dataset under the following licenses:
*  Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license.
(License URL: https://creativecommons.org/licenses/by-nc/4.0/)


## References
If you use the source codes or datasets included here in your work, please cite the corresponding papers. The bibtex are listed below:
```
@inproceedings{quan-etal-2020-risawoz,
    title = "{R}i{SAWOZ}: A Large-Scale Multi-Domain {W}izard-of-{O}z Dataset with Rich Semantic Annotations for Task-Oriented Dialogue Modeling",
    author = "Quan, Jun  and
      Zhang, Shian  and
      Cao, Qian  and
      Li, Zizhong  and
      Xiong, Deyi",
    booktitle = "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.emnlp-main.67",
    pages = "930--940",
}

```
