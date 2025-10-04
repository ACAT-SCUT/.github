## 4.时序预测模型与应用 

### 4.1 相关学习资料

- 本团队的开源项目CycleNet（NeurIPS 2024 Spotlight），通过可学习循环周期来显式建模时序数据的周期模式，从而提升预测性能。​https://github.com/ACAT-SCUT/CycleNet.
- 本团队的开源项目SparseTSF（ICML 2024 Oral），通过引入跨周期稀疏预测机制，能够更有效地捕捉时间序列中的关键周期特征的同时显著压缩模型规模，实现预测模型的极致轻量化。 https://github.com/lss-1138/SparseTSF.
- 本团队的开源项目SegRNN，通过分段循环神经网络来实现高精度时序预测。https://github.com/lss-1138/SegRNN.
- TSFpaper仓库整理了 400 多篇关于时间序列预测（TSF）和时空预测（STF）的最新论文，按模型类型分类（如LLM-based、MLP-based），包括经典方法和最新的深度学习模型。​它是一个持续更新的阅读清单，适合快速查找相关文献，了解领域发展趋势。 https://github.com/ddz16/TSFpaper.
- Time-Series-Library (TSLib) 由清华大学 THUML 团队开发，是一个面向深度学习的时间序列任务库，支持五大任务：长期预测、短期预测、缺失值填补、异常检测和分类。​https://github.com/thuml/Time-Series-Library.
- TFB 是一个获得 PVLDB 2024 最佳论文提名的时间序列预测基准框架，旨在提供全面且公平的模型评估方法。​https://github.com/decisionintelligence/TFB.
- BasicTS 是一个面向时间序列预测的基准工具包，强调公平性和可扩展性。​http://github.com/GestaltCogTeam/BasicTS.

### 4.2 实验室相关成果

#### 4.2.1 时序预测建模

1. Lin, Shengsheng and Lin, Weiwei* and Wu, Wentai and Chen, Haojun and Chen, CL Philip. SparseTSF: Lightweight and Robust Time Series Forecasting via Sparse Modeling. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2025.
2. Lin, Shengsheng and Lin, Weiwei* and Wu, Wentai and Chen, Haojun and Yang, Junjie. SparseTSF: Modeling Long-term Time Series Forecasting with 1k Parameters. 2024 International Conference on Machine Learning. (ICML 2024 Oral)
3. Lin, Shengsheng and Lin, Weiwei* and Hu, Xinyi and Wu, Wentai and Mo, Ruichao and Zhong, Haocheng. CycleNet: Enhancing Time Series Forecasting through Modeling Periodic Patterns. 2024 Advances in Neural Information Processing Systems. (NeurIPS 2024 Spotlight)
4. Lin, Shengsheng and Chen, Haojun and Wu, Haijie and Qiu, Chunyun and Lin, Weiwei*. Temporal Query Network for Efficient Multivariate Time Series Forecasting. 2025 International Conference on Machine Learning. (ICML 2025)
5. Lin, Shengsheng and Lin, Weiwei* and Wu, Wentai and Wang, Songbo and Wang, Yongxiang. Petformer: Long-term time series forecasting via placeholder-enhanced transformer. IEEE Transactions on Emerging Topics in Computational Intelligence (TETCI), 2025.
6. Lin, Shengsheng and Lin, Weiwei* and Wu, Wentai and Zhao, Feiyu and Mo, Ruichao and Zhang, Haotong. Segrnn: Segment recurrent neural network for long-term time series forecasting. arXiv preprint arXiv:2308.11200, 2023 (Under Review).

#### 4.2.2 基于时序预测的异常检测

1. Lin, Weiwei and Wang, Songbo and Wu, Wentai and Li, Dongdong and Zomaya, Albert Y. HybridAD: A Hybrid Model-Driven Anomaly Detection Approach for Multivariate Time Series. IEEE Transactions on Emerging Topics in Computational Intelligence, 2024.
2. Wu, Wentai and He, Ligang and Lin, Weiwei and Su, Yi and Cui, Yuhua and Maple, Carsten and Jarvis, Stephen. Developing an unsupervised real-time anomaly detection scheme for time series with multi-seasonality. IEEE Transactions on Knowledge and Data Engineering, 2022.

#### 4.2.3 时序云负载预测

1. Zhao, Feiyu and Lin, Weiwei* and Lin, Shengsheng and Tang, Shaomin and Li, Keqin. MSCNet: Multi-Scale Network with Convolutions for Long-term Cloud Workload Prediction. IEEE Transactions on Services Computing, 2025.
2. Zhao, Feiyu and Lin, Weiwei* and Lin, Shengsheng and Tang, Keqin. TFEGRU: Time-Frequency Enhanced GRU with Attention for Cloud Workload Prediction. IEEE Transactions on Services Computing, 2025.
3. Lin, Shengsheng and Lin, Weiwei* and Zhao, Feiyu and Chen, Haojun. Benchmarking and Revisiting Time Series Forecasting Methods in Cloud Workload Prediction. Cluster Computing, 2025.

#### 4.2.4 时序压缩

1. Lin, Shengsheng and Lin, Weiwei* and Wu, Keyi and Wang, Songbo and Xu, Minxian and Wang, James Z. Cocv: A compression algorithm for time-series data with continuous constant values in IoT-based monitoring systems. Internet of Things, 2024.

#### 4.2.5 相关专利（来源网址：http://search.cnipr.com/pages!tableSearch.action）

1. 授权发明专利（CN119294446B）. 增强时间序列预测的残差周期预测方法、系统、设备及介质. 2025.08. 林伟伟, 林升升
2. 申请发明专利（202311787568.8）. 基于双轴级联网络的时序预测方法及装置. 2023.12. 林伟伟, 林升升
3. 申请发明专利（CN202310083083.4）. 一种动态压缩时序数据的方法及系统. 2023.02. 林伟伟, 林升升

1. 