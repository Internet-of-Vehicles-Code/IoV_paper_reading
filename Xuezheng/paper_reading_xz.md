# Paper-Reading
Paper reading list in Cooperative perception. This repository will keep updating ... 🤗

- [Cooperative perception](cooperative_perception)


## Cooperative perception
* R. Xu, H. Xiang, X. Xia, X. Han, J. Li and J. Ma, "OPV2V: An Open Benchmark Dataset and Fusion Pipeline for Perception with Vehicle-to-Vehicle Communication," 2022 International Conference on Robotics and Automation (ICRA), Philadelphia, PA, USA, 2022, pp. 2583-2589, doi: 10.1109/ICRA46639.2022.9812038. [[paper]](https://ieeexplore.ieee.org/document/9812038);[[code]](https://github.com/DerrickXuNu/OpenCOOD)
  * OpenCOOD支持三种协同感知的融合方式，可添加协同感知GPS位置误差和通信延迟。
* Y. Lu et al., "Robust Collaborative 3D Object Detection in Presence of Pose Errors," 2023 IEEE International Conference on Robotics and Automation (ICRA), London, United Kingdom, 2023, pp. 4812-4818, doi: 10.1109/ICRA48891.2023.10160546.[[paper]](https://ieeexplore.ieee.org/document/10160546) ;[[code]](https://github.com/yifanlu0227/CoAlign)
  * 基于OpenCOOD,利用SLAM位姿图优化理论保持协作感知位姿一致性及鲁棒性。
* T. Hardes, I. Turcanu and C. Sommer, "Poster: A Case for Heterogenous Co-Simulation of Cooperative and Autonomous Driving," 2023 IEEE Vehicular Networking Conference (VNC), Istanbul, Turkiye, 2023, pp. 151-152, doi: 10.1109/VNC57357.2023.10136319. [[paper]](https://ieeexplore.ieee.org/document/10136319),[[code]](https://github.com/veins/veins_carla)
  - 作者修复了bug，已经安装成功！需要研究源码！研究与carla的同步。


## Vehicular edge computing
* Y. Ju et al., "Joint Secure Offloading and Resource Allocation for Vehicular Edge Computing Network: A Multi-Agent Deep Reinforcement Learning Approach," in IEEE Transactions on Intelligent Transportation Systems, vol. 24, no. 5, pp. 5555-5569, May 2023, doi: 10.1109/TITS.2023.3242997. [[paper]](https://ieeexplore.ieee.org/abstract/document/10041957)

## Security in V2X networks
* Ansari, M. R., Petit, J., Monteuuis, J. P., & Chen, C. VASP: V2X Application Spoofing Platform. [[paper]](https://www.ndss-symposium.org/wp-content/uploads/2023/02/vehiclesec2023-23071-paper.pdf),[[code]](https://github.com/quic/vasp),[[Qualcomm Innovation Center]](https://quic.github.io/)
  * VASP攻击仿真平台，比较了VeReMi和F2MD，是F2MD的paper二作，能仿真更多攻击和自定义攻击。
* A. Willecke, B. Kulke and L. C. Wolf, "A4MD: Artery for Misbehavior Detection, Reporting, and Reaction in the ETSI C-ITS," 2023 IEEE Vehicular Networking Conference (VNC), Istanbul, Turkiye, 2023, pp. 33-40, doi: 10.1109/VNC57357.2023.10136315. [[paper]](https://ieeexplore.ieee.org/abstract/document/10136315),[[code]](https://github.com/ibr-cm/a4md)
  * A4MD平台 