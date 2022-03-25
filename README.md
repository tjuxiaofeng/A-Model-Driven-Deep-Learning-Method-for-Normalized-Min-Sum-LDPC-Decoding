# A-Model-Driven-Deep-Learning-Method-for-Normalized-Min-Sum-LDPC-Decoding

*(**Paper Link:** https://ieeexplore.ieee.org/abstract/document/9145237)*

With the applications of deep learning networks booming in physical layer communication, deep-learning-based
channel decoding methods have become a research hotspot. However, the high complexity hinders the application of deep neural network (DNN) on long code. In this paper, we propose a model-driven deep learning method for normalized min-sum (NMS) low-density parity-check (LDPC) decoding. First, we propose a neural normalized min-sum (NNMS) LDPC decoding network. By unfolding the iterative decoding progress between checking nodes (CNs) and variable nodes (VNs) into a feedforward propagation network, we can make use of the advantages of both model-driven deep learning methods and conventional normalized min-sum (CNMS) LDPC decoding method. Second, considering that the NNMS decoder needs large number of multipliers, we propose a shared neural normalized min-sum (SNNMS) decoding network to reduce the number of correction factors. Experimental results show that the BER performance of the proposed NNMS decoder is 1.5dB better than the conventional LDPC decoder, using fewer iterations. Furthermore, the proposed SNNMS decoder outperforms the proposed NNMS decoder and reduces the computation complexity.


This repository contains the code for Nerual Normalized Min Sum Network(NNMS) and Shared Neural Normalized Min Sum (SNNMS).
main.py: you can choose two kinds of neural decoder: NNMS and SNNMS.
Generation_matrix.py: load LDPC_576_432.alist and LDPC_576_432.gamt to generate check matrix H and generator matrix G.

*If you encounter problems during the use of the code, you can contact us through the following email address*
- *wangq@tju.edu.cn*
- *sf_wang@tju.edu.cn*
