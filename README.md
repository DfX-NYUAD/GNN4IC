# GNN4IC
Must-read papers on Graph Neural Networks (GNNs) for Integrated Circuits (ICs) design, security and reliability. This collection of papers is summarized in the following survey paper; L. Alrahis et al. "Graph Neural Networks: A Powerful and Versatile Tool for Advancing Design, Reliability, and Security of ICs," ASP-DAC, 2023.

Contributed by Lilas Alrahis, Johann Knechtel, and Ziad El Sayed.

Please note, the following list is just a collection of papers in no particular order.
## [Content](#content)
<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey Papers</a></td></tr> 
<tr><td colspan="2"><a href="#gnns-for-eda">2. GNNs for EDA</a></td></tr>
<tr>
    <td>&ensp;<a href="#behavioral-and-logic-design">2.1 Behavioral and Logic Design</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#logic-synthesis">2.2 Logic Synthesis</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#timing-closure">2.3 Timing Closure</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#partitioning-and-floorplanning">2.4 Partitioning and Floorplanning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#placement-and-routing">2.5 Placement and Routing</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#verification-and-testing">2.6 Verification and Testing</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#analog-mixed-signal-and-transistor-design">2.7 Analog, Mixed Signal, and Transistor Design</a></td>
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

## [Survey Papers](#content)
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

- **Why are Graph Neural Networks Effective for EDA Problems? (Invited Paper).** IEEE/ACM International Conference On Computer Aided Design (ICCAD) , 2022.0. [paper](https://dl.acm.org/doi/abs/10.1145/3508352.3561093)

    *Haoxing Ren, Siddhartha Nath, Yanqing Zhang, Hao Chen, Mingjie Liu.*

- **On Advancing Physical Design using Graph Neural Networks  (Invited Paper).** IEEE/ACM International Conference On Computer Aided Design (ICCAD) , 2022.0. [paper](https://gtcad.gatech.edu/www/papers/Yi-Chen-ICCAD22.pdf)

    *Yi-Chen Lu, Sung Kyu Lim.*

- **High-Level Synthesis Performance Prediction using GNNs: Benchmarking, Modeling, and Advancing.** ACM/IEEE Design Automation Conference (DAC), 2022.0. [paper](https://dl.acm.org/doi/abs/10.1145/3489517.3530408)

  *Nan Wu, Hang Yang, Yuan Xie, Pan Li, Cong Hao.*

## [GNNs for EDA](#content)
### [Behavioral and Logic Design](#content)
- **Applying GNNs to Timing Estimation at RTL (Invited Paper).** IEEE/ACM International Conference on Computer-Aided Design (ICCAD), 2022. [paper](https://dl.acm.org/doi/10.1145/3508352.3561095)

  	*Daniela Sánchez Lopera, Wolfgang Ecker.*
  
- **Accurate Operation Delay Prediction for FPGA HLS Using Graph Neural Networks.** IEEE/ACM International Conference on Computer-Aided Design (ICCAD), 2020. [paper](https://dl.acm.org/doi/10.1145/3400302.3415657)

  	*Ecenur Ustun, Chenhui Deng, Debjit Pal, Zhijing Li, Zhiru Zhang.*

- **IRONMAN: GNN-assisted Design Space Exploration in High-Level Synthesis via Reinforcement Learning.** Proceedings of the 2021 Great Lakes Symposium on VLSI (GLSVLSI), 2021. [paper](https://dl.acm.org/doi/10.1145/3453688.3461495)

  	*Nan Wu, Yuan Xie, Cong Hao.*
 
- **IronMan-Pro: Multiobjective Design Space Exploration in HLS via Reinforcement Learning and Graph Neural Network-Based Modeling.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, March 2023. [paper](https://ieeexplore.ieee.org/document/9803218), [code](https://github.com/lydiawunan/IronMan)

  	*Nan Wu, Yuan Xie, Cong Hao.*


### [Logic Synthesis](#content)

- **Heterogeneous Graph Neural Network-Based Imitation Learning for Gate Sizing Acceleration.** Proceedings of the 41st IEEE/ACM International Conference on Computer-Aided Design (ICCAD), 2022. [paper](https://dl.acm.org/doi/10.1145/3508352.3549361)
 
	*Xinyi Zhou, Junjie Ye, Chak-Wa Pui, Kun Shao, Guangliang Zhang, Bin Wang, Jianye Hao, Guangyong Chen, Pheng Ann Heng.*
 
- **CongestionNet: Routing Congestion Prediction Using Deep Graph Neural Networks.** IFIP/IEEE 27th International Conference on Very Large Scale Integration (VLSI-SoC), 2019. [paper](https://ieeexplore.ieee.org/document/8920342)
 
	*Robert Kirby, Saad Godil, Rajarshi Roy, Bryan Catanzaro.*
 
- **Generalizable Cross-Graph Embedding for GNN-based Congestion Prediction.** IEEE/ACM International Conference On Computer Aided Design (ICCAD), 2021. [paper](https://ieeexplore.ieee.org/document/9643446)
 
	*Amur Ghose, Vincent Zhang, Yingxue Zhang, Dong Li, Wulong Liu, Mark Coates.*

### [Timing Closure](#content)
- **RL-Sizer: VLSI Gate Sizing for Timing Optimization using Deep Reinforcement Learning.** 58th ACM/IEEE Design Automation Conference (DAC), 2021. [paper](https://ieeexplore.ieee.org/document/9586138)
 
	*Yi-Chen Lu, Siddhartha Nath, Vishal Khandelwal, Sung Kyu Lim.*
  
- **Doomed Run Prediction in Physical Design by Exploiting Sequential Flow and Graph Learning.** IEEE/ACM International Conference On Computer Aided Design (ICCAD), 2021. [paper](https://ieeexplore.ieee.org/abstract/document/9643435/)
 
	*Yi-Chen Lu, Siddhartha Nath, Vishal Khandelwal, Sung Kyu Lim.*

### [Partitioning and Floorplanning](#content)
- **TP-GNN: A Graph Neural Network Framework for Tier Partitioning in Monolithic 3D ICs.** 57th ACM/IEEE Design Automation Conference (DAC), 2020. [paper](https://ieeexplore.ieee.org/document/9218582)
 
	*Yi-Chen Lu, Sai Surya Kiran Pentapati, Lingjun Zhu, Kambiz Samadi, Sung Kyu Lim.*
  
- **A graph placement methodology for fast chip design.** Nature, 2021. [paper](https://www.nature.com/articles/s41586-021-03544-w), [code](https://github.com/google-research/circuit_training)
 
	*Azalia Mirhoseini, Anna Goldie, Mustafa Yazgan, Joe Wenjie Jiang, Ebrahim Songhori, Shen Wang, Young-Joon Lee, Eric Johnson, Omkar Pathak, Azade Nazi, Jiwoo Pak, Andy Tong, Kavya Srinivasa, William Hang, Emre Tuncer, Quoc V. Le, James Laudon, Richard Ho, Roger Carpenter, Jeff Dean.*

### [Placement and Routing](#content)
- **Net2: A Graph Attention Network Method Customized for Pre-Placement Net Length Estimation.** Proceedings of the 26th Asia and South Pacific Design Automation Conference (ASPDAC), 2021. [paper](https://dl.acm.org/doi/10.1145/3394885.3431562)
 
	*Zhiyao Xie, Rongjian Liang, Xiaoqing Xu, Jiang Hu, Yixiao Duan, Yiran Chen.*

- **The Law of Attraction: Affinity-Aware Placement Optimization using Graph Neural Networks.** Proceedings of the 2021 International Symposium on Physical Design (ISPD), 2021. [paper](https://dl.acm.org/doi/10.1145/3439706.3447045)
 
	*Yi-Chen Lu, Sai Pentapati, Sung Kyu Lim.*
- **VLSI placement parameter optimization using deep reinforcement learning.** Proceedings of the 39th International Conference on Computer-Aided Design (ICCAD), 2020. [paper](https://dl.acm.org/doi/10.1145/3400302.3415690)
 
	*Anthony Agnesina, Kyungwook Chang, Sung Kyu Lim.*
 
- **A timing engine inspired graph neural network model for pre-routing slack prediction.** Proceedings of the 59th ACM/IEEE Design Automation Conference (DAC), 2022. [paper](https://dl.acm.org/doi/10.1145/3489517.3530597), [code](https://github.com/TimingPredict/TimingPredict)
   
   	*Zizheng Guo, Mingjie Liu, Jiaqi Gu, Shuhan Zhang, David Z. Pan, Yibo Lin.*
  
- **On Joint Learning for Solving Placement and Routing in Chip Design.** Neural Information Processing Systems (NeurIPS), 2021. [paper](https://arxiv.org/abs/2111.00234), [code](https://github.com/Thinklab-SJTU/EDA-AI)
   
   	*Ruoyu Cheng, Junchi Yan.*

### [Verification and Testing](#content)

- **GRANNITE: Graph Neural Network Inference for Transferable Power Estimation.** 57th ACM/IEEE Design Automation Conference (DAC), 2020. [paper](https://ieeexplore.ieee.org/document/9218643)
 
	*Yanqing Zhang, Haoxing Ren, Brucek Khailany.*
 
- **High Performance Graph Convolutional Networks with Applications in Testability Analysis.** 56th ACM/IEEE Design Automation Conference (DAC), 2019. [paper](https://ieeexplore.ieee.org/document/8807085)
 
	*Yuzhe Ma, Haoxing Ren, Brucek Khailany, Harbinder Sikka, Lijuan Luo, Karthikeyan Natarajan, Bei Yu.*


### [Analog, Mixed Signal, and Transistor Design](#content)

- **Parasitic-Aware Analog Circuit Sizing with Graph Neural Networks and Bayesian Optimization.** Design, Automation & Test in Europe Conference & Exhibition, 2021. [paper](https://ieeexplore.ieee.org/document/9474253)
 
	*Mingjie Liu, Walker J. Turner, George F. Kokai, Brucek Khailany, David Z. Pan, Haoxing Ren.*
 
- **ParaGraph: Layout Parasitics and Device Parameter Prediction using Graph Neural Networks.** 57th ACM/IEEE Design Automation Conference (DAC), 2020. [paper](https://ieeexplore.ieee.org/document/9218515)
 
	*Haoxing Ren, George F. Kokai, Walker J. Turner, Ting-Sheng Ku.*
 
- **Circuit-GNN: Graph Neural Networks for Distributed Circuit Design.** Proceedings of the 36th International Conference on Machine Learning (ICML), 2019. [paper](https://proceedings.mlr.press/v97/zhang19e.html), [code](https://github.com/hehaodele/circuit-gnn)
   
   	*Guo Zhang, Hao He, Dina Katabi.*
 
- **GCN-RL circuit designer: transferable transistor sizing with graph neural networks and reinforcement learning.** Proceedings of the 57th ACM/EDAC/IEEE Design Automation Conference (DAC), 2020. [paper](https://dl.acm.org/doi/10.5555/3437539.3437740)
 
	*Hanrui Wang, Kuan Wang, Jiacheng Yang, Linxiao Shen, Nan Sun, Hae-Seung Lee, Song Han.*
  
## [GNNs for Hardware Security](#content)

### [Attack on Logic Obfuscation](#content)

- **Estimating the circuit de-obfuscation runtime based on graph deep learning.** In 2020 Design, Automation & Test in Europe Conference & Exhibition, 2020. [paper](https://ieeexplore.ieee.org/document/9116544)

    *Zhiqian Chen, Gaurav Kolhe, Setareh Rafatirad, Chang-Tien Lu, Sai Manoj P.D., Houman Homayoun, Liang Zhao.*

- **GNNUnlock: Graph Neural Networks-based Oracle-less Unlocking Scheme for Provably Secure Logic Locking.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2021. [paper](https://ieeexplore.ieee.org/document/9474039), [code](https://github.com/DfX-NYUAD/GNNUnlock)

    *Lilas Alrahis, Satwik Patnaik, Faiq Khalid, Muhammad Abdullah Hanif, Hani Saleh, Muhammad Shafique, Ozgur Sinanoglu.*

- **GNNUnlock+: A Systematic Methodology for Designing Graph Neural Networks-Based Oracle-Less Unlocking Schemes for Provably Secure Logic Locking.** IEEE Transactions on Emerging Topics in Computing, 2021. [paper](https://ieeexplore.ieee.org/document/9529342), [code](https://github.com/DfX-NYUAD/GNNUnlock)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Abdullah Hanif, Hani Saleh, Muhammad Shafique, Ozgur Sinanoglu.*

- **OMLA: An Oracle-Less Machine Learning-Based Attack on Logic Locking.** IEEE Transactions on Circuits and Systems II: Express Briefs, 2021. [paper](https://ieeexplore.ieee.org/document/9539868), [code](https://github.com/DfX-NYUAD/OMLA)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Shafique, Ozgur Sinanoglu.*

- **MuxLink: Circumventing Learning-Resilient MUX-Locking Using Graph Neural Network-based Link Prediction.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2022. [paper](https://ieeexplore.ieee.org/document/9774603), [code](https://github.com/lilasrahis/MuxLink)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Shafique, Ozgur Sinanoglu.*

- **UNTANGLE: Unlocking Routing and Logic Obfuscation Using Graph Neural Networks-based Link Prediction.** IEEE/ACM International Conference On Computer Aided Design (ICCAD), 2021. [paper](https://ieeexplore.ieee.org/document/9643476), [code](https://github.com/lilasrahis/UNTANGLE)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Abdullah Hanif, Muhammad Shafique, Ozgur Sinanoglu.*

- **Titan: Security Analysis of Large-Scale Hardware Obfuscation Using Graph Neural Networks.** IEEE Transactions on Information Forensics and Security, 2022. [paper](https://ieeexplore.ieee.org/abstract/document/9933482), [code](https://github.com/DfX-NYUAD/Titan)

    *Likhitha Mankali, Lilas Alrahis, Satwik Patnaik, Johann Knechtel, Ozgur Sinanoglu.*
  
### [Reverse Engineering](#content)

- **Graph Learning-Based Arithmetic Block Identification.** In 2021 IEEE/ACM International Conference On Computer Aided Design (ICCAD), 2021. [paper](https://ieeexplore.ieee.org/document/9643581)

    *Zhuolun He, Ziyi Wang, Chen Bai, Haoyu Yang, Bei Yu.*

- **Graph Neural Network based Netlist Operator Detection under Circuit Rewriting.** In Proceedings of the Great Lakes Symposium on VLSI 2022 (GLSVLSI '22), 2022. [paper](https://dl.acm.org/doi/10.1145/3526241.3530330)

    *Guangwei Zhao, Kaveh Shamsi.*

- **Functionality matters in netlist representation learning.** In Proceedings of the 59th ACM/IEEE Design Automation Conference (DAC '22), 2022. [paper](https://dl.acm.org/doi/abs/10.1145/3489517.3530410)

    *Ziyi Wang, Chen Bai, Zhuolun He, Guangliang Zhang, Qiang Xu, Tsung-Yi Ho, Bei Yu, Yu Huang.*

- **ReIGNN: State register identification using graph neural networks for circuit reverse engineering.** In 2021 IEEE/ACM International Conference On Computer Aided Design (ICCAD), 2021. [paper](https://arxiv.org/abs/2112.00806)

    *Subhajit Dutta Chowdhury, Kaixin Yang, Pierluigi Nuzzo.*

- **GNN-RE: Graph Neural Networks for Reverse Engineering of Gate-Level Netlists.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2021. [paper](https://ieeexplore.ieee.org/document/9530566), [code](https://github.com/DfX-NYUAD/GNN-RE)

    *Lilas Alrahis, Abhrajit Sengupta, Johann Knechtel, Satwik Patnaik, Hani Saleh, Baker Mohammad, Mahmoud Al-Qutayri, Ozgur Sinanoglu.*

- **AppGNN: Approximation-Aware Functional Reverse Engineering using Graph Neural Networks.** IEEE/ACM International Conference On Computer Aided Design (ICCAD), 2022. [paper](https://arxiv.org/pdf/2208.10868.pdf), [code](https://github.com/ML-CAD/AppGNN)

    *Tim Bucher, Lilas Alrahis, Guilherme Paim, Sergio Bampi, Ozgur Sinanoglu, Hussam Amrouch.*


### [Hardware Trojan Detection](#content)
- **Graph Neural Network based Hardware Trojan Detection at Intermediate Representative for SoC Platforms.** In Proceedings of the Great Lakes Symposium on VLSI 2022 (GLSVLSI '22), 2022. [paper](https://dl.acm.org/doi/10.1145/3526241.3530827)

    *Weimin Fu, Honggang Yu, Orlando Arias, Kaichen Yang, Yier Jin, Tuba Yavuz, Xiaolong Guo.*

### [IP Piracy Detection](#content)

- **GNN4IP: Graph Neural Network for Hardware Intellectual Property Piracy Detection.** In 2021 58th ACM/IEEE Design Automation Conference (DAC), 2021. [paper](https://ieeexplore.ieee.org/document/9586150)

    *Rozhin Yasaei, Shih-Yuan Yu, Emad Kasaeyan Naeini, Mohammad Abdullah Al Faruque.*


## [GNNs for Reliable Hardware](#content)
- **GNN4REL: Graph Neural Networks for Predicting Circuit Reliability Degradation.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2022. [paper](https://ieeexplore.ieee.org/document/9852805), [code](https://github.com/lilasrahis/GNN4REL)

    *Lilas Alrahis, Johann Knechtel, Florian Klemme, Hussam Amrouch, Ozgur Sinanoglu.*

- **Analog IC Aging-induced Degradation Estimation via Heterogeneous Graph Convolutional Networks.** Asia and South Pacific Design Automation Conference (ASP-DAC), 2021. [paper](https://ieeexplore.ieee.org/document/9371619)

    *Tinghuan Chen, Qi Sun, Canhui Zhan, Changze Liu, Huatao Yu, Bei Yu.*

- **Deep H-GCN: Fast Analog IC Aging-Induced Degradation Estimation.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2022. [paper](https://ieeexplore.ieee.org/document/9521579)

    *Tinghuan Chen, Qi Sun, Canhui Zhan, Changze Liu, Huatao Yu, Bei Yu.*
