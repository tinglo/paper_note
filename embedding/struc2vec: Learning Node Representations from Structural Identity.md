## struc2vec: Learning Node Representations from Structural Identity

- **Conference**
    - KDD 2017
- **Author**
    - Leonardo F. R. Ribeiro, Pedro H. P. Saverese, Daniel R. Figueiredo
        - Federal University of Rio de Janeiro Systems Eng. and Comp. Science Dep.

- **Note**
    - 除了local similarity也說明structural similarity也很重要(感覺跟LINE觀念有點像)
    - 創建一個hierarchy來測量node structural similarity(階層最底層代表可能只有degree一樣，階層最上代表整個network一樣(from the viewpoint of the node))
    - 創造random context for nodes, which are sequences of structurally similar nodes as observed by a **weighted random walk** traversing a **multilayer** graph.
    



