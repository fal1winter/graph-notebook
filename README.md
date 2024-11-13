# graph-notebook
Study as hard as you can, don't be too tired
| 序号 | 标题    |   笔记链接 |           bbbbbb概括    |  论文链接  | 代码链接 |
| :--: | :-------------------:  | :--------------------------------:      | :------------------------: | :-------: |:-------: |
|1|ultragcn| [知乎](https://zhuanlan.zhihu.com/p/720972838) |一种用约束损失嵌入学习超多层gcn信息传播结果的方法，特点是效率高，amazonbooks上准确率提升明显。|https://arxiv.org/pdf/2110.15114 |[代码链接](https://github.com/kuisu-GDUT/UltraGCN)|
|2|Heterogeneous Graph Contrastive Learning for Recommendation（HGCL）| [知乎](https://zhuanlan.zhihu.com/p/730907108)| 一种经过少量卷积层的消息传递后，通过元知识（拼接的三种特征嵌入）生成的转换矩阵增强辅助信息（即u-u与i-i嵌入），并使用对比学习和bpr损失进行优化的方法。|https://arxiv.org/pdf/2303.00995|[代码链接](https://github.com/HKUDS/HGCL)|
| 3  | XSimGCL: Towards Extremely Simple Graph Contrastive Learning for Recommendation  |  [知乎](https://zhuanlan.zhihu.com/p/915933300)  |  一种通过在卷积过程中从嵌入层面添加噪声而非进行图增强来进行对比学习的方法，证明对比学习的有效性来自于infonce损失，通过简化结构和噪声均匀嵌入提升了效率和推荐公平性| https://arxiv.org/pdf/2209.02544| [代码链接](https://github.com/Coder-Yu/SELFRec) |
|4|Cooperative Graph Neural Networks| [知乎](https://zhuanlan.zhihu.com/p/1698280644)|一种让节点学习四种状态（听/不听）（广播/不广播）以更灵活和动态地进行消息传递的方法，实现上为节点生成状态概率并采用Gumbel-softmax硬采样方法，并重写消息传递函数，存在动作（决定状态）和环境（执行消息传递）两个网络，并采用相同的优化方式。|https://arxiv.org/pdf/2310.01267.pdf?trk=public_post_comment-text| [代码链接](https://github.com/benfinkelshtein/CoGNN/tree/main)|
|5|Adaptive Graph Contrastive Learning for Recommendation| [知乎](https://zhuanlan.zhihu.com/p/2726120426)|一种同时进行gae学习mean与方差并进行解码进行图增强和attention边去噪的图对比学习方法，去噪网络生成了新的边权重，在优化嵌入后仍使用gcn进行消息传递和cf|https://arxiv.org/pdf/2305.10837|[代码链接](https://github.com/HKUDS/AdaGCL)|
|6|DiffKG: Knowledge Graph Diffusion Model for Recommendation|https://zhuanlan.zhihu.com/p/4200921987|一种通过构建知识图并在知识图上进行去噪和gat消息传递并在去噪前后进行对比学习以优化item嵌入的方法|https://arxiv.org/pdf/2312.16890|[代码链接](https://github.com/HKUDS/DiffKG.)|
