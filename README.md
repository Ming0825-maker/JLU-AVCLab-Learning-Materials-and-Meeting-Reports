# JLU-AVCLab Learning Materials and Meeting Reports

吉林大学 AVCLab 实验室学习资料与组会汇报汇总。

## 关于我

- 吉林大学 **AVCLab** 实验室成员
- 研究方向：**计算机视觉（Computer Vision）**、**世界模型（World Models）**
- GitHub：[Ming0825-maker](https://github.com/Ming0825-maker)

## 组会汇报

本仓库持续整理组会汇报的**汇报主题、讲述内容、飞书 / PPT 资源与 B 站视频链接**，便于回顾与分享。

| 汇报主题 | 讲述内容 | 飞书 / PPT 资源 | B站链接 |
| --- | --- | --- | --- |
| Computer Vision | ①图像张量：彩色图为 (H,W,3) 三维张量，RGB + 0~255，归一化到 0~1 减小尺度差异；②分类任务：二分类 / 多分类 / 多标签 / 细粒度分类；③KNN：免训练，L1/L2 距离 + 邻居投票，K 值用验证集调优；④线性分类器：权重×像素+偏置→分数，Softmax 转概率；⑤损失与优化：交叉熵 + 梯度下降，Momentum / RMSprop / Adam 应对拐点、缓坡、悬崖；⑥过拟合与正则化：L2 正则化（岭回归）更常用，AdamW 解耦权重衰减 | [PPT](https://github.com/Ming0825-maker/JLU-AVCLab-Learning-Materials-and-Meeting-Reports/blob/main/reports/计算机视觉基础知识_陈一鸣_20260813.pptx) | https://bilibili.com/video/BV1rwgN6kE19/?spm_id_from=333.1387.upload.video_card.click |
| Computer Vision-02 | 从非线性变换、激活函数和前向传播讲起，逐步拆解反向传播、链式求导与梯度更新的基本原理；随后介绍 CNN 的局部连接、权重共享、Padding 与感受野，并回顾 LeNet、AlexNet、VGGNet 到 ResNet 的架构演进；最后延伸至自注意力机制与 Transformer 的基本结构 | [PPT](https://github.com/Ming0825-maker/JLU-AVCLab-Learning-Materials-and-Meeting-Reports/blob/main/reports/计算机视觉基础知识_陈一鸣_20260820.pptx) | https://bilibili.com/video/BV1WE8t6fEgg/?spm_id_from=333.1387.upload.video_card.click |
| 汇报主题 3（待补充） | 待补充 | 待补充 | 待补充 |

> 💡 说明：PPT 源文件统一存放在 `reports/` 目录，点击表格中的「PPT」即可查看或下载。

## 更新记录

- 2026-10-18：初始化 README，组会汇报表格新增「讲述内容」列
- 2026-10-18：填入第一、二条汇报（Computer Vision / Computer Vision-02）
- 2026-10-18：上传汇报 PPT 至 `reports/`，补齐表格中 PPT 资源链接
- 2026-10-18：更新 Computer Vision 讲述内容为精简要点版
