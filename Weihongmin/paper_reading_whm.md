# Paper-Reading
Paper reading list in Cooperative perception. This repository will keep updating ... 🤗

## Authentication
- J. Zhang, H. Zhong, J. Cui, L. Wei and L. Liu, "CVAR: Distributed and Extensible Cross-Region Vehicle Authentication With Reputation for VANETs," in IEEE Transactions on Intelligent Transportation Systems, doi: 10.1109/TITS.2023.3306547. [[paper]](https://ieeexplore.ieee.org/abstract/document/10234677) 
  - 将车辆分为本地车辆（ECV）和跨域车辆（CV），将信誉分纳入认证方案来选择合适的本地车辆辅助认证。
  - 本地车辆作为边缘计算车辆，广播{信誉分，有效期，签名，当前位置，公钥，对当前位置的签名}。跨域车辆使用本区域公钥通过ECDSA算法验证本地车辆的信誉身份。
  - 信誉分计算，每辆CV使用估计的（方向/360°、速度/最大速度、与每辆车距离/最大通信距离、1-ECV信誉分）加权和。
  - 使用的加密库：MIRACL。
  
