## LINE: Large-scale Information Network Embedding

- **Conference**
    - WWW 2015
- **Author**
    - Jian Tang(1), Meng Qu(2), Mingzhe Wang(2), Ming Zhang(2), Jun Yan(1), Qiaozhu Mei(3)
        - (1) Microsoft Research Asia
        - (2) School of EECS, Peking University
        - (3) School of Information, University of Michigan
- **Note**
    - **key point:** 提出一種embedding的方法，將network映射到較低維的空間，且致力保留local and global network structures。說此方法適用於有向、無向、weighted networks，在language network, social network, citation network都有好的效果，且可以scale a large network
    - Method:
        - LINE
            - 致力保存致力保存local(first-order proximity) and global(second-order proximity) structure
        - edge sampling algorithm
- **Datasets**
    - english wikipedia page
    - flickr
    - youtube
    - DBLP
- **Baseline**
    - Graph factorization
    - DeepWalk
    - LINE-SGD
    - LINE
    - LINE(1st+ 2nd)
- **Other reference**
    - [source code](https://github.com/tangjianpku/LINE)


