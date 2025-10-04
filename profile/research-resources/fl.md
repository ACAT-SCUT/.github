## 5.边缘智能

### 5.1 相关学习资料

1. 实验室内部报告：《基于Atlas计算平台的端边云协同及统一调度技术研究》
2. Docker: 容器化平台，轻量级部署，https://www.docker.com/
3. 《The Blockchain Developer: A Practical Guide for Designing, Implementing, Publishing, Testing, and Securing Distributed Blockchain-based Projects》：是一本实践指南，旨在帮助开发者学习如何设计、搭建、发布、测试和确保区块链应用的安全性。由Elad Elrom于2019年撰写，书中详细介绍了区块链的技术原理，并阐述了如何将这些原理应用于实际项目中。
4. 《Automated Machine Learning: Methods, Systems, Challenges (The Springer Series on Challenges in Machine Learning)》：是关于自动化机器学习（AutoML）的第一本全面概述，介绍了AutoML中的通用方法、基于这些方法的现有系统，并讨论了首系列国际AutoML系统挑战。由Frank Hutter、Lars Kotthoff和Joaquin Vanschoren编辑，2019年出版，书中深入探讨了商用机器学习应用的成功和这一领域的快速增长，为研究人员、高级学生及实践者提供了进入这一快速发展的领域的入门参考。

### 5.2 实验室相关成果

1. Wangbo Shen, Weiwei Lin*, Wentai Wu, Haijie Wu, Keqin Li. Reinforcement learning-based task scheduling for heterogeneous computing in end-edge-cloud environment.  Cluster Computing, 2025, 28(3)
2. Haijie Wu, Weiwei Lin*, Wangbo Shen, Xiumin Wang, C. L. Philip Chen, Keqin Li. Prediction of Heterogeneous Device Task Runtime Based on Edge Server-Oriented Deep Neuro-Fuzzy System.  IEEE Transactions on Services Computing, 2025,18(1):372 - 384
3. Peng Peng, Wentai Wu*, Weiwei Lin*, Fan Zhang, Yongheng Liu, Keqin Li. Reliable Task Offloading in Sustainable Edge Computing with Imperfect Channel State Information.  IEEE Transactions on Network and Service Management, 2024, 21(6):6423 - 6436
4. Haijie Wu, Wangbo Shen, Weiwei Lin*, Wei Li, Keqin Li,. End-Edge-Cloud Heterogeneous Resources Scheduling Method Based on RNN and Particle Swarm Optimization.  IEEE Transactions on Network and Service Management, 2024: 1–1
5. Peng Peng, Weiwei Lin, Wentai Wu, Haotong Zhang,, Shaoliang Peng, Qingbo Wu, Keqin Li. A survey on computation offloading in edge systems: From the perspective of deep reinforcement learning approaches.  Computer Science Review, 2024, 53: 100656.
6. Senjiong Zheng, Bo Liu*, Weiwei Lin*, Xiaoying Ye, Keqin Li. A package-aware scheduling strategy for edge serverless functions based on multi-stage optimization.  Future Generation Computer Systems , 2023, 144: 105--116
7. Haotong Zhang, Weiwei Lin*, Rong Xie, Shenghai Li, Zhiyan Dai, James Z. Wang. An optimal container update method for edge-cloud collaboration.  Software: Practice and Experience , Wiley, 2023, 1-18, DOI: 10.1002/spe.3232
8. Huabin Wang, Ruichao Mo, Yuping Chen, Weiwei Lin*, Minxian Xu, Bo Liu*. Pedestrian and Vehicle Detection Based on Pruning YOLOv4 with Cloud-Edge Collaboration.  Computer Modeling in Engineering & Sciences, 2023, 137(2):2025-2047
9. Tiansheng Huang, Weiwei Lin*, Xiaobin Hong, Xiumin Wang*, Qingbo Wu, Ching-Hsien Hsu, Albert Y. Zomaya. Adaptive Processor Frequency Adjustment for Mobile Edge Computing with Intermittent Energy Supply.  IEEE Internet of Things Journal, 2022,9(10):7446 - 7462
10. 陈玉平, 刘波, 林伟伟*, 程慧雯. 云边协同综述.  计算机科学, 2021, 48(3):259-267

## 6.联邦学习

### 6.1 相关学习资料

#### 6.1.1 官方教程与文档

**1.Google's Federated Learning:**
[https://ai.googleblog.com/2017/04/federated-learning-collaborative.html](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html)
**谷歌官方博客中介绍了FL的基本概念与应用。**

**2.TensorFlow Federated (TFF):**
[https://www.tensorflow.org/federated](https://www.tensorflow.org/federated)
**官方的联邦学习框架，适合实际动手实践。**

#### 6.1.2 基础文章推荐

**1.Kairouz et al. (2021). "Advances and Open Problems in Federated Learning"**
**这是联邦学习领域的权威综述文章：**
[https://arxiv.org/abs/1912.04977](https://arxiv.org/abs/1912.04977)

**2.McMahan et al. (2017). "Communication-Efficient Learning of Deep Networks from Decentralized Data"**
**提出FedAvg的经典论文：**
[https://arxiv.org/abs/1602.05629](https://arxiv.org/abs/1602.05629)

#### 6.1.3 推荐书籍

**1.Federated Learning: Privacy and Incentive**
**作者：Qiang Yang 等，Springer 出版，涵盖系统架构、隐私机制、激励机制等。**

**2.Federated Learning: Challenges, Methods, and Future Directions**
**一本稍微进阶一点的书，介绍研究热点与挑战。**

#### 6.1.4 课程与讲座推荐

**1.卡内基梅隆大学（CMU）10-719：联邦与协同学习**
**课程名称：10-719: Federated and Collaborative Learning**

**授课教师：Prof. Virginia Smith**

**课程主页：**[https://www.cs.cmu.edu/~smithv/10719/](https://www.cs.cmu.edu/~smithv/10719/)

#### 6.1.5 开源框架

**1.Flower**	**灵活的 FL 框架，支持多种ML库**	[https://flower.dev/](https://flower.dev/)
**2.FedML**	**支持跨设备/跨边缘服务器等多场景的研究平台**	[https://fedml.ai/](https://fedml.ai/)
**3.LEAF**	**联邦学习评估框架，含丰富数据集**	[https://leaf.cmu.edu/](https://leaf.cmu.edu/)

#### 6.1.6 开源项目

1. **一个精心整理的联邦学习（Federated Learning, FL）研究资源列表，涵盖了多个子领域的前沿论文、方法和应用。该列表主要从 arXiv 等来源收集，并按主题分类，便于研究人员查阅和学习。**
   * 基础与优化方法 ：包括如 SCAFFOLD、FedDANE、FedOpt 等优化算法，旨在提高联邦学习在非独立同分布（non-IID）数据和异构设备上的性能。
   * 垂直联邦学习（Vertical FL） ：聚焦于特征分布在不同参与方之间的场景，涵盖如 SecureBoost、基于准牛顿法的框架，以及利用同态加密进行实体解析的方法。
   * 分层联邦学习（Hierarchical FL） ：探讨了客户端、边缘设备和云端之间的协同学习机制，提升系统的可扩展性和隐私保护能力。
   * 通信效率优化 ：研究如深度梯度压缩（Deep Gradient Compression）、双向压缩（Artemis）等技术，以减少通信开销，提高训练效率。
   * 项目地址：https://github.com/FedML-AI/FedML/blob/master/research/Awesome-Federated-Learning.md
2. **该基准测试的主要目的是评估不同联邦学习算法在面对各种非IID数据分布时的性能表现。通过模拟现实中常见的数据异质性场景，如标签不均、特征差异和数据量不平衡，研究人员可以更全面地理解各算法的优势和局限性，从而为实际应用中的算法选择和优化提供参考。**

   * 项目地址：[https://github.com/Xtra-Computing/NIID-Bench](https://github.com/Xtra-Computing/NIID-Bench)
3. **最新联邦学习论文梳理**

   * 项目地址：https://github.com/luozhengquan/Federated-paper

6.2 实验室相关成果

1. Fang Shi, Weiwei Lin*, Chaoda Peng, Cankun Zhong, Dong Wang, Mingyue Cheng. Dynamic Client Selection for Over-the-Air Federated Learning Network.  IEEE Internet of Things Journal, 2025: 1–1
2. Dongdong Li, Weiwei Lin*, Wentai Wu, Haotong Zhang, XiuMin Wang. SynFlowFL: A Dynamic Synaptic Flow Framework for Efficient, Personalized Federated Learning.  IEEE Transactions on Emerging Topics in Computational Intelligence, 2025: 1–15
3. Dongdong Li, Bo Liu*, Chunqiao Yang, Fang Shi, Yunfei Peng, Weiwei Lin*. K-Core Structure Feature Encoding-Based Enhanced Federated Graph Learning Framework.  IEEE Transactions on Emerging Topics in Computational Intelligence, 2025: 1–15
4. Fang Shi, Weiwei Lin*, Xiumin Wang, Keqin Li, Albert Y. Zomaya. The Analysis and Optimization of Volatile Clients in Over-the-Air Federated Learning.  IEEE Transactions on Mobile Computing, 2024,23(12):13144 – 13157
5. Wentai Wu, Ligang He*, Weiwei Lin*, Carsten Maple. FedProf: Selective Federated Learning based on Distributional Representation Profiling.  IEEE Transactions on Parallel and Distributed Systems , 2023,34(6):1942 - 1953, DOI: 10.1109/TPDS.2023.3265588
6. Weiwei Lin*, Yinhai Xu, Bo Liu*, Dongdong Li, Tiansheng Huang, Fang Shi. Contribution-based Federated Learning client selection.  International Journal of Intelligent Systems , 2022, 37 (10):7235-7260
7. Fang Shi, Chunchao Hu, Weiwei Lin*, Lisheng Fan, Tiansheng Huang, Wentai Wu. VFedCS: Optimizing Client Selection for Volatile Federated Learning.  IEEE Internet of Things Journal, 2022, DOI: 10.1109/JIOT.2022.3195073
8. Wentai Wu, Ligang He, Weiwei Lin, Rui Mao, Carsten Maple, Stephen Jarvis. SAFA: a Semi-Asynchronous Protocol for Fast Federated Learning with Low Overhead.  IEEE Transactions on Computers, 2021,70(5): 655-668, DOI: 10.1109/TC.2020.2994391
9. Tiansheng Huang, Weiwei Lin*, Wentai Wu, Ligang He, Keqin Li, Albert Zomaya. An Efficiency-boosting Client Selection Scheme for Federated Learning with Fairness Guarantee.  IEEE Transactions on Parallel and Distributed Systems, 2021, 32(7): 1552-1564
10. 吴文泰, 吴应良*, 林伟伟, 左文明. 横向联邦学习：研究现状、系统应用与挑战.  计算机学报, 2025,48(1):35-67
11. 林伟伟, 石方, 曾岚, 李董东, 许银海, 刘波*. 联邦学习开源框架综述.  计算机研究与发展, 2023, 60(7): 1551-1580.
12. 梁文雅, 刘波*, 林伟伟*, 严远超. 联邦学习激励机制研究综述.  计算机科学, 2022, 49 (12): 46-52.
13. 林伟伟*, 彭绍亮, 王田, 吴文泰, LI Keqin. 联邦学习专题序言.  计算机科学 , 2022, 49(12): 1-4.