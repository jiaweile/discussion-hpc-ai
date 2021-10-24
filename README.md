# HPC-AI Discussion

### 🌟 Virtual HPC+AI seminar, 2021 Spring to Fall

- **When:** 🕒 Monday  910:30 am -- 12:30 am
- **Where:** 💻 Wechat meeting. 
  Please send me an email (jiaweile@ict.ac.cn) to ask for the meeting id.
- **Moderator**: Siyu Hu

---------

<div align="center">
  <h3>Let's start!</h3>
  <h1> Week 24 </h1>
  <h1> A Coordinated Tiling and Batching Framework for Efficient GEMM on GPUs </h1>
  <strong> Chunyang Xiang </strong>
  <h6> Octorber 25, 10:30 am -- 12:30 pm</h6>
</div>



-----
## 📌 Schedule (2021)


🆕✨🔨: **reserve the time** * please contact husiyu@ncic.ac.cn to book time slot for your talk for the year 2021

| Week | Date | Topic                                                                                     | Speaker               |
| ---- | ---- | :---------------------------------------------------------------------------------------: | --------------------- |
| 1    | 3/24 | DFT overview <br> [selected inversion](#1) <br> the DeepMD-kit on the DFT algorithm. | Yujin Yan<br>Siyu HU<br>Weile Jia |            
| 2    | 3/31 | [deep learning for symbolic mathematics & Seq2Seq](#14)   | Junqing Gong |            
| 3    | 4/7  | Application of Quantum Computing in Quantum Chemistry     | Zhendong Li  |            
| 4    | 4/21 | [Accelerating Sparse DNN Models without Hardware-Support via Tile-Wise Sparsity](#15) | Zhuoqiang Guo|            
| 5    | 4/28 | [SchNet: A continuous-filter convolutional neural network for modeling quantum interactions](#11) | Tao LIU        |            
| 6    | 5/12 | [DP-GEN](#3)          | Yun ZHONG      |            
| 7    | 5/19 | [Anatomy of High-Performance Matrix Multiplication](#16)          | Chunyang Xiang|            
| 8    | 5/28 | DFT overview|Yujin Yan|            
| 9    | 6/2  | [Ansor : Generating High-Performance Tensor Programs for Deep Learning](#19)| Han BAO |            
| 10   | 6/9  | DFT overview          |Siyu Hu|            
| 11   | 6/23 | [A Systematic Approach to Improving Data Locality Across Fourier Transforms and Linear Algebra Operations](#20)| Guofeng Feng |            
| 12   | 6/30 | [DeepONet](#17)  |Rongrong Liu|            
| 13   | 7/14 | [DNNFusion: Accelerating Deep Neural Networks Execution with Advanced Operator Fusion](#21) | Zhuoqiang Guo |            
| 14   | 7/21 | [FNO](#18)    | Siyu Hu |  
| 15   | 7/28 | [GEMS](#23) | Yun ZHONG | 
| 16   | 8/18 | [Sparse GPU Kernels for Deep Learning](#25) |Han BAO|
| 17   | 8/25 | [yaSpMV: Yet Another SpMV Framework on GPUs](#26) |Chunyang Xiang| 
| 18   | 9/1  | [Solving ill-posed inverse problems using iterative deep neural networks](#27)|Haibo Li|
| 19   | 9/8  | [Machine-learning interatomic potentials for materials science](#28)|Yujin Yan|
| 20   | 9/15 | DFT overview | Tong ZHAO |
| 21   | 9/27 | [DCNV2](#29) | Siyu Hu |
| 22   | 10/11| Extending the limit of molecular dynamics with ab initio accuracy to 10 billion atoms | Zhuoqiang Guo |
| 23   | 10/18| DFT review | Tong ZHAO |
| 24   | 10/25| A Coordinated Tiling and Batching Framework for Efficient GEMM on GPUs| Chunyang Xiang |



## 🗂 Reading materials 
<!----
<details>
<summary>View contents</summary>
-->

###### 1
[Pushing the Limit of Molecular Dynamics with Ab Initio Accuracy to 100 Million Atoms with Machine Learning](https://arxiv.org/pdf/2005.00223.pdf)

> Weile Jia, et al 
> 
> **Arxiv, 2020**

###### 2
[Enhancing the scalability and load balancing of the parallel selected inversion algorithm via tree-based asynchronous communication](https://ieeexplore.ieee.org/document/7516015)

> Mathias Jacquelin, Lin Lin, Nathan Wichmann and Chao Yang
>
> **IPDPS, 2016**

###### 3

[DP-GEN: A concurrent learning platform for the generation of reliable deep learning based potential energy models](https://www.sciencedirect.com/science/article/abs/pii/S001046552030045X)

> Yuzhi Zhang, Haidi Wang, Weijie Chen, Jinzhe Zeng, Linfeng Zhang, HanWang and Weinan E
>
> **Computer Physics Communications, Volume 253, August 2020, 107206**

###### 4 

[Reactive uptake of N2O5 by atmospheric aerosol is dominated by interfacial processes](https://science.sciencemag.org/content/371/6532/921/tab-pdf)

> Mirza Galib and David T. Limmer
>
> **Science  26 Feb 2021: Vol. 371, Issue 6532, pp. 921-925**

###### 5

[Liquid to crystal Si growth simulation using machine learning force field](https://aip.scitation.org/doi/abs/10.1063/5.0011163)

> L. Miao and L.W. Wang
> 
> **The Journal of Chemical Physics, Volume 153, Issue 7, 10.1063/5.0011163**

###### 6

[Density functional theory based neural network force fields from energy decompositions](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.99.064103)

> Y. Huang, J. Kang, W.A. Goddard III and  L.W. Wang
> 
> **Phys. Rev. B 99, 064103 (2019)**

###### 7

[On representing chemical environments](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.87.184115)
> Bartók, A. P., Kondor, R. and Csányi, G  
>
> **Physical Review B 87, 184115 (2013)**

###### 8

[Machine learning of accurate energy-conserving molecular force fields](https://advances.sciencemag.org/content/3/5/e1603015.short)
> Stefan Chmiela. et al
>
> **Science Advances 3, e1603015 (2017)**

###### 9

[Quantum-chemical insights from deep tensor neural networks](https://www.nature.com/articles/ncomms13890)
> Schütt, K. T., Arbabzadah, F., Chmiela, S., Müller, K. R. and Tkatchenko, A 
>
> **Nature Communications 8, 13890 (2017)**

###### 10

[Generalized neural-network representation of high-dimensional potential-energy surfaces](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.98.146401)
> Behler, J. and Parrinello, M 
>
> **Physical Review Letters 98, 146401 (2007)**

###### 11

[Schnet: A continuous-filter convolutional neural network for modeling quantum interactions](https://arxiv.org/pdf/1706.08566.pdf)
> Schütt, K. et al 
>
> **NIPS(2017)**

###### 12

[End-to-end Symmetry Preserving Inter-atomic Potential Energy Model for Finite and Extended Systems](https://arxiv.org/pdf/1805.09003.pdf)
> Linfeng Zhang, et al 
>
> **Arxiv 2018**

###### 13

[Machine-learning interatomic potentials for material science](https://arxiv.org/pdf/2102.06163.pdf)
> Y. Mishin 
>
> **Arxiv 2021**

###### 14

[DEEP LEARNING FOR SYMBOLIC MATHEMATICS](https://arxiv.org/abs/1912.01412)
> Guillaume Lample, François Charton
>
> **ArXiv 2019**

###### 15

[Accelerating Sparse DNN Models without Hardware-Support via Tile-Wise Sparsity](https://arxiv.org/pdf/2008.13006.pdf)
> Cong Guo, Bo Yang Hsueh
>
> **ArXiv 2008**

###### 16

[Anatomy of High-Performance Matrix Multiplication](https://dl.acm.org/doi/abs/10.1145/1356052.1356053)
> Kazushige Goto,  Robert A. van de Geijn
>
> **ACM Transactions on Mathematical Software, 2008**

###### 17

[DeepONet: Learning nonlinear operators for identifying differential equations based on the universal approximation theorem of operators](http://arxiv-export-lb.library.cornell.edu/pdf/1910.03193)
> Lu Lu, Pengzhan Jin, and George Em Karniadakis
>
> **ArXiv 2020**

###### 18

[FOURIER NEURAL OPERATOR FOR PARAMETRIC PARTIAL DIFFERENTIAL EQUATIONS](https://arxiv.org/pdf/2010.08895v2.pdf)
> Zongyi Li, et al
>
> **ICLR 2021**

###### 19

[Ansor : Generating High-Performance Tensor Programs for Deep Learning](https://www.usenix.org/conference/osdi20/presentation/zheng)
> Lianmin Zheng, et al
>
> **Arxiv 2020**

##### 20

[A Systematic Approach to Improving Data Locality Across Fourier Transforms and Linear Algebra Operations](https://dl.acm.org/doi/pdf/10.1145/3447818.3460354)
> Doru Thom Popovici, et al
>
> **ICS 21**

#####  21

[DNNFusion: Accelerating Deep Neural Networks Execution with Advanced Operator Fusion](https://pldi21.sigplan.org/details/pldi-2021-papers/58/DNNFusion-Accelerating-Deep-Neural-Networks-Execution-with-Advanced-Operator-Fusion)
> Wei Niu, Jiexiong Guan, Yanzhi Wang, Gagan Agrawal, Bin Ren
> 
> **PLDI2021**

##### 22

[BiQGEMM: Matrix Multiplication with Lookup Table For Binary-Coding-based Quantized DNNs](https://arxiv.org/abs/2005.09904)
> Yongkweon Jeon, Baeseong Park, Se Jung Kwon, Byeongwook Kim, Jeongin Yun, Dongsoo Lee
>
> **Arxiv2021**

##### 23

[GEMS: GPU-Enabled Memory-Aware Model-Parallelism System for Distributed DNN Training](https://ieeexplore.ieee.org/document/9355254)
> Arpan Jain; Ammar Ahmad Awan, et al
>
> **SC20**

#####24

[Density matrix quantum circuit simulation via the BSP machine on modern GPU clusters](https://dl.acm.org/doi/10.5555/3433701.3433718)
> ANG LI,  OMER SUBASI, et al
>
> **SC20**

#####25

[Sparse GPU Kernels for Deep Learning](https://ieeexplore.ieee.org/abstract/document/9355309)
> Trevor Gale, et al
>
> **SC20**

#####26

[yaSpMV: Yet Another SpMV Framework on GPUs](https://dl.acm.org/doi/10.1145/2692916.2555255)
> Shengen Yan, et al
>
> **ACM SIGPLAN Notices,2014**

#####27

[Solving ill-posed inverse problems using iterative deep neural networks](https://arxiv.org/abs/1704.04058)
> Jonas Adler, et al
>
> **ArXiv2017**

#####28

[Machine-learning interatomic potentials for materials science](https://www.sciencedirect.com/science/article/abs/pii/S1359645421003608)
> Y. Mishin
>
> **Arxiv2021**

#####29

[DCN V2: Improved Deep & Cross Network and Practical Lessons for Web-scale Learning to Rank Systems](https://arxiv.org/pdf/2008.13535.pdf)
> Ruoxi Wang, et al
>
> **CS,IR,2020**

<br>[⬆ Back to top](#-reading-materials)

</details>

## Other materials (randomly ordered)

1. [A Quantum Algorithm for the Sensitivity Analysis of Business Risks](https://arxiv.org/pdf/2103.05475.pdf)

2. [Transferability of machine learning potentials: Protonated water neural network potential applied to the protonated water hexamer](https://aip.scitation.org/doi/full/10.1063/5.0035438)

3. [When do short-range atomistic machine-learning models fall short?](https://aip.scitation.org/doi/full/10.1063/5.0031215?casa_token=t8DwcF92hUcAAAAA%3Ai3KVvyHNG1XpzZomieQcZZosmnyFwvOkJdJnj9OcDpWrxanc_vlvqGhrXeTF-cLfKV2YLV6UVU5m)

4. [Accelerating atomistic simulations with piecewise machine-learned ab Initio potentials at a classical force field-like cost](https://pubs.rsc.org/fa/content/articlehtml/2021/cp/d0cp05089j?casa_token=dv9BUNc08JYAAAAA:0PBcE84WyLsGvBM-02RSWjT9KS4LCeqgmqJbR4t4OsDHe4X3FdMsxjb7rRlwmRaChOYyrbvemxCPzpM)

5. [Optimizing Training Data Set for the Machine Learning Potential of Li-Si Alloys via Structural Similarity-based Screening](https://arxiv.org/abs/2103.04347)
