# 林升升（Shengsheng Lin）

华南理工大学计算机科学与技术学院2023级博士研究生 
主要研究方向为时间序列预测模型设计、周期性建模与大模型推理优化。

---

## 研究方向

- 长期时间序列预测（Long-term Time Series Forecasting, LTSF）
- 模型轻量化与结构化稀疏建模
- 周期性特征建模与趋势分解
- 多变量时序预测与跨变量关系建模
- 工业与云计算场景下的预测模型应用

---

## 代表论文

1. **SparseTSF: Lightweight and Robust Time Series Forecasting via Sparse Modeling**  
   *TPAMI 2025 & ICML 2024 (Oral)*  
   提出Cross-Period Sparse Forecasting方法，通过对输入序列的跨周期下采样建模，实现小于1k参数的超轻量时序预测模型。

2. **CycleNet: Residual Cycle Forecasting for Long-term Time Series Modeling**  
   *NeurIPS 2024 (Spotlight)*  
   在SparseTSF的基础上引入显式周期性建模，通过残差周期预测机制显著提升周期性数据的建模能力。

3. **TQNet: Temporal Query Networks for Multivariate Time Series Forecasting**  
   *ICML 2025*  
   提出基于时间查询机制的注意力结构，在多变量时序预测中实现了更鲁棒的跨变量相关性建模。

4. **SegRNN: Segment Recurrent Neural Network for Long-term Time Series Forecasting**  
   （投稿中）  
   探索基于分段机制的时序建模方法，实现长依赖建模与短期模式捕获的平衡。

---

## 主要研究成果

林升升长期致力于**面向长时间序列预测的高效模型设计**，围绕周期性特征建模展开系统研究，形成了SparseTSF → CycleNet → TQNet的连续技术路线：

- **SparseTSF**：通过跨周期稀疏预测实现超轻量设计，性能接近主流SOTA；
- **CycleNet**：在SparseTSF的基础上显式引入可学习周期参数，强化周期性信号建模；
- **TQNet**：进一步扩展到多变量时序预测任务，提出时间查询机制以增强跨变量关系建模；

该系列工作系统性地推动了轻量化长时序预测模型的发展，在参数量、泛化性能与建模效率之间取得了良好平衡。

---

## 相关链接

- Google Scholar: [https://scholar.google.com.hk/citations?user=_qbjJbAAAAAJ](https://scholar.google.com.hk/citations?user=_qbjJbAAAAAJ)
- GitHub: [https://github.com/lss-1138](https://github.com/lss-1138)