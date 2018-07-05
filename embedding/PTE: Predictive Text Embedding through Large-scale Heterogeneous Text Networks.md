## PTE: Predictive Text Embedding through Large-scale Heterogeneous Text Networks

- **Conference**
    - KDD 2015
- **Author**
    - Jian Tang
        - Microsoft Research Asia
    - Meng Qu
        - Peking University
    - Qiaozhu Mei
        - University of Michigan
- **Note**
    - **Problem statement:** 
        - Given a large collection of text data with unlabeled and labeled information, the problem of predictive text embedding aims to learn low dimensional representations of words by embed- ding the heterogeneous text network constructed from the collection into a low dimensional vector space.
    - **key point:** 過往unsupervised text embedding methods對於特別的task結果不好，原本是因為對於能取得label資源無法發現其功效，於是本篇便提出semi-unsupervised的ＰＴＥ方法，比supervised based的ＣＮＮ結果還要好
    - embedding the heterogeneous text network(labeled and unlabeled) into a low dimensional space
    - **Method**
        - 建三種network
            - word-word
            - word-document
            - word-label
        - 混合這三種network成一個heterogeneous text network

- **Datasets**
    - long document corpora
        - 20NG
        - WIKI
        - IMDB
        - RCV1
    - short document corpora
        - DBLP
        - MR
        - Twitter

- **Basline**
    - BOW
    - Skip-gram
    - PVDBOW
    - PVDM
    - LINE
    - CNN
    - PTE

- **supplementary information**
    - visualized graph: t-SNE tool

