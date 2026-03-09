# project
科研数据集
### 📊 实验数据集 (Datasets)

本项目（TransSAM 框架）在 5 个公开的权威网络流量数据集上进行了广泛的交叉验证与评估。为了方便研究人员复现我们的实验结果，请访问以下官方链接获取原始 PCAP/CSV 数据：

* [CIC-IDS-2017](https://www.unb.ca/cic/datasets/ids-2017.html): 用于评估模型对 Web 攻击、渗透测试等隐蔽性对抗意图流量的识别能力。
* [CIC-DDoS-2019](https://www.unb.ca/cic/datasets/ddos-2019.html): 包含多种反射放大及 TCP SYN Flood 攻击，用于检验模型对体积型异常波动的感知精度。
* [DoHBrw-2020](https://www.unb.ca/cic/datasets/dohbrw-2020.html): 聚焦基于 HTTPS 的 DNS (DoH) 隐蔽隧道流量检测。
* [USTC-TFC2016](https://github.com/yungshenglu/USTC-TFC2016): 包含多类真实恶意软件（如僵尸网络）及正常应用流量的基准测试集。
* [CIC-IoV-2024](https://www.unb.ca/cic/datasets/iov-dataset-2024.html): 最新的车联网 (CAN bus) 异常流量，主要用于验证模型在跨数据集场景下的零日威胁 (Zero-Day) 泛化能力。
