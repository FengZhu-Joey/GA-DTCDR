# GA-DTCDR
This is the model in "A Graphical and Attentional Framework for Dual-Target Cross-Domain Recommendation" (IJCAI2020).
GA-DTCDR is an optimized model for DTCDR ("DTCDR: A Framework for Dual-Target Cross-Domain Recommendation" in CIKM2019).
DTCDR is the first work for dual-target cross-domain recommendation. Compared with DTCDR, we improved the embedding strategy (from DMF/NeuMF to Graph Embedding) and combination strategy (from fixed combination operators to element-wise attention). 

As for the doc2vec code and the raw data including text information, I did not generate the desensitization dataset. I will share the desensitization raw data later. If you want to learn how to use Doc2vec, you can visit https://radimrehurek.com/gensim/models/doc2vec.html#gensim.models.doc2vec.Doc2Vec.

# Citations
@inproceedings{zhugraphical,
  title={A Graphical and Attentional Framework for Dual-Target Cross-Domain Recommendation},
  author={Zhu, Feng and Wang, Yan and Chen, Chaochao and Liu, Guanfeng and Zheng, Xiaolin},
  booktitle={Proceedings of the 28th ACM International Conference on Information and Knowledge Management, CIKM 2019},
  pages={1533--1542},
  year={2019}
}

@inproceedings{zhu2019dtcdr,
  title={DTCDR: A framework for dual-target cross-domain recommendation},
  author={Zhu, Feng and Chen, Chaochao and Wang, Yan and Liu, Guanfeng and Zheng, Xiaolin},
  booktitle={Proceedings of the Twenty-Ninth International Joint Conference on Artificial Intelligence, IJCAI 2020},
  pages={3001--3008},
  year={2020}
}
