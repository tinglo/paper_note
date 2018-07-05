## graph2vec: Learning Distributed Representations of Graphs

- **Conference**
    - 2017
- **Author**
    - Annamalai Narayanan, Mahinthan Chandramohan, Rajasekar Venkatesan, Lihui Chen, Yang Liu and Shantanu Jaiswal
        - Nanyang Technological University, Singapore
- **Note**
    - 之前的distributed reprensentations 通常是base on nodes or subgraph(ex, walk, path), 但有些task(such as "graph" classfication or clustering) requried representing "entire graph" as fixed length featrue vectors, 而graph kernel是可以做到這點。 以往graph kernels作法use handcrafted features(e.g. shortestp ahts, graphlet) 會造成poor generalization
        - 當在處理很大的data時, it leads to building very high dimensional , sparse and non-smooth representations and this yield poor generealization
    - 因此此篇paper發明的一個neural embedding framework叫做 ”graph2vec“ to learn data-driven distributed representations of arbitrary sized graph => feature learning, 而不是用既定的算法(ex: jaccard)
    - **Method**
        - 學習來learn 的node不是一班的linear substructure (such as walks and paths)，而是用"rooted subgraph"
            - rooted subgraph需要label
                - use WL relabeling strategy

