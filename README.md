# Blockchain-Apple-APTrace
# 忙而不茫团队-智慧兴农——从触网到触链，“红星苹果”特色农产品持“证”一键溯源
# 项目介绍
智慧农业特色农产品溯源系统是集大数据、云计算和物联网技术、区块链技术为一体，依托部署在农业生产现场的各种传感节点和云端数据中心实现农产品的追踪、溯源和农业生产环优化，提高农作物质量的真实性，从而实现智能化决策和精准化种植。该系统采用前后端分离的开发部署模式，运用了FISCO BCOS区块链底层平台、We BASE工具集、vue.js、vant组件库、RocketMQ消息中间件、MyBatis持久化框架等技术，通过axios进行数据交互。该系统可实现多设备端的访问，包括安卓端、H5前端以及小程序混合开发。

我们本次所开发的智慧农业特色农产品溯源系统以乡村振兴的新的路径探索为目标，致力于推进农业智能化的实现。突出集群成链，延长产业链、提升价值链，培育发展新动能，加快构建现代农业产业体系、生产体系和经营体系，推动形成城乡融合发展格局，为农业农村现代化奠定坚实基础。
# 项目背景
随着社会经济的快速发展和人民日益增长的美好生活需要,农业技术不断进步，农业方面农产品提取和产量已不再是农业规划的难点，可保障农产品质量安全一直是“三农”问题中难啃的骨头，农产品无法溯源，消费者难辨真伪。在《农产品质量安全法》《食品安全法》等安全法中，均严格要求建立食品安全管理、记录制度；近10年中央一号文件均提出要求建立、健全、推进农产品质量可追溯体系建设；《食品安全法》第42条，也明确规定食品生产经营者应建立食品安全追溯体系。

通过代码溯源并使用区块链技术可以实现农产品安全溯源，追溯到生产企业，深入到全程质量安全追溯，满足消费者所关注的生产信息及产地环境的信息。区块链技术基于加密算法，能够保证数据的不可篡改和可追溯特点，同时结合共识算法促使节点间数据保持一致性，具有区块链去中心化、匿名、自治、开放、信息不可篡改的技术特点，可以应用于农产品溯源系统去中心化、不可篡改的数据存储。通过溯源系统，消费者可以利用溯源查询二维码进行农产品的溯源，查询全过程信息，保证数据可靠性。
# 项目目标
## 1.	建立标准化种植模型
该系统在实现农业生产公开透明、农业环境数据云端实时监测、农业智能云平台远程控制和云端AI智能化分析、诊断、决策科学化种植等功能的同时，实现农业科学化管理。
## 2.	完善信息真实化模型
未来与国家食品安全局建立合作，建立更加完善安全的信息库模型，实现更加全面、系统、便捷的农产品溯源管理，提高农产品的质量安全可控水平，保障消费者的知情权和选择权，进而提高消费者满意度和购买信心。实现全程可追溯，提高农产品安全监管能力，促进农产品品牌化，更好的保障消费者权益。
## 3.	实现智能决策
实现科学培养决策、科学管理决策、科学销售决策。通过传感器数据分析可判定土壤合适培养的作物品种；通过气候环境传感器可以实时搜集作物生长环境数据控制；通过区块链去中心化网络架构实现数据的存储和传输。实现农产品信息的可塑性，使消费者放心购买。
## 4.	实现供应链智能化
采用智能物联网技术，建立以区块链技术为基础的农产品供应链智能管理平台，实现数据信息化、智能化、共享化。通过物联网、传感器等技术，实现对农产品流通环节的智能监控和控制。通过人工智能算法，实现农产品流通环节的智能管理和优化，控制和分摊风险，提高供应链的整体效率。
# 方案：
## 1.智慧农业特色农产品溯源系统整体思路
 ![001](https://github.com/IMXiaoBai666/Blockchain-Apple-APTrace/assets/135217781/9361a1e9-008f-42e6-8405-e5b7fb3a0ab8)

## 2.智慧农业特色农产品溯源系统架构图
 ![架构图](https://github.com/IMXiaoBai666/Blockchain-Apple-APTrace/assets/135217781/9d1c9dea-cbe9-4477-8681-acdabec935a2)

# 项目结构说明
blockchain-trace-bcnetwork：区块链网络。

blockchain-trace-pc：PC端,使用的是RuoYi-Vue。

blockchain-trace-basic-data：系统基础数据后台，使用的是RuoYi。

前端：Vue.js, Element UI, mpvue。

后端：Spring Boot, MyBatis, FastDFS, Node.js, Redis, MySQL。

区块链：FISCO BCOS。

