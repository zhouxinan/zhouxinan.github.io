---
title: Publications
date: 2024-07-02 12:00:38
---
## 2026

### [Poster: Exploiting Side-Channel Leakage in AI Glasses](https://dl.acm.org/doi/pdf/10.1145/3842203.3844595)
Zixun Xiong, Cheng Gu, Xin'an Zhou, Yanan Guo, Yicheng Zhang
Proceedings of the Second Workshop on Enhancing Security, Privacy, and Trust in Extended Reality

### [Three Steps to the Terminal: A Siemens ROX II Zero-Day Trilogy](https://unit42.paloaltonetworks.com/siemens-rox-ii-zero-day-vulnerabilities/)
Emmanuel Zhou, Adam Robbie, Rick Wyble, Miguel Pereira
Unit 42 by Palo Alto Networks

### [AirSnitch: Breaking Client Isolation in Wi-Fi Networks](https://blackhat.com/archive/asia/2026/briefings/schedule/#airsnitch-breaking-client-isolation-in-wi-fi-networks-51283)
Mathy Vanhoef, Zhiyun Qian, Xin'an Zhou, Juefei Pu, Zhutian Liu, Zhaowei Tan, Srikanth V. Krishnamurthy
Black Hat Asia 2026

### [When Wi-Fi Encryption Fails: Protecting Your Enterprise from AirSnitch Attacks](https://unit42.paloaltonetworks.com/air-snitch-enterprise-wireless-attacks/)
Emmanuel Zhou, Adam Robbie, Rick Wyble, Zhutian Liu, Zhiyun Qian, Zhaowei Tan, Srikanth V. Krishnamurthy, Mathy Vanhoef
Unit 42 by Palo Alto Networks

### [AirSnitch: Demystifying and Breaking Client Isolation in Wi-Fi Networks](https://www.ndss-symposium.org/ndss-paper/airsnitch-demystifying-and-breaking-client-isolation-in-wi-fi-networks/)
[Site](https://www.airsnitchattacks.com/) [Source](https://github.com/zhouxinan/airsnitch)
Xin'an Zhou, Juefei Pu, Zhutian Liu, Zhiyun Qian, Zhaowei Tan, Srikanth V. Krishnamurthy, Mathy Vanhoef
NDSS 2026
**Finalist of 2026 Pwnie Awards for Most Innovative Research**

<details>
  <summary>BibTeX</summary>
    
  ```bibtex
@inproceedings{zhou_airsnitch:_2026,
  address = {San Diego, CA, USA},
  title = {{AirSnitch}: {Demystifying} and {Breaking} {Client} {Isolation} in {Wi}-{Fi} {Networks}},
  isbn = {9798991927680},
  shorttitle = {{AirSnitch}},
  url = {https://www.ndss-symposium.org/wp-content/uploads/2026-f1282-paper.pdf},
  doi = {10.14722/ndss.2026.241282},
  language = {en},
  urldate = {2026-11-18},
  booktitle = {Proceedings of the 2026 {Network} and {Distributed} {System} {Security} {Symposium}},
  publisher = {Internet Society},
  author = {Zhou, Xin'an and Pu, Juefei and Liu, Zhutian and Qian, Zhiyun and Tan, Zhaowei and Krishnamurthy, Srikanth V. and Vanhoef, Mathy},
  year = {2026},
}
  ```
</details>

## 2025

### [Rethinking Network Access Control Protocols to Protect Critical Systems](https://escholarship.org/uc/item/9rh2b0mz)
Xin'an Zhou
UC Riverside

### [SCAD: Towards a Universal and Automated Network Side-Channel Vulnerability Detection](https://www.computer.org/csdl/proceedings-article/sp/2025/223600a068/21B7RcuK7C0)
Keyu Man, Zhongjie Wang, Yu Hao, Shenghan Zheng, Xin'an Zhou, Yue Cao, Zhiyun Qian
2025 IEEE Symposium on Security and Privacy (SP)

<details>
  <summary>BibTeX</summary>
    
  ```bibtex
  @INPROCEEDINGS {,
author = { Man, Keyu and Wang, Zhongjie and Hao, Yu and Zheng, Shenghan and Zhou, Xin'an and Cao, Yue and Qian, Zhiyun },
booktitle = { 2025 IEEE Symposium on Security and Privacy (SP) },
title = {{ SCAD: Towards a Universal and Automated Network Side-Channel Vulnerability Detection }},
year = {2025},
volume = {},
ISSN = {2375-1207},
pages = {68-68},
abstract = { Network side-channel attacks have recently been highlighted due to their severity and elusive nature. For example, SADDNS attacks allow an off-path attacker to launch cache poisoning attacks leveraging network side channels. Due to the subtle nature of network side channels, it is challenging to identify such side channels. To this date, few automated bug discovery techniques are tailored for such vulnerabilities. Unfortunately, none of them is general and automated enough, making their impact and longer-term use limited. In this paper, we describe the first solution that aims to fill this gap. Specifically, we develop SCAD, aiming at identifying violations of the non-interference property, which are commonly understood as the root cause of network side channels. As non-interference property is a hyperproperty, it necessitates reasoning across multiple execution traces. This motivated us to develop our solution based on under-constrained and dynamic symbolic execution. The state-of-the-art solution, SCENT, applies model checking, which requires extra effort in modeling or simplifying certain parts of a network protocol, in order to scale. Unfortunately, such modeling and simplification is time-consuming, error prone, and can overlook important details, leading to missed vulnerabilities. For example, it was reported that 2.5 person-week was required to construct a self-contained using SCENT. In comparison, SCAD requires only a single person-day to perform labeling of secrets and attacker-observables, and decide the analysis scope. By applying SCAD to multiple TCP and UDP implementations, including Linux, FreeBSD, and lwIP, we find 14 network side-channels, 7 of which were previously unknown, with a false positive rate of only 17.6%. The results reveal serious vulnerabilities, including those that can be used to compromise the previously patched Linux and FreeBSD kernels, making them susceptible to SADDNS attacks or off-path TCP exploits. Our analysis concludes that the majority of the side channels cannot be found by existing solutions due to the aforementioned limitations. },
keywords = {network;side channel;symbolic execution;state variable;tcp;attack},
doi = {10.1109/SP61157.2025.00068},
url = {https://doi.ieeecomputersociety.org/10.1109/SP61157.2025.00068},
publisher = {IEEE Computer Society},
address = {Los Alamitos, CA, USA},
month =May}
  ```
</details>

## 2024

### [Fallen Tower of Babel: Rooting Wireless Mesh Networks by Abusing Heterogeneous Control Protocols](https://www.blackhat.com/us-24/briefings/schedule/index.html#fallen-tower-of-babel-rooting-wireless-mesh-networks-by-abusing-heterogeneous-control-protocols-39898)
Xin'an Zhou, Zhiyun Qian, Juefei Pu, Qing Deng, Srikanth V. Krishnamurthy, Keyu Man
Black Hat USA 2024 

### [Untangling the Knot: Breaking Access Control in Home Wireless Mesh Networks](https://www.cs.ucr.edu/%7Ezhiyunq/pub/ccs24_wireless_mesh.pdf)
Xin'an Zhou, Qing Deng, Juefei Pu, Keyu Man, Zhiyun Qian, Srikanth V. Krishnamurthy
Proceedings of the 2024 ACM SIGSAC Conference on Computer and Communications Security. 
**Finalist of 2025 Pwnie Awards for Best Cryptographic Attack**

<details>
  <summary>BibTeX</summary>
    
  ```bibtex
@inproceedings{zhou2024untangling,
  title={Untangling the Knot: Breaking Access Control in Home Wireless Mesh Networks},
  author={Zhou, Xin'an and Deng, Qing and Pu, Juefei and Man, Keyu and Qian, Zhiyun and Krishnamurthy, Srikanth V},
  booktitle={Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security},
  pages={2072--2086},
  year={2024}
}
  ```
</details>

## 2023
### [Dilemma in IoT Access Control: Revealing Novel Attacks and Design Challenges in Mobile-as-a-Gateway IoT](https://www.blackhat.com/asia-23/briefings/schedule/index.html#dilemma-in-iot-access-control-revealing-novel-attacks-and-design-challenges-in-mobile-as-a-gateway-iot-31040)
[PDF](http://i.blackhat.com/Asia-23/AS-23-Xing-Dilemma-In-IoT-Access-Control.pdf?_gl=1*1l99mon*_ga*MTI2Nzg1NTY3My4xNjgzNDI2Mjkx*_ga_K4JK67TFYV*MTY4NDM2MDY0MC41LjEuMTY4NDM2MTgyNy4wLjAuMA..&_ga=2.145530036.1850328154.1684360640-1267855673.1683426291)
Luyi Xing, Xin'an Zhou, Jiale Guan, Zhiyun Qian
Black Hat Asia 2023

### (An anonymous workshop paper)

## 2022
### [Perils and Mitigation of Security Risks of Cooperation in Mobile-as-a-Gateway IoT](https://dl.acm.org/doi/10.1145/3548606.3560590)
[Site](https://maag-iot.xinanzhou.com/)
Xin'an Zhou, Jiale Guan, Luyi Xing, Zhiyun Qian
Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security.
**Finalist of 2023 Pwnie Awards for Most Under-hyped Research**

<details>
  <summary>BibTeX</summary>
    
  ```bibtex
  @inproceedings{zhou2022perils,
  title={Perils and mitigation of security risks of cooperation in mobile-as-a-gateway iot},
  author={Zhou, Xin'an and Guan, Jiale and Xing, Luyi and Qian, Zhiyun},
  booktitle={Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security},
  pages={3285--3299},
  year={2022}
}
  ```
</details>


## 2021
### [DNS Cache Poisoning Attack: Resurrections with Side Channels](https://dl.acm.org/doi/abs/10.1145/3460120.3486219)
[Site](https://www.saddns.net/)
Keyu Man, Xin'an Zhou, and Zhiyun Qian
Proceedings of the 2021 ACM SIGSAC Conference on Computer and Communications Security.
**Key Insight: Using ICMP as a side-channel to perform DNS Cache Poisoning Attacks.**

<details>
  <summary>BibTeX</summary>
    
  ```bibtex
@inproceedings{man2021dns,
  title={Dns cache poisoning attack: Resurrections with side channels},
  author={Man, Keyu and Zhou, Xin'an and Qian, Zhiyun},
  booktitle={Proceedings of the 2021 ACM SIGSAC Conference on Computer and Communications Security},
  pages={3400--3414},
  year={2021}
}
  ```
</details>


