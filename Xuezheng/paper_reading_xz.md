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