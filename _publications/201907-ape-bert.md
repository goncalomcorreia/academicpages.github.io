---
title: "A Simple and Effective Approach to Automatic Post-Editing with Transfer Learning"
collection: publications
permalink: /publication/201907-ape-bert
authors: 'Gonçalo M Correia, André FT Martins'
conference: 'In Proceedings of ACL'
conference_year: '2019'
arxiv_link: 'https://arxiv.org/abs/1906.06253'
code_link: 'https://github.com/deep-spin/OpenNMT-APE'
abstract: "Automatic post-editing (APE) seeks to automatically refine the output of a black-box machine translation (MT) system through human post-edits. APE systems are usually trained by complementing human post-edited data with large, artificial data generated through back-translations, a time-consuming process often no easier than training an MT system from scratch. In this paper, we propose an alternative where we fine-tune pre-trained BERT models on both the encoder and decoder of an APE system, exploring several parameter sharing strategies. By only training on a dataset of 23K sentences for 3 hours on a single GPU, we obtain results that are competitive with systems that were trained on 5M artificial sentences. When we add this artificial data, our method obtains state-of-the-art results."
bibtex: "@inproceedings{Correia2019,
author = {Correia, Gonçalo M. and Martins, André F. T.},
booktitle = {Proceedings of ACL},
title = A Simple and Effective Approach to Automatic Post-Editing with Transfer Learning,
year = {2019}}"
---