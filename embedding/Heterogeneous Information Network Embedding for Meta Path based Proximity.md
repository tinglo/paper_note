## Heterogeneous Information Network Embedding for Meta Path based Proximity

- **Conference**
    - 2017
- **Author**
    - Zhipeng Huang, Nikos Mamoulis
        - The University of Hong Kong

- **Note**
    - **key point**:  一個好的embedding應該要preserve the proximity between vertices in the original graph，但以往的embedding大都是homogeneous networks( all vertices are considered to belong to a single class)，所以此篇focus在hetergogeneous network embedding. 定義了一個objective function旨在minimize distance between two distribution
        - 1. one modeling the meta path based proximities.
        - 2. the other modeling the proximities in the embedded vector space.
    - **difficuties**: The proximity among objects in a HIN(heterogeneous information networks) is not just a measure of closeness or distance, but it is also based on semantics.(相同距離的link，但意思不同)。研發HINE based on meta path 效果比沒有用meta path的方法還好（在HIN裡）
    - **Method**
        - HINE: Heterogeneous Information Network embedding
        - 計算保留某meta path, 兩點間的 proximity score
            - PathCount(PC)
            - Path Constrained Random Walk(PCRW)
        - negative sampling （可見[paper](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)）
        
- **Datasets**
    - DBLP
    - MOVIE: extract subset from YAGO
    - YELP
    - GAME
    
- **Baseline**
    - DeepWalk
    - LINE
    - HINE_PC
    - HINE_PCRW 

