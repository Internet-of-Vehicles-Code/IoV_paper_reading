# Paper-Reading
Paper reading list in Cooperative perception. This repository will keep updating ... 🤗

- [Cooperative perception](cooperative_perception)


## Cooperative perception
* R. Xu, H. Xiang, X. Xia, X. Han, J. Li and J. Ma, "OPV2V: An Open Benchmark Dataset and Fusion Pipeline for Perception with Vehicle-to-Vehicle Communication," 2022 International Conference on Robotics and Automation (ICRA), Philadelphia, PA, USA, 2022, pp. 2583-2589, doi: 10.1109/ICRA46639.2022.9812038. [[paper]](https://ieeexplore.ieee.org/document/9812038);[[code]](https://github.com/DerrickXuNu/OpenCOOD)
  * OpenCOOD支持三种协同感知的融合方式，可添加协同感知GPS位置误差和通信延迟。目前已经安装成功，看配置文档初步先跑通一个demo。
* Y. Lu et al., "Robust Collaborative 3D Object Detection in Presence of Pose Errors," 2023 IEEE International Conference on Robotics and Automation (ICRA), London, United Kingdom, 2023, pp. 4812-4818, doi: 10.1109/ICRA48891.2023.10160546.[[paper]](https://ieeexplore.ieee.org/document/10160546) ;[[code]](https://github.com/yifanlu0227/CoAlign)
  * 基于OpenCOOD,利用SLAM位姿图优化理论保持协作感知位姿一致性及鲁棒性。
* T. Hardes, I. Turcanu and C. Sommer, "Poster: A Case for Heterogenous Co-Simulation of Cooperative and Autonomous Driving," 2023 IEEE Vehicular Networking Conference (VNC), Istanbul, Turkiye, 2023, pp. 151-152, doi: 10.1109/VNC57357.2023.10136319. [[paper]](https://ieeexplore.ieee.org/document/10136319),[[code]](https://github.com/veins/veins_carla)
  - 作者修复了bug，已经安装成功！需要研究源码！研究与carla的同步。


## Vehicular edge computing
* Y. Ju et al., "Joint Secure Offloading and Resource Allocation for Vehicular Edge Computing Network: A Multi-Agent Deep Reinforcement Learning Approach," in IEEE Transactions on Intelligent Transportation Systems, vol. 24, no. 5, pp. 5555-5569, May 2023, doi: 10.1109/TITS.2023.3242997. [[paper]](https://ieeexplore.ieee.org/abstract/document/10041957)
* Rodolfo Meneguette, Robson De Grande, Jo Ueyama, Geraldo P. Rocha Filho, and Edmundo Madeira. 2021. Vehicular Edge Computing: Architecture, Resource Management, Security, and Challenges. ACM Comput. Surv. 55, 1, Article 4 (January 2023), 46 pages. https://doi.org/10.1145/3485129 [[paper]](https://dl.acm.org/doi/full/10.1145/3485129)

## Security in V2X networks
* Ansari, M. R., Petit, J., Monteuuis, J. P., & Chen, C. VASP: V2X Application Spoofing Platform. [[paper]](https://www.ndss-symposium.org/wp-content/uploads/2023/02/vehiclesec2023-23071-paper.pdf),[[code]](https://github.com/quic/vasp),[[Qualcomm Innovation Center]](https://quic.github.io/)
  * VASP攻击仿真平台，比较了VeReMi和F2MD，是F2MD的paper二作，能仿真更多攻击和自定义攻击。
* A. Willecke, B. Kulke and L. C. Wolf, "A4MD: Artery for Misbehavior Detection, Reporting, and Reaction in the ETSI C-ITS," 2023 IEEE Vehicular Networking Conference (VNC), Istanbul, Turkiye, 2023, pp. 33-40, doi: 10.1109/VNC57357.2023.10136315. [[paper]](https://ieeexplore.ieee.org/abstract/document/10136315),[[code]](https://github.com/ibr-cm/a4md)
  * A4MD平台 
- R. Sedar, C. Kalalas, F. Vázquez-Gallego, L. Alonso and J. Alonso-Zarate, "A Comprehensive Survey of V2X Cybersecurity Mechanisms and Future Research Paths," in IEEE Open Journal of the Communications Society, vol. 4, pp. 325-391, 2023, doi: 10.1109/OJCOMS.2023.3239115. [[paper]](https://ieeexplore.ieee.org/abstract/document/10026338):star::star::star::star::star:
  - 有监督的机器学习方法在实时 V2X 场景中可能不切实际，因为当攻击动态变化时，标记数据的训练和检测效果不佳。在这种情况下，强化学习和模仿学习方法可以在主动和上下文感知的 V2X 安全中得到进一步利用，例如，用于增强威胁检测性能[331]、[342]。检测机制可以随着经验的积累而动态改进，并在快速变化的环境中学习新的V2X威胁和攻击。在[343]中，作者声称大多数现有的异常检测算法在存在高维数据时变得不太有效。原则上，V2X 移动数据表现出高维性，具有多个特征，例如速度、位置和航向角，这些特征在时间和空间上共同演化。基于强化学习的检测机制被认为在处理此类不断变化的数据方面非常有效，即使标记的异常数据样本很少[333]、[344]。更重要的是，基于强化学习的检测可以从与未知环境的交互中学习新的威胁和攻击，同时提高检测体验和性能[345]。此类方法实际上可以应用于 V2X 不当行为检测，否则该检测可能会因缺乏标记数据和/或依赖安全阈值而受到阻碍。例如， [332]中提出了一种强化学习机制，用于检测 VeReMi 数据集中的多种不当行为攻击变体。通过顺序分析行为不当的车辆的移动模式（即实时位置坐标和速度矢量），可以有效地检测到行为不当的车辆。

## Digital Twin-Assisted Task Offloading for VEC
- L. Zhao et al., "A Digital Twin-Assisted Intelligent Partial Offloading Approach for Vehicular Edge Computing," in IEEE Journal on Selected Areas in Communications, vol. 41, no. 11, pp. 3386-3400, Nov. 2023, doi: 10.1109/JSAC.2023.3310062. [[paper]](https://ieeexplore.ieee.org/document/10234624),[[code]](https://github.com/NetworkCommunication/IGNITE)  
  - **摘要**：数字孪生辅助智能部分卸载，改进的聚类算法与数字孪生 (DT) 技术相结合，通过减小决策空间的大小可以避免不合理的决策。其次，为降低系统整体成本，采用深度强化学习（DRL）算法训练卸载策略，实现计算延迟和车辆服务价格的自动优化。为提高数字空间与物理空间协同的效率，建立了反馈机制，根据本次聚类的最终卸载结果调整聚类算法的参数。
  - **动机**：针对VEC的DT解决方案尚处于早期阶段，还有很大的改进空间。首先，目前还缺乏利用DT进行VEC预测以优化卸载决策的研究。其次，在当前使用DT辅助车辆任务卸载的方案中，所采用的卸载方法主要是二元卸载，且只有一个优化目标，通常是为了减少延迟。
  - **贡献**：反馈机制，根据最终卸载目标选择和资源分配结果调整DTN中聚类算法的参数，使使用DT的聚类算法更加准确和高效。形成了预测-卸载-反馈的完整闭环。一种新的车辆聚类方案，G k均值 在DTN中引入了聚类算法，其优点是（i）聚类时考虑了车辆之间的资源、通信、社交关系等因素；（ii）通过聚类找到的最优卸载空间可以提高任务卸载的效率。提出了一种自主动态定价和部分卸载方案，该方案由深度确定性策略梯度 (DDPG) 算法训练。目标是通过结合 V2V 和 V2R 卸载场景来联合优化任务卸载延迟和车辆服务价格，以最大限度地降低系统总体成本。
  - **系统模型（DT模型）**：DT模型由物理实体层和数字孪生层组成，物理车辆边缘计算网络由用户层、边缘层和云端层组成。用户层中的每辆车都会收集并分析来自各种应用程序和传感器的数据，这些任务大多数都是计算密集型和时间敏感型的。边缘层由分布在车辆附近并通过无线通信与其覆盖范围内的车辆相连的RSU组成，并实时掌握道路上车辆的信息。车辆的数字孪生在RSU中建模。云端层的云服务器由具有超高性能计算能力和存储能力的服务器组成，可以高效管理多台边缘服务器。数字孪生网络的构建主要包括数据存储、模型映射和数字孪生管理三个关键组成部分。数据存储是物理网络中车辆状态、路侧单元状态、网络状态和信道状态的存储，为构建模型提供原始素材。模型映射包括车辆虚拟模型的映射，包括方向盘、行驶速度、胎压等信息；路侧单元虚拟模型的映射，包括位置、资源等信息；网络虚拟模型的映射，包括路况、拥堵等信息。数字孪生管理是指实时更新和管理物理层和数字孪生层之间的映射。DTN可以学习道路上所有车辆的全局信息，如车辆资源、路况等。具体来说，基于聚类算法在RSU中形成DTN框架，然后利用DTN框架将道路上的车辆划分为不同的聚合组，当组内车辆资源不足需要卸载时，进行组内卸载约束，即提前缩小选定卸载对象的范围，以达到卸载预测的目的。
  - **社会关系模型**：VEC网络的高度动态性，社交网络作为一种有前途的聚合VEC网络多尺度因素的架构，可以提取车辆的原始数据来构建社会关系，使用社会关系模型来描述车辆间链路连接稳定性的模型。并提出社会信任值作为车辆间社会关系的度量，并将其量化为社会信任矩阵。其中，车辆间的社会信任值通过两个主要指标来衡量，即方向相似性和速度相似性。主要设计原则是测量两辆车的接近度。用社会关系模型对车辆进行聚类，其中同一聚合组内的车辆之间的链接连接将更加稳定，并且可以提高 V2V 计算卸载的效率。