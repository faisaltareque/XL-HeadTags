# XL-HeadTags

This is the official repository contains the code, data, and models of the paper titled [**"XL-HeadTags: Leveraging Multimodal Retrieval Augmentation for the Multilingual Generation of News Headlines and Tags"**](https://arxiv.org/abs/2406.03776), accepted for publication in Findings of the 62nd Annual Meeting of the Association for Computational Linguistics (ACL’24).

## Table of Contents

- [Shironaam](#shironaam)
  - [Table of Contents](#table-of-contents)
  - [Abstract](#abstract)
  - [Dataset](#dataset)
  - [Models](#Models)
  - [Multilingual Tools](#multilingual-tools)
  - [Implementation](#implementation)
  - [License](#license)
  - [Contributors](#contributors)
  - [Acknowledgements](#acknowledgements)

## Abstract
> Millions of news articles published online daily can overwhelm readers. Headlines and entity (topic) tags are essential for guiding readers to decide if the content is worth their time. While headline generation has been extensively studied, tag generation remains largely unexplored, yet it offers readers better access to topics of interest. The need for conciseness in capturing readers' attention necessitates improved content selection strategies for identifying salient and relevant segments within lengthy articles, thereby guiding language models effectively. To address this, we propose to leverage auxiliary information such as images and captions embedded in the articles to retrieve relevant sentences and utilize instruction tuning with variations to generate both headlines and tags for news articles in a multilingual context. To make use of the auxiliary information, we have compiled a dataset named XL-HeadTags, which includes 20 languages across 6 diverse language families. Through extensive evaluation, we demonstrate the effectiveness of our plug-and-play multimodal-multilingual retrievers for both tasks. Additionally, we have developed a suite of tools for processing and evaluating multilingual texts, significantly contributing to the research community by enabling more accurate and efficient analysis across languages.

## Dataset
Dataset used in this work is available here: [XL-HeadTags](https://huggingface.co/datasets/faisaltareque/XL-HeadTags)

## Models
Models with caption Retrieved K=5 (Top-K) can be found here:
- [XL-HeadTags-mT5-c5](https://huggingface.co/faisaltareque/XL-HeadTags-mT5-c5)
- [XL-HeadTags-mT0-c5](https://huggingface.co/faisaltareque/XL-HeadTags-mT0-c5)
- [XL-HeadTags-FlanT5-c5](https://huggingface.co/faisaltareque/XL-HeadTags-FlanT5-c5)

## Multilingual Tools
Multilingual tools used in this work can be found here:
- [Multilingual Sentence Tokenizer](https://github.com/faisaltareque/Multilingual-Sentence-Tokenizer)
- [Multilingual Stemmer](https://github.com/faisaltareque/Multilingual-Stemmer)
- [Multilingual ROUGE Scorer](https://github.com/faisaltareque/Multilingual-Rouge-Scorer/tree/main)

## Implementation
**Code for this work will be added soon**

## License
Contents of this repository are restricted to only non-commercial research purposes under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). Copyright of the dataset contents belongs to the original copyright holders.

## Contributors
- Faisal Tareque Shohan (faisaltareque@hotmail.com)
- Mir Tafseer Nayeem (mnayeem@ualberta.ca)
- Samsul Islam (samsulratul98@gmail.com)
- Abu Ubaida Akash (abu.ubaida.akash@usherbrooke.ca)
- Shafiq Joty (sjoty@salesforce.com)

## Acknowledgements
- Mir Tafseer Nayeem is supported by [Huawei](https://digitalpower.huawei.com/en/) Doctoral Fellowship.