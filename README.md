# AI-Backdoor
The aim of this Github repository is to gather and summarise Backdoor in AI resources. In particular, we will list and present attacks and defenses on AI and Deep Learning systems together with code repositories if exist.
First, we will list the papers in chronological order from older to newer.
In addition, we will try to categorize the attacks and defenses based on the threat model, the amount of knowledge available to the attacker and the defender and the adversarial settings.

The main categories of attacks are: "clean label", "poisoned label", "blackbox", "whitebox", "full control", "partial control"

The main research contributions to improve the backdoor attack works on one of the following:
* reducing the backdoor signal (trigger) visibility to human visual system - stealthiness
* improve the backdoor robustness
* fine-tuning

The defences on the other hand work on one of three levels:
* Data
* Model
* Training Data


So, under each paper, we will try to classify the categories selected by the authors in order to make the work comparable with others.

Keywords: "Backdoor attacks", "Adversarial attacks", "Trojans", "Neural Trojans"

# Surveys on Backdoor attacks and defenses
## 2022
###### 1. A Survey of Neural Trojan Attacks and Defenses in Deep Learning [Paper](https://arxiv.org/pdf/2202.07183)
 > Authors: J Wang, GM Hassan, N Akhtar
 
 > Publisher: ArXiv
 
 > A literature review of the existing attacks and exploration of the available defenses.

## 2021
###### 1. An Overview of Backdoor Attacks Against Deep Neural Networks and Possible Defences [Paper](https://arxiv.org/pdf/2111.08429)
 > Authors: W Guo, B Tondi, M Barni
 
 > Publisher: ArXiv
 
 > A literature review of the existing attacks and exploration of the available defenses. Classifications of attacks and defenses and exploration of benign use of backdoor attacks.

###### 2. Artificial Intelligence Security: Threats and Countermeasures [Paper](https://dl.acm.org/doi/pdf/10.1145/3487890)
 > Authors: Y Hu, W Kuang, Z Qin, K Li, J Zhang, Y Gao
 
 > Publisher: ACM Computing Surveys
 
 > Review the challenges and recent research advances for security issues in AI.

###### 3. Security Meets Deep Learning [PhD Dissertation](https://search.proquest.com/openview/b52f04da04e5213385f37eb6ec00cae8/1?pq-origsite=gscholar&cbl=18750&diss=y)
 > Authors: He, Zecheng
 
 > Publisher: Princeton University
 
 > Review the literature and focus on power grid anomaly detection.


## 2020
###### 1. Machine learning security: Threats, countermeasures, and evaluations [Paper](https://ieeexplore.ieee.org/iel7/6287639/8948470/09064510.pdf)
 > Authors: M Xue, C Yuan, H Wu, Y Zhang, W Liu
 
 > Publisher: IEEE Access
 
 > Covers all the aspects of machine learning security from the training phase to the test phase. The threat models, attack approaches, and defense techniques are analyzed.

###### 2. A survey on neural trojans [Paper](https://ieeexplore.ieee.org/iel7/9131689/9136966/09137011.pdf)
 > Authors: Y Liu, A Mondal, A Chakraborty
 
 > Publisher: IEEE International Symposium on Quality Electronic Design
 
 > A review on Neural Trojan Attacks and their classes.

###### 3. Backdoor attacks and countermeasures on deep learning: A comprehensive review [Paper](https://ieeexplore.ieee.org/iel7/9131689/9136966/09137011.pdf)
 > Authors: Y Gao, BG Doan, Z Zhang, S Ma, J Zhang, A Fu
 
 > Publisher: ArXiv
 
 > A review on Attacks and Countermeasures.

###### 4. Deep learning backdoors [Paper](https://arxiv.org/pdf/2007.08273.pdf?ref=https://githubhelp.com)
 > Authors: S Li, S Ma, M Xue, BZH Zhao
 
 > Publisher:  ArXiv
 

###### 5. Backdoor learning: A survey [Paper](https://arxiv.org/pdf/2007.08745)
 > Authors: Y Li, B Wu, Y Jiang, Z Li, ST Xia
 
 > Publisher: ArXiv
 
 > Survey that categorize existing backdoor attacks and defenses based on their characteristics.




# Available sources and toolboxes

# Backdoor Attacks
In this section, we will list the backdoor attacks on image and video models as they are the most common in the literature. In addition, we will tag each paper by category keywords so that a reader can understand where the work is located on the research map.
## 2022
###### 1. Label-Smoothed Backdoor Attack [Paper](https://arxiv.org/pdf/2202.11203)
 > Authors: M Peng, Z Xiong, M Sun, P Li
 
 > Publisher: ArXiv
 
 > Label smoothed Backdoor Attack. The true label of the poisoned sample will be changed to the target following a probability distribution. This work is to overcome the over-fitting in the case of poisoned label attacks.

 > Category: clean label, blackbox, control the dataset and the labels

## 2021
###### 1. WaNet--Imperceptible Warping-based Backdoor Attack [Paper](https://arxiv.org/pdf/2102.10369)
 > Authors: A Nguyen, A Tran 
 
 > Publisher: ArXiv
 
 > Perceptually  invisible  trigger  based  on  image  warping. The invisibility is reached by relying on the difficulty of the humanpsychovisual system  to  detect  smooth  geometric  deformations.

 > Category: poisoned label, blackbox, control the dataset and the labels

###### 2. LIRA: Learnable, Imperceptible and Robust Backdoor Attacks [Paper](http://openaccess.thecvf.com/content/ICCV2021/papers/Doan_LIRA_Learnable_Imperceptible_and_Robust_Backdoor_Attacks_ICCV_2021_paper.pdf)
 > Authors: K Doan, Y Lao, W Zhao, P Li
 
 > Publisher: IEEE/CVF
 
 > To improve backdoor stealthiness, the medthod regularize the L-norm of the perturbation when optimizing backdoor trigger.

 > Category: poisoned label (the label is one shifted), blackbox, control the dataset and the labels


###### 3. Invisible poison: A blackbox clean label backdoor attack to deep neural networks [Paper](https://ieeexplore.ieee.org/iel7/9488422/9488423/09488902.pdf)
 > Authors: 
 
 > Publisher: 
 
 >

###### 4. Check your other door! establishing backdoor attacks in the frequency domain [Paper](https://arxiv.org/pdf/2109.05507)
 > Authors: 
 
 > Publisher: 
 
 >

###### 5. Use Procedural Noise to Achieve Backdoor Attack [Paper](https://ieeexplore.ieee.org/iel7/6287639/9312710/09529206.pdf)
 > Authors: 
 
 > Publisher: 
 
 >

###### 6. Poison Ink: Robust and Invisible Backdoor Attack [Paper](https://arxiv.org/pdf/2108.02488)
 > Authors: 
 
 > Publisher: 
 
 >

###### 7. AdvDoor: adversarial backdoor attack of deep learning system [Paper](https://dl.acm.org/doi/pdf/10.1145/3460319.3464809)
 > Authors: 
 
 > Publisher: 
 
 >

###### 8. Backdoor attack in the physical world [Paper](https://arxiv.org/pdf/2104.02361)
 > Authors: 
 
 > Publisher: 
 
 >

###### 9. Defense-resistant backdoor attacks against deep neural networks in outsourced cloud environment [Paper](https://ieeexplore.ieee.org/iel7/49/9486979/09450029.pdf)
 > Authors: 
 
 > Publisher: 
 
 >

###### 10. Deep feature space trojan attack of neural networks by controlled detoxification [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/16201/16008)
 > Authors: 
 
 > Publisher: 
 
 >

###### 11. A Master Key backdoor for universal impersonation attack against DNN-based face verification [Paper](https://www.sciencedirect.com/science/article/pii/S0167865521000210)
 > Authors: 
 
 > Publisher: 
 
 >

###### 12. DeepPoison: Feature Transfer Based Stealthy Poisoning Attack for DNNs [Paper](https://ieeexplore.ieee.org/iel7/8920/4358609/09359658.pdf)
 > Authors: 
 
 > Publisher: 
 
 >


## 2021
###### 1. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

###### 2. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

###### 3. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

###### 4. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >

###### 5. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >

###### 6. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >

###### 7. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >

###### 8. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >

###### 9. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >

###### 10. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >

###### 11. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >



## 2019
###### 1. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

###### 2. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

###### 3. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

###### 4. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >

###### 5. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >

## 2018
###### 1. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

###### 2. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 >

## 2017
###### 1. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

###### 2. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

###### 3. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

###### 4. [Paper]()
 > Authors: 
 
 > Publisher: 
 
 > 

# Backdoor Defenses

## 2022

## 2021

## 2020

## 2019

## 2018

## 2017


# Benign use of Backdoor attacks
## DNN Watermarking

###### 2022

###### 2021

###### 2020

###### 2019

###### 2018

###### 2017

## Adversarial examples detection
###### 2022

###### 2021

###### 2020

###### 2019

###### 2018

###### 2017
