# Kaggle_Titani：Machine Learning from Disaster

## Kernel：
- https://www.kaggle.com/sinakhorami/titanic-best-working-classifier
- https://www.kaggle.com/arthurtok/introduction-to-ensembling-stacking-in-python/notebook

### [步驟](http://happycoder.org/2017/10/14/python-data-science-and-machine-learning-scikit-learn-basic-tutorial/)
 1. 明確定義問題 (Problem Definition)
 1. 獲取資料與探索性資料分析 (Get Data & Exploratory Data Analysis)
 1. 資料預處理與特徵工程 (Data Clean/Preprocessing & Feature Engineering)
 1. 訓練模型與校調 (Model Training)
 1. 模型驗證 (Model Predict & Testing)
 1. 模型優化 (Model Optimization)
 1. 上線運行 (Deploy Model)

---

1. 明確定義問題 (Problem Definition)
  - 監督式學習：二元分類問題（binary classification）
  - 預測：乘客存活與否
 
1. 獲取資料與探索性資料分析 (Get Data & Exploratory Data Analysis)
  - 匯入資料
    - 中文字串path ：`train = pd.read_csv(open("C:/Users/poduo/Anaconda3_JupyterNB/SC00030/作業/Kaggle_Titanic/DataSet/train.csv"))`

  
1. 資料預處理與特徵工程 (Data Clean/Preprocessing & Feature Engineering)
  1. 資料探索 及 預處理
    - 觀察各項目與 存活 之間的相關性
    - Age : 處理遺失值、分箱
    - Fare : 分箱
  
  1. 相關性分析
 
1. 訓練模型與校調 (Model Training)
  1. w3-1 Ensemble Learning
    - [ ] Voting Classifier
    - [ ] Bagging
    - [ ] Random Forest
    - [ ] Adaptive Boosting

1. 模型驗證 (Model Predict & Testing)
1. 模型優化 (Model Optimization)
1. 上線運行 (Deploy Model)

 