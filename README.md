# Paper4Beginnners
List of Suggested papers for nlp and computational biology *beginners*. The list is compiled from  
- https://github.com/thunlp/PLMpaper

## Deep Learning Tutorials
- **[李宏毅机器学习](http://speech.ee.ntu.edu.tw/~tlkagk/courses_ML20.html)**. 
- **[跟李沐学AI](https://space.bilibili.com/1567748478?spm_id_from=333.337.0.0)**.
- **[深度学习专项课程 by Andrew Ng](https://www.coursera.org/specializations/deep-learning?utm_medium=sem&utm_source=gg&utm_campaign=B2C_NAMER_deep-learning_deeplearning-ai_FTCOF_specializations_country-US-country-CA&campaignid=904733485&adgroupid=43839369503&device=c&keyword=andrew%20ng%20deep%20learning&matchtype=b&network=g&devicemodel=&adposition=&creativeid=654942386826&hide_mobile_promo&gclid=CjwKCAjwhdWkBhBZEiwA1ibLmKQA7LisCioRWYxITFoFGbaDaYHH4NobkU6wtTIsOBD3DA9hOEY5SBoCm9wQAvD_BwE)**
- **[Let's build GPT: from scratch, in code, spelled out.](https://www.youtube.com/watch?v=kCc8FmEb1nY&t=1194s)**

## Pre-trained Language Models (PLM)
- **Improving Language Understanding by Generative Pre-Training**. *Alec Radford, Karthik Narasimhan, Tim Salimans and Ilya Sutskever*. Preprint. [[pdf](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)] [[project](https://openai.com/blog/language-unsupervised/)] (**GPT**)
- **BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding**. *Jacob Devlin, Ming-Wei Chang, Kenton Lee and Kristina Toutanova*. NAACL 2019. [[pdf](https://arxiv.org/pdf/1810.04805.pdf)] [[code & model](https://github.com/google-research/bert)]
- **RoBERTa: A Robustly Optimized BERT Pretraining Approach**. *Yinhan Liu, Myle Ott, Naman Goyal, Jingfei Du, Mandar Joshi, Danqi Chen, Omer Levy, Mike Lewis, Luke Zettlemoyer, Veselin Stoyanov*. Preprint. [[pdf](https://arxiv.org/pdf/1907.11692.pdf)] [[code & model](https://github.com/pytorch/fairseq)]
- **Language Models are Unsupervised Multitask Learners**. *Alec Radford, Jeffrey Wu, Rewon Child, David Luan, Dario Amodei and Ilya Sutskever*. Preprint. [[pdf](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)] [[code](https://github.com/openai/gpt-2)] (**GPT-2**)
- **Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer**.  *Colin Raffel, Noam Shazeer, Adam Roberts, Katherine Lee, Sharan Narang, Michael Matena, Yanqi Zhou, Wei Li, Peter J. Liu*. Preprint. [[pdf](https://arxiv.org/pdf/1910.10683.pdf)] [[code & model](https://github.com/google-research/text-to-text-transfer-transformer)] (**T5**)
- **Language Models are Few-Shot Learners**, *Tom B. Brown, et al.*. Preprint. [[pdf](https://arxiv.org/abs/2005.14165)]


## PLM for Bio Sequences
- **Biological Structure and Function Emerge from Scaling Unsupervised Learning to 250 Million Protein Sequences** *Alexander Rives, Joshua Meier, Tom Sercu, Siddharth Goyal, Zeming Lin, Demi Guo, Myle Ott, C Lawrence Zitnick, Jerry Ma, and Rob Fergu.* Preprint. [[pdf](https://www.biorxiv.org/content/10.1101/622803v3.full.pdf)] [[code&model](https://github.com/facebookresearch/esm)] (**ESM-1b**)
- **Language Models Enable Zero-shot Prediction of the Effects of Mutations on Protein Function** *Joshua Meier   Roshan Rao,Robert Verkuil, Jason Liu, Tom Sercu, Alexander Rives.* Preprint. [[pdf](https://www.biorxiv.org/content/10.1101/2021.07.09.450648v1.full.pdf)][[code&model](https://github.com/facebookresearch/esm)] (**ESM-1v**)
- **MSA Transformer** *Alexander Rives, Joshua Meier, Tom Sercu, Siddharth Goyal, Zeming Lin, Demi Guo, Myle Ott, C Lawrence Zitnick, Jerry Ma, Rob Fergu.*[[pdf](https://www.biorxiv.org/content/10.1101/2021.02.12.430858v1.full.pdf)][[code&model](https://github.com/rmrao/msa-transformer)]
- **Language Models of Protein Sequences at the Scale of Evolution Enable Accurate Structure Prediction**. *Zeming Lin, Halil Akin1, Roshan Rao, Brian Hie, Zhongkai Zhu, Wenting Lu, Allan dos SantosCosta, Maryam Fazel-Zarandi1, Tom Sercu1, Sal Candido1, Alexander Rives*. Preprint. [[pdf](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1.full.pdf)] [[code & model](https://github.com/facebookresearch/esm)] (**ESM-2**)
- **Interpretable RNA Foundation Model from Unannotated Data for Highly Accurate RNA Structure and Function Predictions** *Jiayang Chen, Zhihang Hu, Siqi Sun, Qingxiong Tan, Yixuan Wang, Qinze Yu,Licheng Zong, Liang Hong, Jin Xiao, Tao Shen, Irwin King, and Yu L.* Preprint. [[pdf](https://arxiv.org/pdf/2204.00300.pdf)] [[code&model](https://github.com/ml4bio/RNA-FM)] (**RNA-FM**)
- **Highly Accurate Protein Structure Prediction with Alphafold**. *John Jumper, et al*. Nature volume 596, pages 583–589 (2021) [[pdf](https://www.nature.com/articles/s41586-021-03819-2)] [[code & model](https://github.com/deepmind/alphafold)] (**AlphaFold2**)
