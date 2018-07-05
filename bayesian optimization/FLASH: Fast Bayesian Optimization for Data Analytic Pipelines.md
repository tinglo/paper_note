## FLASH: Fast Bayesian Optimization for Data Analytic Pipelines

- **Conference**
    - KDD 2016
- **Author**
    - Yuyu Zhang, Mohammad Taha Bahadori, Hang Su, Jimeng Sun
        - Georgia Institute of Technology
- **Note**
    - Data analytic pipelines(data preprocessing, feature extraction, model building/evaluation ...)中通常每個階段是會互相影響的，而為了達到好的performance，每個階段需要決定要使用的algorithm和其參數的設定，隨著pipelines架構越複雜，計算所花費的時間當然也就越大。 
    - 本篇主要是利用bayesian optimization概念來解決上述問題。BOA通常是拿來解決單個演算法的優化問題，而為應用在pipelines optmization上，本篇提由兩層bayesian optimization algorithm組成的FLASH架構(Fast LineAr SearcH)，第一層用來決定每個階段algorithm的選擇，第二層用來tune algorithm的hyperparameters。
    - 其實驗結果顯示FLASH在不同time budget下，相較於其他方法(SMAC, TPE)能更快的達到最佳結果。
    - Dataset:
    - MADELON
    - MNIST
    - MRBI
    - CONVEX
- **亮點**
    - 原來bayesian optimization不一定做在趴數上
- **Datasets**
    - MADELON
    - MNIST
    - MRBI
    - CONVEX
- **Baseline**
    - TPE
        - Tree-structured Parzen Estimator
    - SMAC
        - sequential model-based algorithm configuration
    - (others)
        - evolutionary algorithms, optimistic optimization
- **Other reference**
    - [source code](https://github.com/yuyuz/FLASH)

- **supplementary information**
    - bayesian optimization
        - probabilistic model
            - gaussian porcess
            - random forest such as SMAC
            - density estimation models such as TPE
        - acquistion model
            - Expected Improvement(EI) function