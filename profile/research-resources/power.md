## 1.数据中心节能与绿色计算

### 1.1 相关学习资料

1. 实验室内部报告：《ARM与x86服务器节能技术分析及能效测试报告》、《云业务节能技术分析报告》、《数据中心能效建模及基于模型的节能方法》（包括服务器能效建模、供电能效建模、散热能效建模和节能方法三个部分）、《基准测试场景集群能效优化调研报告》、《实际业务场景集群能效优化调研报告》
2. 《Energy Efficient servers Blueprints for Data Center Optimization》：是一本介绍能源高效服务器及其在数据中心优化中应用的图书。该书由C. Gough、I. Steiner和W. Saunders撰写，详细探讨了用于能源高效服务器的电源管理技术和方法。
3. 《性能之巅：洞悉系统、企业与云计算》：性能工程领域的经典著作，由资深专家Brendan Gregg撰写。本书系统性地探讨了复杂环境下的性能分析与优化方法，覆盖从传统硬件到云计算的全栈技术，结合理论与实践，为读者提供了应对现代系统性能挑战的全面指南。
4. 服务器功耗数据集：https://www.spec.org/power_ssj2008/results/power_ssj2008/
5. Marconi 100超算中心数据集：https://gitlab.com/ecs-lab/exadata/-/tree/main?ref_type=heads
6. 荷兰SURFsara数据中心Lisa集群的数据集：http://github.com/sara-nl/SURFace 
7. 功耗相关基准：https://www.spec.org/power/
8. Wentai Wu，Weiwei Lin，Keqin Li. Energy efficiency of servers in data centers. (Encyclopedia of Sustainable Technologies (可持续技术百科全书), 2nd Edition) Elsevier. 2023.03  
9. Weiwei Lin，Wentai Wu，Keqin Li. Energy-Saving Technologies of Servers in Data Centers . (Data Center Handbook: Plan, Design, Build, and Operations of a Smart Data Center, 2021: 337-348.) John Wiley & Sons, Inc.. 2021.05
10. 数据中心CFD仿真软件介绍：https://www.cadence.com/en_US/home/tools/reality-digital-twin.html#cadence-reality-dc-design
11. 施耐德公司发布的数据中心解决方案和白皮书：https://www.schneider-electric.cn/zh/work/solutions/data-centers-and-networks/

### 1.2 实验室相关成果

#### 1.2.1论文

1. Huikang Huang, Weiwei Lin*, Jianpeng Lin, Keqin Li. Power Management Optimization for Data Centers: A Power Supply Perspective.  IEEE Transactions on Sustainable Computing, 2025: 1–20
2. Jianpeng Lin, Weiwei Lin*, Wentai Wu, Wenjun Lin, Keqin Li. Energy-aware virtual machine placement based on a holistic thermal model for cloud data centers.  Future Generation Computer Systems, 2024, 161:302-314
3. Jianpeng Lin,, Wenjun Lin, Weiwei Lin*, Tianyi Liu, Jiangtao Wang,, Hongliang Jiang. Multi-objective cooling control optimization for air-liquid cooled data centers using TCN-BiGRU-Attention-based thermal prediction models.  Building Simulation, 2024,17:2145–2161
4. Weiwei Lin, Jianpeng Lin*, Zhiping Peng, Huikang Huang, Wenjun Lin, Keqin Li. A systematic review of green-aware management techniques for sustainable data center.  Sustainable Computing: Informatics and Systems, 2024, 42: 100989
5. Wenjun Lin, Weiwei Lin*, Jianpeng Lin, Haocheng Zhong, Jiangtao Wang, Ligang He. A multi-agent reinforcement learning-based method for server energy efficiency optimization combining DVFS and dynamic fan control.  Sustainable Computing: Informatics and Systems, 2024, 42: 100977
6. Guokai Wu, Huabin Wang*, Weiwei Lin*, Ruichao Mo, Xiaoxuan Luo. FS-DBoost: cross-server energy efficiency and performance prediction in cloud based on transfer regression.  Cluster Computing, 2024, 27(6): 7705-7719.
7. Rui Chen, Huikang Huang, Xiaoxuan Luo, Weiwei Lin*. A Server Placement Algorithm for Reducing Risk and Improving Power Utilization in Data Centers.  Tsinghua Science and Technology , Tsinghua University Press, 2024, 29(1): 158--173
8. Lin, Jianpeng, Lin, Weiwei*, Huang, Huikang, Lin, Wenjun, Li, Keqin. Thermal Modeling and Thermal-aware Energy Saving Methods for Cloud Data Centers: A Review.  IEEE Transactions on Sustainable Computing, 2023: 1–20
9. Liang, Jiechao, Lin, Weiwei*, Xu, Yangguang, Liu, Yubin, Mo, Ruichao, Luo, Xiaoxuan. Energy-aware parameter tuning for mixed workloads in cloud server.  Cluster Computing, 2023, https://doi.org/10.1007/s10586-023-04212-6
10. Weiwei Lin, Xiaoxuan Luo*, ChunKi Li, Jiechao Liang, Guokai Wu, Keqin Li. An Energy-Efficient Tuning Method for Cloud Servers Combining DVFS and Parameter Optimization.  IEEE Transactions on Cloud Computing, 2023,11(4):3643-3655, DOI: 10.1109/TCC.2023.3308927
11. Rui Chen, Bo Liu, WeiWei Lin*, JianPeng Lin, HuiWen Cheng, KeQin Li. Power and thermal-aware virtual machine scheduling optimization in cloud data center.  Future Generation Computer Systems , 2023, 145: 578--589
12. Jianpeng Lin, Weiwei Lin*, Wenjun Lin, Jiangtao Wang, Hongliang Jiang. Thermal prediction for Air-cooled data center using data Driven-based model.  Applied Thermal Engineering, 2022,217,119207
13. 金育妍, 余天豪, 王松波, 林伟伟*, 潘宇聪. ARM架构云服务器的CPU功耗模型研究.  计算机科学, 2022, 49(10): 59-65.
14. 李俊祺, 林伟伟*, 石 方, 李克勤. 基于混合群智能的节能虚拟机整合方法.  软件学报, 2022,33(11):3944−3966
15. Wentai Wu, Weiwei Lin*, Ligang He, Guangxin Wu, Ching-Hsien Hsu. A Power Consumption Model for Cloud Servers Based on Elman Neural Network.  IEEE Transactions on Cloud Computing, 2021, 9(4): 1268-1277
16. Huiwen Cheng, Bo Liu, Weiwei Lin*, Zehua Ma, Keqin Li, Ching-Hsien Hsu. A survey of energy-saving technologies in cloud data centers.  The Journal of Supercomputing, 2021, 1-36, https://doi.org/10.1007/s11227-021-03805-5
17. Weiwei Lin, Tianhao Yu, Chongzhi Gao, Fagui Liu, Tengyue Li, Simon Fong, Yongxiang Wang. A Hardware-aware CPU Power Measurement Based on the Power-exponent Function Model for Cloud Servers.  Information Sciences, 2021,547, 1045-1065
18. Weiwei Lin*, Guangxin Wu, Xinyang Wang, Keqin Li. An Artificial Neural Network Approach to Power Consumption Model Construction for Servers in Cloud Data Centers.  IEEE Transactions on Sustainable Computing, 2020, 5(3):329-340
19. Weiwei Lin, Fang Shi*, Wentai Wu, Keqin Li, Guangxin Wu, Al-Alas Mohammed. A Taxonomy and Survey of Power Models and Power Modeling for Cloud Servers.  ACM Computing Surveys, 2020, 53(5): 1-41
20. Weiwei lin, Siyao xu, Ligang He, Jin Li. Multi-Resource Scheduling and Power Simulation for Cloud Computing.  Information Sciences, 2017, 397: 168-186.
21. Weiwei Lin, Weiqi Wang, Wentai Wu,Xiongwen Pang, Bo Liu, et al. A Heuristic Task Scheduling Algorithm Based on Server Power Efficiency Model in Cloud Environments.  Sustainable Computing: Informatics and Systems, 2017,DOI:10.1016/j.suscom.2017.10.007
22. Wentai Wu, Weiwei Lin*, Zhiping Peng. An Intelligent Power Consumption Model for Virtual Machines under CPU-intensive workload in Cloud Environment .  Soft Computing.2017, 21(19):5755–5764.
23. 林伟伟,吴文泰. 面向云计算环境的能耗测量和管理方法.  软件学报,2016,27(4):1026-1041

#### 1.2.2专利（详细参见学者网https://www.scholat.com/linweiwei）

1. 授权发明专利（202311844246.2）. 基于热预测模型的数据中心冷却控制方法及装置. 2024.12. 林伟伟, 林建鹏
2. 申请发明专利（2024118755550）. 一种基于软硬件联合优化的高性能计算集群基准能效调优方法. 2024.12. 林伟伟, 李志豪, 林建鹏
3. 申请发明专利（2024118755565）. 基于混合调节策略的加速器功耗优化方法、系统、设备及存储介质. 2024.12. 林伟伟, 牟奇
4. 申请发明专利（202410670153.0 ）. 知识迁移驱动的数据中心算力能效建模方法及装置. 2024.05. 林伟伟, 莫瑞超