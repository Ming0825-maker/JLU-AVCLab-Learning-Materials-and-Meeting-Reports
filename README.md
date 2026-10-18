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
| 注意力机制、Transformer | • 点积注意力与自注意力：向量化、语义相似度、依赖关系图<br>• Attention 公式讲解<br>• 多头注意力：多子空间并行计算 + 拼接线性变换<br>• Transformer 架构详细介绍<br>• 掩码多头自注意力<br>• 编码器-解码器注意力<br>• 训练与推理：教师强制、逐步预测 | [飞书笔记](https://acn3t8qa5wm4.feishu.cn/wiki/NUZEwrOsQiRo9YkW3emcIY7PnIc) | 待补充 |
| 生成式模型 | • 概率与信息论基础<br>• 隐变量模型与 VAE：ELBO 推导、编码器-解码器<br>• DDPM 扩散模型：前向加噪 / 反向去噪 / 噪声预测损失<br>• DDIM：非马尔可夫路径加速采样<br>• U-Net 与 LDM（Stable Diffusion）：潜空间扩散 + 条件生成<br>• ViT → DiT → MMDiT：扩散主干演进、多模态双流架构<br>• Flow Matching 与 Flux：速度场学习、CFM 目标、直线轨迹积分 | [飞书笔记](https://acn3t8qa5wm4.feishu.cn/wiki/Edm6wpAdlinyuvkvezycUIpHn9c) | 待补充 |
| Codex 使用与 Skill 推荐 | • Codex：云端软件工程智能体，支持 CLI / Desktop / IDE<br>• 模型选择与推理强度设置<br>• 计划模式、Vibe Coding、Git 审核与多对话协作<br>• PPT、文档、PDF、表格、绘图等 Skill 推荐<br>• Codex + Zotero + Obsidian 论文精读工作流 | [飞书笔记](https://acn3t8qa5wm4.feishu.cn/wiki/CDKBwfb1OiFMHekJFXwcvkL6nKd) | [B站视频](https://www.bilibili.com/video/BV1kHLU6jEoi/?spm_id_from=333.1387.upload.video_card.click&vd_source=00d603d7ea836bdbba791b1c2d6976c6) |
| AI大模型制作PowerPoint | • ChatGPT：用 Lyra 的 4-D 方法生成结构化 PPT 大纲<br>• OpenClaw：安装 PowerPoint PPTX Skill，支持编辑、导出和布局优化<br>• Gamma：支持提示词、粘贴文本、模板和文件导入四种生成方式<br>• Gemini 3.1 Pro：使用 Canvas 生成 Google 幻灯片，可导出演示文稿并提供演讲稿<br>• NotebookLM：基于文本、PDF、Word 等来源生成 PPT，视觉效果好但编辑能力有限<br>• Kimi：输入 PPT 大纲并指定输出 PPT，内容和图表较丰富<br>• 对比：OpenClaw、Gamma、Gemini 3.1 Pro 和 Kimi 可编辑；NotebookLM 视觉效果最佳但不可编辑 | [飞书笔记](https://acn3t8qa5wm4.feishu.cn/wiki/J6QWwB89ZisM5KkijrfcxjtYnUe) | 待补充 |
| Qwen 大模型报告 | • Dense、MoE 与 Base / Instruct / Thinking 基础概念<br>• GQA、MQA、RoPE、SwiGLU、Pre-RMSNorm 等关键组件<br>• Qwen2.5：预训练、后训练与 DPO / GRPO<br>• Qwen3：Thinking / Non-thinking、强化学习与知识蒸馏<br>• Qwen3-Next、Qwen3-VL 与 Qwen3.5 Agent 技术演进 | [PPT](https://github.com/Ming0825-maker/JLU-AVCLab-Learning-Materials-and-Meeting-Reports/blob/main/reports/Qwen_大模型报告_陈一鸣_20260922.pptx) | [B站视频](https://www.bilibili.com/video/BV1H5H46PEaD/?spm_id_from=333.1387.upload.video_card.click&vd_source=00d603d7ea836bdbba791b1c2d6976c6) |
| Qwen 微调实验 | • 基于 Qwen2-VL 的 LoRA 微调实验 | [PPT](https://github.com/Ming0825-maker/JLU-AVCLab-Learning-Materials-and-Meeting-Reports/blob/main/reports/Qwen_微调实验报告_陈一鸣_20260922.pptx) | [B站视频](https://www.bilibili.com/video/BV1H5H46PEaD/?spm_id_from=333.1387.upload.video_card.click&vd_source=00d603d7ea836bdbba791b1c2d6976c6) |
| Wan 2.1/2.2 深度解析 | • Wan2.1/2.2 模型家族与多模态视频生成<br>• 视频时空结构与扩散模型基础<br>• Wan-VAE：时空压缩、因果建模与帧缓存<br>• DiT、Cross-Attention 与 Flow Matching<br>• Wan2.2 双专家 MoE 的分阶段去噪<br>• 视频生成模型作为世界模型 Backbone 的原因<br>• Matrix-Game 3.0：误差历史、长期记忆与多段蒸馏 | [PPT](https://github.com/Ming0825-maker/JLU-AVCLab-Learning-Materials-and-Meeting-Reports/blob/main/reports/Wan_技术报告_陈一鸣_20261013.pptx) | [B站视频](https://www.bilibili.com/video/BV11RJD6TEeq/?spm_id_from=333.1387.upload.video_card.click&vd_source=00d603d7ea836bdbba791b1c2d6976c6) |
| 基于 Wan 的微调以及世界模型推理实验 | • Wan 视频模型微调：针对动作、特效与风格进行定制<br>• 阿里云百炼平台：上传数据集、创建微调任务与 API 调用<br>• 金钱雨特效 LoRA：输入首帧图像，无需提示词生成目标视频<br>• BWM 世界模型：根据场景首帧和机器人动作序列预测后续视频<br>• 输入历史帧、动作状态与随机噪声，输出 896×672、24 FPS 的 H.264 视频<br>• Wan2.2-TI2V-5B 与 BWM Checkpoint 组成模型，支持双臂 14 维状态归一化和逐帧轨迹推理 | [飞书笔记](https://acn3t8qa5wm4.feishu.cn/wiki/SvsvwfbcciMRpckRmUackXS8nRb) | [B站视频](https://www.bilibili.com/video/BV11RJD6TEeq/?spm_id_from=333.1387.upload.video_card.click&vd_source=00d603d7ea836bdbba791b1c2d6976c6) |


💡 说明：PPT 源文件统一存放在 reports/ 目录，点击表格中的「PPT」即可查看或下载；「B站视频」点击即可跳转播放。


## 更新记录


- 2026-10-18：初始化 README，组会汇报表格新增「讲述内容」列
- 2026-10-18：填入第一、二条汇报（Computer Vision / Computer Vision-02）
- 2026-10-18：上传汇报 PPT 至 reports/，补齐表格中 PPT 资源链接
- 2026-10-18：第一、二条讲述内容统一为圆点短要点分行排版
- 2026-10-18：填入第三条汇报 Computer Vision-03 并补齐 B 站链接
- 2026-10-18：B 站链接改为文字链接，压缩列宽以突出讲述内容列
- 2026-10-18：填入第四条「生成式模型」（AI 总结自飞书笔记）
- 2026-10-18：填入「注意力机制、Transformer」（AI 总结自飞书笔记）
- 2026-10-18：填入并补充「Codex 使用与 Skill 推荐」的 B 站视频链接
- 2026-10-18：填入「AI大模型制作PowerPoint」（AI 总结自飞书笔记）
- 2026-10-18：填入「Qwen 大模型报告」并补齐 PPT、B 站链接
- 2026-10-18：填入「Qwen 微调实验」并补齐 PPT、B 站链接
- 2026-10-18：填入「Wan 2.1/2.2 深度解析」并补齐 PPT、B 站链接
- 2026-10-18：填入「基于 Wan 的微调以及世界模型推理实验」（AI 总结自飞书笔记）并补齐飞书、B 站链接
