# Stochastic Gradient Perturbation: An Implicit Regularizer for Person Re-Identification - Accepted at IEEE Transactions on Circuits and Systems for Video Technology, 2023
- The paper can be accessed at [TCSVT2023](https://ieeexplore.ieee.org/document/10081020)


- The code will be available after collation. If you find this code useful in your research then please cite


'''
@ARTICLE{10081020,

  author={Zhou, Yuhang and Huang, Fuxiang and Chen, Weijie and Pu, Shiliang and Zhang, Lei},
  
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  
  title={Stochastic Gradient Perturbation: An Implicit Regularizer for Person Re-Identification}, 
  
  year={2023},
  
  volume={33},
  
  number={10},
  
  pages={5894-5907},
  
  doi={10.1109/TCSVT.2023.3261333}}
'''


## Abstract

Generalization of the person re-identification (ReID) model plays an important role in practical application, and we discuss a simple yet effective regularizer to improve it inspired by Adversarial Training (AT). AT has been indicated as an advanced regularizer due to its adversarial mechanism, ability to mine hard samples, and nature of data augmentation. However, serving as an augmentation-based regularizer, AT shows low diversity of the perturbation, excessive computational cost, and the optimization dilemma between adversarial robustness and accuracy for ReID task, and is thus suboptimal. To tackle these limitations and get a more effective regularizer for ReID, we rethink the nature of AT and unveil that the adversarial data augmentation is essentially reflected by gradients. Based on this, a novel implicit regularizer, named Stochastic Gradient Perturbation (SGP), is proposed, which naturally brings three merits: 1) Better diversity of the perturbation due to the proposed non-directional stochastic perturbations rather than directional adversarial perturbations. 2) Lower computational cost due to the proposed implicit gradient augmentation rather than explicitly additional data. 3) The optimization dilemma of the adversarial robustness and generalization is naturally overcome since SGP contains the adversarial gradient perturbation. Further, we put forward a perspective that the generalization and adversarial robustness may have an inter unity. Experiments on the baseline and SOTA models demonstrate powerful performances of the plugged-played SGP, and both generalization and adversarial robustness can be guaranteed.

## 








