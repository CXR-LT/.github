## About

Chest radiography, like many diagnostic medical exams, produces a long-tailed distribution of clinical findings; 
while a small subset of diseases is routinely observed, the vast majority of diseases are relatively rare [1]. 
This poses a challenge for standard deep learning methods, which exhibit bias toward the most common classes at the expense of the important but rare "tail" classes [2]. 
Many existing methods [3] have been proposed to tackle this specific type of imbalance, though only recently has attention been given to long-tailed medical image recognition problems [4–6]. 
Diagnosis on chest X-rays (CXRs) is also a multi-label problem, as patients often present with multiple disease findings simultaneously; 
however, only a select few studies incorporate knowledge of label co-occurrence into the learning process [7–10]. 
Since most large-scale image classification benchmarks contain single-label images with a mostly balanced distribution of labels, 
many standard deep learning methods fail to accommodate the class imbalance and co-occurrence problems posed by the long-tailed, 
multi-label nature of tasks like disease diagnosis on CXRs [2].

The CXR-LT challenge tasks will feature two main tasks: (i) long-tailed, multi-label classification and (ii) zero-shot generalization to previously unseen disease findings. 

## Publications

* Holste G, Zhou Y, Wang S, Jaiswal A, Lin M, Zhuge S, Yang Y, Kim D, Nguyen-Mau TH, Tran MT, Jeong J, Park W, Ryu J, Hong F, Verma A, Yamagishi Y, Kim C, Seo H, Kang M, Celi LA, Lu Z, Summers RM, Shih G, Wang Z, Peng Y. Towards long-tailed, multi-label disease classification from chest X-ray: Overview of the CXR-LT challenge. Med Image Anal. 2024 May 31;97:103224. doi: 10.1016/j.media.2024.103224. Epub ahead of print. PMID: 38850624.
* Holste G, Jiang Z, Jaiswal A, Hanna M, Minkowitz S, Legasto A, Escalon J, Steinberger S, Bittman M, Ding Y, Shih G, Peng Y, Wang Z. How Does Pruning Impact Long-Tailed Multi-Label Medical Image Classifiers? Med Image Comput Comput Assist Interv. 2023 Oct;14224:663-673. doi: 10.1007/978-3-031-43904-9_64. Epub 2023 Oct 1. PMID: 37829549; PMCID: PMC10568970.

## Research support

* R01CA289249, NIH/NLM, 2024-2029
* NSF CAREER Award, NSF, 2022-2026

## References

1. Zhou SK, Greenspan H, Davatzikos C, Duncan JS, van Ginneken B, Madabhushi A, et al. A review of deep learning in medical imaging: Imaging traits, technology trends, case studies with progress highlights, and future promises. Proc IEEE Inst Electr Electron Eng. 2021;109: 820–838. doi:10.1109/JPROC.2021.3054390
1. Holste G, Wang S, Jiang Z, Shen TC, Shih G, Summers RM, et al. Long-Tailed Classification of Thorax Diseases on Chest X-Ray: A New Benchmark Study. Data Augment Label Imperfections (2022). 2022;13567: 22–32. doi:10.1007/978-3-031-17027-0_3
1. Zhang Y, Kang B, Hooi B, Yan S, Feng J. Deep Long-Tailed Learning: A Survey. IEEE Trans Pattern Anal Mach Intell. 2023;PP: 1–20. doi:10.1109/TPAMI.2023.3268118
1. Zhang R, E H, Yuan L, He J, Zhang H, Zhang S, et al. MBNM: Multi-branch network based on memory features for long-tailed medical image recognition. Comput Methods Programs Biomed. 2021;212: 106448. doi:10.1016/j.cmpb.2021.106448
1. Ju L, Wang X, Wang L, Liu T, Zhao X, Drummond T, et al. Relational subsets knowledge distillation for long-tailed retinal diseases recognition. Medical Image Computing and Computer Assisted Intervention – MICCAI 2021. Cham: Springer International Publishing; 2021. pp. 3–12. doi:10.1007/978-3-030-87237-3_1
1. Yang Z, Pan J, Yang Y, Shi X, Zhou H-Y, Zhang Z, et al. ProCo: Prototype-aware contrastive learning for long-tailed medical image classification. Lecture Notes in Computer Science. Cham: Springer Nature Switzerland; 2022. pp. 173–182. doi:10.1007/978-3-031-16452-1_17
1. Chen H, Miao S, Xu D, Hager GD, Harrison AP. Deep hiearchical multi-label classification applied to chest X-ray abnormality taxonomies. Med Image Anal. 2020;66: 101811. doi:10.1016/j.media.2020.101811
1. Wang G, Wang P, Cong J, Liu K, Wei B. BB-GCN: A Bi-modal Bridged Graph Convolutional Network for multi-label chest X-ray recognition. arXiv [cs.CV]. 2023. Available: http://arxiv.org/abs/2302.11082
1. Chen B, Li J, Lu G, Yu H, Zhang D. Label co-occurrence learning with graph convolutional networks for multi-label chest X-ray image classification. IEEE J Biomed Health Inform. 2020;24: 2292–2302. doi:10.1109/JBHI.2020.2967084
1. Moukheiber D, Mahindre S, Moukheiber L, Moukheiber M, Wang S, Ma C, et al. Few-Shot Learning Geometric Ensemble for Multi-label Classification of Chest X-Rays. Data Augment Label Imperfections (2022). 2022;13567: 112–122. doi:10.1007/978-3-031-17027-0_12
