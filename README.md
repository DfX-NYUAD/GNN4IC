# GNN4IC
Must-read papers on Graph Neural Networks (GNNs) for Integrated Circuits (ICs) design, security and reliability. This collection of papers is summarized in the following survey paper; L. Alrahis et al. "Graph Neural Networks: A Powerful and Versatile Tool for Advancing Design, Reliability, and Security of ICs," ASP-DAC, 2023.

Contributed by Lilas Alrahis and Johann Knechtel

Please note, the following list is just a collection of papers in no particular order.
## [Content](#content)
<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#gnns-for-eda">2. GNNs for EDA</a></td></tr>
<tr>
    <td>&ensp;<a href="#partitioning-and-floorplanning">2.1 Partitioning and Floorplanning</a></td>
</tr>
<tr><td colspan="2"><a href="#gnns-for-hardware-security">3. GNNs for Hardware Security</a></td></tr>
<tr>
    <td>&ensp;<a href="#attack-on-logic-obfuscation">3.1 Attack on Logic Obfuscation</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#reverse-engineering">3.2 Reverse Engineering</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#hardware-trojan-detection">3.3 Hardware Trojan Detection</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#ip-piracy-detection">3.4 IP Piracy Detection</a></td>
</tr>
<tr><td colspan="2"><a href="#gnns-for-reliable-hardware">4. GNNs for Hardware Reliability</a></td></tr> 
</table>

## [Survey papers](#content)
- **Embracing Graph Neural Networks for Hardware Security.** International Conference on Computer-Aided Design (ICCAD), 2022. [paper](https://arxiv.org/pdf/2208.08554.pdf)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Shafique, Ozgur Sinanoglu.* 
- **Machine Learning for Electronic Design Automation: A Survey.** ACM Transactions on Design Automation of Electronic Systems, 2021. [paper](https://dl.acm.org/doi/10.1145/3451179)

    *Guyue Huang, Jingbo Hu, Yifan He, Jialong Liu, Mingyuan Ma, Zhaoyang Shen, Juejian Wu, Yuanfan Xu, Hengrui Zhang, Kai Zhong, Xuefei Ning, Yuzhe Ma, Haoyu Yang, Bei Yu, Huazhong Yang, Yu Wang.*
- **Accelerating Chip Design With Machine Learning.** IEEE Micro, 2020. [paper](https://ieeexplore.ieee.org/document/9205654)

    *Brucek Khailany, Haoxing Ren, Steve Dai, Saad Godil, Ben Keller, Robert Kirby, Alicia Klinefelter, Rangharajan Venkatesan, Yanqing Zhang, Bryan Catanzaro, William J. Dally.*
- **Understanding Graphs in EDA: From Shallow to Deep Learning.** International Symposium on Physical Design (ISPD), 2020. [paper](https://dl.acm.org/doi/10.1145/3372780.3378173)

    *Yuzhe Ma, Zhuolun He, Wei Li, Lu Zhang, Bei Yu.*
- **MLCAD: A Survey of Research in Machine Learning for CAD Keynote Paper.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2022. [paper](https://ieeexplore.ieee.org/document/9598835)

    *Martin Rapp, Hussam Amrouch, Yibo Lin, Bei Yu, David Z. Pan, Marilyn Wolf, Jörg Henkel.*
    
- **Survey of Graph Neural Networks for Electronic Design Automation.** ACM/IEEE Workshop on Machine Learning for CAD (MLCAD), 2021. [paper](https://ieeexplore.ieee.org/document/9531070)

    *Daniela Sanchez Lopera, Lorenzo Servadei, Gamze Naz Kiprit, Souvik Hazra, Robert Wille, Wolfgang Ecker.*

- **A Comprehensive Survey on Electronic Design Automation and Graph Neural Networks: Theory and Applications.** ACM Transactions on Design Automation of Electronic Systems, 2022.0. [paper](https://dl.acm.org/doi/10.1145/3543853)

    *Daniela Sánchez Lopera, Lorenzo Servadei, Gamze Naz Kiprit, Robert Wille, Wolfgang Ecker.*

- **Why are Graph Neural Networks Effective for EDA Problems? (Invited Paper).** IEEE/ACM International Conference On Computer Aided Design (ICCAD) , 2022.0.

    *Haoxing Ren, Siddhartha Nath, Yanqing Zhang, Hao Chen, Mingjie Liu.*

- **On Advancing Physical Design using Graph Neural Networks  (Invited Paper).** IEEE/ACM International Conference On Computer Aided Design (ICCAD) , 2022.0.

    *Yi-Chen Lu, Sung Kyu Lim.*

- **High-Level Synthesis Performance Prediction using GNNs: Benchmarking, Modeling, and Advancing.** ACM/IEEE Design Automation Conference (DAC), 2022.0. [paper](https://dl.acm.org/doi/abs/10.1145/3489517.3530408)

    *Nan Wu, Hang Yang, Yuan Xie, Pan Li, Cong Hao.*

## [GNNs for EDA](#content)
### [Partitioning and Floorplanning](#content)
## [GNNs for Hardware Security](#content)
### [Attack on Logic Obfuscation](#content)
- **GNNUnlock: Graph Neural Networks-based Oracle-less Unlocking Scheme for Provably Secure Logic Locking.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2021. [paper](https://ieeexplore.ieee.org/document/9474039), [code](https://github.com/DfX-NYUAD/GNNUnlock)

    *Lilas Alrahis, Satwik Patnaik, Faiq Khalid, Muhammad Abdullah Hanif, Hani Saleh, Muhammad Shafique, Ozgur Sinanoglu.*

- **GNNUnlock+: A Systematic Methodology for Designing Graph Neural Networks-Based Oracle-Less Unlocking Schemes for Provably Secure Logic Locking.** IEEE Transactions on Emerging Topics in Computing, 2021. [paper](https://ieeexplore.ieee.org/document/9529342), [code](https://github.com/DfX-NYUAD/GNNUnlock)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Abdullah Hanif, Hani Saleh, Muhammad Shafique, Ozgur Sinanoglu.*

- **OMLA: An Oracle-Less Machine Learning-Based Attack on Logic Locking.** IEEE Transactions on Circuits and Systems II: Express Briefs, 2021. [paper](https://ieeexplore.ieee.org/document/9539868), [code](https://github.com/DfX-NYUAD/OMLA)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Shafique, Ozgur Sinanoglu.*

- **MuxLink: Circumventing Learning-Resilient MUX-Locking Using Graph Neural Network-based Link Prediction.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2022. [paper](https://ieeexplore.ieee.org/document/9774603), [code](https://github.com/lilasrahis/MuxLink)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Shafique, Ozgur Sinanoglu.*

- **UNTANGLE: Unlocking Routing and Logic Obfuscation Using Graph Neural Networks-based Link Prediction.** IEEE/ACM International Conference On Computer Aided Design (ICCAD), 2021. [paper](https://ieeexplore.ieee.org/document/9643476), [code](https://github.com/lilasrahis/UNTANGLE)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Abdullah Hanif, Muhammad Shafique, Ozgur Sinanoglu.*

- **Titan: Security Analysis of Large-Scale Hardware Obfuscation Using Graph Neural Networks.** IEEE Transactions on Information Forensics and Security, 2022. [paper](https://ieeexplore.ieee.org/abstract/document/9933482), [code](https://github.com/DfX-NYUAD/Titan)

    *Likhitha Mankali, Lilas Alrahis, Satwik Patnaik, Johann Knechtel, Ozgur Sinanoglu.*
### [Reverse Engineering](#content)
- **GNN-RE: Graph Neural Networks for Reverse Engineering of Gate-Level Netlists.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2021. [paper](https://ieeexplore.ieee.org/document/9530566), [code](https://github.com/DfX-NYUAD/GNN-RE)

    *Lilas Alrahis, Abhrajit Sengupta, Johann Knechtel, Satwik Patnaik, Hani Saleh, Baker Mohammad, Mahmoud Al-Qutayri, Ozgur Sinanoglu.*

- **AppGNN: Approximation-Aware Functional Reverse Engineering using Graph Neural Networks.** IEEE/ACM International Conference On Computer Aided Design (ICCAD), 2022. [paper](https://arxiv.org/pdf/2208.10868.pdf), [code](https://github.com/ML-CAD/AppGNN)

    *Tim Bucher, Lilas Alrahis, Guilherme Paim, Sergio Bampi, Ozgur Sinanoglu, Hussam Amrouch.*


### [Hardware Trojan Detection](#content)

### [IP Piracy Detection](#content)

## [GNNs for Reliable Hardware](#content)
- **GNN4REL: Graph Neural Networks for Predicting Circuit Reliability Degradation.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2022. [paper](https://ieeexplore.ieee.org/document/9852805), [code](https://github.com/lilasrahis/GNN4REL)

    *Lilas Alrahis, Johann Knechtel, Florian Klemme, Hussam Amrouch, Ozgur Sinanoglu.*

- **Analog IC Aging-induced Degradation Estimation via Heterogeneous Graph Convolutional Networks.** Asia and South Pacific Design Automation Conference (ASP-DAC), 2021. [paper](https://ieeexplore.ieee.org/document/9371619)

    *Tinghuan Chen, Qi Sun, Canhui Zhan, Changze Liu, Huatao Yu, Bei Yu.*

- **Deep H-GCN: Fast Analog IC Aging-Induced Degradation Estimation.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2022. [paper](https://ieeexplore.ieee.org/document/9521579)

    *Tinghuan Chen, Qi Sun, Canhui Zhan, Changze Liu, Huatao Yu, Bei Yu.*

