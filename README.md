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
| Computer Vision | • 图像张量与归一化<br>• 四种分类任务<br>• KNN 与 L1/L2 距离<br>• 线性分类器 + Softmax<br>• 交叉熵与梯度下降<br>• Momentum / RMSprop / Adam<br>• L2 正则化与 AdamW | [PPT](https://github.com/Ming0825-maker/JLU-AVCLab-Learning-Materials-and-Meeting-Reports/blob/main/reports/计算机视觉基础知识_陈一鸣_20260813.pptx) | [B站视频](https://bilibili.com/video/BV1rwgN6kE19/?spm_id_from=333.1387.upload.video_card.click) |
| Computer Vision-02 | • 非线性变换与激活函数<br>• 前向传播与反向传播<br>• 链式求导与梯度更新<br>• CNN 局部连接与权重共享<br>• Padding 与感受野<br>• LeNet / AlexNet / VGGNet / ResNet 演进<br>• 自注意力机制与 Transformer | [PPT](https://github.com/Ming0825-maker/JLU-AVCLab-Learning-Materials-and-Meeting-Reports/blob/main/reports/计算机视觉基础知识_陈一鸣_20260820.pptx) | [B站视频](https://bilibili.com/video/BV1WE8t6fEgg/?spm_id_from=333.1387.upload.video_card.click) |
| Computer Vision-03 | • 候选区域与滑动窗口<br>• IoU / Precision / Recall / NMS<br>• R-CNN → Fast R-CNN → Faster R-CNN<br>• YOLO 单阶段检测<br>• DETR 端到端集合预测<br>• FCN / SegNet / U-Net 分割 | [PPT](https://github.com/Ming0825-maker/JLU-AVCLab-Learning-Materials-and-Meeting-Reports/blob/main/reports/计算机视觉基础知识_陈一鸣_20260827.pptx) | [B站视频](https://www.bilibili.com/video/BV14itt68EdN/) |
| 注意力机制、Transformer | • 点积注意力与自注意力：向量化、语义相似度、依赖关系图<br>• Attention 公式：softmax(QK^T/√d) V，Q / K / V 的角色理解<br>• 多头注意力：多子空间并行计算 + 拼接线性变换<br>• Transformer 架构：Embedding + 位置编码 + 多头自注意力 + FFN + 残差与层归一化<br>• 掩码多头自注意力：防止偷看未来 token<br>• 编码器-解码器注意力：K、V 来自编码器，Q 来自解码器<br>• 训练与推理：教师强制、逐步预测 | [飞书笔记](https://acn3t8qa5wm4.feishu.cn/wiki/NUZEwrOsQiRo9YkW3emcIY7PnIc) | 待补充 |
| 生成式模型 | • 概率与信息论基础：似然 / 最大似然估计 / 熵 / 交叉熵 / KL 散度 / 贝叶斯公式<br>• 隐变量模型与 VAE：ELBO 推导、编码器-解码器<br>• DDPM 扩散模型：前向加噪 / 反向去噪 / 噪声预测损失<br>• DDIM：非马尔可夫路径加速采样<br>• U-Net 与 LDM（Stable Diffusion）：潜空间扩散 + 条件生成<br>• ViT → DiT → MMDiT：扩散主干演进、多模态双流架构<br>• Flow Matching 与 Flux：速度场学习、CFM 目标、直线轨迹积分 | [飞书笔记](https://acn3t8qa5wm4.feishu.cn/wiki/Edm6wpAdlinyuvkvezycUIpHn9c) | 待补充 |

> 💡 说明：PPT 源文件统一存放在 `reports/` 目录，点击表格中的「PPT」即可查看或下载；「B站视频」点击即可跳转播放。

## 更新记录

- 2026-10-18：初始化 README，组会汇报表格新增「讲述内容」列
- 2026-10-18：填入第一、二条汇报（Computer Vision / Computer Vision-02）
- 2026-10-18：上传汇报 PPT 至 `reports/`，补齐表格中 PPT 资源链接
- 2026-10-18：第一、二条讲述内容统一为圆点短要点分行排版
- 2026-10-18：填入第三条汇报 Computer Vision-03 并补齐 B 站链接
- 2026-10-18：B 站链接改为文字链接，压缩列宽以突出讲述内容列
- 2026-10-18：填入第四条「生成式模型」（AI 总结自飞书笔记）
- 2026-10-18：填入「注意力机制、Transformer」（AI 总结自飞书笔记）
