# GNN4IC
Must-read papers on Graph Neural Networks (GNNs) for Integrated Circuits (ICs) design, security and reliability.

Contributed by Lilas Alrahis, Johann Knechtel, and Ziad El Sayed.

Please note, the following list is just a collection of papers in no particular order.

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#common-datasets--benchmarks">0. Common Datasets/Benchmarks</a></td></tr>
<tr><td colspan="2"><a href="#gnns-for-eda">1. GNNs for EDA</a></td></tr>
<tr>
    <td>&ensp;<a href="#behavioral-and-logic-design">1.1 Behavioral and Logic Design</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#logic-synthesis">1.2 Logic Synthesis</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#partitioning-and-floorplanning">1.3 Partitioning and Floorplanning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#placement-and-routing">1.4 Placement and Routing</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#timing-closure">1.5 Timing Closure</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#verification-and-testing">1.6 Verification and Testing</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#analog-mixed-signal-and-transistor-design">1.7 Analog, Mixed Signal, and Transistor Design</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#circuit-design-completion">1.8 Circuit Design Completion</a></td>
</tr>
<tr><td colspan="2"><a href="#gnns-for-hardware-reliability">2. GNNs for Hardware Reliability</a></td></tr>
<tr>
    <td>&ensp;<a href="#aging-delay-prediction">2.1 Aging Delay Prediction</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#functional-de-rating-prediction">2.2 Functional De-Rating Prediction</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#critical-component-identification">2.3 Critical Component Identification</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#fault-diagnosis-and-evaluation">2.4 Fault Diagnosis and Evaluation</a></td>
</tr>
<tr><td colspan="2"><a href="#gnns-for-hardware-security">3. GNNs for Hardware Security</a></td></tr>
<tr>
    <td>&ensp;<a href="#ht-detection">3.1 HT Detection</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#piracy-detection">3.2 Piracy Detection</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#functional-reverse-engineering">3.3 Functional Reverse Engineering</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#attacks-on-design-for-trust-methods">3.4 Attacks on Design-for-Trust Methods</a></td>
</tr>
<tr>
    <td>&ensp;&ensp;<a href="#key-leakage">3.4.1 Key Leakage</a></td>
</tr>
<tr>
    <td>&ensp;&ensp;<a href="#link-formation">3.4.2 Link Formation</a></td>
</tr>
<tr>
    <td>&ensp;&ensp;<a href="#structural-leakage">3.4.3 Structural Leakage</a></td>
</tr>
<tr>
    <td>&ensp;&ensp;<a href="#attack-scalability">3.4.4 Attack Scalability</a></td>
</tr>
<tr>
    <td>&ensp;&ensp;<a href="#attack-sensitivity">3.4.5 Attack Sensitivity</a></td>
</tr>
</table>

## [Common Datasets & Benchmarks](#content)
* I99T obfuscation benchmarks: large obfuscated netlists for logic locking and split-manufacturing research. Official repository: [https://github.com/cad-polito-it/I99T](https://github.com/cad-polito-it/I99T)
* EPFL combinational benchmark suite: 23 combinational circuits designed to challenge logic optimization tools across arithmetic, random/control and MtM categories. Official site: [https://www.epfl.ch/labs/lsi/page-102566-en-html/benchmarks/](https://www.epfl.ch/labs/lsi/page-102566-en-html/benchmarks/)
* TrustHub hardware Trojan benchmarks: collection of infected and golden circuits for Trojan detection and localization. Official site: [https://trust-hub.org/](https://trust-hub.org/)

## [GNNs for EDA](#content)
### [Behavioral and Logic Design](#content)
- **IronMan-Pro: Multiobjective Design Space Exploration in HLS via Reinforcement Learning and Graph Neural Network-Based Modeling.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2022. [paper](https://ieeexplore.ieee.org/document/9803218). [code](https://github.com/lydiawunan/IronMan). [dataset](https://github.com/lydiawunan/IronMan/tree/main/DATASET).

    *Nan Wu, Yuan Xie, Cong Hao.*
  
- **IronMan: GNN-assisted Design Space Exploration in High-Level Synthesis via Reinforcement Learning.** Great Lakes Symposium on VLSI (GLVLSI), 2021. [paper](https://dl.acm.org/doi/10.1145/3453688.3461495). [code](https://github.com/lydiawunan/IronMan). [dataset](https://github.com/lydiawunan/IronMan/tree/main/DATASET).

    *Nan Wu, Yuan Xie, Cong Hao.*

- **Graph Neural Networks for High-Level Synthesis Design Space Exploration.** ACM Transactions on Design Automation of Electronic Systems, 2022. [paper](https://dl.acm.org/doi/10.1145/3570925)

    *Lorenzo Ferretti, Andrea Cini, Georgios Zacharopoulos, Cesare Alippi, Laura Pozzi.* 

- **Accurate Operation Delay Prediction for FPGA HLS Using Graph Neural Networks.** International Conference on Computer-Aided Design (ICCAD), 2020. [paper](https://ieeexplore.ieee.org/document/9256462)

    *Ecenur Ustun, Chenhui Deng, Debjit Pal, Zhijing Li, Zhiru Zhang.* 

- **Applying GNNs to Timing Estimation at RTL (Invited Paper).** International Conference on Computer-Aided Design (ICCAD), 2022. [paper](https://ieeexplore.ieee.org/document/10069111/)

    *Daniela Sánchez Lopera, Wolfgang Ecker.* 

- **DeepGate: Learning Neural Representations of Logic Gates.** Proceedings of the 59th ACM/IEEE Design Automation Conference (DAC), 2022. [paper](https://dl.acm.org/doi/10.1145/3489517.3530497). [code.](https://github.com/cure-lab/DeepGate) [dataset.](https://github.com/cure-lab/DeepGate/blob/main/DATASETS.md)

    *Min Li, Sadaf Khan, Zhengyuan Shi, Naixing Wang, Huang Yu, Qiang Xu.* 

- **DeepSeq: Deep Sequential Circuit Learning.** IEEE, 2023. [paper](https://ieeexplore.ieee.org/document/10546639)

    *Sadaf Khan, Zhengyuan Shi, Min Li, Qiang Xu.*

- **Versatile Multi-Stage Graph Neural Network for Circuit Representation.** Advances in Neural Information Processing Systems (NeurIPS), 2022. [paper.](https://proceedings.neurips.cc/paper_files/paper/2022/file/7fa548155f40c014372146be387c4f6a-Paper-Conference.pdf) [code.](https://github.com/PKUterran/NetlistGNN) [dataset 1.](https://www.ispd.cc/contests/11/ispd2011_contest.html) [dataset 2.](https://archive.sigda.org/dac2012/contest/dac2012_contest_benchmarks.html)

    *Shuwen Yang, Zhihao Yang, Dong Li, Yingxue Zhang, Zhanguang Zhang, Guojie Song, Jianye Hao.* 

### [Logic Synthesis](#content)
- **CongestionNet: Routing Congestion Prediction Using Deep Graph Neural Networks.** VLSI-SoC, 2019. [paper](https://ieeexplore.ieee.org/document/8920342)

    *Robert Kirby, Saad Godil, Rajarshi Roy, Bryan Catanzaro.* 

- **Generalizable Cross-Graph Embedding for GNN-based Congestion Prediction.** International Conference on Computer-Aided Design (ICCAD), 2021. [paper](https://dl.acm.org/doi/10.1109/ICCAD51958.2021.9643446)

    *Amur Ghose, Vincent Zhang, Yingxue Zhang, Dong Li, Wulong Liu, Mark Coates.* 

- **Heterogeneous Graph Neural Network-based Imitation Learning for Gate Sizing Acceleration.** International Conference on Computer-Aided Design (ICCAD), 2022. [paper](https://ieeexplore.ieee.org/document/10069687)

    *Xinyi Zhou, Junjie Ye, Chak-Wa Pui, Kun Shao, Guangliang Zhang, Bin Wang, Jianye Hao, Guangyong Chen, Pheng Ann Heng.* 

- **LOSTIN: Logic Optimization via Spatio-Temporal Information with Hybrid Graph Models.** Application-Specific Systems, Architectures and Processors (ASAP), 2022. [paper.](https://ieeexplore.ieee.org/document/9912015) [code.](https://github.com/sharc-lab/LOSTIN) [dataset.](https://github.com/lsils/benchmarks)

    *Nan Wu, Jiwon Lee, Yuan Xie, Cong Hao.* 

- **Delay Prediction for ASIC HLS: Comparing Graph-Based and Nongraph-Based Learning Models.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2023. [paper](https://ieeexplore.ieee.org/document/9854193/)

    *Sayandip De, Muhammad Shafique, Henk Corporaal.* 

- **BoolGebra: Attributed Graph-Learning for Boolean Algebraic Manipulation.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2024. [paper](https://ieeexplore.ieee.org/document/10546512/)

    *Yingjie Li, Anthony Agnesina, Yanqing Zhang, Haoxing Ren, Cunxi Yu.* 

### [Partitioning and Floorplanning](#content)
- **TP-GNN: A Graph Neural Network Framework for Tier Partitioning in Monolithic 3D ICs.** Design Automation Conference (DAC), 2020. [paper](https://ieeexplore.ieee.org/document/9218582)

    *Yi-Chen Lu, Sai Surya Kiran Pentapati, Lingjun Zhu, Kambiz Samadi, Sung Kyu Lim.* 

- **A Graph Placement Methodology for Fast Chip Design.** Nature, 2021. [paper.](https://www.nature.com/articles/s41586-021-03544-w) [code.](https://github.com/google-research/circuit_training)

    *Azalia Mirhoseini, Anna Goldie, Mustafa Yazgan, Joe Wenjie Jiang, Ebrahim Songhori, Shen Wang, Young-Joon Lee, Eric Johnson, Omkar Pathak, Azade Nova, Jiwoo Pak, Andy Tong, Kavya Srinivasa, William Hang, Emre Tuncer, Quoc V. Le, James Laudon, Richard Ho, Roger Carpenter, Jeff Dean.* 

- **GraphPlanner: Floorplanning with Graph Neural Network.** ACM Transactions on Design Automation of Electronic Systems (TODAES), 2022. [paper](https://dl.acm.org/doi/10.1145/3555804)

    *Yiting Liu, Ziyi Ju, Zhengming Li, Mingzhi Dong, Hai Zhou, Jia Wang, Fan Yang, Xuan Zeng, Li Shang.* 

- **GraphClusNet: A Hierarchical Graph Neural Network for Recovered Circuit Netlist Partitioning.** IEEE Transactions on Artificial Intelligence, 2023. [paper.](https://ieeexplore.ieee.org/document/9858021/) [code.](https://github.com/hongxuenong/GraphClusNet) [dataset 1.](https://opencores.org/projects/8051) [dataset 2.](https://github.com/stnolting/neorv32) [dataset 3.](https://opencores.org/projects/aoocs) [dataset 4.](https://opencores.org/projects/openfpu64)

  *Xuenong Hong, Tong Lin, Yiqiong Shi, Bah Hwee Gwee.*

- **DeepTH: Chip Placement with Deep Reinforcement Learning Using a Three-Head Policy Network.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2023. [paper.](https://ieeexplore.ieee.org/document/10137100) [code.](https://github.com/CMACH508/DeepTH) [dataset 1.](https://pan.baidu.com/s/1uDlRzpX209Kw3FjESCtzyA?pwd=feb0) [dataset 2.](https://www.ispd.cc/contests/05/contest.htm)
  
  *Dengwei Zhao, Shuai Yuan, Yanan Sun, Shikui Tu, Lei Xu.*

### [Placement and Routing](#content)

- **Net2: A Graph Attention Network Method Customized for Pre-Placement Net Length Estimation.** Asia and South Pacific Design Automation Conference (ASP-DAC), 2021. [paper](https://dl.acm.org/doi/10.1145/3394885.3431562)

    *Zhiyao Xie, Rongjian Liang, Xiaoqing Xu, Jiang Hu, Yixiao Duan, Yiran Chen.* 

- **VLSI Placement Optimization using Graph Neural Networks.** Advances in Neural Information Processing Systems (NeurIPS), 2020. [paper](https://mlforsystems.org/assets/papers/neurips2020/vlsi_placement_lu_2020.pdf)

    *Yi-Chen Lu, Sai Pentapati, Sung Kyu Lim.* 

- **The Law of Attraction: Affinity-Aware Placement Optimization using Graph Neural Networks.** International Symposium on Physical Design (ISPD), 2021. [paper](https://dl.acm.org/doi/10.1145/3439706.3447045)

    *Yi-Chen Lu, Sai Pentapati, Sung Kyu Lim.* 

- **VLSI Placement Parameter Optimization using Deep Reinforcement Learning.** International Conference on Computer-Aided Design (ICCAD), 2020. [paper](https://ieeexplore.ieee.org/document/9256814)

    *Anthony Agnesina, Kyungwook Chang, Sung Kyu Lim.* 

- **A General Framework for VLSI Tool Parameter Optimization with Deep Reinforcement Learning.** Advances in Neural Information Processing Systems (NeurIPS), 2020. [paper](https://mlforsystems.org/assets/papers/neurips2020/a_general_agnesina_2020.pdf)

    *Anthony Agnesina, Sai Pentapati, Sung Kyu Lim.* 

- **A Timing Engine Inspired Graph Neural Network Model for Pre-Routing Slack Prediction.** Design Automation Conference (DAC), 2022. [paper.](https://dl.acm.org/doi/10.1145/3489517.3530597) [code.](https://github.com/TimingPredict/TimingPredict) [dataset.](https://github.com/TimingPredict/Dataset)

    *Zizheng Guo, Mingjie Liu, Jiaqi Gu, Shuhan Zhang, David Z. Pan, Yibo Lin.*

- **Pin Accessibility and Routing Congestion Aware DRC Hotspot Prediction Using Graph Neural Network and U-Net.** International Conference on Computer-Aided Design (ICCAD), 2022. [paper](https://dl.acm.org/doi/10.1145/3508352.3549346)

    *Kyeonghyeon Baek, Hyunbum Park, Suwan Kim, Kyumyung Choi, Taewhan Kim.* 

- **On Joint Learning for Solving Placement and Routing in Chip Design.** Advances in Neural Information Processing Systems (NeurIPS), 2021. [paper.](https://proceedings.neurips.cc/paper/2021/file/898aef0932f6aaecda27aba8e9903991-Paper.pdf) [code.](https://github.com/Thinklab-SJTU/EDA-AI/tree/main/DeepPlace) [dataset.](https://www.ispd.cc/contests/05/contest.htm)

    *Ruoyu Cheng, Junchi Yan.*

- **A Learning-Based Algorithm for Early Floorplan With Flexible Blocks.** IEEE Asian Solid-State Circuits Conference (A-SSCC), 2022. [paper](https://ieeexplore.ieee.org/document/9980637)

    *Jen-Wei Lee, Yi-Ying Liao, Te-Wei Chen, Yu-Hsiu Lin, Chia-Wei Chen, Chun-Ku Ting, Sheng-Tai Tseng, Ronald Kuo-Hua Ho, Hsin-Chuan Kuo, Chun-Chieh Wang, Ming-Fang Tsai, Chun-Chih Yang, Tai-Lai Tung, Da-Shan Shiu.* 

- **Detailed Routing Short Violation Prediction Using Graph-Based Deep Learning Model.** IEEE Transactions on Circuits and Systems II: Express Briefs, 2022. [paper](https://ieeexplore.ieee.org/document/9467312)

    *X. Chen, Z. Di, W. Wu, Q. Wu, J. Shi, Q. Feng.* 

- **Reinforcement Learning Guided Detailed Routing for Custom Circuits.** International Symposium on Physical Design (ISPD), 2023. [paper](https://dl.acm.org/doi/10.1145/3569052.3571874)

    *Hao Chen, Kai-Chieh Hsu, Walker J. Turner, Po-Hsuan Wei, Keren Zhu, David Z. Pan, Haoxing Ren.* 

### [Timing Closure](#content)
- **RL-Sizer: VLSI Gate Sizing for Timing Optimization using Deep Reinforcement Learning.** Design Automation Conference (DAC), 2021. [paper](https://ieeexplore.ieee.org/document/9586138)

    *Yi-Chen Lu, Siddhartha Nath, Vishal Khandelwal, Sung Kyu Lim.* 

- **Doomed Run Prediction in Physical Design by Exploiting Sequential Flow and Graph Learning.** International Conference on Computer-Aided Design (ICCAD), 2021. [paper](https://ieeexplore.ieee.org/document/9643435)

    *Yi-Chen Lu, Siddhartha Nath, Vishal Khandelwal, Sung Kyu Lim.* 

- **Graph-Learning-Driven Path-Based Timing Analysis Results Predictor from Graph-Based Timing Analysis.** Asia and South Pacific Design Automation Conference (ASP-DAC), 2023. [paper](https://ieeexplore.ieee.org/document/10044841)

    *Yuyang Ye, Tinghuan Chen, Yifei Gao, Hao Yan, Bei Yu, Longxing Shi.* 

- **SyncTREE: Fast Timing Analysis for Integrated Circuit Design through a Physics-Informed Tree-Based Graph Neural Network.** Advances in Neural Information Processing Systems (NeurIPS), 2024. [paper.](https://proceedings.neurips.cc/paper_files/paper/2023/file/435e8fbbfc2c6072d4f3a5cb6e56a39a-Paper-Conference.pdf) [code.](https://github.com/xlab-ub/SyncTree) [dataset 1.](https://drive.google.com/file/d/1TEux9yTVc2--zC-__4qbd2MJQJdSGzof/view?usp=drive_link) [dataset 2.](https://drive.google.com/file/d/1S4g8cYjFqOTxjGYRjzYCJIor5_4Bvlss/view?usp=sharing)

    *Yuting Hu, Jiajie Li, Florian Klemme, Gi-Joon Nam, Tengfei Ma, Hussam Amrouch, Jinjun Xiong.*

### [Verification and Testing](#content)

- **GRANNITE: Graph Neural Network Inference for Transferable Power Estimation.** Design Automation Conference (DAC), 2020. [paper](https://ieeexplore.ieee.org/document/9218643)

    *Yanqing Zhang, Haoxing Ren, Brucek Khailany.* 

- **High Performance Graph Convolutional Networks with Applications in Testability Analysis.** Design Automation Conference (DAC), 2019. [paper](https://ieeexplore.ieee.org/document/8807085)

    *Y. Ma, H. Ren, B. Khailany, H. Sikka, L. Luo, K. Natarajan, B. Yu.* 

- **DeepTPI: Test Point Insertion with Deep Reinforcement Learning.** IEEE International Test Conference (ITC), 2022. [paper.](https://ieeexplore.ieee.org/abstract/document/9983950) [code.](https://github.com/zshi0616/DeepTPI) [dataset.](https://github.com/zshi0616/DeepTPI/tree/main/data/ITC22_dataset)

    *Zhengyuan Shi, Min Li, Sadaf Khan, Liuzheng Wang, Naixing Wang, Yu Huang.*

- **RC-GNN: Fast and Accurate Signoff Wire Delay Estimation with Customized Graph Neural Networks.** IEEE 5th International Conference on Artificial Intelligence Circuits and Systems (AICAS), 2023. [paper](https://ieeexplore.ieee.org/document/10168562/)

    *Linyu Zhu, Yue Gu, Xinfei Guo.* 

- **Transferable Graph Neural Network-Based Delay-Fault Localization for Monolithic 3-D ICs.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2023. [paper](https://ieeexplore.ieee.org/document/10123099)

    *Shao-Chun Hung, Sanmitra Banerjee, Arjun Chaudhuri, Jinwoo Kim, Sung Kyu Lim, Krishnendu Chakrabarty.* 

- **GRAND: A Graph Neural Network Framework for Improved Diagnosis.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2024. [paper](https://ieeexplore.ieee.org/document/10328653/)

    *Hongfei Wang, Ziqiang Zhang, Hongcan Xiong, Dongmian Zou, Yu Chen, Hai Jin.* 

### [Analog, Mixed Signal, and Transistor Design](#content)
- **Circuit-GNN: Graph Neural Networks for Distributed Circuit Design.** International Conference on Machine Learning (ICML), 2019. [paper.](https://proceedings.mlr.press/v97/zhang19e.html) [code.](https://github.com/hehaodele/circuit-gnn) [dataset.](http://circuit-gnn.csail.mit.edu/data.zip)
  
  *Guo Zhang, Hao He, Dina Katabi.*

- **ParaGraph: Layout Parasitics and Device Parameter Prediction using Graph Neural Networks.** Design Automation Conference (DAC), 2020. [paper](https://ieeexplore.ieee.org/document/9218515)

    *Haoxing Ren, George F. Kokai, Walker J. Turner, Ting-Sheng Ku.* 

- **GCN-RL Circuit Designer: Transferable Transistor Sizing with Graph Neural Networks and Reinforcement Learning.** Design Automation Conference (DAC), 2020. [paper](https://ieeexplore.ieee.org/document/9218757/)

    *Hanrui Wang, Kuan Wang, Jiacheng Yang, Linxiao Shen, Nan Sun, Hae-Seung Lee, Song Han.* 

- **Universal Symmetry Constraint Extraction for Analog and Mixed-Signal Circuits with Graph Neural Networks.** ACM/IEEE Design Automation Conference (DAC), 2021. [paper](https://dl.acm.org/doi/10.1109/DAC18074.2021.9586211)

    *Hao Chen, Keren Zhu, Mingjie Liu, Xiyuan Tang, Nan Sun, David Z. Pan.* 

- **CktGNN: Circuit Graph Neural Network for Electronic Design Automation.** International Conference on Learning Representations (ICLR), 2023. [paper.](https://openreview.net/forum?id=NE2911Kq1sp) [code.](https://github.com/zehao-dong/CktGNN) [dataset 1.](https://github.com/zehao-dong/CktGNN/tree/main/OCB/CktBench101) [dataset 2.](https://github.com/zehao-dong/CktGNN/tree/main/OCB/CktBench301)

    *Zehao Dong, Weidong Cao, Muhan Zhang, Dacheng Tao, Yixin Chen, Xuan Zhang.*

- **Graph of Circuits with GNN for Exploring the Optimal Design Space.** Advances in Neural Information Processing Systems (NeurIPS), 2024. [paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/12da92b7c64176eb6eb6ad0ae31554fd-Paper-Conference.pdf)

    *Aditya Hemant Shahane, Swapna Manjiri, Ankesh Jain, Ankesh Jain.* 

- **GNN-Based Hierarchical Annotation for Analog Circuits.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2023. [paper](https://ieeexplore.ieee.org/document/10015088/)

    *Kishor Kunal, Tonmoy Dhar, Meghna Madhusudan, Jitesh Poojary, Arvind K. Sharma, Wenbin Xu, Steven M. Burns, Jiang Hu, Ramesh Harjani, Sachin S. Sapatnekar.* 

### [Circuit Design Completion](#content)

- **Circuit Design Completion Using Graph Neural Networks.** Neural Computing and Applications, 2023. [paper.](https://link.springer.com/article/10.1007/s00521-023-08346-x) [code.](https://github.com/Anwar-Said/Circuit-Completion-Using-GNNs) [dataset.](https://github.com/symbench/spice-datasets)

  *Anwar Said, Mudassir Shabbir, Brian Broll, Waseem Abbas, Peter Völgyesi, Xenofon Koutsoukos.*


## [GNNs for Hardware Reliability](#content)
### [Aging Delay Prediction](#content)

- **GNN4REL: Graph Neural Networks for Predicting Circuit Reliability Degradation.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2022. [paper.](https://ieeexplore.ieee.org/document/9852805/) [code.](https://github.com/lilasrahis/GNN4REL)

  *Lilas Alrahis, Johann Knechtel, Florian Klemme, Hussam Amrouch, Ozgur Sinanoglu.*

- **Analog IC Aging-Induced Degradation Estimation via Heterogeneous Graph Convolutional Networks.** Asia and South Pacific Design Automation Conference (ASP-DAC), 2021. [paper](https://dl.acm.org/doi/10.1145/3394885.3431546)

    *Tinghuan Chen, Qi Sun, Canhui Zhan, Changze Liu, Huatao Yu, Bei Yu.* 

- **Deep H-GCN: Fast Analog IC Aging-Induced Degradation Estimation.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2022. [paper](https://ieeexplore.ieee.org/document/9521579)

    *Tinghuan Chen, Qi Sun, Canhui Zhan, Changze Liu, Huatao Yu, Bei Yu.* 

- **Fast Aging-Aware Timing Analysis Framework with Temporal–Spatial Graph Neural Network.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2023. [paper](https://ieeexplore.ieee.org/document/10373573/)

    *Jinfeng Ye, Pengpeng Ren, Yongkang Xue, Hui Fang, Zhigang Ji.* 

### [Functional De-Rating Prediction](#content)

- **Modeling Gate-Level Abstraction Hierarchy Using Graph Convolutional Neural Networks to Predict Functional De-Rating Factors.** NASA/ESA Conference on Adaptive Hardware and Systems (AHS), 2019. [paper](https://ieeexplore.ieee.org/document/8792929/)

    *Aneesh Balakrishnan, Thomas Lange, Maximilien Glorieux, Dan Alexandrescu, Maksim Jenihhin.* 

### [Critical Component Identification](#content)

- **Toward Critical Flip-Flop Identification for Soft-Error Tolerance With Graph Neural Networks.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2023. [paper](https://ieeexplore.ieee.org/document/10314712)

    *Li Lu, Junchao Chen, Markus Ulbricht, Milos Krstic.* 

- **Graph Attention Networks to Identify the Impact of Transistor Degradation on Circuit Reliability.** IEEE Transactions on Circuits and Systems I: Regular Papers, 2024. [paper](https://ieeexplore.ieee.org/document/10535497/)

    *Tarek Mohamed, Victor M. van Santen, Lilas Alrahis, Ozgur Sinanoglu, Hussam Amrouch.* 

### [Fault Diagnosis and Evaluation](#content)

- **An Intelligent Fault Detection Approach for Digital Integrated Circuits Through Graph Neural Networks.** Mathematical Biosciences and Engineering, 2023. [paper](https://www.aimspress.com/article/doi/10.3934/mbe.2023438)

    *Zulin Xu.* 

- **On the Prediction of Hardware Security Properties of HLS Designs Using Graph Neural Networks.** IEEE International Symposium on Defect and Fault Tolerance in VLSI and Nanotechnology Systems (DFT), 2023. [paper.](https://ieeexplore.ieee.org/document/10313544/) [code.](https://github.com/unipieslab/SecureHLS)

    *Amalia-Artemis Koufopoulou, Athanasios Papadimitriou, Aggelos Pikrakis, Mihalis Psarakis, David Hely.*


## [GNNs for Hardware Security](#content)
### [HT Detection](#content)

- **GNN4TJ: Graph Neural Networks for Hardware Trojan Detection at Register Transfer Level.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2021. [paper.](https://ieeexplore.ieee.org/document/9474174/)

  *Rozhin Yasaei, Shih-Yuan Yu, Mohammad Abdullah Al Faruque.*

- **Hardware Trojan Detection Using Graph Neural Networks.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2022. [paper](https://dl.acm.org/doi/10.1109/TCAD.2022.3178355)

    *Rozhin Yasaei, Luke Chen, Shih-Yuan Yu, Mohammad Abdullah Al Faruque.* 

- **HW2VEC: A Graph Learning Tool for Automating Hardware Security.** IEEE International Symposium on Hardware Oriented Security and Trust (HOST), 2021. [paper.](https://ieeexplore.ieee.org/document/9702281/) [code.](https://github.com/aicps/hw2vec)

    *Shih-Yuan Yu, Rozhin Yasaei, Qingrong Zhou, Tommy Nguyen, Mohammad Abdullah Al Faruque.* 

- **Golden Reference-Free Hardware Trojan Localization Using Graph Convolutional Network.** IEEE Transactions on Very Large Scale Integration (VLSI) Systems (TVLSI), 2022. [paper](https://ieeexplore.ieee.org/document/9843948/)

    *Rozhin Yasaei, Sina Faezi, Mohammad Abdullah Al Faruque.* 

- **Contrastive Graph Convolutional Networks for Hardware Trojan Detection in Third-Party IP Cores.** IEEE International Symposium on Hardware Oriented Security and Trust (HOST), 2021. [paper](https://ieeexplore.ieee.org/document/9702276/)

    *Nikhil Muralidhar, Abdullah Zubair, Nathanael Weidler, Ryan Gerdes, Naren Ramakrishnan.* 

- **BGNN-HT: Bidirectional Graph Neural Network for Hardware Trojan Cells Detection at Gate Level.** IEEE International Symposium on Circuits and Systems (ISCAS), 2023. [paper](https://ieeexplore.ieee.org/document/10181569/)

    *Peiheng Zhan, Haihua Shen, Shan Li, Huawei Li.* 

- **A Fine-Grained Detection Method for Gate-Level Hardware Trojan Based on Bidirectional Graph Neural Networks.** Journal of King Saud University-Computer and Information Sciences, 2023. [paper](https://www.sciencedirect.com/science/article/pii/S1319157823003762)

    *Dong Cheng, Chen Dong, Wenwu He, Zhenyi Chen, Ximeng Liu, Hao Zhang.* 

- **A Needle in the Haystack: Inspecting Circuit Layout to Identify Hardware Trojans.** Cryptology ePrint Archive, 2023. [paper](https://ieeexplore.ieee.org/abstract/document/10528739)

    *Xingyu Meng, Abhrajit Sengupta, Kanad Basu.* 

- **A Unioned Graph Neural Network Based Hardware Trojan Node Detection.** IEICE Electronics Express, 2023. [paper](https://www.jstage.jst.go.jp/article/elex/20/13/20_20.20230204/_pdf)

    *Weitao Pan, Meng Dong, Cong Wen, Hongjin Liu, Shaolin Zhang, Bo Shi, Zhixiong Di, Zhiliang Qiu, Yiming Gao, Ling Zheng.* 

- **Circuit Topology-Aware Vaccination-Based Hardware Trojan Detection.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2023. [paper](https://ieeexplore.ieee.org/document/10008912)

    *Rakibul Hassan, Xingyu Meng, Kanad Basu, Sai Manoj Pudukotai Dinakarrao.* 

- **MaliGNNoma: GNN-Based Malicious Circuit Classifier for Secure Cloud FPGAs.** IEEE International Symposium on Hardware Oriented Security and Trust (HOST), 2024. [paper](https://ieeexplore.ieee.org/document/10545411/)

    *Lilas Alrahis, Hassan Nassar, Jonas Krautter, Dennis Gnad, Lars Bauer, Jörg Henkel.* 

### [Piracy Detection](#content)

- **GNN4IP: Graph Neural Network for Hardware Intellectual Property Piracy Detection.** Design Automation Conference (DAC), 2021. [paper.](https://ieeexplore.ieee.org/document/9586150/) [code.](https://github.com/sushi-aa/hw2vec)

    *Rozhin Yasaei, Shih-Yuan Yu, Emad Kasaeyan Naeini, Mohammad Abdullah Al Faruque.* 

- **HW2VEC: A Graph Learning Tool for Automating Hardware Security.** IEEE International Symposium on Hardware Oriented Security and Trust (HOST), 2021. [paper.](https://ieeexplore.ieee.org/document/9702281) [code.](https://github.com/sushi-aa/hw2vec)

    *Shih-Yuan Yu, Rozhin Yasaei, Qingrong Zhou, Tommy Nguyen, Mohammad Abdullah Al Faruque.* 

- **PoisonedGNN: Backdoor Attack on Graph Neural Networks-Based Hardware Security Systems.** IEEE Transactions on Computers, 2023. [paper](https://ieeexplore.ieee.org/document/10114622)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Abdullah Hanif, Muhammad Shafique, Ozgur Sinanoglu.* 

- **GoCLIP: Graph One-Class Classification for Intellectual Property Circuit Identification.** IEEE International Symposium on the Physical and Failure Analysis of Integrated Circuits (IPFA), 2023. [paper](https://ieeexplore.ieee.org/document/10249040/)

    *Xuenong Hong, Yee-Yang Tee, Tong Lin, Yiqiong Shi, Deruo Cheng, Erdong Huang.* 

### [Functional Reverse Engineering](#content)

- **GNN-RE: Graph Neural Networks for Reverse Engineering of Gate-Level Netlists.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2022. [paper.](https://ieeexplore.ieee.org/document/9530566/) [code.](https://github.com/DfX-NYUAD/GNN-RE) [dataset 1.](https://github.com/DfX-NYUAD/GNN-RE/raw/main/Netlist_to_graph.zip) [dataset 2.](https://github.com/DfX-NYUAD/GNN-RE/raw/main/RTL_Dataset.zip)

  *Lilas Alrahis, Abhrajit Sengupta, Johann Knechtel, Satwik Patnaik, Hani Saleh, Baker Mohammad, Mahmoud Al-Qutayri, Ozgur Sinanoglu.*

- **Gamora: Graph Learning-Based Symbolic Reasoning for Large-Scale Boolean Networks.** IEEE, 2023. [paper.](https://ieeexplore.ieee.org/document/10247828/) [code.](https://github.com/Yu-Maryland/Gamora) [dataset.](https://huggingface.co/datasets/yucx0626/Gamora-CSA-Multiplier/tree/main)

  *Nan Wu, Yingjie Li, Cong Hao, Steve Dai, Cunxi Yu, Yuan Xie.*

- **DepthGraphNet: Circuit Graph Isomorphism Detection via Siamese-Graph Neural Networks.** ACM/IEEE 5th Workshop on Machine Learning for CAD (MLCAD), 2023. [paper.](https://ieeexplore.ieee.org/document/10299839/) [code.](https://github.com/FinAminToastCrunch/DepthGraphNet) [dataset.](https://drive.google.com/drive/folders/1PIF7fRZj44ABROP28tgva8F5LkDaP0zb?usp=sharing)

  *Fin Amin, Soumyadeep Chatterjee, Paul D. Franzon.*

- **ReIGNN: State Register Identification Using Graph Neural Networks for Circuit Reverse Engineering.** International Conference on Computer-Aided Design (ICCAD), 2021. [paper.](https://ieeexplore.ieee.org/document/9643498/) [code.](https://github.com/SubhajitDuttaChowdhury/ReIGNN) [dataset.](https://github.com/SubhajitDuttaChowdhury/ReIGNN/tree/master/dataset)

  *Subhajit Dutta Chowdhury, Kaixin Yang, Pierluigi Nuzzo.*

- **Graph Learning-Based Arithmetic Block Identification.** International Conference on Computer-Aided Design (ICCAD), 2021. [paper.](https://ieeexplore.ieee.org/document/9643581/) [dataset 1.](https://github.com/riscv-boom/riscv-boom) [dataset 2.](https://github.com/chipsalliance/rocket-chip) 

    *Zhuolun He, Ziyi Wang, Chen Bai, Haoyu Yang, Bei Yu.* 

- **Functionality Matters in Netlist Representation Learning.** Design Automation Conference (DAC), 2022. [paper.](https://dl.acm.org/doi/10.1145/3489517.3530410) [code.](https://github.com/ZeayW/FGNN2) [dataset 1.](https://github.com/FGNN2/FGNN2_pretraindata)

    *Ziyi Wang, Chen Bai, Zhuolun He, Guangliang Zhang, Qiang Xu, Tsung-Yi Ho, Bei Yu, Yu Huang.* 

- **ConVERTS: Contrastively Learning Structurally Invariant Netlist Representations.** ACM/IEEE 5th Workshop on Machine Learning for CAD (MLCAD), 2023. [paper](https://ieeexplore.ieee.org/document/10299862/)

    *Animesh B. Chowdhury, Jitendra Bhandari, Luca Collini, Ramesh Karri, Benjamin Tan, Siddharth Garg.* 

- **Graph Neural Network-Based Netlist Operator Detection Under Circuit Rewriting.** Great Lakes Symposium on VLSI (GLSVLSI), 2022. [paper](https://dl.acm.org/doi/10.1145/3526241.3530330)

    *Guangwei Zhao, Kaveh Shamsi.* 

- **AppGNN: Approximation-Aware Functional Reverse Engineering Using Graph Neural Networks.** International Conference on Computer-Aided Design (ICCAD), 2022. [paper.](https://dl.acm.org/doi/10.1145/3508352.3549471) [code.](https://github.com/ML-CAD/AppGNN)
  
    *Tim Bücher, Lilas Alrahis, Guilherme Paim, Sergio Bampi, Ozgur Sinanoglu, Hussam Amrouch.* 

- **GANA: Graph Convolutional Network-Based Automated Netlist Annotation for Analog Circuits.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2020. [paper.](https://ieeexplore.ieee.org/document/9116329/) [code.](https://github.com/kkunal1408/GANA_circuit_data) [dataset.](https://github.com/kkunal1408/GANA_circuit_data/raw/master/circuit_data/OTA_data/spice.zip)

    *Kishor Kunal, Tonmoy Dhar, Meghna Madhusudan, Jitesh Poojary, Arvind Sharma, Wenbin Xu, Steven M. Burns, Jiang Hu, Ramesh Harjani, Sachin S. Sapatnekar.*
  
### [Attacks on Design-for-Trust Methods](#content)

#### [Key Leakage](#key-leakage)
- **OMLA: An Oracle-less Machine Learning-based Attack on Logic Locking.** IEEE Transactions on Circuits and Systems II: Express Briefs, 2022. [paper.](https://ieeexplore.ieee.org/document/9539868/) [code.](https://github.com/DfX-NYUAD/OMLA) [dataset.](https://github.com/DfX-NYUAD/OMLA/tree/main/circuit_datasets)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Shafique, Ozgur Sinanoglu.* 

#### [Link Formation](#link-formation)
- **MuxLink: Circumventing Learning-Resilient MUX-Locking Using Graph Neural Network-Based Link Prediction.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2022. [paper.](https://ieeexplore.ieee.org/document/9774603/) [code.](https://github.com/lilasrahis/MuxLink)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Shafique, Ozgur Sinanoglu.* 

- **UNTANGLE: Unlocking Routing and Logic Obfuscation Using Graph Neural Networks-based Link Prediction.** International Conference on Computer-Aided Design (ICCAD), 2021. [paper.](https://ieeexplore.ieee.org/document/9643476/) [code.](https://github.com/lilasrahis/UNTANGLE) [dataset 1.](https://github.com/ispras/hdl-benchmarks/tree/master/iscas85) [dataset 2.](https://github.com/cad-polito-it/I99T)

    *Lilas Alrahis, Satwik Patnaik, Muhammad Abdullah Hanif, Muhammad Shafique, Ozgur Sinanoglu.* 

#### [Structural Leakage](#structural-leakage)
- **Deceptive Logic Locking for Hardware Integrity Protection Against Machine Learning Attacks.** IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2021. [paper](https://ieeexplore.ieee.org/document/9496607)

    *Dominik Sisejkovic, Farhad Merchant, Lennart M. Reimann, Rainer Leupers.* 

- **SCOPE: Synthesis-Based Constant Propagation Attack on Logic Locking.** IEEE Transactions on Very Large Scale Integration (VLSI) Systems (TVLSI), 2021. [paper.](https://ieeexplore.ieee.org/document/9466931/) [code.](https://github.com/alaql89/SCOPE)

    *Abdulrahman Alaql, Md Moshiur Rahman, Swarup Bhunia.* 

- **InterLock: An Intercorrelated Logic and Routing Locking.** International Conference on Computer-Aided Design (ICCAD), 2020. [paper](https://ieeexplore.ieee.org/document/9256537/)

    *Hadi Mardani Kamali, Kimia Zamiri Azar, Houman Homayoun, Avesta Sasan.* 

#### [Attack Scalability](#attack-scalability)
- **Titan: Security Analysis of Large-Scale Hardware Obfuscation Using Graph Neural Networks.** IEEE Transactions on Information Forensics and Security (TIFS), 2022. [paper.](https://ieeexplore.ieee.org/document/9933482) [dataset.](https://github.com/cad-polito-it/I99T)

    *Likhitha Mankali, Lilas Alrahis, Satwik Patnaik, Johann Knechtel, Ozgur Sinanoglu.* 

- **UN-SPLIT: Attacking Split Manufacturing Using Link Prediction in Graph Neural Networks.** International Conference on Security, Privacy, and Applied Cryptography Engineering, 2023. [paper](https://link.springer.com/chapter/10.1007/978-3-031-51583-5_12)

    *Lilas Alrahis, Likhitha Mankali, Satwik Patnaik, Abhrajit Sengupta, Johann Knechtel, Ozgur Sinanoglu.* 

- **GNNUnlock: Graph Neural Networks-Based Oracle-Less Unlocking Scheme for Provably Secure Logic Locking.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2021. [paper.](https://ieeexplore.ieee.org/document/9474039/) [code.](https://github.com/DfX-NYUAD/GNNUnlock) [dataset.](https://github.com/DfX-NYUAD/GNNUnlock/tree/main/Netlist_to_graph/Circuits_datasets)

    *Lilas Alrahis, Satwik Patnaik, Faiq Khalid, Muhammad Abdullah Hanif, Hani Saleh, Muhammad Shafique, Ozgur Sinanoglu.* 

- **Estimating the Circuit De-Obfuscation Runtime Based on Graph Deep Learning.** Design, Automation & Test in Europe Conference & Exhibition (DATE), 2020. [paper](https://ieeexplore.ieee.org/document/9116544/)

    *Zhiqian Chen, Gaurav Kolhe, Setareh Rafatirad, Chang-Tien Lu, Sai Manoj P.D., Houman Homayoun, Liang Zhao.* 

#### [Attack Sensitivity](#attack-sensitivity)
- **NetlistGNN: Characterizing the Ability of GNNs in Attacking Logic Locking.** ACM/IEEE 5th Workshop on Machine Learning for CAD (MLCAD), 2023. [paper](https://ieeexplore.ieee.org/document/10299817)

    *Wei Li, Ruben Purdy, José M. F. Moura, R.D. Blanton.*
