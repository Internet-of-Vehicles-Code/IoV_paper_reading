- [Paper-Reading](#paper-reading)
  - [Authentication](#authentication)
    - [Survery](#survery)
    - [Journals](#journals)
    - [Conferences](#conferences)
  - [Sybil Attack Detection](#sybil-attack-detection)
    - [Overview](#overview)
    - [Conferences](#conferences-1)
  - [Pseudonym Changing Scheme](#pseudonym-changing-scheme)
    - [Journals](#journals-1)
    - [Conferences](#conferences-2)
  - [Other](#other)
    - [Journals](#journals-2)
    - [Conference](#conference)


# Paper-Reading
Paper reading list in Cooperative perception. This repository will keep updating ... 🤗

## Authentication

### Survery
- Patruni Muralidhara Rao al., A comprehensive survey on authentication and secure key management in internet of things: Challenges, countermeasures, and future directions," in Ad Hoc Networks, Vol. 146, 1 July 2023, 103159. [[paper]](https://doi.org/10.1016/j.adhoc.2023.103159)
  - 介绍了目前物联网中的一些身份认证技术，专业术语，以及形式化安全性能分析工具。

- S. Dong, H. Su, Y. Xia, F. Zhu, X. Hu and B. Wang, "A Comprehensive Survey on Authentication and Attack Detection Schemes That Threaten It in Vehicular Ad-Hoc Networks," in IEEE Transactions on Intelligent Transportation Systems, doi: 10.1109/TITS.2023.3297527. [[paper]](https://ieeexplore.ieee.org/abstract/document/10201386)
  - 身份认证与隐私保护方案主要分为三类：基于加密（对称（消息认证码、哈希函数、高效流丢失容忍）、非对称、身份三类）、基于数字签名的和基于验证的。

- Nath, H.J., Choudhury, H. Privacy-Preserving Authentication Protocols in Vanet. SN COMPUT. SCI. 4, 589 (2023). [[paper]](https://doi.org/10.1007/s42979-023-02122-3)

- Pravin Mundheet al.,, "A comprehensive survey on authentication and privacy-preserving schemes in VANETs," in Computer Science Review, Vol. 41, 2021, 100411, ISSN 1574-0137. [[paper]](https://www.sciencedirect.com/science/article/pii/S1574013721000514)

- S. A. Jan, N. U. Amin, M. Othman, M. Ali, A. I. Umar and A. Basir, "A Survey on Privacy-Preserving Authentication Schemes in VANETs: Attacks, Challenges and Open Issues," in IEEE Access, vol. 9, pp. 153701-153726, 2021, doi: 10.1109/ACCESS.2021.3125521. [[paper]](https://ieeexplore.ieee.org/abstract/document/9600861)

- D. Manivannan et al., "Secure authentication and privacy-preserving techniques in Vehicular Ad-hoc NETworks (VANETs)," in Vehicular Communications, Vol. 25, October 2020, 100247. [[paper]](https://www.sciencedirect.com/science/article/pii/S2214209620300188)

- Ikram Ali et al., "Authentication and privacy schemes for vehicular ad hoc networks (VANETs): A survey," in Vehicular Communications, Vol. 16, April 2019, Pages 45-61. [[paper]](https://www.sciencedirect.com/science/article/pii/S221420961830319X)

- Sunilkumar S. Manvi et al., "A survey on authentication schemes in VANETs for secured communication," in Vehicular Communications, vol. 9, July 2017, Pages 19-30. [[paper]](https://www.sciencedirect.com/science/article/pii/S2214209616300018#ab0010)



### Journals
- L. Wei, J. Cui, H. Zhong, I. Bolodurina, C. Gu and D. He, "A Decentralized Authenticated Key Agreement Scheme Based on Smart Contract for Securing Vehicular Ad-hoc Networks," in IEEE Transactions on Mobile Computing, doi: 10.1109/TMC.2023.3288930. [[paper]](https://ieeexplore.ieee.org/abstract/document/10160143)
    - 丢包率分析参考，丢包率主要由MAC层竞争机制引起的。在V2V场景中，Li等人的方案[10]的丢包率超过0.6，而我们提出的方案和Chattaraj等人的方案[21]的丢包率均为0。在V2I场景中，AKA消息相关丢包率的仿真结果如图7所示，我们可以发现我们提出的方案的丢包率略高于Ma等人的方案[9]但低于 Chattaraj 等人的方案 [21]。

- F. Wu, X. Zhang, C. Zhang, X. Chen, W. Fan and Y. Liu, "Batch-Assisted Verification Scheme for Reducing Message Verification Delay of the Vehicular Ad Hoc Networks," in IEEE Internet of Things Journal, vol. 7, no. 9, pp. 8144-8156, Sept. 2020, doi: 10.1109/JIOT.2020.3004811. [[paper]](https://ieeexplore.ieee.org/document/9125873)
  - 为了降低验证延迟实现快速消息验证，通过在 VANETs 系统中选择合理数量的辅助验证终端与路边单元合作，共同验证网络消息，提出了一种新的分布式协同认证方法。
  - 实验设置：在 SUMO 中进行仿真分析，仿真区域（2000 m x 2000 m）RSU 通信范围（1000 m），车辆通信范围（300 m），数据传输速率（12 Mb/s）。使用 MIRACL 库得到基本的密码操作执行时间。
  
- Udit Bansal et al., "ID-CEPPA: Identity-based Computationally Efficient Privacy-Preserving Authentication scheme for vehicle-to-vehicle communications," in Journal of Systems Architecture, Vol. 123, February 2022, 102387. [[paper]](https://www.sciencedirect.com/science/article/pii/S1383762121002654)
  - 提出了一种基于身份的计算高效隐私保护身份验证（ID-CEPPA）方案，使用基于身份的加密技术（IDC）和椭圆曲线加密技术（ECC）进行车载自组网（VANET）中的车对车（V2V）通信。该方案有效保证了V2V通信中车辆身份的消息源认证、消息完整性、不可否认性和匿名性。

- H. Liu, H. Wang and H. Gu, "HPBS: A Hybrid Proxy Based Authentication Scheme in VANETs," in IEEE Access, vol. 8, pp. 161655-161667, 2020, doi: 10.1109/ACCESS.2020.3021408. [[paper]](https://ieeexplore.ieee.org/document/9186126)
  - 提出了一种基于混合代理的认证方案。该方案选择了一些具有固定路线和更多计算和存储资源的车辆作为代理车辆，例如公交车，并使用这些代理车辆向RSU进行身份验证。

- Z. Wang et al., "An Anonymous and Revocable Authentication Protocol for Vehicle-to-Vehicle Communications," in IEEE Internet of Things Journal, vol. 10, no. 6, pp. 5114-5127, 15 March15, 2023, doi: 10.1109/JIOT.2022.3222469. [[paper]](https://ieeexplore.ieee.org/document/9953072)

- S. Bojjagani, Y. C. A. P. Reddy, T. Anuradha, P. V. V. Rao, B. R. Reddy and M. K. Khan, "Secure Authentication and Key Management Protocol for Deployment of Internet of Vehicles (IoV) Concerning Intelligent Transport Systems," in IEEE Transactions on Intelligent Transportation Systems, vol. 23, no. 12, pp. 24698-24713, Dec. 2022, doi: 10.1109/TITS.2022.3207593. [[paper]](https://ieeexplore.ieee.org/document/9905232)
  - （scyther开源代码，签名算法执行时间参考等）

- H. Xiong, J. Chen, Q. Mei and Y. Zhao, "Conditional Privacy-Preserving Authentication Protocol With Dynamic Membership Updating for VANETs," in IEEE Transactions on Dependable and Secure Computing, vol. 19, no. 3, pp. 2089-2104, 1 May-June 2022, doi: 10.1109/TDSC.2020.3047872. [[paper]](https://ieeexplore.ieee.org/abstract/document/9310200)
  - （批认证-CRT）

- P. Vijayakumar, M. Azees, S. A. Kozlov and J. J. P. C. Rodrigues, "An Anonymous Batch Authentication and Key Exchange Protocols for 6G Enabled VANETs," in IEEE Transactions on Intelligent Transportation Systems, vol. 23, no. 2, pp. 1630-1638, Feb. 2022, doi: 10.1109/TITS.2021.3099488. [[paper]](https://ieeexplore.ieee.org/abstract/document/9507051)
  - （批认证）

- K. Sutrala, P. Bagga, A. K. Das, N. Kumar, J. J. P. C. Rodrigues and P. Lorenz, "On the Design of Conditional Privacy Preserving Batch Verification-Based Authentication Scheme for Internet of Vehicles Deployment," in IEEE Transactions on Vehicular Technology, vol. 69, no. 5, pp. 5535-5548, May 2020, doi: 10.1109/TVT.2020.2981934. [[paper]](https://ieeexplore.ieee.org/document/9042206)

- J. Cui, X. Zhang, H. Zhong, J. Zhang and L. Liu, "Extensible Conditional Privacy Protection Authentication Scheme for Secure Vehicular Networks in a Multi-Cloud Environment," in IEEE Transactions on Information Forensics and Security, vol. 15, pp. 1654-1667, 2020, doi: 10.1109/TIFS.2019.2946933. [[paper]](https://ieeexplore.ieee.org/document/8865553)
  
- J. Cui, X. Zhang, H. Zhong, Z. Ying and L. Liu, "RSMA: Reputation System-Based Lightweight Message Authentication Framework and Protocol for 5G-Enabled Vehicular Networks," in IEEE Internet of Things Journal, vol. 6, no. 4, pp. 6417-6428, Aug. 2019, doi: 10.1109/JIOT.2019.2895136. [[paper]](https://ieeexplore.ieee.org/document/8625573)

- L. Wei, J. Cui, Y. Xu, J. Cheng and H. Zhong, "Secure and Lightweight Conditional Privacy-Preserving Authentication for Securing Traffic Emergency Messages in VANETs," in IEEE Transactions on Information Forensics and Security, vol. 16, pp. 1681-1695, 2021, doi: 10.1109/TIFS.2020.3040876. [[paper]](https://ieeexplore.ieee.org/document/9272352)
  
- P. Wang and Y. Liu, "SEMA: Secure and Efficient Message Authentication Protocol for VANETs," in IEEE Systems Journal, vol. 15, no. 1, pp. 846-855, March 2021, doi: 10.1109/JSYST.2021.3051435. [[paper]](https://ieeexplore.ieee.org/document/9360640)

- L. Song, G. Sun, H. Yu, X. Du and M. Guizani, "FBIA: A Fog-Based Identity Authentication Scheme for Privacy Preservation in Internet of Vehicles," in IEEE Transactions on Vehicular Technology, vol. 69, no. 5, pp. 5403-5415, May 2020, doi: 10.1109/TVT.2020.2977829. [[paper]](https://ieeexplore.ieee.org/document/9020102)
  - 预备知识：匿名、椭圆曲线、雾计算。
  - 提出了一种新的雾头选择方案，使雾中的车辆与雾头具有高度的行为一致性，大大提高了网络的稳定性。
  - 提出一种基于雾的双向认证方法，该方法不仅可以验证申请加入雾的新车的身份，而且雾头在雾的构建和使用过程中也是安全可靠的。
  - 将路侧单元（RSU）的工作分配给雾头和可信机构，而不是在认证过程中使用RSU。

- A. Yang, J. Weng, K. Yang, C. Huang and X. Shen, "Delegating Authentication to Edge: A Decentralized Authentication Architecture for Vehicular Networks," in IEEE Transactions on Intelligent Transportation Systems, vol. 23, no. 2, pp. 1284-1298, Feb. 2022, doi: 10.1109/TITS.2020.3024000. [[paper]](https://ieeexplore.ieee.org/abstract/document/9205261)
  - 预备知识：双线性映射、椭圆曲线、门限密码学。
  - 为了降低认证服务器与RSU交互与跨RSU切换认证时延，将认证服务器的认证能力委托给分布式边缘节点。
  - 针对车辆是否为首次访问网络，提出了一种支持快速切换阈值相互认证协议。
  - 为解决洪泛攻击，方案实施中由第一个接收到认证请求的RSU首先验证请求的有效性，再转发给其他的RSU。

- N. Xi, W. Li, L. Jing and J. Ma, "ZAMA: A ZKP-Based Anonymous Mutual Authentication Scheme for the IoV," in IEEE Internet of Things Journal, vol. 9, no. 22, pp. 22903-22913, 15 Nov.15, 2022, doi: 10.1109/JIOT.2022.3186921. [[paper]](https://ieeexplore.ieee.org/document/9809980)
  - 预备知识：ZKP、椭圆曲线、FO承诺。
  - 设计了一个基于非交互ZKP和椭圆曲线密码（ECC）的匿名相互认证协议。
  - 为了减少相互认证时延提高认证效率，方案中引入了预计算机制。
  - 针对在认证过程中认证断开的情况，设计了一个快速重新连接协议。

- J. Zhang, J. Cui, H. Zhong, Z. Chen and L. Liu, "PA-CRT: Chinese Remainder Theorem Based Conditional Privacy-Preserving Authentication Scheme in Vehicular Ad-Hoc Networks," in IEEE Transactions on Dependable and Secure Computing, vol. 18, no. 2, pp. 722-735, 1 March-April 2021, doi: 10.1109/TDSC.2019.2904274. [[paper]](https://ieeexplore.ieee.org/document/8664195)
  - 预备知识：中国剩余定理（CRT）、群密钥管理。
  - 提出了一种新的基于中国剩余定理（CRT）的条件隐私保护认证方案。

- K. Gu, K. Wang, X. Li and W. Jia, "Multi-Fogs-Based Traceable Privacy-Preserving Scheme for Vehicular Identity in Internet of Vehicles," in IEEE Transactions on Intelligent Transportation Systems, vol. 23, no. 8, pp. 12544-12561, Aug. 2022, doi: 10.1109/TITS.2021.3115171. [[paper]](https://ieeexplore.ieee.org/abstract/document/9557754)
  - 预备知识：秘密共享、ROR模型。
  - 提出了一种基于雾计算的IoV中车辆身份的分散式可追踪隐私保护方案。
  - 基于雾计算的数据收集框架，提出了车辆身份保护与认证方案。
  - 构造了一种投票机制来生成最可靠的雾服务器，该服务器能够通过基于秘密共享方案重建多项式来计算车辆的真实身份和相应的轨迹，每个雾服务器仅通过计算多项式获得车辆真实身份的秘密份额。

- M. Shen, H. Lu, F. Wang, H. Liu and L. Zhu, "Secure and Efficient Blockchain-Assisted Authentication for Edge-Integrated Internet-of-Vehicles," in IEEE Transactions on Vehicular Technology, vol. 71, no. 11, pp. 12250-12263, Nov. 2022, doi: 10.1109/TVT.2022.3194008. [[paper]](https://ieeexplore.ieee.org/abstract/document/9842355)
  - 预备知识：ECDSA、ECDHE、区块链。
  - 提出了一种安全高效的IoV区块链辅助认证方案，设计了初始认证和重新认证过程。
  - 通过利用联盟区块链来共享认证结果，设计了时间高效的重新认证过程。

- H. Chai, S. Leng, J. He, K. Zhang and B. Cheng, "CyberChain: Cybertwin Empowered Blockchain for Lightweight and Privacy-Preserving Authentication in Internet of Vehicles," in IEEE Transactions on Vehicular Technology, vol. 71, no. 5, pp. 4620-4631, May 2022, doi: 10.1109/TVT.2021.3132961. [[paper]](https://ieeexplore.ieee.org/document/9645276)
  - 预备知识：Cybertwin、Pedersen承诺、共识机制、PBFT。
  - 提出了一个基于Cybertwin的区块链认证框架，即CyberChain，用于高动态IoVs认证。
  - 设计了一种隐私保护并行Pedersen承诺(P4C)算法，以在动态环境中保护车辆隐私并加快认证过程。
  - 借助Cybertwin可靠通信，可以在小范围内快速完成车辆认证，提出了一种扩散实用拜占庭容错(DPBFT)机制，以在网络空间中达成共识，减少共识延迟。

- H. Sikarwar and D. Das, "A Novel MAC-Based Authentication Scheme (NoMAS) for Internet of Vehicles (IoV)," in IEEE Transactions on Intelligent Transportation Systems, vol. 24, no. 5, pp. 4904-4916, May 2023, doi: 10.1109/TITS.2023.3242291. [[paper]](https://ieeexplore.ieee.org/document/10042068)
  - 预备知识：DSRC标准、消息认证码。
  - 提出了一种轻量级的基于消息认证码（MAC）的车联网身份认证方案（NoMAS）。

- J. Liu et al., "CPAHP: Conditional Privacy-Preserving Authentication Scheme With Hierarchical Pseudonym for 5G-Enabled IoV," in IEEE Transactions on Vehicular Technology, vol. 72, no. 7, pp. 8929-8940, July 2023, doi: 10.1109/TVT.2023.3246466. [[paper]](https://ieeexplore.ieee.org/document/10049189)
  - 预备知识：ECDHE、假名方案、批量认证、区块链。
  - 基于椭圆曲线ECDH问题，提出了一种基于分层假名（系统假名和通信假名）的条件隐私保护认证方案(CPAHP)。
  - 通过利用批量验证方法，接收者可以一次验证多条消息。 
  - 提出了一个区块链框架来存储消息，使得交通信息能够在所有车辆之间顺利共享。

- J. Zhang, H. Zhong, J. Cui, L. Wei and L. Liu, "CVAR: Distributed and Extensible Cross-Region Vehicle Authentication With Reputation for VANETs," in IEEE Transactions on Intelligent Transportation Systems, doi: 10.1109/TITS.2023.3306547. [[paper]](https://ieeexplore.ieee.org/abstract/document/10234677) 
  - 预备知识：椭圆曲线数字签名、信誉评估。
  - 将车辆分为本地车辆（ECV）和跨域车辆（CV），将信誉分纳入认证方案来选择合适的本地车辆辅助认证。
  - 本地车辆作为边缘计算车辆，广播{信誉分，有效期，签名，当前位置，公钥，对当前位置的签名}。跨域车辆使用本区域公钥通过ECDSA算法验证本地车辆的信誉身份。
  - 信誉分计算，每辆CV使用估计的（方向/360°、速度/最大速度、与每辆车距离/最大通信距离、1-ECV信誉分）加权和。
  - 使用的密码学库：MIRACL。

- S. A. Soleymani, S. Goudarzi, M. H. Anisi, Z. Movahedi, A. Jindal and N. Kama, "PACMAN: Privacy-Preserving Authentication Scheme for Managing Cybertwin-Based 6G Networking," in IEEE Transactions on Industrial Informatics, vol. 18, no. 7, pp. 4902-4911, July 2022, doi: 10.1109/TII.2021.3121505. [[paper]](https://ieeexplore.ieee.org/document/9582763) 
  - 提出了基于Cybertwin的以云为中心的网络，为6G工业4.0网络提供可扩展性、移动性和可用性。对于所提出的网络架构开发了基于优先级和计算时间的卸载策略。
  - 提出了一种基于数字签名和认证密钥交换的具有隐私保留的认证协议，以生成和共享用于处理非法实体的会话密钥，并确保数据的完整性。

- M. Zhang, J. Zhou, P. Cong, G. Zhang, C. Zhuo and S. Hu, "LIAS: A Lightweight Incentive Authentication Scheme for Forensic Services in IoV," in IEEE Transactions on Automation Science and Engineering, vol. 20, no. 2, pp. 805-820, April 2023, doi: 10.1109/TASE.2022.3165174. [[paper]](https://ieeexplore.ieee.org/abstract/document/9758074) 
  - 预备知识：双线性映射、雾计算、激励机制。
  - 提出了一种基于雾计算的轻量级激励认证方案(LIAS)。提出的LIAS利用无配对无证书签名来实现轻量级的安全匿名身份验证。
  - 在LIAS中部署了假名更新机制、可追溯机制和激励机制。

- M. N. Aman, U. Javaid and B. Sikdar, "A Privacy-Preserving and Scalable Authentication Protocol for the Internet of Vehicles," in IEEE Internet of Things Journal, vol. 8, no. 2, pp. 1123-1139, 15 Jan.15, 2021, doi: 10.1109/JIOT.2020.3010893. [[paper]](https://ieeexplore.ieee.org/document/9145530)
  - 预备知识：物理不可克隆函数。
  - 本文基于物理不可克隆函数提出了一种高效的车联网认证协议。

### Conferences
- N. Pathak and P. R. Patil, "Securing VANET Communication Using Block Chain: A Review," 2023 International Conference on Communication System, Computing and IT Applications (CSCITA), Mumbai, India, 2023, pp. 215-218, doi: 10.1109/CSCITA55725.2023.10105098. [[paper]](https://ieeexplore.ieee.org/abstract/document/10105098)

- R. Boutahala, H. Fouchal, M. Ayaida and S. Mao, "Light and Efficient Authentication Mechanism for Connected Vehicles Using Unsupervised Detection," ICC 2023 - IEEE International Conference on Communications, Rome, Italy, 2023, pp. 329-333, doi: 10.1109/ICC45041.2023.10279812. [[paper]](https://ieeexplore.ieee.org/document/10279812)
  - 当车辆信任邻居时，它们会与未签名的消息进行通信。当信任无法得到保证时，车辆将切换到标准通信，直到信任恢复。为了达到信任，每辆车都会计算自己对邻居行为的预测。基于轨迹，速度。使用运行 LTSM 算法的自动编码器执行预测。

- S. Son, M. Kim and Y. Park, "A Lightweight Seamless Authentication Scheme for Edge-Assisted IoV networks," 2023 Fourteenth International Conference on Ubiquitous and Future Networks (ICUFN), Paris, France, 2023, pp. 305-310, doi: 10.1109/ICUFN57995.2023.10200823. [[paper]](https://ieeexplore.ieee.org/document/10200823)
  - 提出了初始认证、重新认证和移交认证三种情况下的认证方案。
  - 在初始认证阶段使用Chebyshev混沌映射来降低计算成本。

- F. Yu, M. Ma and X. Li, "A Blockchain-Assisted Seamless Handover Authentication for V2I Communication in 5G Wireless Networks," ICC 2021 - IEEE International Conference on Communications, Montreal, QC, Canada, 2021, pp. 1-6, doi: 10.1109/ICC42927.2021.9500334. [[paper]](https://ieeexplore.ieee.org/document/9500334)
  - （切换认证）



## Sybil Attack Detection
### Overview
- M. M. Hamdi, M. Dhafer, A. S. Mustafa, S. A. Rashid, A. J. Ahmed and A. M. Shantaf, "Effect Sybil attack on security Authentication Service in VANET," 2022 International Congress on Human-Computer Interaction, Optimization and Robotic Applications (HORA), Ankara, Turkey, 2022, pp. 1-6, doi: 10.1109/HORA55278.2022.9799810. [[paper]](https://ieeexplore.ieee.org/document/9799810)

- S. Kumar, A. Vasudeva and M. Sood, "Sybil Attack Countermeasures in Vehicular Ad Hoc Networks," 2022 International Conference on Communications, Information, Electronic and Energy Systems (CIEES), Veliko Tarnovo, Bulgaria, 2022, pp. 1-6, doi: 10.1109/CIEES55704.2022.9990799. [[paper]](https://ieeexplore.ieee.org/document/9990799)

- H. Yang et al., "An Overview of Sybil Attack Detection Mechanisms in VFC," 2022 52nd Annual IEEE/IFIP International Conference on Dependable Systems and Networks Workshops (DSN-W), Baltimore, MD, USA, 2022, pp. 117-122, doi: 10.1109/DSN-W54100.2022.00028. [[paper]](https://ieeexplore.ieee.org/document/9833826)

- Douceur, J.R. (2002). The Sybil Attack. In: Druschel, P., Kaashoek, F., Rowstron, A. (eds) Peer-to-Peer Systems. IPTPS 2002. Lecture Notes in Computer Science, vol 2429. Springer, Berlin, Heidelberg. [[paper]](https://link.springer.com/chapter/10.1007/3-540-45748-8_24)
  - Sybil 提出。


### Conferences
- B. Liu, J. Cai and J. Liu, "RSSI-Based Sybil Attack Detection Under Fading Channel in VANET," ICC 2023 - IEEE International Conference on Communications, Rome, Italy, 2023, pp. 5879-5884, doi: 10.1109/ICC45041.2023.10279536. [[paper]](https://ieeexplore.ieee.org/document/10279536)
  - 针对VANET中衰落信道和节点高度移动性的特点，提出了一种改进的基于RSSI的Sybil攻击检测方法。
  - 首先通过**最大似然估计**估计各通信节点之间的距离，然后通过**均值漂移聚类算法**检测sybil节点。
  - 通过合理设置均值漂移算法的检测时间和搜索半径，本文提出的算法在VANET中对sybil攻击的检测具有较高的准确性。
  - 基于Rayleigh分布，使用RSU对车辆进行检测，讨论了RSSI样本数对距离估计的影响。
  - MATLAB仿真，允许两车最小距离为5米。

- Maleknasab Ardakani, M., Tabarzad, M.A. & Shayegan, M.A. Detecting sybil attacks in vehicular ad hoc networks using fuzzy logic and arithmetic optimization algorithm. J Supercomput 78, 16303–16335 (2022). [[paper]](https://link.springer.com/article/10.1007/s11227-022-04526-z#citeas)

- A. Afdhal, A. Ahmadiar and R. Adriman, "Sybil Attack Detection on ITS-V2X System using a Realistic Traffic Model-based Approach," 2022 IEEE International Conference on Communication, Networks and Satellite (COMNETSAT), Solo, Indonesia, 2022, pp. 333-338, doi: 10.1109/COMNETSAT56033.2022.9994541. [[paper]](https://ieeexplore.ieee.org/document/9994541/authors#authors)

- Q. Hu, X. Fan, A. Shan and Z. Wang, "Sybil Attack Detection Method based on Timestamp-Chain in Internet of Vehicles," 2021 IEEE International Conference on Smart Internet of Things (SmartIoT), Jeju, Korea, Republic of, 2021, pp. 174-178, doi: 10.1109/SmartIoT52359.2021.00035. [[paper]](https://ieeexplore.ieee.org/document/9556187)
  - 时戳链、邻居列表。


## Pseudonym Changing Scheme
### Journals

### Conferences
- J. Wang, Y. Sun and C. Phillips, "Fake Beacon: A Pseudonym Changing Scheme for Low Vehicle Density in VANETs," 2023 IEEE 97th Vehicular Technology Conference (VTC2023-Spring), Florence, Italy, 2023, pp. 1-7, doi: 10.1109/VTC2023-Spring57618.2023.10199627. [[paper]](https://ieeexplore.ieee.org/document/10199627)
  - 提出了一种适用于低车辆密度情况的假信标假名更改方案，使得 mix-zone 中的 RSU 可以生成假信标。与传统的混合区域方案相比，对手恢复车辆轨迹的成功率下降了 50% 以上。
  - 目前的假名更改方案在车辆低密度场景下容易受到攻击。（1）CMIX：加密混合，信标在内部进行加密。更改假名的过程被隐藏，使得窃听者无法持续跟踪车辆。（2）基于 chaff：RSU 预测车辆方向，并使用假信标或虚拟车辆填充没有车辆的其他方向。
  - 比较了允许超车和不允许超车情况下方案的性能。



## Other
### Journals
- Q. Feng, K. Yang, M. Ma and D. He, "Efficient Multi-Party EdDSA Signature With Identifiable Aborts and its Applications to Blockchain," in IEEE Transactions on Information Forensics and Security, vol. 18, pp. 1937-1950, 2023, doi: 10.1109/TIFS.2023.3256710. [[paper]](https://ieeexplore.ieee.org/document/10068261)

- J. Guruprakash and S. Koppu, “An Empirical Study to Demonstrate that EdDSA can be used as a Performance Improvement Alternative to ECDSA in Blockchain and IoT,” Informatica  (Slovenia), vol. 46, no. 2, pp. 277–290, Jun. 2022, doi: 10.31449/inf.v46i2.3807. [[paper]](https://www.informatica.si/index.php/informatica/article/viewFile/3807/1764)
  - 对 ECDSA 与爱德华兹曲线数字签名算法（EdDSA）进行了实证比较。该研究的结论表明，EdDSA 优于 ECDSA，并且可以应用于区块链和物联网领域。
  - [10] 建议对比特币使用带有 SHA-512 的 EdDSA，因为与带有哈希 SHA-265 的现有 secp256k1 相比，它有助于提高安全性和效率。
  - EdCDH
  - 爱德华兹曲线使用消息散列而不是随机数，使该系统无冲突，并且每个消息都有不同的密钥。签名计算基于SHA算法，长度固定。签名和私钥用于生成签名并对消息进行签名。该数字签名允许接收者确定真实性并提供不可否认性。

- Q. Yu, J. Ren, Y. Fu, Y. Li and W. Zhang, "Cybertwin: An Origin of Next Generation Network Architecture," in IEEE Wireless Communications, vol. 26, no. 6, pp. 111-117, December 2019, doi: 10.1109/MWC.001.1900184. [[paper]](https://ieeexplore.ieee.org/document/8910636)  
  - 提出了一种基于Cybertwin的四层网络架构：Core Cloud、Edge Cloud、Cybertwin、Ends。
  - 作为虚拟网络空间中人或物的数字表示Cybertwin主要具有3个功能：通信助手、网络行为记录器和数字资产所有者。

- G. Li, C. Lai, R. Lu and D. Zheng, "SecCDV: A Security Reference Architecture for Cybertwin-Driven 6G V2X," in IEEE Transactions on Vehicular Technology, vol. 71, no. 5, pp. 4535-4550, May 2022, doi: 10.1109/TVT.2021.3133308. [[paper]](https://ieeexplore.ieee.org/document/9645213)
  - （面向网络孪生驱动6G V2X的安全参考架构）

- Y. Ni, C. Zhao and L. Cai, "Hybrid RSU Management in Cybertwin-IoV for Temporal and Spatial Service Coverage," in IEEE Transactions on Vehicular Technology, vol. 71, no. 5, pp. 4596-4606, May 2022, doi: 10.1109/TVT.2021.3138749. [[paper]](https://ieeexplore.ieee.org/document/9664342) 
  - 提出了一种Cybertwin-IoV架构，可促进RSU管理并实现始终在线的V2X服务。在所提出的架构下，混合RSU部署和管理问题被建模成一个整数规划问题。
  - 提出了一种基于效用的混合RSU调度策略，利用全局信息和流量预测分别获得sRSUs的位置和mRSUs的调度。
  - 提出了一种三阶段策略（sRSUs部署、mRSUs部署、实时调度）来解决RSU部署与优化问题，满足不同粒度的服务负载。

- M. A. Javed, T. N. Nguyen, J. Mirza, J. Ahmed and B. Ali, "Reliable Communications for Cybertwin-Driven 6G IoVs Using Intelligent Reflecting Surfaces," in IEEE Transactions on Industrial Informatics, vol. 18, no. 11, pp. 7454-7462, Nov. 2022, doi: 10.1109/TII.2022.3151773. [[paper]](https://ieeexplore.ieee.org/document/9714139) 
  - 解释了在6G车联网中应用IRS的四大优势：克服障碍、缓解多普勒效应、增强车辆定位、增强安全性。
  - 模拟了两个部署IRS的场景：密集城市、双向多车道道路。
  - 总结了IRS技术未来的机遇与挑战。

- Z. Yin, N. Cheng, T. H. Luan and P. Wang, "Physical Layer Security in Cybertwin-Enabled Integrated Satellite-Terrestrial Vehicle Networks," in IEEE Transactions on Vehicular Technology, vol. 71, no. 5, pp. 4561-4572, May 2022, doi: 10.1109/TVT.2021.3133574. [[paper]](https://ieeexplore.ieee.org/document/9645156) 
  - 在卫星-地面一体化车联网中引入Cybertwin网络架构提高物理层安全。

- Y. Guan, R. Lu, Y. Zheng, S. Zhang, J. Shao and G. Wei, "Toward Privacy-Preserving Cybertwin-Based Spatiotemporal Keyword Query for ITS in 6G Era," in IEEE Internet of Things Journal, vol. 8, no. 22, pp. 16243-16255, 15 Nov.15, 2021, doi: 10.1109/JIOT.2021.3096674. [[paper]](https://ieeexplore.ieee.org/document/9481235)
  - 设计了一个基于线段树的分层数据结构来动态索引发布者发布的消息，该索引能够有效地支持包含空间、时间和关键字条件的查询。
  - 提出了两种算法分别对索引和查询进行加密。（在不知道密钥的情况下能够输出对称同态加密(SHE)方案的密文）。
  - 提出了基于Cybertwin的隐私保护时空关键字查询方案，在保持消息和查询的隐私的同时，对消息进行索引和查询。

- R. Kumar, P. Kumar, R. Tripathi, G. P. Gupta, S. Garg and M. M. Hassan, "BDTwin: An Integrated Framework for Enhancing Security and Privacy in Cybertwin-Driven Automotive Industrial Internet of Things," in IEEE Internet of Things Journal, vol. 9, no. 18, pp. 17110-17119, 15 Sept.15, 2022, doi: 10.1109/JIOT.2021.3122021. [[paper]](https://ieeexplore.ieee.org/document/9583667)
  - 介绍了一个名为BDTwin的新集成框架，以增强CT驱动的V2X应用程序的安全性和隐私性。
  - 提出了一种基于深度学习的IDS，该IDS最初使用区块链方案的认证数据，并以无监督的学习方式使用AR-DVAE技术提取代表性特征。提取的特征被提议的A-BLSTM技术用于检测入侵。



### Conference
- W. D. Walidaniy, M. Yuliana and H. A. Darwito, "Enhancing Document Authenticity with QR Codes and ECC-Based Digital Signatures," 2023 International Electronics Symposium (IES), Denpasar, Indonesia, 2023, pp. 238-243, doi: 10.1109/IES59143.2023.10242576. [[paper]](https://ieeexplore.ieee.org/abstract/document/10242576)
  - 本文讨论了一种使用 OpenSSL 库实现的 ECDSA 认证方案，专门用于在智能电表和服务器之间建立认证。
  - 文中提到：（1）EdwardsCurve 数字签名算法 （EdDSA），因为它是椭圆曲线密码学（ECC）中最先进的算法。与常用的椭圆曲线数字签名算法（ECDSA）相比，EdDSA 在速度和安全性方面具有显著优势[8]。（2）椭圆曲线数字签名算法 （ECDSA） 由于容易受到侧信道分析（SCA）攻击，因此不再被认为适用于嵌入式设备。在 ECDSA 中，安全性在很大程度上依赖于随机数生成器（RNG）的质量和安全实现，以生成用于对消息进行签名的临时秘密随机数。相比之下，EdDSA 使用哈希函数来安全且确定地生成随机数。这种区别加强了EdDSA提供的增强安全措施，解决了 ECDSA 中与 RNG 相关的潜在漏洞[12]。

- H. Bao, X. Zhang, G. Wang, M. Zhang, Y. Wang and Y. Zhao, "RepuFilter: Prevention of Untrusted Packet Spread Based on Trust Evaluation in Wireless Networks," ICC 2023 - IEEE International Conference on Communications, Rome, Italy, 2023, pp. 5972-5977, doi: 10.1109/ICC45041.2023.10278691. [[paper]](https://ieeexplore.ieee.org/document/10278691) 
  - 提出了一种基于网络用户之间信任评估的传递性的动态信任评估模型，并将该模型应用于数据包过滤。

- A. Kumar and D. Das, "EIoVChain: Towards Authentication and Secure Communication Based Blockchain for Internet of Vehicles (IoV)," 2021 IEEE International Conference on Blockchain (Blockchain), 2021, pp. 47-54, doi: 10.1109/Blockchain53845.2021.00018. [[paper]](https://ieeexplore.ieee.org/document/9680517)
  - 提出了一种基于边缘PBFT模型的区块链架构——EIoVChain，可以最大限度地减少验证延迟和通信延迟，并提供高效的信息存储和访问策略。
  - EIoVCchain实现了一个主/辅边缘服务器分配算法，主要边缘服务器用以生成块，其他所有次边缘服务器用以验证块。
