## 2.云计算调度和算力管理优化（虚拟化、容器、AI资源） 

### 2.1 相关学习资料

#### 2.1.1 虚拟机、容器调度

1. 实验室内部报告：《云数据中心VM调度优化方法》、《主流云业务类型的负载分类模式》、《云计算弹性调度与GPU共享调度调研报告》
2. 林伟伟，刘波，刘发贵. 《分布式计算、云计算与大数据》第2版. 机械工业出版社. 2024.07
3. 林伟伟，彭绍亮. 云计算与大数据技术理论及应用. 清华大学出版社. 2019.07
4. Kubernetes：容器编排工具，学习Pod调度、自动扩缩容策略，https://github.com/kubernetes/kubernetes
5. 云数据集综述：https://github.com/ACAT-SCUT/Awesome-CloudComputing-Datasets
6. 云计算调度仿真工具CloudSim：http://www.cloudbus.org/cloudsim/

#### 2.1.2 DL负载调度

---

#### - 最新DL负载调度论文梳理

##### 通用DL负载调度

- **Awesome-DL-Scheduling-Papers**​  
  [GitHub链接](https://github.com/S-Lab-System-Group/Awesome-DL-Scheduling-Papers)  
  📚 深度学习集群调度论文精选集，覆盖训练/推理调度器设计（如Acme、Cassini等）。

- **ML-Systems-Papers**​  
  [GitHub链接](https://github.com/byungsoo-oh/ml-systems-papers)  
  🔍 机器学习系统领域论文分类整理，含调度优化方向。

##### LLM推理负载调度（LLM System）

- **Awesome_LLM_System-PaperList**​  
  [GitHub链接](https://github.com/galeselee/Awesome_LLM_System-PaperList)  
  🚀 大语言模型推理优化技术全集（vLLM、DeepSpeed等），涵盖KV缓存、推测解码等。

- **LLMSys-PaperList**​  
  [GitHub链接](https://github.com/AmberLJC/LLMSys-PaperList)  
  🔥 补充性LLM系统论文列表。

---

#### - 开源算法实现项目

- **S-Lab开源调度器项目**​  
  [GitHub组织](https://github.com/S-Lab-System-Group)  
  ⚙️ 包含DL调度器原型实现（如Lucid、Hydro等）。

- **微软研究院工具集**​  
  [MSR-Fiddle](https://github.com/msr-fiddle?tab=repositories)  
  🧪 实验性调度算法与性能分析工具。

---

#### - 仿真调度器

| 项目名称             | 链接                                                       | 特点                                                         |
| -------------------- | ---------------------------------------------------------- | ------------------------------------------------------------ |
| Blox                 | [GitHub](https://github.com/msr-fiddle/blox)               | 集群调度模拟器                                               |
| Lucid                | [GitHub](https://github.com/S-Lab-System-Group/Lucid)      | 弹性训练调度仿真                                             |
| Splitwise-Sim        | [GitHub](https://github.com/mutinifni/splitwise-sim)       | 分阶段推理模拟                                               |
| Vidur                | [GitHub](https://github.com/microsoft/vidur)               | **微软开源的LLM服务仿真平台**，支持：<br>• 多维度并行策略（流水线/张量并行）<br>• 推测解码工作流模拟<br>• 自动化部署配置搜索<br> |
| DL-Cluster-Simulator | [GitHub](https://github.com/nexuslrf/DL_cluster_simulator) | 可视化集群调度模拟器                                         |

---

#### - 开源框架

- **vLLM**​  
  [GitHub](https://github.com/vllm-project/vllm)  
  🏆 生产级LLM服务框架，支持PagedAttention优化。

- **SGLang**​  
  [GitHub](https://github.com/sgl-project/sglang)  
  🌐 面向LLM的高效服务框架。

---

#### - 典型DL负载

##### 语音模型

- [DeepSpeech-PyTorch](https://github.com/SeanNaren/deepspeech.pytorch)  
  📢 开源的基于PyTorch的语音识别模型实现。

##### 视觉模型

- [TorchVision Models](https://github.com/pytorch/vision/tree/main/torchvision/models)  
  🖼️ 标准CV模型库（ResNet、ViT等）。

##### 语言模型

- [NVIDIA翻译模型](https://github.com/NVIDIA/DeepLearningExamples/tree/master/PyTorch/Translation)  
  🌍 Transformer/GNMT实现。
- [NVIDIA语言建模](https://github.com/NVIDIA/DeepLearningExamples/tree/master/PyTorch/LanguageModeling)  
  📖 BERT/Transformer-XL等模型。

---


### 2.2 实验室相关成果

1. Guozhi Liu, Weiwei Lin*, Haotong Zhang, Jianpeng Lin, Shaoliang Peng, Keqin Li. Public Datasets for Cloud Computing: A Comprehensive Survey.  ACM Computing Surveys, 2025,57(8):1-38
2. Wangbo Shen, Weiwei Lin*, Wentai Wu, Haijie Wu, Keqin Li. Reinforcement learning-based task scheduling for heterogeneous computing in end-edge-cloud environment.  Cluster Computing, 2025, 28(3)
3. Haijie Wu, Weiwei Lin*, Wangbo Shen, Xiumin Wang, C. L. Philip Chen, Keqin Li. Prediction of Heterogeneous Device Task Runtime Based on Edge Server-Oriented Deep Neuro-Fuzzy System.  IEEE Transactions on Services Computing, 2025,18(1):372 - 384
4. Peng Peng, Wentai Wu*, Weiwei Lin*, Fan Zhang, Yongheng Liu, Keqin Li. Reliable Task Offloading in Sustainable Edge Computing with Imperfect Channel State Information.  IEEE Transactions on Network and Service Management, 2024, 21(6):6423 - 6436
5. Haijie Wu, Wangbo Shen, Weiwei Lin*, Wei Li, Keqin Li,. End-Edge-Cloud Heterogeneous Resources Scheduling Method Based on RNN and Particle Swarm Optimization.  IEEE Transactions on Network and Service Management, 2024: 1–1
6. Peng Peng, Weiwei Lin, Wentai Wu, Haotong Zhang,, Shaoliang Peng, Qingbo Wu, Keqin Li. A survey on computation offloading in edge systems: From the perspective of deep reinforcement learning approaches.  Computer Science Review, 2024, 53: 100656.
7. Hongrui Lin, Guodong Liu*, Weiwei Lin*, Xinhua Wang, Xiumin Wang. A novel virtual machine consolidation algorithm with server power mode management for energy-efficient cloud data centers.  Cluster Computing, 2024: 1-17.
8. Haotong Zhang, Weiwei Lin*, Rong Xie, Shenghai Li, Zhiyan Dai, James Z. Wang. An optimal container update method for edge-cloud collaboration.  Software: Practice and Experience , Wiley, 2023, 1-18, DOI: 10.1002/spe.3232
9. Weiwei Lin, Chennian Xiong*, Wentai Wu*, Fang Shi, Keqin Li, Minxian Xu. Performance Interference of Virtual Machines: A Survey.  ACM Computing Surveys, 2023, 55(12): 1-37.
10. Bo Liu, Rui Chen, Weiwei Lin*, Wentai Wu*, Jianpeng Lin, Keqin Li. Thermal-aware virtual machine placement based on multi-objective optimization.  The Journal of Supercomputing , 2023, 79, pages12563–12590
11. 林伟伟, 石方, 李毓睿, 刘发贵, 刘捷, 彭绍亮, 王子骏. 面向混部云失败批处理作业的预测算法.  国防科技大学学报, 2022,44(5):71-79
12. Weiwei Lin, Kun Yao, Lan Zeng, Fagui Liu, Chun Shan, Xiaobin Hong*. A GAN-based method for time-dependent cloud workload generation.  Journal of Parallel and Distributed Computing , 2022,168:33-44
13. Weiwei Lin*, Wentai Wu*, Ligang He. An On-line Virtual Machine Consolidation Strategy for Dual Improvement in Performance and Energy Conservation of Server Clusters in Cloud Data Centers.  IEEE Transactions on Services Computing, 2022,15(2): 766-777 
14. 林伟伟, 王泽涛. 基于遗传算法的Docker集群调度策略.  华南理工大学学报(自然科学版), 2018, 46(3):127-133
15. Weiwei Lin, SiYao Xu, Jin Li, Lingling Xu, Zhiping Peng. Design and theoretical analysis of virtual machine placement algorithm based on peak workload characteristics.  Soft Computing. 2017, 21(5): 1301-1314
16. 徐思尧，林伟伟*，王子骏. 基于负载高峰特征的虚拟机放置算法.  软件学报, 2016,27(7):1876-1887