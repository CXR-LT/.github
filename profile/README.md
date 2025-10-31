## About

Chest radiography, like many diagnostic medical exams, produces a long-tailed distribution of clinical findings; 
while a small subset of diseases is routinely observed, the vast majority of diseases are relatively rare. 
This poses a challenge for standard deep learning methods, which exhibit bias toward the most common classes at the expense of the important but rare "tail" classes. 
Many existing methods [3] have been proposed to tackle this specific type of imbalance, though only recently has attention been given to long-tailed medical image recognition problems. 
Diagnosis on chest X-rays (CXRs) is also a multi-label problem, as patients often present with multiple disease findings simultaneously; 
however, only a select few studies incorporate knowledge of label co-occurrence into the learning process. 
Since most large-scale image classification benchmarks contain single-label images with a mostly balanced distribution of labels, 
many standard deep learning methods fail to accommodate the class imbalance and co-occurrence problems posed by the long-tailed, 
multi-label nature of tasks like disease diagnosis on CXRs.

The CXR-LT challenge tasks will feature two main tasks: (i) long-tailed, multi-label classification and (ii) zero-shot generalization to previously unseen disease findings. 

## Publications

* Lin M, Holste G, Wang S, Zhou Y, Wei Y, Banerjee I, Chen P, Dai T, Du Y, Dvornek NC, Ge Y, Guo Z, Hanaoka S, Kim D, Messina P, Lu Y, Parra D, Son D, Soto Á, Urooj A, Vidal R, Yamagishi Y, Yan P, Yang Z, Zhang R, Zhou Y, Celi LA, Summers RM, Lu Z, Chen H, Flanders A, Shih G, Wang Z, Peng Y. CXR-LT 2024: A MICCAI challenge on long-tailed, multi-label, and zero-shot disease classification from chest X-ray. Med Image Anal. 2025 Dec;106:103739. doi: 10.1016/j.media.2025.103739. Epub 2025 Jul 29. PMID: 40795541; PMCID: PMC12396843.
* Holste G, Zhou Y, Wang S, Jaiswal A, Lin M, Zhuge S, Yang Y, Kim D, Nguyen-Mau TH, Tran MT, Jeong J, Park W, Ryu J, Hong F, Verma A, Yamagishi Y, Kim C, Seo H, Kang M, Celi LA, Lu Z, Summers RM, Shih G, Wang Z, Peng Y. Towards long-tailed, multi-label disease classification from chest X-ray: Overview of the CXR-LT challenge. Med Image Anal. 2024 May 31;97:103224. doi: 10.1016/j.media.2024.103224. Epub ahead of print. PMID: 38850624.
* Holste G, Jiang Z, Jaiswal A, Hanna M, Minkowitz S, Legasto A, Escalon J, Steinberger S, Bittman M, Ding Y, Shih G, Peng Y, Wang Z. How Does Pruning Impact Long-Tailed Multi-Label Medical Image Classifiers? Med Image Comput Comput Assist Interv. 2023 Oct;14224:663-673. doi: 10.1007/978-3-031-43904-9_64. Epub 2023 Oct 1. PMID: 37829549; PMCID: PMC10568970.

## Research support

* R01CA289249, NIH/NLM, 2024-2029
* NSF CAREER Award, NSF, 2022-2026
