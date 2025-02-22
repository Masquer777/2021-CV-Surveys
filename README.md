<div align="center">
  <img src="image/52CV1.png" width="600"/>
</div>

# 2021-CV-Surveys

2021 年，计算机视觉相关综述。包括目标检测、跟踪........

### :green_book::green_book::green_book:下载这些综述在【我爱计算机视觉】后台回复“CV综述”，即可收到。目前已公开 95 篇。

## 目录

|:cat:|:dog:|:tiger:|:wolf:|
|------|------|------|------|
|[32.Adversarial Example Detection(对抗性示例检测)](#32)|[31.Change Detection(变化检测)](#31)|
|[30.Gaze Estimation(视线估计)](#30)|[29.图像标注](#29)|[Depth Estimation(深度估计)](#28)|[27.Sign Language Production(手语制作)](#27)|[26.Image Representation(图像表征)](#26)|[25.Multimedia Technology(多媒体技术)](#25)|
|[24.Image Processing(图像处理)](#24)|[23.3D 语义场景完成(SSC)](#23)|[22.Image Segmentation(图像分割)](#22)|[21.Few-Shot/Zero-Shot Learning,Domain Generalization/Adaptation(小/零样本学习，域适应，域泛化)](#21)|
|[20.Anomaly Detection(异常检测)](#20)|[19.Transformers](#19)|[18.Point Clouds(点云)](#18)|[17.Object Detection(目标检测)](#17)|
|[16.Human Action Detection and Recognitionn(人体动作检测与识别)](#16)|[15.Person Re-Identification(人员重识别)](#15)|[14.:dancers:Human Pose Estimation(人体姿态估计)](#14)|[13.Image Classification(图像分类)](#13)|
|[12.Image Retrieval(图像检索)](#12)|[11.:neutral_face:Face(人脸技术)](#11)|[10.Super-Resolution(超分辨率)](#10)|[9.Quantization/Pruning/Knowledge Distillation/Model Compression(量化、剪枝、蒸馏、模型压缩/扩展与优化)](#9)|
[8.Deep Learning(深度学习)](#8)|[7.Aeria/Drones/Satellite/RS Image(航空影像/无人机)](#7)|[6.GAN 生成对抗网络](#6)|[5.:bus:智能驾驶](5)|
|[4.Video Processing(视频相关技术)](#4)|[3.Visual Question Answering(视觉问答)](#3)|[2.:hospital:医学影像](#2)|[1.Unkown(未分)](#1)|

详细请看：

- [推荐几篇近期必看的视觉综述，含图像检索、目标检测、人脸关键点检测、医学图像分割、遥感、模型优化等](https://mp.weixin.qq.com/s/rO-0IaDy7cAehryFKYbT_g) <br>[一月中下旬]

- [推荐几篇近期必看的视觉综述，含GAN、Transformer、人脸超分辨、遥感等](https://mp.weixin.qq.com/s?__biz=MzUzODkxNzQzMw==&mid=2247488123&idx=1&sn=f51f3137a16e625c962705997f0daf0a&chksm=fad13d2dcda6b43b1001b8ff924f317f5fcbdbcbd41894b193823e2fcd1d2412f4c3394ebb8e&scene=21#wechat_redirect) <br>[一月上旬]

<a name="32"/>

## 32.Adversarial Example Detection(对抗性示例检测)
* [Adversarial Example Detection for DNN Models: A Review](https://arxiv.org/abs/2105.00203)<br>[2021-05-04]<br>本文试图为 AE 检测方法提供一个理论和实验回顾。对这些方法进行了详细的讨论，并在四个数据集的不同场景下介绍了八个最先进的检测器的实验结果。还提供了该研究方向的潜在挑战和未来前景。

<a name="31"/>

## 31.Change Detection(变化检测)
* [An Empirical Review of Deep Learning Frameworks for Change Detection: Model Design, Experimental Frameworks, Challenges and Research Needs](https://arxiv.org/abs/2105.01342)<br>[2021-05-05]<br>用于变化检测的深度学习框架的经验性回顾:模型设计、实验框架、挑战和研究需求

<a name="30"/>

## 30.Gaze Estimation(视线估计)
* [Appearance-based Gaze Estimation With Deep Learning: A Review and Benchmark](https://arxiv.org/abs/2104.12668)<br>[2021-04-27]<br>:star:[code](http://phi-ai.org/GazeHub/)<br>本片综述是对基于外观的深度学习的视线估计方法进行的全面回顾。并从四个角度讨论这些方法：深度特征提取、深度神经网络架构设计、个人校准以及设备和平台。

<a name="29"/>

## 29.图像标注
* [A survey of image labelling for computer vision applications](https://arxiv.org/abs/2104.08885)<br>[2021-04-20]<br>图像标注在计算机视觉中的应用调研

<a name="28"/>

## 28.Depth Estimation(深度估计)
* [Single Image Depth Estimation: An Overview](https://arxiv.org/abs/2104.06456)<br>[2021-04-15]<br>本文是对场景理解中的重要子任务深度估计的回顾，并重点关注单图像深度估计。从早于深度学习，利用手工制作的特征和假设的非深度学习方法，到大多使用深度学习技术的最新作品；从监督到无监督。以及将深度估计问题与语义分割和表面法线估计等相关任务相结合的多任务方法。最后，还讨论了对当代解决方案的机制、原理和失败案例的调查。

<a name="27"/>

## 27.Sign Language Production(手语制作)
* [Sign Language Production: A Review](https://arxiv.org/abs/2103.15910)<br>[2021-03-31]<br>本文回顾了利用深度学习在手语制作（SLP）和相关领域的最新进展。旨在简要总结SLP 的最新成就，讨论其优势、局限性和未来的研究方向。

<a name="26"/>

## 26.Image Representation(图像表征)

* [A Survey of Orthogonal Moments for Image Representation: Theory, Implementation, and Evaluation](https://arxiv.org/abs/2103.14799)<br>[2021-03-30]<br>本文是对用于图像表征的正交矩进行的全面调查，涵盖快速/精准计算、鲁棒性/不变性优化和定义扩展方面的最新进展。为各种广泛使用的正交矩创建了一个软件包，并在同一基础上对这些方法进行了评估。作者表示所提出的理论分析、软件实现和评价结果可以为社会提供支持，特别是在开发新技术和推广实际应用方面。


<a name="25"/>

## 25.Multimedia Technology(多媒体技术)

* [A Survey of Multimedia Technologies and Robust Algorithms](https://arxiv.org/abs/2103.13477)<br>[2021-03-26]<br>本文是对从日常生活到医学研究的各种多媒体技术和强大算法的调研。
* [Multimedia Technology Applications and Algorithms: A Survey](https://arxiv.org/abs/2104.01301)<br>[2021-04-06]<br>多媒体技术及用于综述调研

<a name="24"/>

## 24.Image Processing(图像处理)
* 图像美学评级
  * [A Survey of Hand Crafted and Deep Learning Methods for Image Aesthetic Assessment](https://arxiv.org/abs/2103.11616)<br>[2021-03-23]<br>文章是对近期图像美学自动评估技术进行的文献调查。回顾大量的传统手工制作和基于深度学习的方法。并对关键的问题进行讨论，如为什么一些特征或模型比其他的表现更好，有什么局限性。最后对不同方法的量化结果进行比较。

<a name="23"/>

## 23.Semantic Scene Completion(语义场景完成SSC)

- [3D Semantic Scene Completion: a Survey](https://arxiv.org/abs/2103.07466)<br>[2021-03-15]<br>本文是对当代最先进的 3D 语义场景完成方法进行的全面调查。回顾并严格分析了所提出的方法的主要方面，包括需要考虑的重要设计选择，并比较了它们在流行的 SSC 数据集中的性能。作者希望这项调查将支持该领域的进一步发展，旨在提供新的见解，并帮助没有经验的读者浏览该领域。

<a name="22"/>

## 22.Image Segmentation(图像分割)

- [Deep Learning based 3D Segmentation: A Survey](https://arxiv.org/abs/2103.05423)<br>[2021-03-10]<br>本篇综述是对基于深度学习的三维分割的最新进展进行了全面的调查，包含150多篇论文文献。总结了最常用的 pipelines，对其亮点和不足进行了讨论，并分析了这些分割方法的竞争结果。还在分析的基础上，提供了未来有前景的研究方向。


<a name="21"/> 

## 21.Few-Shot/Zero-Shot Learning,Domain Generalization/Adaptation(小/零样本学习，域适应，域泛化)

* 域泛化
  * [Generalizing to Unseen Domains: A Survey on Domain Generalization](https://arxiv.org/abs/2103.03097)<br>[2021-03-05]<br>本篇文章作者从 same-source（同源） 和 cross-source（跨源）域对点云配准进行了全面的回顾
  * [Domain Generalization: A Survey](https://arxiv.org/abs/2103.02503)<br>[2021-03-04]<br>本篇文章是首次对 DG（Domain Generalization）的十年发展进行了全面的文献回顾总结<br>


<a name="20"/> 

## 20.Anomaly Detection(异常检测)

- [Image/Video Deep Anomaly Detection: A Survey](https://arxiv.org/abs/2103.01739)
<br>[2021-03-03]<br>基于图像和视频的深度学习 AD 的专业综述的缺失，作者对此进行了深入调查。工作的重点在无监督技术上，并提供 AD 概念的精确定义，同时对最近提出的 AD 方法进行了的分类。以及对当前的挑战和未来的研究方向进行了彻底讨论。


<a name="19"/> 

## 19.Transformers<br>

- [Transformers in Vision: A Survey](https://arxiv.org/abs/2101.01169)<br>[2021-01-01]<br>旨在为计算机视觉学科中的 Transformer 模型提供一个全面的概述


<a name="18"/> 

## 18.Point Clouds(点云)


- [Attention Models for Point Clouds in Deep Learning: A Survey](https://arxiv.org/abs/2102.10788) <br>[2021-02-23]<br>对使用注意力模型的点云特征表示进行全面的概述
- [A comprehensive survey on point cloud registration](https://arxiv.org/abs/2103.02690)<br>[2021-03-05]<br>回顾了跨源点云配准的发展，并建立一个新的基准来评估最新的配准算法。此外，本次综述还总结了基准数据集，并讨论了各领域的点云配准应用。

<a name="17"/> 

## 17.Object Detection(目标检测)

- [Occlusion Handling in Generic Object Detection: A Review](https://arxiv.org/abs/2101.08845)<br>[2021-01-25]
- [A Survey of Deep Learning Techniques for Weed Detection from Images](https://arxiv.org/abs/2103.01415)<br>[2021-03-03]<br>从图像中检测杂草的深度学习技术调查报告,共梳理了70篇相关文献。
- [A Survey of Modern Deep Learning based Object Detection Models](https://arxiv.org/abs/2104.11892)<br>[2021-04-27]<br>本片综述是对基于深度学习的目标检测器最新发展的调查。提供了检测中使用的基准数据集和评估指标的简要概述，以及识别任务中使用的一些突出的骨干架构。涵盖了在边缘设备上使用的当代轻量级分类模型。并比较了这些架构在多个指标上的表现。
* 弱监督目标定位与检测
  * [Weakly Supervised Object Localization and Detection: A Survey](https://arxiv.org/abs/2104.07918)<br>[2021-04-19]<br>本篇综述回顾了弱监督目标定位与检测的经典模型，来自现成深度网络的特征表示方法，完全基于深度学习的方法，以及在该领域广泛使用的公开数据集和标准评估指标。还该领域的主要挑战、发展历史、各类方法的优/劣势、不同类别方法之间的关系、应用以及未来可能的发展方向进行了讨论，以进一步促进该研究领域的发展。
* 微生物检测
  * [A State-of-the-art Survey of Object Detection Techniques in Microorganism Image Analysis: from Traditional Image Processing and Classical Machine Learning to Current Deep Convolutional Neural Networks and Potential Visual Transformers](https://arxiv.org/abs/2105.03148)<br>[2021-05-10]<br>本篇综述总结了从 1985 年至今的 137 篇相关技术论文。按照时间顺序对现有的微生物检测方法，从传统的图像处理和传统的机器学习到深度学习方法进行了分析。并介绍一些潜在的方法，包括 visual transformers。有助于研究人员对微生物检测领域的发展过程、研究现状和未来趋势有更全面的了解，为其他领域的研究人员提供参考。
* 显著目标检测
  * [Salient Objects in Clutter](https://arxiv.org/abs/2105.03053)<br>[2021-05-10]<br>本篇综述涉及 348 个参考文献，201个模型的调研，以及100个基准模型。发现并解决了 SOD 中长期被忽视的数据选择偏差问题。与以前的研究不同，本次目标是在自然环境探索 SOD 任务。

<a name="16"/> 

## 16.Human Action Detection and Recognitionn(人体动作检测与识别)

- [Human Activity Recognition using Wearable Sensors: Review, Challenges, Evaluation Benchmark](https://arxiv.org/abs/2101.01665)<br>[2021-01-05]<br>对近期基于可穿戴传感器的人类活动识别中的优异表现方法进行了广泛回顾



<a name="15"/> 

## 15.Person Re-identification(人员重识别)
- [Deep Learning for Person Re-identification: A Survey and Outlook](https://arxiv.org/abs/2001.04193v2)<br>[[github](github.com/mangye16/ReI)]<br>[2021-01-06]

- [Deep Gait Recognition: A Survey](https://arxiv.org/abs/2102.09546)<br>[2021-02-19]<br>全面调查深度学习在步态识别方面的突破和最新发展，并涵盖了包括数据集、测试协议、最先进的解决方案、挑战和未来研究方向在内的广泛话题。
* Person Search
  * [Person Search Challenges and Solutions: A Survey](https://arxiv.org/abs/2105.01605)<br>[2021-05-05]<br>IJCAI 2021<br>本篇综述从挑战和解决方案的角度对近期关于基于图像和文本的人物搜索工作进行的调研

<a name="14"/> 

## 14.Human Pose Estimation(人体姿态估计)

- [Gesture Recognition in Robotic Surgery: a Review](https://arxiv.org/abs/2102.00027) <br>[2021-02-02]<br>机器人手术中的手势识别：综述

<a name="13"/> 

## 13.Image Classification(图像分类)

- [One-Class Classification: A Survey](https://arxiv.org/abs/2101.03064)<br>[2021-01-11] <br>单分类综述<br>
- [Hyperspectral Image Classification -- Traditional to Deep Models: A Survey for Future Prospects](https://arxiv.org/abs/2101.06116)<br>[2021-01-18] <br>高光谱图像分类综述<br>
- [Deep Learning for Scene Classification: A Survey](https://arxiv.org/abs/2101.10531)<br>[2021-01-27] <br>深度学习在场景分类的应用综述<br>
- [Online Continual Learning in Image Classification: An Empirical Survey](https://arxiv.org/abs/2101.10423)<br>[2021-01-27]<br>图像分类中的在线持续学习综述<br>
* 杂草检测
  * [Deep Learning Techniques for In-Crop Weed Identification: A Review](https://arxiv.org/abs/2103.14872)<br>[2021-03-30]<br>文章是对深度学习技术在基于图像的杂草检测领域最新发展的调查。首先介绍了与杂草检测相关的深度学习基本原理。然后对关于深度杂草检测的进展进行回顾，以及讨论了包括公共杂草数据集在内的研究材料。最后，总结开发可实际部署的杂草检测方法所面临的挑战，以及对未来研究机会的讨论。作者希望这篇综述能对该领域进行及时的调查，并吸引更多的研究者来解决这一跨学科的研究问题。
* 小样本分类
  * [Deep Metric Learning for Few-Shot Image Classification: A Selective Review](https://arxiv.org/abs/2105.08149)<br>[2021-05-19]

<a name="12"/> 

## 12.Image Retrieval(图像检索)

- [Deep Image Retrieval: A Survey](https://arxiv.org/abs/2101.11282)<br>[2021-01-28] <br>图像检索综述
- [Survey of Visual-Semantic Embedding Methods for Zero-Shot Image Retrieval](https://arxiv.org/abs/2105.07391)<br>[2021-05-18]


<a name="11"/> 

## 11.Face(人脸技术)

- [Fast Facial Landmark Detection and Applications: A Survey](https://arxiv.org/abs/2101.10808)<br>[2021-01-27]<br>人脸关键点检测综述<br>
- [Countering Malicious DeepFakes: Survey, Battleground, and Horizon](https://arxiv.org/abs/2103.00218)<br>[[主页](http://www.xujuefei.com/dfsurvey)]<br>[2021-03-02]<br>对抵制恶意的 DeepFakes 综述调查
* 人脸超分辨率
  * [Deep Learning-based Face Super-resolution: A Survey](https://arxiv.org/abs/2101.03749)<br>[2021-01-12]<br>人脸超分辨率也称为【facial hallucination人脸幻构】系统地对人脸超分辨率中的深度学习技术进行了全面的回顾。<br>
* 人脸识别检测
  * [About Face: A Survey of Facial Recognition Evaluation](https://arxiv.org/abs/2102.00813)<br>[2021-02-02]<br>人脸识别综述<br>
  * [Going Deeper Into Face Detection: A Survey](https://arxiv.org/abs/2103.14983)<br>[2021-03-30]<br>本文是对近期基于深度学习的人脸检测方面文献的综述，包括五十多种人脸检测方法。并对这些方法的不同方面进行了全面的评述，包括训练数据、网络结构的选择、损失函数、训练策略以及它们贡献。作者根据对人脸检测的贡献技术将这些方法分为以下几个架构组：1) Cascade-CNN Based Models 2) R-CNN and Faster-RCNN Based Models 3) Single Shot Detector Models 4) Feature Pyramid Network Based Models 5) Other models 。还总结一些流行的人脸检测基准，如 Wider-Face、FDDB 和 PASCAL Face，以及在这些流行基准上的量化性能。最后，对未来几年基于深度学习的人脸检测的一些公开挑战和有前途的方向进行了讨论。
  * [Performance analysis of facial recognition: A critical review through glass factor](https://arxiv.org/abs/2104.01536)<br>[2021-04-06]<>本篇综述针对 glass factor 对人脸识别影响的全面调研。
* 人脸表情识别
  * [Weakly Supervised Learning for Facial Behavior Analysis : A Review](https://arxiv.org/abs/2101.09858)<br>[2021-01-26]<br>无监督学习在人脸表情识别的应用综述<br>
* 面部情感分析FAA
  * [Graph-based Facial Affect Analysis: A Review of Methods, Applications and Challenges](https://arxiv.org/abs/2103.15599)<br>[2021-03-30]<br>本文是对基于 Graph 的面部情感分析的全面调查，包括算法的演变及其应用。首先，介绍情感分析的背景知识，特别是关于 Graph（图）的作用。然后，对文献中广泛用于基于图的情感表示的方法进行讨论，并展示出图构建的趋势。对于基于图的情感分析中的关系推理，作者根据传统方法或深度模型的使用情况对现有研究进行分类，特别强调最新的图神经网络。还总结了标准 FAA 问题上最先进的实验比较。最后，将综述扩展到当前的挑战和潜在的方向。作者称是首次对基于图的 FAA 方法的调查，该研究结果可以作为该领域未来研究的参考点。

<a name="10"/> 

## 10.Image Super-resolution(图像超分辨率)

- [A Comprehensive Review of Deep Learning-based Single Image Super-resolution](https://arxiv.org/abs/2102.09351)<br>[2021-02-19] <br>基于深度学习的单图像超分辨调查
- [Real-World Single Image Super-Resolution: A Brief Review](https://arxiv.org/abs/2103.02368)<br>[2021-03-04]<br>真实单图像超分辨率综述

<a name="9"/> 

## 9.Quantization/Pruning/Knowledge Distillation/Model Compression(量化、剪枝、蒸馏、模型压缩/扩展与优化)

- [Pruning and Quantization for Deep Neural Network Acceleration: A Survey](https://arxiv.org/abs/2101.09671)<br>[2021-01-26]<br>量化剪枝综述
- [Dynamic Neural Networks: A Survey](https://arxiv.org/abs/2102.04906)<br>[2021-02-09]<br>解读：[【深度】清华黄高等人新作：动态神经网络首篇综述](https://mp.weixin.qq.com/s/aEj1JfkpnsXB4ZRxeWfZAQ)

<a name="8"/> 

## 8.Deep Learning(深度学习)

- [Aesthetics, Personalization and Recommendation: A survey on Deep Learning in Fashion](https://arxiv.org/abs/2101.08301)<br>[2021-01-22] <br>基于深度学习、人工智能、机器学习的时尚穿搭技术综述
* 神经网络
  * [A Survey of Quantization Methods for Efficient Neural Network Inference](https://arxiv.org/abs/2103.13630)<br>[2021-03-26]<br>用于高效神经网络推理的量化方法研究
  * [Hyperbolic Deep Neural Networks: A Survey](https://arxiv.org/abs/2101.04562)<br>[2021-01-13]<br>
* 注意力机制
  * [Attention, please! A survey of Neural Attention Models in Deep Learning](https://arxiv.org/abs/2103.16775)<br>[2021-04-01]<br>为了评估注意力在深度神经网络中的应用广度，作者在本次调查中对该领域进行了系统的回顾。包括该领域的数百种架构，确定并讨论一些表现出重大影响的架构。还开发并公开一种自动化的方法，以促进该领域评论的发展。通过对 650 部作品进行批判性分析，描述了注意力在卷积、循环网络和生成模型中的主要用途，并确定共同的用途和应用子群。此外，还描述了注意力在不同应用领域的影响，以及它们对神经网络可解释性的影响。最后，列出可能的趋势和进一步研究的机会，希望这篇综述能对该领域的主要注意力模型进行简洁的概述，并指导研究人员开发未来的方法，以推动进一步的改进。
* 集成学习
  * [Ensemble deep learning: A review](https://arxiv.org/abs/2104.02395)<br>[2021-04-07]<br>本篇综述是对目前最先进的深度集成模型的调研，为研究学者提供一个广泛的总结。集成模型大致可分为  bagging, boosting 和 stacking，基于 negative correlation 的深度集成模型，显式/隐式合集，同质/异质合集，决策融合策略，无监督、半监督、强化学习和基于在线/增量、多标签的深度集成模型。此外，还深度集成模型在不同领域的应用进行了简要讨论。并在本文的最后提出一些未来的建议和研究方向。

<a name="7"/> 

## 7.Aeria/Drones/Satellite/RS Image(航空影像/无人机)

- [A Review on Deep Learning in UAV Remote Sensing](https://arxiv.org/abs/2101.10861)<br>[2021-01-29] <br>深度学习在无人机遥感中的应用综述
* 遥感图像分类
  * [A survey of active learning algorithms for supervised remote sensing image classification](https://arxiv.org/abs/2104.07784)<br>[2021-04-19] <br>主动学习算法在监督式遥感图像分类中的应用研究.本篇综述回顾并测试了主动学习算法的主要系列：committee, large margin 和 posterior probability-based。并对每一种算法，都讨论了遥感界的最新进展，以及详细介绍和测试了一些启发式算法。考虑了几个具有挑战性的遥感场景，包括非常高的空间分辨率和高光谱图像分类。最后，为新用户和/或没有经验的用户提供了选择良好架构的指南。

<a name="6"/> 

## 6.GAN(生成对抗网络)

- [GAN Inversion: A Survey](https://arxiv.org/abs/2101.05278)<br>[2021-01-15] <br>[[awesome gan-inversion papers](https://github.com/weihaox/awesome-image-translation/blob/master/awesome-gan-inversion.md)]<br>[[Papers on generative modeling](https://github.com/zhoubolei/awesome-generative-modeling)]<br>GAN 逆映射综述<br>
- [Adversarial Text-to-Image Synthesis: A Review](https://arxiv.org/abs/2101.09983)<br>[2021-01-26]<br>文本到图像生成综述<br>
- [Generative Adversarial Networks in Computer Vision: A Survey and Taxonomy](https://arxiv.org/abs/1906.01529)<br>[2021-03-29]<br>:star:[code](https://github.com/sheqi/GAN_Review):newspaper:[Publication](https://dl.acm.org/doi/fullHtml/10.1145/3439723)
* [Generative Adversarial Networks (GAN) Powered Fast Magnetic Resonance Imaging -- Mini Review, Comparison and Perspectives](https://arxiv.org/abs/2105.01800)<br>[2021-05-06]<br>本篇综述对基于 GAN 驱动的快速 MRI 方法进行了回顾，并对各种解剖数据集进行了比较研究，以证明这种快速 MRI 的通用性和鲁棒性，同时提供了未来的展望。

<a name="5"/> 

## 5.智能驾驶
- [Vision-based Vehicle Speed Estimation for ITS: A Survey](https://arxiv.org/abs/2101.06159)<br>[2021-01-18]<br>车速估计综述<br>
* 自动驾驶
  * [Explainability of vision-based autonomous driving systems: Review and challenges](https://arxiv.org/abs/2101.05307)<br>[2021-01-15] <br>自动驾驶综述<br>
  * [Deep Learning-Based Autonomous Driving Systems: A Survey of Attacks and Defenses](https://arxiv.org/abs/2104.01789)<br>[2021-04-06]<br>本篇综述对各种针对基于深度学习的 ADS pipeline 的攻击进行了详细的回顾和分析。全面阐明了基于深度学习的 ADS 中最先进的攻击和防御方法。并提出未来应用新攻击的研究方向，以及保障和提高基于深度学习的 ADS 的鲁棒性。
  * [Vision-based Driver Assistance Systems: Survey, Taxonomy and Advances](https://arxiv.org/abs/2104.12583)<br>[2021-04-27]<br>基于视觉的驾驶辅助系统：调查、分类学和进展


<a name="4"/> 

## 4.Video视频相关技术（摘要理解/字幕）

* Video Summarization 视频摘要
  * [Video Summarization Using Deep Neural Networks: A Survey](https://arxiv.org/abs/2101.06072)<br>[2021-01-18]
* 视频字幕
   * [Bridging Vision and Language from the Video-to-Text Perspective: A Comprehensive Review](https://arxiv.org/abs/2103.14785)<br>[2021-03-30]<br>本篇综述作者对 VTT 问题的最重要方法进行了分类和分析。回顾了常用于训练和测试模型的流行基准数据集和最相关的比赛。对优化过程中使用的自动评估指标和损失函数进行了回顾与比较。以及对每一个主要数据集的最先进结果进行了总结和分析。
* 视频检索
  [A Survey on Natural Language Video Localization](https://arxiv.org/abs/2104.00234)<br>[2021-04-02]<br>本篇综述是对 Natural Language Video Localization（NLVL）算法的全面调研，先是提出 NLVL 的 pipeline，并分为有监督和弱监督的方法，接着对每种方法的优缺点进行分析。随后，提出对数据集、评估协议和一般性能分析。最后，通过对现有方法的总结，得到一些可能的观点。
* 视频监控
  * 人员检索
    * [Person Retrieval in Surveillance Using Textual Query: A Review](https://arxiv.org/abs/2105.02414)<br>[2021-05-07]<br>使用文本查询进行监控中的人员检索调研
<a name="3"/> 

## 3.Visual Question Answering(视觉问答)
* 视频问答
    * [Recent Advances in Video Question Answering: A Review of Datasets and Methods](https://arxiv.org/abs/2101.05954)<br>[2021-01-18]
    * [A survey on VQA_Datasets and Approaches](https://arxiv.org/abs/2105.00421)<br>[2021-05-04]<br>本篇综述是对2018年以后的 VQA 数据集、指标和模型，尤其是2018年以后的作品的调研
* 场景解析
  * 场景图
    * [Scene Graphs: A Survey of Generations and Applications](https://arxiv.org/abs/2104.01111)<br>[2021-04-05]<br>本篇综述是对目前的场景图研究进行了全面的调查。具体来说，首先总结了场景图的一般定义，然后对场景图(SGG)的生成方法进行了全面系统的讨论，并借助先验知识对SGG进行了研究。然后，研究了场景图的主要应用，并总结了最常用的数据集。最后，对场景图的未来发展提出了一些见解。并相信这将是未来场景图研究的一个非常有益的基础。

<a name="2"/> 

## 2.Medical Image(医学影像)

- [Diagnostic Captioning: A Survey](https://arxiv.org/abs/2101.07299)<br>[2021-01-20] <br>医学诊断字幕综述
- [Applications of Deep Learning in Fundus Images: A Review](https://arxiv.org/abs/2101.09864)<br>[2021-01-26] <br>[[github](https://github.com/nkicsl/Fundus_Review)]<br>深度学习在眼底图像中应用综述
- [A Survey and Analysis on Automated Glioma Brain Tumor Segmentation and Overall Patient Survival Prediction](https://arxiv.org/abs/2101.10599)<br>[2021-01-27]<br>医学图像分析综述
- [Domain Adaptation for Medical Image Analysis: A Survey](https://arxiv.org/abs/2102.09508)<br>[2021-02-19]<br>旨在调查医学图像分析中域适应方法的最新进展
- [A Comprehensive Review of Computer-aided Whole-slide Image Analysis: from Datasets to Feature Extraction, Segmentation, Classification, and Detection Approaches](https://arxiv.org/abs/2102.10553) <br>[2021-02-23]<br>对基于机器学习的 WSI 分割、分类和检测的综述
- [Deep reinforcement learning in medical imaging: A literature review](https://arxiv.org/abs/2103.05115)<br>[2021-03-10]<br>医学影像中DRL的文献综述
- [Deep Learning for Chest X-ray Analysis: A Survey](https://arxiv.org/abs/2103.08700)<br>[2021-03-17]<br>本篇综述是对所有在胸部 X 光片上使用深度学习研究的全面调查，包含 2015 年至2021 年所发表的 295 篇论文文献，按照任务对作品进行分类：图像级预测（分类和回归）、分割、定位、图像生成和域适应。在调查中发现有 209 篇论文文献在研究中使用了一个或多个公共数据集。因此作者还提供了一个全面的公共数据集列表，包括图像和标签的数量和类型，以及关于这些数据集各个方面的一些讨论和注意事项。并详细介绍了商业化的应用，以及对目前的技术水平和未来的潜在方向进行了全面的讨论。
* [Artificial Intelligence in Tumor Subregion Analysis Based on Medical Imaging: A Review](https://arxiv.org/abs/2103.13588)<br>[2021-03-26]<br>本文对医学影像中基于 AI 的 tumor subregion 分析进行调研。
* 医学图像检测
  * [Applications of Deep Learning Techniques for Automated Multiple Sclerosis Detection Using Magnetic Resonance Imaging: A Review](https://arxiv.org/abs/2105.04881)<br>[2021-05-12]<br>本篇综述讨论了使用 DL 技术和 MRI 神经成像模式进行的 MS 自动诊断方法的完整调研。同时，对每项工作进行了彻底的回顾和讨论。最后，详细介绍了使用 DL 技术结合 MRI 模式进行 MS 自动诊断的最重要的挑战和未来的方向。
* 医学图像分割
  * [A survey on shape-constraint deep learning for medical image segmentation](https://arxiv.org/abs/2101.07721)<br>[2021-01-20]<br>医学图像分割综述
  * [Medical Image Segmentation with Limited Supervision: A Review of Deep Network Models](https://arxiv.org/abs/2103.00429)<br>[2021-03-02]<br>
  * [Automated liver tissues delineation based on machine learning techniques: A survey, current trends and future orientations](https://arxiv.org/abs/2103.06384)<br>[2021-03-12]<br>本篇综述是对2014年至2020年期间所发表的主要研究的调查，包含研究人员用于分割肝脏、肝脏肿瘤和肝脏-血管结构的不同机器学习算法。
* 病理图像（WSI）分析
  * [A State-of-the-art Survey of Artificial Neural Networks for Whole-slide Image Analysis:from Popular Convolutional Neural Networks to Potential Visual Transformers](https://arxiv.org/abs/2104.06243)<br>[2021-04-14]<br>从流行的 CNN 到具有强大潜力的 Transformers，对用于 Whole-slide Image（病理图像） 分析的人工智能神经网络（ANN）调查。
* 牙齿矫正
  * [Convolutional Neural Networks in Orthodontics: a review](https://arxiv.org/abs/2104.08886)<br>[2021-04-20]<br>卷积神经网络在矫正牙齿中应用调研
 
<a name="1"/> 

## 1.Unkown(未分)

- [Urban land-use analysis using proximate sensing imagery: a survey](https://arxiv.org/abs/2101.04827)<br>[2021-01-14] <br>对 proximate sensing 支持土地利用分析的最先进方法和公开的数据集进行了全面回顾。<br>
- [Curriculum Learning: A Survey](https://arxiv.org/abs/2101.10382)<br>[2021-01-27] <br>机器学习综述<br>
- [Investigating Bi-Level Optimization for Learning and Vision from a Unified Perspective: A Survey and Beyond](https://arxiv.org/abs/2101.11517)<br>[2021-01-28] <br>
- [A Survey On Universal Adversarial Attack](https://arxiv.org/abs/2103.01498)<br>[2021-03-03]<br>
- [Material Measurement Units: Foundations Through a Survey](https://arxiv.org/abs/2103.01997)<br>[2021-03-04]<br>本篇综述确定一种新兴的计算机视觉支持的物料监测技术，称为物料测量单元(MMU)；对发展 MMU 的相关工作进行了调查；描述了一个部署多个 MMU的物料库存监测传感器网络。<br>
- [Land Cover Mapping in Limited Labels Scenario: A Survey](https://arxiv.org/abs/2103.02429)<br> [2021-03-04]<br>IJCAI 2021<br>本篇文章是对土地覆盖测绘中的挑战和用于解决这些问题的机器学习方法进行了结构化的全面概述。并对该领域推进研究的差距和机会进行了讨论。<br>
- [Deep Neural Networks for the Assessment of Surgical Skills: A Systematic Review](https://arxiv.org/abs/2103.05113)<br>[2021-03-10]<br>本篇综述是对深度神经网络在手术技能评估中的应用的全面调查，包含530篇论文文献。
- [Deep Learning and Machine Vision for Food Processing: A Survey](https://arxiv.org/abs/2103.16106)<br>[2021-03-31]<br>本文是对传统的机器学习和深度学习方法，以及可应用于食品加工领域的机器视觉技术进行的调查。总结了近五年来该领域所发表的代表性论文。是根据它们所使用的不同功能和方法来组织的，便于追踪机器视觉系统和图像处理在食品加工领域的最先进方法。
- [Application of Computer Vision and Machine Learning for Digitized Herbarium Specimens: A Systematic Literature Review](https://arxiv.org/abs/2104.08732)<br>[2021-04-20]<br>计算机视觉和机器学习在数字化标本馆中的应用综述
- [A Review on Explainability in Multimodal Deep Neural Nets](https://arxiv.org/abs/2105.07878)<br>[2021-05-18]<br>本片综述对多模态深度神经网络的可解释性进行了全面的调查和评论，特别是针对视觉和语言任务。

## 扫码CV君微信（注明：CV）入微信交流群：

![image](https://user-images.githubusercontent.com/62801906/112356924-051e6700-8d0a-11eb-96dd-5c9890832fbf.png)


