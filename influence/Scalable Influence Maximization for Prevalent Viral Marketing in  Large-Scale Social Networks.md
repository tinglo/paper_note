## Scalable Influence Maximization for Prevalent Viral Marketing in  Large-Scale Social Networks

- **Conference**
    - 2010
- **Author**
    - Wei Chen
        - Microsoft Research Asia
    - Chi Wang
        - Department of Computer Science University of Illinois at Urbana-Champaign
    - Yajun Wang
        - Microsoft Research Asia
- **Note**
    - 提出MIA演算法(maximum influence arborescence)，利用dijkstra建立每個node的arborescence(tree)，分成MIIA、MIOA(from node and to node)，設定threshold，若probability太低的path便不加入，計算每個點的activation probability，每次有新seed加入時，並提出ap更新的方法，便只在每個點各自的MIIA、MIOA來更新點activation probability(更新阿法、更新ap、更新IncInf)，計算activation probability增加最多的點(IncInf)來加入成為新的seed.
    
- **Datasets**
    - NetPHY
    - DM



