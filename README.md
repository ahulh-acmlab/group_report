# 组会报告记录

## 2021年4月21日

| 论文     | EfficientNetV2: Smaller Models and Faster Training           |
| -------- | ------------------------------------------------------------ |
| 发表时间 | 2021年3月                                                    |
| 作者     | Mingxing Tan , Quoc V. Le                                    |
| 来源     | Google brain                                                 |
| 主要内容 | 本文介绍了EfficientNetV2，这是一种用于图像识别的更小，更快的神经网络新系列。Efficient-NetV2通过具有训练意识的**NAS和模型扩展**进行了优化，其性能大大优于以前的模型，同时在参数上更快速，更高效。 为了进一步加快训练速度，我们提出了一种改进的**渐进式学习**方法，该方法可以在训练过程中共同**增加图像大小和正则化**。 |
| 实验结果 | 大量实验表明，我们的EfficientNetV2在Ima-geNet和CIFAR /鲜花/汽车上均取得了出色的成绩。 与EfficientNet和更近期的作品相比，我们的EfficientNetV2的**训练速度提高了11倍，而小了6.8倍**. |
| paper    | [EfficientNetV2.pdf](https://github.com/ahulh-acmlab/group_report/blob/main/2021-4-21/EfficientNetV2.pdf) |
| code     | <https://github.com/google/automl/>(efficientv2的代码尚未)   |
| ppt      | [EfficientNetV2.pptx](https://github.com/ahulh-acmlab/group_report/blob/main/2021-4-21/EfficientNetV2.pptx) |
| 报告人   | [吴昌广](https://github.com/PiKaChu-wcg)                     |



| 论文     | What Can Help Pedestrian Detection ?                         |
| -------- | ------------------------------------------------------------ |
| 发表时间 | 2017 年                                                      |
| 作者     | Jiayuan Mao, Tete Xiao, Yuning Jiang, Zhimin Cao             |
| 来源     | CVPR 2017                                                    |
| 主要内容 | 本文通过将额外的**特征聚合**到基于CNN的行人检测框架中来讨论基于CNN的行人探测器是否以及如何受益于额外特征。通过大量的实验，我们对不同类型的额外特征的效果进行了定量的评估。此外，我们还提出了一种新的网络结构，即**HyperLearner**，用于联合学习行人检测和给定的额外特征。 |
| 实验结果 | 通过多任务训练，HyperLearner能够利用给定特征的信息，在不增加推理输入的情况下提高检测性能。在多个行人数据集上的实验结果验证了所提出的HyperLearner算法的有效性。我们的定量实验显示**语义信道特征**可以帮助检测器辨别困难的正样本和低分辨率的负样本。而**表征信道特征**可**抑制**背景的**误报**并**提高**高分辨率下的**定位精度**。 |
| paper    | [What Can Help Pedeatrian Detection.pdf](https://github.com/ahulh-acmlab/group_report/blob/main/2021-4-21/What%20Can%20Help%20Pedeatrian%20Detection.pdf) |
| code     | 暂无                                                         |
| ppt      | [What Can Help Pedestrian Detection.pptx](https://github.com/ahulh-acmlab/group_report/blob/main/2021-4-21/What%20Can%20Help%20Pedestrian%20Detection.pptx) |
| 报告人   | [张子谦](https://github.com/zzqwtc)                          |

## 2021年4月28日

| 论文     | Occlusion-aware R-CNN Detecting Pedestrians in a Crowd       |
| -------- | ------------------------------------------------------------ |
| 发表时间 | 2018年9月                                                     |
| 作者     | Shifeng Zhang, Longyin Wen, Xiao Bian, Zhen Lei, Stan Z. Li  |
| 来源     | ECCV 2018                                                    |
| 主要内容 | 本文主要解决对于行人的遮挡问题，本文在R-CNN的基础上主要引入了两个内容，一是**聚合损失函数**(aggregation loss)强制使proposals能够靠近真实值，二是用**部分遮挡感知 ROI 池单元** (part occlusion-aware region of interest(PORoI)pooling unit)对RoI池化层进行替换,将具有可见性的预测人体先验结构信息整合到网络中处理遮挡.|
| 实验结果 | 采用端到端的方式进行训练，在三个行人数据集 City Person、ETHI、INRIA上实现了2018年6月最先进的精度 |
| paper    | [Occlusion-aware R-CNN Detecting](https://github.com/ahulh-acmlab/group_report/blob/main/2021-4-28/Shifeng_Zhang_Occlusion-aware_R-CNN_Detecting_ECCV_2018_paper.pdf) |
| code     | 暂无                                                        |
| ppt      | [or-cnn.pptx](https://github.com/ahulh-acmlab/group_report/blob/main/2021-4-28/or-cnn.pptx) |
| 报告人   | [李哲楷](https://github.com/Ayric-cmad)                     |



| 论文     | Designing Network Design Spaces       |
| -------- | ------------------------------------------------------------ |
| 发表时间 |    2020年                                                  |
| 作者     | Ilija Radosavovic,Raj Prateek Kosaraju,Ross Girshick,Kaiming He,Piotr Doll´ar  |
| 来源     | CVPR 2020                                                    |
| 主要内容 | 本文针对图像识别，提出了一种**改进神经网络**的方法。本文结合了手动设计与NAS(neural architecture search)的优点，力求使得改进后的神经网络在保持各项指标优秀的情况下，具有**更强的简易性、可解释性**与**更低的算力需求、训练次数需求**；同时在此基础上，提高了该方法的**普适性**。|
| 实验结果 |实验数据表明，其他条件相同时，在中等水准以上flops的情况下，尤其是高水准flops时，RegNet的表现优于EfficientNet，**误差更小**，且训练速度更快，**最高可达5倍速度**。  |
| paper    | [Designing Network Design Spaces](https://github.com/ahulh-acmlab/group_report/blob/main/2021-4-28/Radosavovic_Designing_Network_Design_Spaces_CVPR_2020_paper.pdf) |
| code     | [RegNet-Search-PyTorch](https://github.com/zhanghang1989/RegNet-Search-PyTorch)                                                        |
| ppt      | [Designing%20Network%20Design%20Spaces](https://github.com/ahulh-acmlab/group_report/blob/main/2021-4-28/Designing%20Network%20Design%20Spaces.pptx) |
| 报告人   | [常昊冉](https://github.com/Rienotox)                     |
