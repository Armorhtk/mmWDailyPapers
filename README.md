# mmWave Radar Daily Papers

毫米波雷达相关论文简报归档，人工筛选后整理。

更新频率：每周三、周日。

## 最新一期

[独立页面：2026-04-15 至 2026-04-18](daily/2026-04-15_to_2026-04-18.md)

<details>
<summary>历史归档</summary>

- [2026-04-15 至 2026-04-18](daily/2026-04-15_to_2026-04-18.md)

</details>

## 毫米波雷达论文半周报 2026-04-15 至 2026-04-18

- 日期：2026-04-15 至 2026-04-18
- 论文数：22

### “带我回家，Wi-Fi无人机”：一种基于无人机的荒野搜救无线系统

原英文标题："Take Me Home, Wi-Fi Drone": A Drone-based Wireless System for Wilderness Search and Rescue

作者：Weiying Hou, Luca Jiang-Tao Yu, Chenshu Wu

出版来源：arXiv

出版时间：2026-04-10

原英文摘要：Wilderness Search and Rescue (WiSAR) represents a longstanding and critical societal challenge, demanding innovative and automatic technological solutions. In this paper, we introduce Wi2SAR, a novel autonomous drone-based wireless system for long-range, through-occlusion WiSAR operations, without relying on existing infrastructure. Our basic insight is to leverage the automatic reconnection behavior of modern Wi-Fi devices to known networks. By mimicking these networks via on-drone Wi-Fi, Wi2SAR uniquely facilitates the discovery and localization of victims through their accompanying mobile devices. Translating this simple idea into a practical system poses substantial technical challenges. Wi2SAR overcomes these challenges via three distinct innovations: (1) a rapid and energy-efficient device discovery mechanism to discover and identify the target victim, (2) a novel RSS-only, long-range direction finding approach using a 3D-printed Luneburg Lens, amplifying the directional signal strength differences and significantly extending the operational range, and (3) an adaptive drone navigation scheme that guides the drone toward the target efficiently. We implement an end-to-end prototype and evaluate Wi2SAR across various mobile devices and real-world wilderness scenarios. Experimental results demonstrate Wi2SAR's high performance, efficiency, and practicality, highlighting its potential to advance autonomous WiSAR solutions. Wi2SAR is open-sourced at https://aiot-lab.github.io/Wi2SAR to facilitate further research and real-world deployment.

中文摘要：荒野搜救（WiSAR）是一个长期存在且至关重要的社会挑战，需要创新和自动化的技术解决方案。本文介绍了Wi2SAR，一种新颖的、基于无人机的自主无线系统，用于长距离、穿透遮挡的WiSAR操作，且不依赖现有基础设施。我们的核心思路是利用现代Wi-Fi设备对已知网络的自动重连行为。通过机载Wi-Fi模拟这些网络，Wi2SAR能够独特地通过受害者随身的移动设备来发现并定位他们。将这一简单想法转化为实用系统面临着巨大的技术挑战。Wi2SAR通过三项独特的创新克服了这些挑战：（1）一种快速且节能的设备发现机制，用于发现和识别目标受害者；（2）一种仅使用RSS的新型长距离测向方法，该方法利用3D打印的Luneburg透镜，放大了定向信号强度差异，并显著扩展了操作范围；（3）一种自适应无人机导航方案，能高效引导无人机飞向目标。我们实现了一个端到端的原型系统，并在各种移动设备和真实荒野场景中对Wi2SAR进行了评估。实验结果表明，Wi2SAR具有高性能、高效率和实用性，凸显了其在推进自主WiSAR解决方案方面的潜力。Wi2SAR已在 https://aiot-lab.github.io/Wi2SAR 开源，以促进进一步的研究和实际部署。

原文链接：https://arxiv.org/abs/2604.09115

### 3DRO：使用2D成像雷达和陀螺仪实现激光雷达级SE(3)直接雷达里程计

原英文标题：3DRO: Lidar-level SE(3) Direct Radar Odometry Using a 2D Imaging Radar and a Gyroscope

作者：Cedric Le Gentil, Daniil Lisus, Timothy D. Barfoot

出版来源：arXiv

出版时间：2026-04-13

原英文摘要：Recently, the robotics community has regained interest in radar-based perception and state estimation. A 2D imaging radar provides dense 360deg information about the environment. Despite the radar antenna's cone of emission and reception, the collected data is generally assumed to be limited to the plane orthogonal to the radar's spinning axis. Accordingly, most methods based on 2D imaging radars only perform SE(2) state estimation. This paper presents 3DRO, an extension of the SE(2) Direct Radar Odometry (DRO) framework to perform state estimation in SE(3). While still assuming planarity of the data through DRO's 2D velocity estimates, it integrates 3D gyroscope measurements over SO(3) to estimate SE(3) ego motion. While simple, this approach provides lidar-level odometry accuracy as demonstrated using 643km of data from the Boreas-RT dataset.

中文摘要：最近，机器人学界重新对基于雷达的感知和状态估计产生了兴趣。2D成像雷达提供关于环境的密集360度信息。尽管雷达天线具有发射和接收的锥形波束，但采集的数据通常被假设为限制在垂直于雷达旋转轴的平面上。因此，大多数基于2D成像雷达的方法仅执行SE(2)状态估计。本文提出3DRO，这是SE(2)直接雷达里程计（DRO）框架的扩展，用于执行SE(3)状态估计。虽然仍通过DRO的2D速度估计假设数据的平面性，但它集成了SO(3)上的3D陀螺仪测量来估计SE(3)自运动。尽管简单，但这种方法提供了激光雷达级的里程计精度，如使用Boreas-RT数据集的643公里数据所证明的那样。

原文链接：https://arxiv.org/abs/2604.12027

### 网络数字孪生框架：生成真实数据集

原英文标题：Advancing Network Digital Twin Framework for Generating Realistic Datasets

作者：Oscar Stenhammar, Sundeep Rangan, Gábor Fodor, Carlo Fischione

出版来源：arXiv

出版时间：2026-04-14

原英文摘要：The integration of accurate and reproducible wireless network simulations is a key enabler for research on open, virtualized, and intelligent communication systems. Network Digital Twins (NDTs) provide a scalable alternative to costly and time-consuming measurement campaigns, while enabling controlled experimentation and data generation for data-driven network design. In this paper, we present an open and user-friendly NDT framework that integrates controllable vehicular mobility with the site-specific ray tracer Sionna and the discrete-event ns-3 network simulator, enabling virtualized end-to-end modeling of wireless networks across the radio, network, and application layers. The proposed framework is particularly well-suited for dynamic vehicular networks and urban deployments, supporting realistic mobility, traffic dynamics, and the extraction of cross-layer metrics. To promote open-source initiatives, we release both the NDT implementation and a representative dataset generated from realistic vehicular and urban scenarios. The framework and dataset facilitate reproducible experimentation and benchmarking of machine learning-based quality of service prediction, network optimization, and intelligent network management algorithms, lowering the entry barrier for research on virtual and open wireless network services.

中文摘要：集成准确且可复现的无线网络仿真是研究开放、虚拟化和智能通信系统的关键推动力。网络数字孪生（NDTs）为成本高昂且耗时的测量活动提供了一种可扩展的替代方案，同时支持为数据驱动的网络设计进行受控实验和数据生成。本文提出了一种开放且用户友好的NDT框架，该框架将可控的车辆移动性与特定场景的射线追踪器Sionna以及离散事件网络模拟器ns-3相结合，实现了跨无线、网络和应用层的无线网络端到端虚拟化建模。所提出的框架特别适用于动态车辆网络和城市部署，支持真实的移动性、交通动态以及跨层指标的提取。为促进开源计划，我们同时发布了NDT实现以及一个基于真实车辆和城市场景生成的代表性数据集。该框架和数据集有助于对基于机器学习的服务质量预测、网络优化和智能网络管理算法进行可复现的实验和基准测试，降低了虚拟和开放无线网络服务研究的入门门槛。

原文链接：https://arxiv.org/abs/2604.12888

### 改进的ANC算法：用于FMCW雷达的干扰抑制

原英文标题：An Improved Adaptive Noise Cancellation Algorithm for Interference Suppression in FMCW Radar

作者：Qinmmin Wang, Chuxiang Chen, Yuming Sun, Wanzhong Sun

出版来源：MDPI AG

出版时间：2026-04-13

原英文摘要：This study investigates the vulnerability of target signals to co-channel Linear Frequency Modulation (LFM) interference in automotive Frequency-Modulated Continuous-Wave (FMCW) radar systems. It analyzes the limitations of conventional adaptive noise cancellation (ANC) techniques, particularly slow convergence and performance degradation under intense interference. To address these issues, an improved ANC algorithm is proposed. The method generates reference signals through single-channel self-delay processing and adopts a joint optimization framework for weight adaptation, which integrates normalized variable-step-size Least Mean Squares (LMS) adaptation with a leakage factor. Notably, the algorithm achieves robust performance in high-interference scenarios without requiring additional hardware or complex signal transformations. Simulation results verify that the proposed algorithm significantly improves the signal-to-interference-plus-noise ratio (SINR) preserves signal fidelity, and enhances detection probability under strong LFM interference.

中文摘要：本研究探讨了汽车调频连续波（FMCW）雷达系统中目标信号对同信道线性调频（LFM）干扰的脆弱性。分析了传统自适应噪声消除（ANC）技术的局限性，特别是在强干扰下收敛慢和性能下降的问题。为了解决这些问题，提出了一种改进的ANC算法。该方法通过单通道自延迟处理生成参考信号，并采用一种联合优化框架进行权重自适应，该框架集成了归一化变步长最小均方（LMS）自适应与泄漏因子。值得注意的是，该算法在高干扰场景下实现了鲁棒性能，无需额外硬件或复杂信号变换。仿真结果验证了所提算法显著提高了信号与干扰加噪声比（SINR），保持了信号保真度，并增强了在强LFM干扰下的检测概率。

原文链接：https://www.preprints.org/frontend/manuscript/5af9676540695947337df979d79bb89c/download_pub

### 毫米波FMCW雷达三面角反射器雷达截面积分析

原英文标题：Analysis of Radar Cross Section Using Trihedral Corner Reflector for Millimeter-Wave FMCW Radar

作者：N. A. Yusri, Sevia Mahdaliza Idrus, N. Mohamed, P. N. Ja'afar, S. Ambran, N. Shibagaki, K. Kashima, N. Yonemoto

出版来源：Innovations in Electrical and Mechanical Engineering for a Sustainable Future

出版时间：2026-04-07

原英文摘要：Foreign object debris (FOD) encompasses any foreign materials on an airfield that pose risks to aircraft and airport operations that potentially cause accidents and damage. Detecting various types and sizes of objects on airport pavements is a challenge due to complex backgrounds and weak echoes from distant targets. Instead, using FOD simulators under controlled conditions offers cost-effective, convenient, and flexible testing. This chapter introduces an analysis of millimeter-wave radar detection that interacts with a target simulator on the airport runway while considering the impact of the runway’s surface. This analysis focused on the radar cross section (RCS) characteristics and how they change 38based on various factors such as distances, frequency, angles, and the size of triangular trihedral corner reflector. A comprehensive analysis and method ensures consistency in RCS values across the entire runway area, providing a thorough understanding of the radar system’s performance based on its standard design. The demonstrated results are based on the actual measurement of the KLIA runway and between radar antenna units surveillance radar towers. These findings underscore millimeter-wave radar’s potential as a promising technology for enhancing airport safety by enabling reliable FOD detection.

中文摘要：外来物碎片（FOD）指机场内任何可能对飞机和机场运营构成风险、导致事故和损坏的外来材料。由于复杂的背景和远处目标的微弱回波，检测机场道面上各种类型和尺寸的物体是一项挑战。相反，在受控条件下使用FOD模拟器进行测试，具有成本效益高、方便和灵活的优点。本章介绍了毫米波雷达检测的分析，该分析与机场跑道上的目标模拟器相互作用，同时考虑了道面表面的影响。该分析侧重于雷达截面积（RCS）特性，以及其如何基于距离、频率、角度和三角形三面角反射器尺寸等各种因素而变化。全面的分析和方法确保了整个跑道区域RCS值的一致性，从而基于雷达系统的标准设计提供了对其性能的透彻理解。所展示的结果基于对KLIA跑道以及雷达天线单元之间监视雷达塔的实际测量。这些发现强调了毫米波雷达作为一种有前景技术的潜力，可通过实现可靠的FOD检测来增强机场安全。

原文链接：https://api.taylorfrancis.com/content/chapters/edit/download?identifierName=doi&identifierValue=10.1201/9781779644084-4&type=chapterpdf

### 基于毫米波雷达的生猪呼吸频率检测方法

原英文标题：Detection method of hog respiratory rate based on millimeter-wave radar

作者：JIE Deng-fei, WANG Yang, JIANG Peng-hui, LI Tian-le, HE Jin-cheng

出版来源：Journal of Southern Agriculture

出版时间：2026-04-10

原英文摘要：【Objective】This study aimed to establish a contactless detection method of hog respiratory rate using millimeter-wave radar combined with deep learning， thereby providing an intelligent and precise health monitoring solution for large-scale hog farming， enhancing breeding efficiency， reducing disease risks， and advancing the modernization of management for livestock industry.【Method】Respiratory radar data of hogs were collected using an AWR1843BOOST radar. A dual alignment calibration method （DACM） was developed to achieve phase alignment and unwrapping， specifically aimed at mitigating the effects of multipath interference and noise. Signal denoising and smooth tracking were performed through Kalman filtering. Subsequently， a model was constructed using EfficientNetV1 model as the backbone， integrating convolutional block attention module （CBAM） and dilated convolution （DilatedConv） module， and incorporating a lightweight Transformer module to achieve an efficient fusion of local multi-scale features and global dependencies. Finally， the respiratory rate prediction values were generated through global average pooling and a fully connected layer.【Result】Compared to the MobileNetV3 and ResNet1D models， the EfficientNet-CBAM-Transformer model demonstrated a superior predictive performance； on the validation set， the model achieved a mean absolute error （MAE） of 1.06 bpm， a mean absolute percentage error （MAPE） of 1.33 bpm， a root mean square error （RMSE） of 5.5%， and a coefficient of determination （<i>R</i><sup>2</sup>） of 0.91. Compared with the original EfficientNetV1， the MAE， RMSE， and MAPE were reduced by 31.17%， 28.49%， and 29.49% respectively， while the <i>R</i><sup>2</sup> increased by 7.06%. By utilizing automated searches to uniformly scale network depth， width， and input resolution， the EfficientNet-CBAM-Transformer model attained enhanced feature representation capabilities under the same computational budget， and the prediction results of EfficientNet-CBAM-Transformer were closer to true values， with the <i>R</i><sup>2</sup> of 0.86 in the fitted regression equation. The numbers of sample groups with true or predicted values of MAE greater than 1.00 bpm was reduced to six groups， showing a decrease of 50% compared to the baseline EfficientNetV1 model， thus indicating a better detection accuracy of the improved model.【Conclusion】The EfficientNet-CBAM-Transformer model based on radar echo data provides the best regression prediction， whose detection accuracy meets the requirements for hog respiratory rate detection in actual production， thereby offering an efficient， non-invasive， and intelligent technology for real-time monitoring of hog health and technical support for future development of portable devices and online intelligent detection systems.

中文摘要：【目的】本研究旨在建立一种利用毫米波雷达结合深度学习的生猪呼吸频率非接触式检测方法，从而为大规模生猪养殖提供智能化、精准化的健康监测解决方案，以提高养殖效率、降低疾病风险，并推动畜牧行业管理的现代化。【方法】使用AWR1843BOOST雷达采集生猪的呼吸雷达数据。开发了一种双对齐校准方法（DACM）以实现相位对齐和解缠，专门用于减轻多径干扰和噪声的影响。通过卡尔曼滤波进行信号去噪和平滑跟踪。随后，以EfficientNetV1模型为骨干构建模型，集成了卷积块注意力模块（CBAM）和空洞卷积（DilatedConv）模块，并引入轻量级Transformer模块，以实现局部多尺度特征与全局依赖关系的高效融合。最后，通过全局平均池化和全连接层生成呼吸频率预测值。【结果】与MobileNetV3和ResNet1D模型相比，EfficientNet-CBAM-Transformer模型表现出更优的预测性能；在验证集上，该模型的平均绝对误差（MAE）为1.06 bpm，平均绝对百分比误差（MAPE）为1.33 bpm，均方根误差（RMSE）为5.5%，决定系数（R²）为0.91。与原始EfficientNetV1相比，MAE、RMSE和MAPE分别降低了31.17%、28.49%和29.49%，而R²提高了7.06%。通过利用自动化搜索来统一缩放网络深度、宽度和输入分辨率，EfficientNet-CBAM-Transformer模型在相同计算预算下获得了增强的特征表示能力，其预测结果更接近真实值，拟合回归方程的R²为0.86。MAE大于1.00 bpm的真实值或预测值的样本组数量减少到六组，与基线EfficientNetV1模型相比减少了50%，这表明改进模型具有更好的检测精度。【结论】基于雷达回波数据的EfficientNet-CBAM-Transformer模型提供了最佳的回归预测，其检测精度满足实际生产中生猪呼吸频率检测的要求，从而为生猪健康的实时监测提供了一种高效、非侵入、智能化的技术，并为未来便携式设备和在线智能检测系统的开发提供了技术支持。

原文链接：http://nfnyxb.xml-journal.net/en/article/doi/10.3969/j.issn.2095-1191.2026.02.003

### 物理引导的微多普勒描述符在无人机与鸟类分类中的特征级鲁棒性研究

原英文标题：Feature-Level Robustness of Physics-Guided Micro-Doppler Descriptors for classification of Drones and Birds

作者：Shaiq e Mustafa, Salman Liaquat, Imran Hafeez Abbasi, Azhar Hasan

出版来源：arXiv

出版时间：2026-04-14

原英文摘要：Micro-Doppler signatures are a proven modality for discriminating between drones and birds, but their reliability degrades in low-SNR, data-constrained settings where deep learning models often fail. This paper presents a systematic study of ten statistical and physics-motivated handcrafted features for micro-Doppler classification under controlled signal degradation, using a publicly available 77 GHz FMCW radar dataset. Spectrograms are corrupted with additive white Gaussian noise, phase noise, and their combination across SNRs from -10 dB to 10 dB and phase noise levels from 1 to 10 degrees. Features are evaluated using stratified 5-fold cross-validation with Support Vector Machine and Random Forest classifiers, using fixed hyperparameters across all noise conditions. On clean data, both models achieve mean accuracy of 0.916, with F1 scores of 0.909 (SVM) and 0.892 (Random Forest). Under severe noise, entropy-based and side-lobe features remain robust, yielding F1 scores up to 0.773 and 0.831, respectively. Permutation-based importance analysis shows that some features retain complementary discriminative power even when their individual importance is low. These results highlight the value of principled feature design and provide insight into feature robustness for interpretable radar classification systems.

中文摘要：微多普勒特征已被证明是区分无人机与鸟类的有效模态，但在低信噪比和数据受限的场景下，其可靠性会下降，而深度学习模型在这些场景中往往失效。本文利用公开的77 GHz FMCW雷达数据集，在受控的信号退化条件下，对十种基于统计和物理原理的手工特征进行了系统研究，用于微多普勒分类。时频谱图被加性高斯白噪声、相位噪声及其组合所破坏，信噪比范围从-10 dB到10 dB，相位噪声水平从1度到10度。使用支持向量机和随机森林分类器进行分层5折交叉验证评估特征，所有噪声条件下均采用固定超参数。在干净数据上，两种模型的平均准确率达到0.916，F1分数分别为0.909（SVM）和0.892（随机森林）。在严重噪声下，基于熵的特征和旁瓣特征仍保持鲁棒性，分别获得高达0.773和0.831的F1分数。基于排列的重要性分析表明，即使某些特征的个体重要性较低，它们仍能保持互补的判别能力。这些结果凸显了基于原理的特征设计的价值，并为可解释的雷达分类系统的特征鲁棒性提供了见解。

原文链接：https://arxiv.org/abs/2604.12567

### FeelWave：通过噪声鲁棒的毫米波情感感知实现情感感知语音交互

原英文标题：FeelWave: Enabling Emotion-Aware Voice Interaction through Noise-Robust mmWave Emotion Sensing

作者：Lingyu Wang, You Zuo, Di Wang, Chenming He, Chengzhen Meng, Xinran Zhang, Xiaoran Fan, Yanyong Zhang

出版来源：Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems

出版时间：2026-04-13

原英文摘要：Voice has been a primary interaction mode with LLM-powered assistants. Beyond semantics, voice carries emotional cues with potential to guide empathetic system responses. Yet, robust vocal emotion sensing in noise and its use in optimizing interactions remain underexplored. In response, we present FeelWave, which achieves empathetic voice interaction through noise-robust mmWave emotion sensing and structured LLM prompts. It extracts robust vocal information from mmWave signals, applies audio-to-mmWave transfer learning for efficient emotion recognition, and employs chain-of-thought-based query optimization to enable emotion-adaptive responses. Evaluations show that FeelWave achieves 92.3% emotion recognition accuracy and remains robust in noisy environments, yielding a 62.9 percentage-point gain over audio-based models. In voice interaction studies, 74.3% of users prefer FeelWave, reporting significantly higher satisfaction than a baseline without emotion sensing (4.37 vs. 3.22). A SUS score of 88.3 confirms FeelWave’s high usability in real-world deployment. We hope this work will inspire more empathetic, user-centered AI-driven assistants.

中文摘要：语音已成为与LLM驱动助手的主要交互方式。除了语义外，语音携带情感线索，有潜力引导共情的系统响应。然而，在噪声中鲁棒的声音情感感知及其在优化交互中的应用仍未得到充分探索。为此，我们提出FeelWave，它通过噪声鲁棒的毫米波情感感知和结构化的LLM提示实现共情语音交互。它从毫米波信号中提取鲁棒的声音信息，应用音频到毫米波的迁移学习进行高效情感识别，并采用基于思维链的查询优化以实现情感自适应响应。评估显示，FeelWave达到92.3%的情感识别准确率，并在噪声环境中保持鲁棒，相比基于音频的模型有62.9个百分点的提升。在语音交互研究中，74.3%的用户偏好FeelWave，报告满意度显著高于无情感感知的基线（4.37 vs. 3.22）。SUS得分为88.3，证实了FeelWave在实际部署中的高可用性。我们希望这项工作能激发更多共情的、以用户为中心的AI驱动助手。

原文链接：https://dl.acm.org/doi/full/10.1145/3772318.3790631

### FlowGait：利用毫米波雷达实现跨现实世界协变量的鲁棒长期步态识别

原英文标题：FlowGait: Enabling Robust Long-Term Gait Recognition Across Real-World Covariates with mmWave Radar

作者：Di Wang, Chenming He, Lingyu Wang, Chengzhen Meng, Xiaoran Fan, Yanyong Zhang

出版来源：Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems

出版时间：2026-04-13

原英文摘要：Gait recognition enables proactive and personalized smart home interactions, but its long-term reliability is challenged by the non-static nature of gait. Covariates like carrying items and clothing induce a persistent domain shift that degrades traditional, static models. To solve this, we introduce FlowGait, a mmWave-based framework designed for robust, long-term adaptation. It combines self-training with continual learning, allowing the model to daily align with a user’s evolving gait by learning from readily available unlabeled data. It features a specialized transformer network for radar spectrogram analysis and a novel two-stage labeling algorithm that leverages the gait’s hierarchical nature to assign pseudo-labels to the unlabeled data accurately. Evaluated on three challenging datasets from 47 volunteers (covering 12 gait-covariates, 11 routes, and two weeks), FlowGait achieves high accuracies of 94.8 (cross-covariate), 98.6% (cross-route), and 95.5% (cross-day). Notably, for the long-term dataset, it reduced performance decay from 13.6% to just 1.4%, demonstrating its real-world robustness.

中文摘要：步态识别能够实现主动和个性化的智能家居交互，但其长期可靠性受到步态非静态特性的挑战。携带物品和衣物等协变量会引起持续的域偏移，从而降低传统静态模型的性能。为了解决这个问题，我们引入了FlowGait，这是一个基于毫米波雷达的框架，专为鲁棒的长期适应而设计。它将自训练与持续学习相结合，允许模型通过从现成的未标记数据中学习，每天与用户不断变化的步态保持一致。其特点包括一个用于雷达频谱图分析的专用Transformer网络，以及一种新颖的两阶段标记算法，该算法利用步态的层次结构特性，为未标记数据准确分配伪标签。在来自47名志愿者的三个具有挑战性的数据集（涵盖12种步态协变量、11条路线和两周时间）上进行评估，FlowGait实现了94.8%（跨协变量）、98.6%（跨路线）和95.5%（跨天）的高准确率。值得注意的是，对于长期数据集，它将性能衰减从13.6%降低到仅1.4%，证明了其在现实世界中的鲁棒性。

原文链接：https://dl.acm.org/doi/pdf/10.1145/3772318.3790623

### FMCW雷达动态解调：实现精确振动测量

原英文标题：FMCW radar dynamic demodulation: Enabling accurate vibration measurement

作者：Long Su, Zhibo Yang, Shuming Wu, Yajie Guan, Ye Tian, Baijie Qiao, Xuefeng Chen

出版来源：Mechanical Systems and Signal Processing

出版时间：2026-04-13

原英文摘要：High-accuracy vibration displacement reconstruction and parameter estimation using frequency-modulated continuous-wave (FMCW) radar are essential for non-contact condition monitoring of engineering structures. However, conventional displacement estimation methods (e.g. CZT) suffer from phase jump phenomenon and high computational cost. Moreover, phase-based displacement extraction yields heteroscedastic measurement uncertainty due to additive observation phase noise (AOPN), which reduces the reliability of vibration parameter estimation when using unweighted spectral or least-squares methods. To address these issues, this paper proposes a two-stage framework consisting of a dynamic demodulation algorithm (DDA) and an AOPN-weighted iterative optimization (AWIO) method. The DDA updates the demodulation beat frequency on a sweep-by-sweep basis to suppress phase jump and stabilize slow-time displacement tracking for vibrating targets. The AWIO formulates vibration frequency and amplitude estimation as a weighted optimization problem, where sample-wise weights are derived from the uncertainty induced by observation phase noise, improving robustness to noise and multi-component interference. Simulation and experimental results demonstrate that the proposed methods maintain superior performance under low signal-to-noise ratios and multi-component interference. The displacement estimation error is significantly lower than that of conventional methods, and the amplitude estimation accuracy can reach the micrometer scale. This paper provides a high-accuracy, computationally efficient, and practical non-contact solution for engineering vibration monitoring.

中文摘要：使用调频连续波（FMCW）雷达进行高精度振动位移重构和参数估计对于工程结构的非接触状态监测至关重要。然而，传统的位移估计方法（如CZT）存在相位跳变现象和高计算成本的问题。此外，基于相位的位移提取由于加性观测相位噪声（AOPN）导致异方差测量不确定性，这在使用非加权谱方法或最小二乘法时降低了振动参数估计的可靠性。为了解决这些问题，本文提出了一个两阶段框架，包括动态解调算法（DDA）和AOPN加权迭代优化（AWIO）方法。DDA在逐扫描基础上更新解拍频，以抑制相位跳变并稳定振动目标的慢时间位移跟踪。AWIO将振动频率和振幅估计表述为一个加权优化问题，其中样本级权重源自观测相位噪声引起的不确定性，提高了对噪声和多分量干扰的鲁棒性。仿真和实验结果表明，所提方法在低信噪比和多分量干扰下保持优越性能。位移估计误差显著低于传统方法，振幅估计精度可达微米级。本文为工程振动监测提供了一种高精度、计算高效且实用的非接触解决方案。

原文链接：https://www.sciencedirect.com/science/article/pii/S088832702600381X

### 从原始ADC到3D点云生成：用于人体检测与活动分析的端到端毫米波雷达框架

原英文标题：FROM RAW ADC TO 3D POINT CLOUD GENERATION: AN END-TO-END MMWAVE RADAR FRAMEWORK FOR HUMAN BODY DETECTION AND ACTIVITY ANALYSIS

作者：A Shahin

出版来源：Master's thesis, The University of Akron

出版时间：2026-04-15

原英文摘要：Millimeter-wave (mmWave) radar has emerged as a promising sensing modality for human-centered applications due to its robustness to lighting conditions and its ability to preserve user privacy. Recent studies have demonstrated the effectiveness of mmWave radar-based point clouds for tasks such as human localization, activity recognition, and tracking. However, many existing works rely on vendor-generated point clouds or focus primarily on downstream learning tasks. Consequently, the underlying signal processing stages that produce these 3D representations often remain opaque, limiting reproducibility and control over point-cloud generation. This thesis presents a transparent end-to-end framework for generating 3D human point clouds directly from raw mmWave radar analog-to-digital converter (ADC) data. Starting from raw frequency-modulated continuous-wave (FMCW) radar measurements, the proposed pipeline implements range processing, Doppler estimation, azimuth and elevation angle-of-arrival estimation, and Cartesian coordinate mapping to reconstruct spatial representations of detected targets. By explicitly implementing each stage of the radar signal processing pipeline, the framework provides improved transparency and allows detailed analysis of the generated spatial measurements. iii To improve the quality and stability of the generated point clouds, the framework incorporates practical filtering mechanisms including field-of-view gating, height constraints, ghost-point suppression, and the extraction of per-point attributes such as velocity and reflection intensity. The resulting point clouds provide a sparse yet informative representation of human targets, capturing both spatial structure and motion characteristics. The proposed system is designed to support efficient processing through frame-level parallelization. Experimental results demonstrate that the proposed framework can reliably generate consistent and interpretable 3D human point clouds in indoor environments. The results show that the generated spatial measurements capture meaningful motion characteristics and provide a suitable foundation for downstream tasks such as localization, tracking, and learning-based human activity analysis. iv

中文摘要：毫米波（mmWave）雷达因其对光照条件的鲁棒性和保护用户隐私的能力，已成为以人为中心应用的有前景的传感方式。最近的研究表明，基于毫米波雷达的点云在人体定位、活动识别和跟踪等任务中具有有效性。然而，许多现有工作依赖于供应商生成的点云，或主要关注下游学习任务。因此，产生这些3D表示的底层信号处理阶段往往不透明，限制了点云生成的可重复性和控制。本论文提出了一个透明的端到端框架，直接从原始毫米波雷达模数转换器（ADC）数据生成3D人体点云。从原始调频连续波（FMCW）雷达测量开始，所提出的流程实现了距离处理、多普勒估计、方位角和仰角到达角估计，以及笛卡尔坐标映射，以重建检测目标的空间表示。通过明确实现雷达信号处理流程的每个阶段，该框架提供了更高的透明度，并允许对生成的空间测量进行详细分析。iii 为了提高生成点云的质量和稳定性，该框架结合了实用的滤波机制，包括视场门控、高度约束、鬼点抑制，以及提取每点属性如速度和反射强度。生成的点云提供了人体目标的稀疏但信息丰富的表示，捕捉了空间结构和运动特征。所提出的系统设计支持通过帧级并行化进行高效处理。实验结果表明，所提出的框架能够在室内环境中可靠地生成一致且可解释的3D人体点云。结果表明，生成的空间测量捕捉了有意义的运动特征，并为下游任务如定位、跟踪和基于学习的人体活动分析提供了合适的基础。iv

原文链接：https://etd.ohiolink.edu/acprod/odb_etd/ws/send_file/send?accession=akron1775215337562707&disposition=inline

### 混合物理光学与几何光学方法：用于毫米波FMCW雷达地下成像建模

原英文标题：Hybrid Physical and Geometrical Optics Method for Modeling Subsurface Imaging Using mmWave FMCW Radar

作者：Kaito Ichijo, Hang Song, Xin Du, Bo Wei, Junichi Takada

出版来源：arXiv

出版时间：2026-04-11

原英文摘要：A hybrid physical and geometrical optics method is proposed to model the subsurface imaging using mmWave FMCW radar. Modeling of the wave propagation for subsurface imaging can improve the interpretation of acquired data and imaging results. Full-wave simulation is common in simulating wave propagation. However, when the frequency is high such as mmWave frequency, it is difficult to implement since it costs large computation resource and time. In this paper, the physical and geometrical optics are hybridized to simulate the wave propagation in subsurface imaging scenarios. In the proposed method, physical optics method is utilized to calculate the reflection from the object and geometrical optics method is utilized to calculate the transmission of the wave through object. By combining the results from physical and geometrical optics, the wave propagation in the subsurface imaging scenarios is simulated. The synthetic-aperture radar imaging is applied to the simulated data and the image is successfully reconstructed. Further, the experiment setup is developed and the comparison between simulation and experiment is carried out. The results demonstrated that the proposed simulation method can model the subsurface imaging with mmWave FMCW radar.

中文摘要：本文提出了一种混合物理光学与几何光学方法，用于对毫米波FMCW雷达的地下成像进行建模。对地下成像中的波传播进行建模，可以改进对获取数据和成像结果的解释。全波仿真常用于模拟波传播。然而，当频率较高（例如毫米波频段）时，全波仿真难以实施，因为它需要大量的计算资源和时间。本文中，物理光学和几何光学被混合使用，以模拟地下成像场景中的波传播。在所提出的方法中，物理光学方法用于计算来自目标的反射，而几何光学方法用于计算波穿过目标的透射。通过结合物理光学和几何光学的计算结果，模拟了地下成像场景中的波传播。将合成孔径雷达成像技术应用于模拟数据，并成功重建了图像。此外，还搭建了实验装置，并进行了仿真与实验的对比。结果表明，所提出的仿真方法能够对毫米波FMCW雷达的地下成像进行有效建模。

原文链接：https://arxiv.org/abs/2604.10185

### 异构迁移学习：有限数据下的MIMO穿墙雷达微多普勒特征表示

原英文标题：MIMO Through-the-Wall Radar Micro-Doppler Signature Representation Under Limited Data Using Heterogeneous Transfer Learning

作者：Weicheng Gao, Kun Dong, Jingyi Feng, Yi Xu, Xiaodong Qu, Xiaopeng Yang

出版来源：IEEE Signal Processing Letters

出版时间：2026-01-01

原英文摘要：Identifying indoor individuals using micro-Doppler signature of multiple-input multiple-output (MIMO) through-the-wall radar (TWR), and determining whether they pose a threat holds significant research value in the field of urban security surveillance. However, large-scale TWR human motion data is difficult to collect, which reduces the recognition performance. To address this issue, a MIMO TWR micro-Doppler signature representation method under limited data based on heterogeneous transfer learning is proposed in this letter. The multi-channel TWR human motion Doppler-time maps (DTMs) are first generated, and the trace-ratio group sparse method is then proposed for multi-channel DTM feature augmentation. In addition, a micro-Doppler signature representation method based on optimal transport domain adaptation heterogeneous transfer learning is proposed. By leveraging large-scale millimeter-wave radar human gait data, the proposed method guides the micro-Doppler signature representation to maximize inter-class separation on the TWR DTM set. The effectiveness of the proposed method is validated through a few-shot measured dataset collected for TWR human threat identification.

中文摘要：利用多输入多输出（MIMO）穿墙雷达（TWR）的微多普勒特征识别室内人员并判断其是否构成威胁，在城市安防监控领域具有重要研究价值。然而，大规模TWR人体运动数据难以采集，这降低了识别性能。为解决此问题，本文提出一种基于异构迁移学习的有限数据下MIMO TWR微多普勒特征表示方法。首先生成多通道TWR人体运动多普勒-时间图（DTM），随后提出迹比组稀疏方法用于多通道DTM特征增强。此外，提出一种基于最优传输域自适应的异构迁移学习微多普勒特征表示方法。通过利用大规模毫米波雷达人体步态数据，该方法引导微多普勒特征表示在TWR DTM数据集上实现类间分离最大化。通过为TWR人体威胁识别采集的小样本实测数据集验证了所提方法的有效性。

原文链接：https://pure.bit.edu.cn/en/publications/mimo-through-the-wall-radar-micro-doppler-signature-representatio/

### 海上监视中的多传感器数据融合：方法与应用综述

原英文标题：Multi-sensor data fusion in maritime surveillance: a review on methods and applications

作者：Berrin Bal Şahin, Çağatay Berke Erdaş, Emre Sümer

出版来源：PeerJ Computer Science

出版时间：2026-04-14

原英文摘要：The aim of maritime surveillance is to support maritime security by protecting national and international rights and interests through reliable monitoring systems, thereby increasing situational awareness. As threats continue to grow, ranging from piracy and illegal fishing to environmental hazards like oil spills the critical importance of surveillance to ensure security and support sustainable use of the ocean becomes increasingly evident. However, relying solely on single-sensor data for detection and identification purposes is often inadequate. To increase the likelihood of successful detection and identification of vessels, it is critical that heterogeneous ( i.e ., varying types of) data from several different sensors ( i.e ., radar, optical systems, Automatic Identification System (AIS), and Synthetic Aperture Radar (SAR)) be integrated to eliminate the limitations of individual sensors and create a more comprehensive view of the maritime domain. The focus of this review is to provide a systematic overview of various approaches to multi-sensor fusion with emphasis on artificial intelligence (AI)-based methodologies. The article provides a structured literature review of literature related to the ship detection, recognition, tracking, and anomaly detection using fusion processes and presents and discusses most recent and successful practices, some of the technical challenges that exist today, and potential areas of future research. The evaluation includes both traditional and contemporary AI-based techniques ( i.e ., machine learning and deep learning) as well as the complexities that exist when attempting to handle large volumes of data, process data in real-time, and account for variability in the environment and potential cyber threats. In summary, the ultimate goal of this study is to provide an informative reference, for the purpose of enhancing maritime situational awareness.

中文摘要：海上监视的目标是通过可靠的监控系统保护国家和国际权益，从而支持海上安全，提高态势感知能力。随着威胁不断增长，从海盗和非法捕鱼到漏油等环境危害，监视对于确保安全和支持海洋可持续利用的关键重要性日益明显。然而，仅依赖单传感器数据进行检测和识别往往不足。为了提高成功检测和识别船舶的可能性，关键是将来自多种不同传感器（即雷达、光学系统、自动识别系统（AIS）和合成孔径雷达（SAR））的异构（即不同类型）数据集成起来，以消除单个传感器的局限性，并创建更全面的海上领域视图。本综述的重点是系统概述多传感器融合的各种方法，特别强调基于人工智能（AI）的方法论。本文对使用融合过程的船舶检测、识别、跟踪和异常检测相关文献进行了结构化文献综述，并介绍和讨论了最新和最成功的实践、当前存在的一些技术挑战以及未来研究的潜在领域。评估包括传统和当代基于AI的技术（即机器学习和深度学习），以及处理大量数据、实时处理数据、考虑环境变异性和潜在网络威胁时存在的复杂性。总之，本研究的最终目标是提供一个信息丰富的参考，以增强海上态势感知。

原文链接：https://peerj.com/articles/cs-3765/

### 多模态传感器融合用于实时目标检测

原英文标题：Multimodal Sensor Fusion for Real-Time Object Detection

作者：Nethra K, Kavya Nayak, Sinchana, Nithish N, Raghavendra M Shet

出版来源：E3S Web of Conferences

出版时间：2026-04-15

原英文摘要：This paper describes a multimodal sensor fusion developed on the Raspberry Pi platform for real-time object detection and distance estimation. This architecture has a camera and a 24 GHz mmWave radar sensor for achieving the vision and a range sensing. A pretrained YOLO model is used for identifying classes such as persons from live video frames to carry out real-time object detection. The radar provides the distance measurement for which a 1-D linear Kalman filter is applied to get a smooth and accurate estimate, and then fused with the camera data. The result of this experiment showed that the fused system offers significantly higher stability in object detection and distance estimation as compared to single sensor readings. A final configuration where radar measurement is activated only when the detected object is at the centre of the frame, which achieved near-accurate results with less noise. The proposed system is lightweight and also cost-effective for real-time perception for low-cost embedded applications in autonomous vehicles and intelligent surveillance.

中文摘要：本文描述了一种在Raspberry Pi平台上开发的多模态传感器融合系统，用于实时目标检测和距离估计。该架构包括一个摄像头和一个24 GHz mmWave雷达传感器，用于实现视觉和距离感知。使用预训练的YOLO模型从实时视频帧中识别类别，如人物，以执行实时目标检测。雷达提供距离测量，应用一维线性卡尔曼滤波器以获得平滑且准确的估计，然后与摄像头数据融合。实验结果表明，与单一传感器读数相比，融合系统在目标检测和距离估计方面提供了显著更高的稳定性。最终配置中，雷达测量仅在检测到的物体位于帧中心时激活，这实现了近乎准确的结果且噪声较少。所提出的系统轻量级且成本效益高，适用于自动驾驶车辆和智能监控中的低成本嵌入式应用的实时感知。

原文链接：https://www.e3s-conferences.org/articles/e3sconf/pdf/2026/23/e3sconf_areev2026_02005.pdf

### 多站点FMCW SISO雷达系统实现多人呼吸监测

原英文标题：Respiration Monitoring of Multiple People using Multi-site FMCW SISO Radar Systems

作者：Lang Qin, Mandong Zhang, Wenting Song, Zhiqiang Huang, Xiaoguang Liu

出版来源：arXiv

出版时间：2026-04-14

原英文摘要：Continuous contactless respiration monitoring of co-sleeping subjects faces a dilemma: conventional single-site multiple-input multiple-output (MIMO) radars struggle with limited angular resolution for closely spaced individuals, while distributed radar networks typically require complex hardware synchronization. To address these limitations, this paper proposes non-coherent multi-site single-input-single-output (SISO) radar systems that completely eliminate the need for physical synchronization cables or common reference clocks. The fundamental challenge of ghost target ambiguity in such non-coherent multilateration is resolved through a novel physiological-feature-assisted suppression technique. By exploiting the inherent statistical independence of individual respiratory rhythms, true target locations are robustly distinguished from ghosts via cross-correlation analysis. Experimental validation demonstrates that the proposed system can accurately resolve two subjects spaced less than 20 cm apart, surpassing the resolution limits of traditional compact MIMO arrays, while achieving a respiration rate estimation accuracy of 0.7 bpm root mean square error (RMSE) compared to contact-based ground truth.

中文摘要：对共眠对象进行连续非接触式呼吸监测面临一个困境：传统的单站点多输入多输出（MIMO）雷达难以分辨间距很近的个体，因其角分辨率有限；而分布式雷达网络通常需要复杂的硬件同步。为解决这些限制，本文提出了非相干多站点单输入单输出（SISO）雷达系统，完全无需物理同步电缆或公共参考时钟。针对此类非相干多边定位中固有的虚假目标模糊性这一根本挑战，我们通过一种新颖的生理特征辅助抑制技术予以解决。该方法利用个体呼吸节律固有的统计独立性，通过互相关分析，能够鲁棒地区分出真实目标位置与虚假目标。实验验证表明，所提出的系统能够准确分辨间距小于20厘米的两个目标，超越了传统紧凑型MIMO阵列的分辨率极限，同时与基于接触式测量的真值相比，其呼吸频率估计精度达到了0.7 bpm的均方根误差（RMSE）。

原文链接：https://arxiv.org/abs/2604.12556

### RF-LEGO：通过深度展开实现射频感知的信号处理-深度学习模块化协同设计

原英文标题：RF-LEGO: Modularized Signal Processing-Deep Learning Co-Design for RF Sensing via Deep Unrolling

作者：Luca Jiang-Tao Yu, Chenshu Wu

出版来源：arXiv

出版时间：2026-04-11

原英文摘要：Wireless sensing, traditionally relying on signal processing (SP) techniques, has recently shifted toward data-driven deep learning (DL) to achieve performance breakthroughs. However, existing deep wireless sensing models are typically end-to-end and task-specific, lacking reusability and interpretability. We propose RF-LEGO, a modular co-design framework that transforms interpretable SP algorithms into trainable, physics-grounded DL modules through deep unrolling. By replacing hand-tuned parameters with learnable ones while preserving core processing structures and mathematical operators, RF-LEGO ensures modularity, cascadability, and structure-aligned interpretability. Specifically, we introduce three deep-unrolled modules for critical RF sensing tasks: frequency transform, spatial angle estimation, and signal detection. Extensive experiments using real-world data for Wi-Fi, millimeter-wave, UWB, and 6G sensing demonstrate that RF-LEGO significantly outperforms existing SP and DL baselines, both standalone and when integrated into multiple downstream tasks. RF-LEGO pioneers a novel SP-DL co-design paradigm for wireless sensing via deep unrolling, shedding light on efficient and interpretable deep wireless sensing solutions. Our code is available at https://github.com/aiot-lab/RF-LEGO.

中文摘要：传统上依赖信号处理（SP）技术的无线感知，近年来已转向数据驱动的深度学习（DL），以期实现性能突破。然而，现有的深度无线感知模型通常是端到端且任务特定的，缺乏可重用性和可解释性。我们提出了RF-LEGO，一个模块化的协同设计框架，它通过深度展开将可解释的SP算法转化为可训练的、基于物理的DL模块。通过用可学习参数替换手动调优的参数，同时保留核心处理结构和数学算子，RF-LEGO确保了模块化、可级联性和结构对齐的可解释性。具体而言，我们为关键的射频感知任务引入了三个深度展开模块：频率变换、空间角度估计和信号检测。使用Wi-Fi、毫米波、UWB和6G感知的真实世界数据进行的大量实验表明，RF-LEGO无论是独立运行还是集成到多个下游任务中，都显著优于现有的SP和DL基线方法。RF-LEGO通过深度展开，开创了一种新颖的无线感知SP-DL协同设计范式，为高效且可解释的深度无线感知解决方案提供了启示。我们的代码可在 https://github.com/aiot-lab/RF-LEGO 获取。

原文链接：https://arxiv.org/abs/2604.10183

### RIS辅助感知：毫米波波段雷达三维成像的实验验证

原英文标题：RIS-Aided Sensing: Experimental Validation of Radar 3D Imaging in the mmWave Band

作者：Sergio Micó-Rosa, Alvaro Villaescusa-Tebar, Saúl Fenollosa, Carlos Villena-Jiménez, Monika Drozdowska, Narcis Cardona

出版来源：arXiv

出版时间：2026-04-14

原英文摘要：The transition toward 6G networks demands energy-efficient hardware capable of active interaction with the environment. Reconfigurable Intelligent Surfaces (RIS) have emerged as a key technology for Integrated Sensing and Communications (ISAC), enabling geometric environment recognition with minimal power consumption. However, achieving targeted 3D spatial mapping in a fully autonomous, closed-loop system remains a significant challenge. In this work, we validate experimentally an autonomous mmWave 3D imaging framework that integrates an Frequency-Modulated Continuous Wave (FMCW) radar with a 1-bit RIS and a Vector Network Analyzer (VNA) to perform targeted 3D reconstruction. The FMCW radar acts as a coarse localizer, providing real-time spatial priors to define dynamic Regions of Interest (ROI). These coordinates are translated into optimized RIS phase profiles to perform Stepped-Frequency Continuous-Wave (SFCW) measurements. We experimentally validate the system through three diverse scenarios, including metallic mannequins, calibration spheres, and a complex multi-target environment containing human subjects and an Automated Guided Vehicle (AGV). The results demonstrate accurate 3D voxel-based reconstruction of targets even at reduced angular resolutions, advancing the feasibility of RIS-based sensing for industrial and security applications.

中文摘要：向6G网络的演进需要能够主动与环境交互的节能硬件。可重构智能表面已成为集成感知与通信的关键技术，能够以极低的功耗实现几何环境识别。然而，在完全自主的闭环系统中实现目标三维空间映射仍然是一个重大挑战。在本工作中，我们通过实验验证了一个自主毫米波三维成像框架，该框架将调频连续波雷达、1比特RIS和矢量网络分析仪集成在一起，以执行目标三维重建。FMCW雷达充当粗略定位器，提供实时空间先验信息以定义动态感兴趣区域。这些坐标被转换为优化的RIS相位剖面，以执行步进频率连续波测量。我们通过三种不同的场景对系统进行了实验验证，包括金属人体模型、校准球体以及包含人体和自动导引车的复杂多目标环境。结果表明，即使在降低的角分辨率下，也能实现基于三维体素的目标精确重建，这推进了基于RIS的感知在工业和安防应用中的可行性。

原文链接：https://arxiv.org/abs/2604.12466

### SynFlow：利用合成数据扩展激光雷达场景流估计

原英文标题：SynFlow: Scaling Up LiDAR Scene Flow Estimation with Synthetic Data

作者：Qingwen Zhang, Xiaomeng Zhu, Chenhan Jiang, Patric Jensfelt

出版来源：arXiv

出版时间：2026-04-10

原英文摘要：Reliable 3D dynamic perception requires models that can anticipate motion beyond predefined categories, yet progress is hindered by the scarcity of dense, high-quality motion annotations. While self-supervision on unlabeled real data offers a path forward, empirical evidence suggests that scaling unlabeled data fails to close the performance gap due to noisy proxy signals. In this paper, we propose a shift in paradigm: learning robust real-world motion priors entirely from scalable simulation. We introduce SynFlow, a data generation pipeline that generates large-scale synthetic dataset specifically designed for LiDAR scene flow. Unlike prior works that prioritize sensor-specific realism, SynFlow employs a motion-oriented strategy to synthesize diverse kinematic patterns across 4,000 sequences ($\sim$940k frames), termed SynFlow-4k. This represents a 34x scale-up in annotated volume over existing real-world benchmarks. Our experiments demonstrate that SynFlow-4k provides a highly domain-invariant motion prior. In a zero-shot regime, models trained exclusively on our synthetic data generalize across multiple real-world benchmarks, rivaling in-domain supervised baselines on nuScenes and outperforming state-of-the-art methods on TruckScenes by 31.8%. Furthermore, SynFlow-4k serves as a label-efficient foundation: fine-tuning with only 5% of real-world labels surpasses models trained from scratch on the full available budget. We open-source the pipeline and dataset to facilitate research in generalizable 3D motion estimation. More detail can be found at https://kin-zhang.github.io/SynFlow.

中文摘要：可靠的3D动态感知需要能够预测超出预定义类别运动的模型，但密集、高质量运动标注的稀缺性阻碍了进展。虽然在未标注的真实数据上进行自监督提供了一条前进路径，但经验证据表明，由于噪声代理信号的存在，扩展未标注数据并不能弥合性能差距。本文提出一种范式转变：完全从可扩展的仿真中学习鲁棒的真实世界运动先验。我们提出了SynFlow，一个专门为激光雷达场景流生成大规模合成数据集的数据生成流程。与先前优先考虑传感器特定真实感的工作不同，SynFlow采用面向运动的策略，在4000个序列（约94万帧）上合成了多样化的运动学模式，称为SynFlow-4k。这比现有的真实世界基准数据集在标注量上实现了34倍的扩展。我们的实验表明，SynFlow-4k提供了高度领域不变的运动先验。在零样本场景下，仅在我们合成数据上训练的模型能够泛化到多个真实世界基准，在nuScenes上与领域内监督基线相当，并在TruckScenes上以31.8%的优势超越了最先进的方法。此外，SynFlow-4k可作为标签高效的基础：仅使用5%的真实世界标签进行微调，其性能就超过了在全部可用标注上从头训练的模型。我们开源了该流程和数据集，以促进可泛化3D运动估计的研究。更多细节请访问 https://kin-zhang.github.io/SynFlow。

原文链接：https://arxiv.org/abs/2604.09411

### 面向环境感知的低空经济：合成孔径雷达作为共享感知基础设施

原英文标题：Toward Environment-Aware LAE: SAR as a Shared Sensing Infrastructure

作者：Xue Zhang, Bang Huang, Mohamed-Slim Alouini

出版来源：arXiv

出版时间：2026-04-13

原英文摘要：The rapid growth of the low-altitude economy (LAE) is making aerial systems an important part of future digital infrastructure. Although major advances have been achieved in unmanned aerial vehicle (UAV) platforms, communications, and autonomous control, environmental perception remains a key bottleneck to reliable and scalable LAE operations. Existing sensing modalities, such as optical, LiDAR, and millimeter-wave radar, are limited by visibility, sensing range, and environmental conditions, resulting in fragmented situational awareness. This article argues that addressing these limitations requires a shift from platform-centric sensing to a shared, environment-aware sensing infrastructure. In this context, synthetic aperture radar (SAR) offers a distinct advantage by enabling all-weather, wide-area perception. We show that SAR can support UAV operations through global environmental awareness, enhance task-level sensing, and enable cooperative sensing across satellites, high-altitude platforms, UAVs, and ground systems. Building on this perspective, we present a system-level view of SAR-enabled LAE, highlighting key transformations from fragmented to infrastructure-centric sensing, from reactive to predictive operation, and from device-centric to environment-aware networking. We further discuss enabling architectures, including multi-platform sensing hierarchies, integration with integrated sensing and communication (ISAC), and the role of artificial intelligence and digital twins, along with the key challenges toward real-world deployment. By positioning SAR as a shared sensing foundation rather than a standalone modality, this article provides new insights into the design of scalable, reliable, and intelligent LAE systems.

中文摘要：低空经济的快速发展正使空中系统成为未来数字基础设施的重要组成部分。尽管无人机平台、通信和自主控制已取得重大进展，但环境感知仍是实现可靠、可扩展低空经济运营的关键瓶颈。现有的光学、激光雷达和毫米波雷达等感知模态受限于能见度、感知范围和环境条件，导致态势感知碎片化。本文认为，解决这些局限需要从以平台为中心的感知转向共享的、环境感知的感知基础设施。在此背景下，合成孔径雷达凭借其全天候、广域感知能力提供了独特优势。我们展示了SAR如何通过提供全球环境感知来支持无人机运营，增强任务级感知，并实现跨卫星、高空平台、无人机和地面系统的协同感知。基于此视角，我们提出了SAR赋能低空经济的系统级视图，强调了从碎片化到以基础设施为中心的感知、从被动响应到预测性运营、以及从以设备为中心到环境感知网络的关键转变。我们进一步讨论了使能架构，包括多平台感知层级、与通感一体化（ISAC）的融合、以及人工智能和数字孪生的作用，同时指出了实际部署面临的关键挑战。通过将SAR定位为共享的感知基础而非独立模态，本文为设计可扩展、可靠和智能的低空经济系统提供了新的见解。

原文链接：https://arxiv.org/abs/2604.11298

### VLMaterial：基于视觉语言模型的相机-雷达融合用于物理基础材料识别

原英文标题：VLMaterial: Vision-Language Model-Based Camera-Radar Fusion for Physics-Grounded Material Identification

作者：Jiangyou Zhu, He Chen

出版来源：arXiv

出版时间：2026-04-13

原英文摘要：Accurate material recognition is a fundamental capability for intelligent perception systems to interact safely and effectively with the physical world. For instance, distinguishing visually similar objects like glass and plastic cups is critical for safety but challenging for vision-based methods due to specular reflections, transparency, and visual deception. While millimeter-wave (mmWave) radar offers robust material sensing regardless of lighting, existing camera-radar fusion methods are limited to closed-set categories and lack semantic interpretability. In this paper, we introduce VLMaterial, a training-free framework that fuses vision-language models (VLMs) with domain-specific radar knowledge for physics-grounded material identification. First, we propose a dual-pipeline architecture: an optical pipeline uses the segment anything model and VLM for material candidate proposals, while an electromagnetic characterization pipeline extracts the intrinsic dielectric constant from radar signals via an effective peak reflection cell area (PRCA) method and weighted vector synthesis. Second, we employ a context-augmented generation (CAG) strategy to equip the VLM with radar-specific physical knowledge, enabling it to interpret electromagnetic parameters as stable references. Third, an adaptive fusion mechanism is introduced to intelligently integrate outputs from both sensors by resolving cross-modal conflicts based on uncertainty estimation. We evaluated VLMaterial in over 120 real-world experiments involving 41 diverse everyday objects and 4 typical visually deceptive counterfeits across varying environments. Experimental results demonstrate that VLMaterial achieves a recognition accuracy of 96.08%, delivering performance on par with state-of-the-art closed-set benchmarks while eliminating the need for extensive task-specific data collection and training.

中文摘要：准确的材料识别是智能感知系统与物理世界安全有效交互的基本能力。例如，区分玻璃杯和塑料杯等视觉上相似的物体对于安全至关重要，但由于镜面反射、透明性和视觉欺骗，这对基于视觉的方法具有挑战性。虽然毫米波雷达无论光照条件如何都能提供鲁棒的材料感知，但现有的相机-雷达融合方法仅限于闭集类别且缺乏语义可解释性。本文介绍了VLMaterial，一个免训练框架，它将视觉语言模型与特定领域的雷达知识相融合，用于物理基础材料识别。首先，我们提出了一种双流水线架构：光学流水线使用分割一切模型和VLM生成材料候选建议，而电磁表征流水线通过有效的峰值反射单元面积方法和加权矢量合成从雷达信号中提取固有介电常数。其次，我们采用上下文增强生成策略，为VLM配备雷达特定的物理知识，使其能够将电磁参数解释为稳定参考。第三，引入了一种自适应融合机制，通过基于不确定性估计解决跨模态冲突，智能地整合来自两个传感器的输出。我们在超过120个真实世界实验中评估了VLMaterial，涉及41种不同的日常物体和4种典型的视觉欺骗性仿制品，覆盖不同环境。实验结果表明，VLMaterial实现了96.08%的识别准确率，其性能与最先进的闭集基准相当，同时无需进行大量特定任务的数据收集和训练。

原文链接：https://arxiv.org/abs/2604.11671

### VULCAN：基于视觉语言模型增强的多智能体协同导航系统，用于室内火灾响应

原英文标题：VULCAN: Vision-Language-Model Enhanced Multi-Agent Cooperative Navigation for Indoor Fire-Disaster Response

作者：Shengding Liu, Qiben Yan

出版来源：arXiv

出版时间：2026-04-14

原英文摘要：Indoor fire disasters pose severe challenges to autonomous search and rescue due to dense smoke, high temperatures, and dynamically evolving indoor environments. In such time-critical scenarios, multi-agent cooperative navigation is particularly useful, as it enables faster and broader exploration than single-agent approaches. However, existing multi-agent navigation systems are primarily vision-based and designed for benign indoor settings, leading to significant performance degradation under fire-driven dynamic conditions. In this paper, we present VULCAN, a multi-agent cooperative navigation framework based on multi-modal perception and vision-language models (VLMs), tailored for indoor fire disaster response. We extend the Habitat-Matterport3D benchmark by simulating physically realistic fire scenarios, including smoke diffusion, thermal hazards, and sensor degradation. We evaluate representative multi-agent cooperative navigation baselines under both normal and fire-driven environments. Our results reveal critical failure modes of existing methods in fire scenarios and underscore the necessity of robust perception and hazard-aware planning for reliable multi-agent search and rescue.

中文摘要：室内火灾因浓烟、高温和动态演变的室内环境，对自主搜救构成了严峻挑战。在此类时间紧迫的场景中，多智能体协同导航尤为有用，因为它比单智能体方法能实现更快、更广的探索。然而，现有的多智能体导航系统主要基于视觉感知，且为良性室内环境设计，导致其在火灾驱动的动态条件下性能显著下降。本文提出了VULCAN，一个基于多模态感知和视觉语言模型的多智能体协同导航框架，专为室内火灾响应而设计。我们通过模拟物理上真实的火灾场景（包括烟雾扩散、热危害和传感器性能退化）扩展了Habitat-Matterport3D基准测试。我们在正常和火灾驱动的环境下评估了代表性的多智能体协同导航基线方法。我们的结果揭示了现有方法在火灾场景中的关键失效模式，并强调了鲁棒的感知和危害感知规划对于可靠的多智能体搜救的必要性。

原文链接：https://arxiv.org/abs/2604.12831
