<html>
<head>
    <title>点击弹出文本框</title>
    <script type="text/javascript">
	const references = {
	"2024PBScaler": "@ARTICLE{2024PBScaler, \n " + "author={Xie, Shuaiyu and Wang, Jian and Li, Bing and Zhang, Zekun and Li, Duantengchuan and Hung, Patrick C. K.}, \n" + "journal={IEEE Transactions on Services Computing}, \n" + "title={PBScaler: A Bottleneck-aware Autoscaling Framework for Microservice-based Applications}, \n" + "year={2024}, \n" + "pages={1-14}, \n" +"}",
	"2024MGIF": "@article{2024MGIF,\n " + "title = {Multi-perspective knowledge graph completion with global and interaction features}, \n " + "journal = {Information Sciences}, \n " + "volume = {666}, \n " + "pages = {120438}, \n " + "year = {2024}, \n " + "author = {Duantengchuan Li and Fobo Shi and Xiaoguang Wang and Chao Zheng and Yuefeng Cai and Bing Li},\n " + "}",
        "2024FHCPL": "@ARTICLE{2024FHCPL,\n" + "author={Lin, Ke and Li, Duantengchuan and Li, Yanjie and Chen, Shiyu and Wu, Xindong}, \n" + "journal={IEEE Transactions on Industrial Informatics}, \n" + "title={FHCPL: An Intelligent Fixed-Horizon Constrained Policy Learning System for Risk-Sensitive Industrial Scenario}, \n" + " year={2023}, \n" + "pages={1-11}, \n" + "doi={10.1109/TII.2023.3336225}} ",
	"2024MPAD": "@ARTICLE{2024MPAD, \n" + "author={Lin, Ke and Li, Yanjie and Chen, Shiyu and Li, Duantengchuan and Wu, Xinyu}, \n" + "journal={IEEE Transactions on Intelligent Vehicles},  \n" + "title={Motion Planner With Fixed-Horizon Constrained Reinforcement Learning for Complex Autonomous Driving Scenarios},  \n" + "year={2024}, \n" + "volume={9}, \n" + "number={1}, \n" + "pages={1577-1588}, \n" + "doi={10.1109/TIV.2023.3273857}} ",
 	"2024TAG": "@ARTICLE{2024TAG, \n" + "author={Lin, Ke and Li, Duantengchuan and Li, Yanjie and Chen, Shiyu and Liu, Qi and Gao, Jianqi and Jin, Yanrui and Gong, Liang}, \n" + "journal={IEEE Transactions on Neural Networks and Learning Systems},  \n" + "title={TAG: Teacher-Advice Mechanism With Gaussian Process for Reinforcement Learning},  \n" + "year={2023},  \n" + "pages={1-15}, \n" + "doi={10.1109/TNNLS.2023.3262956}} ",
  	"2024SDFormer": "@article{2024SDFormer, \n" + "title = {SDFormer: A shallow-to-deep feature interaction for knowledge graph embedding}, \n" + "journal = {Knowledge-Based Systems}, \n" + "volume = {284}, \n" + "pages = {111253}, \n" + "year = {2024}, \n" + "author = {Duantengchuan Li and Tao Xia and Jing Wang and Fobo Shi and Qi Zhang and Bing Li and Yu Xiong},}",
	"2024MRSR": "@article{2024MRSR,  \n" + "title = {Joint inter-word and inter-sentence multi-relation modeling for summary-based recommender system}, \n" + "journal = {Information Processing \\& Management}, \n" + "volume = {61}, \n" + "number = {3}, \n" + "pages = {103631}, \n" + "year = {2024}, \n" + "author = {Duantengchuan Li and Ceyu Deng and Xiaoguang Wang and Zhifei Li and Chao Zheng and Jing Wang and Bing Li},}",
	"2024MDLR": "@article{2024MDLR, \n" + "title = {MDLR: A Multi-Task Disentangled Learning Representations for unsupervised time series domain adaptation}, \n" + "journal = {Information Processing \\& Management}, \n" + "volume = {61}, \n" + "number = {3}, \n" + "pages = {103638}, \n" + "year = {2024}, \n" + "author = {Yu Liu and Duantengchuan Li and Jian Wang and Bing Li and Bo Hang},}",
 	"2024IPSRec": "@article{2024IPSRec, \n" + "title = {Integrating user short-term intentions and long-term preferences in heterogeneous hypergraph networks for sequential recommendation}, \n" + "journal = {Information Processing \\& Management}, \n" + "volume = {61}, \n" + "number = {3}, \n" + "pages = {103680}, \n" + "year = {2024}, \n" + "author = {Bingqian Liu and Duantengchuan Li and Jian Wang and Zhihao Wang and Bing Li and Cheng Zeng},}",
  	"2024SPPO": "@article{2024SPPO, \n" + "title = {Almost surely safe exploration and exploitation for deep reinforcement learning with state safety estimation}, \n" + "journal = {Information Sciences}, \n" + "volume = {662}, \n" + "pages = {120261}, \n" + "year = {2024}, \n" + "author = {Ke Lin and Yanjie Li and Qi Liu and Duantengchuan Li and Xiongtao Shi and Shiyu Chen},}",
   	"2024DSAM": "@ARTICLE{2024DSAM, \n" + "author={Chang, Jiaxin and Wang, Jian and Li, Bing and Zhao, Yuqi and Li, Duantengchuan}, \n" + "journal={IEEE Transactions on Network and Service Management},  \n" + "title={Attention-Based Deep Reinforcement Learning for Edge User Allocation},  \n" + "year={2024}, \n" + "volume={21}, \n" + "number={1}, \n" + "pages={590-604},}",
    	"2024DADL": "@article{2024DADL, \n" + "title = {DADL: Double Asymmetric Distribution Learning for head pose estimation in wisdom museum}, \n" + "journal = {Journal of King Saud University - Computer and Information Sciences}, \n" + "volume = {36}, \n" + "number = {1}, \n" + "pages = {101869}, \n" + "year = {2024}, \n" + "author = {Wanli Zhao and Shutong Wang and Xiaoguang Wang and Duantengchuan Li and Jing Wang and Chenghang Lai and Xiaoxue Li},}",
	"2023PSNet": "@INPROCEEDINGS{2023PSNet, \n" + "author={Zhao, Yuqi and Jiang, Delun and Li, Bing and Fu, Lei and Wang, Jian and Li, Duantengchuan}, \n" + "booktitle={2023 IEEE International Conference on Web Services (ICWS)}, \n" + " title={A Deep Reinforcement Learning-Based Pointer Scoring Network for Edge Task Scheduling}, \n" + " year={2023}, \n" + "pages={299-309},}",
	"2023SHGNet": "@article{2023SHGNet, \n" + "title = {Knowledge graph representation learning with simplifying hierarchical feature propagation}, \n" + "journal = {Information Processing  \\& Management}, \n" + "volume = {60}, \n" + "number = {4}, \n" + "pages = {103348}, \n" + "year = {2023}, \n" + "author = {Zhifei Li and Qi Zhang and Fangfang Zhu and Duantengchuan Li and Chao Zheng and Yan Zhang},}",
	 "2023ConvHLE": "@article{2023ConvHLE, \n" + "title = {Knowledge graph embedding model with attention-based high-low level features interaction convolutional network}, \n" + "journal = {Information Processing \\& Management}, \n" + "volume = {60}, \n" + "number = {4}, \n" + "pages = {103350}, \n" + "year = {2023}, \n" + "author = {Jingxiong Wang and Qi Zhang and Fobo Shi and Duantengchuan Li and Yuefeng Cai and Jian Wang and Bing Li and Xiaoguang Wang and Zhen Zhang and Chao Zheng},}",
 	 "2023BGCL": "@article{2023BGCL, \n" + "title = {BGCL: Bi-subgraph network based on graph contrastive learning for cold-start QoS prediction}, \n" + "journal = {Knowledge-Based Systems}, \n" + "volume = {263}, \n" + "pages = {110296}, \n" + "year = {2023}, \n" + "author = {Jiangyuan Zhu and Bing Li and Jian Wang and Duantengchuan Li and Yongqiang Liu and Zhen Zhang},}",
	"2023GCANet": "@article{2023GCANet, \n" + "title = {GCANet: Geometry cues-aware facial expression recognition based on graph convolutional networks}, \n" + "journal = {Journal of King Saud University - Computer and Information Sciences}, \n" + "volume = {35}, \n" + "number = {7}, \n" + "pages = {101605}, \n" + "year = {2023}, \n" + "author = {Shutong Wang and Anran Zhao and Chenghang Lai and Qi Zhang and Duantengchuan Li and Yihua Gao and Liangshan Dong and Xiaoguang Wang},}",
	"2022MFDNet": "@ARTICLE{2022MFDNet, \n" + "author={Liu, Hai and Fang, Shuai and Zhang, Zhaoli and Li, Duantengchuan and Lin, Ke and Wang, Jiazhang}, \n" + "journal={IEEE Transactions on Multimedia},  \n" + "title={MFDNet: Collaborative Poses Perception and Matrix Fisher Distribution for Head Pose Estimation},  \n" + "year={2022}, \n" + "volume={24}, \n" + "pages={2449-2460},}",
	"2022EDMF": "@ARTICLE{2022EDMF, \n" + "author={Liu, Hai and Zheng, Chao and Li, Duantengchuan and Shen, Xiaoxuan and Lin, Ke and Wang, Jiazhang and Zhang, Zhen and Zhang, Zhaoli and Xiong, Neal N.}, \n" + "journal={IEEE Transactions on Industrial Informatics},  \n" + "title={EDMF: Efficient Deep Matrix Factorization With Review Feature Learning for Industrial Recommender System},  \n" + "year={2022}, \n" + "volume={18}, \n" + "number={7}, \n" + "pages={4361-4371},}",
	 "2022MPSR": "@article{2022MPSR, \n" + "title = {Multi-perspective social recommendation method with graph representation learning}, \n" + "journal = {Neurocomputing}, \n" + "volume = {468}, \n" + "pages = {469-481}, \n" + "year = {2022}, \n" + "author = {Hai Liu and Chao Zheng and Duantengchuan Li and Zhaoli Zhang and Ke Lin and Xiaoxuan Shen and Neal N. Xiong and Jiazhang Wang},}",
	"2022MIF-FWSC": "@article{2022MIF-FWSC, \n" + "title = {Multi-information fusion based few-shot Web service classification}, \n" + "journal = {Future Generation Computer Systems}, \n" + "volume = {130}, \n" + "pages = {231-240}, \n" + "year = {2022}, \n" + "author = {Yongqiang Liu and Bing Li and Jian Wang and Duantengchuan Li and Yutao Ma},}",
	 "2022RLPNet": "@article{2022RLPNet, \n" + "title = {Integrating deep reinforcement learning with pointer networks for service request scheduling in edge computing}, \n" + "journal = {Knowledge-Based Systems}, \n" + "volume = {258}, \n" + "pages = {109983}, \n" + "year = {2022}, \n" + "author = {Yuqi Zhao and Bing Li and Jian Wang and Delun Jiang and Duantengchuan Li},}",
	"2022EAMR": "@INPROCEEDINGS{2022EAMR, \n" + "author={Fu, Zixun and Zhang, Zhen and Zheng, Jie and Lin, Ke and Li, Duantengchuan}, \n" + "booktitle={2022 International Conference on Frontiers of Artificial Intelligence and Machine Learning (FAIML)},  \n" + "title={EAMR: An Emotion-aware Music Recommender Method via Mel Spectrogram and Arousal-Valence Model},  \n" + "year={2022}, \n" + "pages={57-64},}",
	"2021HPD5A": "@article{2021HPD5A, \n" + "title = {Precise head pose estimation on HPD5A database for attention recognition based on convolutional neural network in human-computer interaction}, \n" + "journal = {Infrared Physics \\& Technology}, \n" + "volume = {116}, \n" + "pages = {103740}, \n" + "year = {2021}, \n" + "author = {Hai Liu and Duantengchuan Li and Xiang Wang and Leyuan Liu and Zhaoli Zhang and Sriram Subramanian},}",
	"2021RSGCN": "@InProceedings{2021RSGCN, \n" + "author={Wu, Fan and Li, Duantengchuan and Lin, Ke and Zhang, Huawei}, \n" + "title={Efficient Nodes Representation Learning with Residual Feature Propagation}, \n" + "booktitle={Advances in Knowledge Discovery and Data Mining},  \n" + "year={2021},  \n" + "pages={156-167},}",
	"2021CARM": "@article{2021CARM,  \n" + "title = {CARM: Confidence-aware recommender model via review representation learning and historical rating behavior in the online platforms},  \n" + "journal = {Neurocomputing}, \n" + "volume = {455}, \n" + "pages = {283-296}, \n" + "year = {2021}, \n" + "author = {Duantengchuan Li and Hai Liu and Zhaoli Zhang and Ke Lin and Shuai Fang and Zhifei Li and Neal N. Xiong},}" };
        function showAlert(aa) {
           prompt("请复制下列的BibTex内容，然后粘贴到对应的.bib文件中。", references[aa]);
        }
    </script>
</head>
<body>
</body>
</html>









# 📝 Publications 

**Joint first authors are indicated using #, and corresponding authors using \***.

## 🤖 Recommender System

- [Joint inter-word and inter-sentence multi-relation modeling for summary-based recommender system](https://linkinghub.elsevier.com/retrieve/pii/S0306457323003680). **D. Li**, et al. **<font color=BlueViolet>Information Processing & Management</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024MRSR')">[Bib]</span>, **[[PDF](_pages/paper/2024-MRSR.pdf)]**

- [Integrating user short-term intentions and long-term preferences in heterogeneous hypergraph networks for sequential recommendation](https://linkinghub.elsevier.com/retrieve/pii/S0306457324000402). B. Liu<sup>#</sup>, **D. Li<sup>#</sup>**, et al. **<font color=BlueViolet>Information Processing & Management</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024IPSRec')">[Bib]</span>

- [BGCL: Bi-subgraph network based on graph contrastive learning for cold-start QoS prediction](https://linkinghub.elsevier.com/retrieve/pii/S0950705123000461). J. Zhu, B. Li, J. Wang, **D. Li**, et al. **<font color=BlueViolet>Knowledge-Based Systems</font>**, **<font color=BlueViolet>2023</font>**. (SCI 1区Top, CCF C) <span style="color:blue; cursor:pointer;" onclick="showAlert('2023BGCL')">[Bib]</span>

- [EDMF: Efficient Deep Matrix Factorization With Review Feature Learning for Industrial Recommender System](https://ieeexplore.ieee.org/document/9616457). H Liu, C Zheng, **D Li\***, et al. **<font color=BlueViolet>IEEE Transactions on Industrial Informatics</font>**, **<font color=BlueViolet>2022</font>**. (SCI 1区Top, CCF C) <span style="color:blue; cursor:pointer;" onclick="showAlert('2022EDMF')">[Bib]</span>

- [Multi-perspective social recommendation method with graph representation learning](https://linkinghub.elsevier.com/retrieve/pii/S0925231221015368). H. Liu, C. Zheng, **D. Li**, et al. **<font color=BlueViolet>Neurocomputing</font>**, **<font color=BlueViolet>2022</font>**. (SCI 2区Top, CCF C) <span style="color:blue; cursor:pointer;" onclick="showAlert('2022MPSR')">[Bib]</span>

- [EAMR: An Emotion-aware Music Recommender Method via Mel Spectrogram and Arousal-Valence Model](https://ieeexplore.ieee.org/document/9969215). Z. Fu, Z. Zhang, J. Zheng, K. Lin and **D. Li**. 2022 International Conference on Frontiers of Artificial Intelligence and Machine Learning (FAIML), 2022. <span style="color:blue; cursor:pointer;" onclick="showAlert('2022EAMR')">[Bib]</span>

- [CARM: Confidence-aware recommender model via review representation learning and historical rating behavior in the online platforms](https://linkinghub.elsevier.com/retrieve/pii/S0925231221005142). **D. Li**, et al. **<font color=BlueViolet>Neurocomputing</font>**, **<font color=BlueViolet>2021</font>**. (SCI 2区Top) <span style="color:blue; cursor:pointer;" onclick="showAlert('2021CARM')">[Bib]</span>


## 🌐 Knowledge Graph
- [Multi-perspective knowledge graph completion with global and interaction features](https://linkinghub.elsevier.com/retrieve/pii/S0020025524003517). **D. Li**, et al. **<font color=BlueViolet>Information Sciences</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024MGIF')">[Bib]</span>

- [SDFormer: A shallow-to-deep feature interaction for knowledge graph embedding](https://linkinghub.elsevier.com/retrieve/pii/S095070512301002X). **D. Li**, et al. **<font color=BlueViolet>Knowledge-Based Systems</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF C) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024SDFormer')">[Bib]</span>
 
- [Knowledge graph representation learning with simplifying hierarchical feature propagation](https://linkinghub.elsevier.com/retrieve/pii/S0306457323000857). Z. Li, Q. Zhang, F. Zhu, **D. Li\***, et al. **<font color=BlueViolet>Information Processing & Management</font>**, **<font color=BlueViolet>2023</font>**. (SCI 1区Top, CCF B) <span style="color:blue; cursor:pointer;" onclick="showAlert('2023SHGNet')">[Bib]</span>

- [Knowledge graph embedding model with attention-based high-low level features interaction convolutional network](https://linkinghub.elsevier.com/retrieve/pii/S0306457323000870). J. Wang, Q. Zhang, F. Shi, **D. Li\***, et al. **<font color=BlueViolet>Information Processing & Management</font>**, **<font color=BlueViolet>2023</font>**. (SCI 1区Top, CCF B) <span style="color:blue; cursor:pointer;" onclick="showAlert('2023ConvHLE')">[Bib]</span>


## 📚 Large Language Model

- Prompt Space Optimizing Few-shot Reasoning Success with Large Language Models. F. Shi, P. Qing, D. Yang, N. Wang, Y. Lei, H. Lu, X. Lin, **D. Li**. **<font color=BlueViolet>NAACL</font>** Findings **<font color=BlueViolet>2024</font>**. (CCF B) 
  
## 📷 Computer Vision

- [DADL: Double Asymmetric Distribution Learning for head pose estimation in wisdom museum](https://linkinghub.elsevier.com/retrieve/pii/S1319157823004238). W. Zhao, S. Wang, X. Wang, **D. Li\***, et al. **<font color=BlueViolet>Journal of King Saud University-Computer and Information Sciences</font>**, **<font color=BlueViolet>2024</font>**. (SCI 2区) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024DADL')">[Bib]</span>

- [GCANet: Geometry cues-aware facial expression recognition based on graph convolutional networks](https://linkinghub.elsevier.com/retrieve/pii/S1319157823001593). S. Wang, A. Zhao, C. Lai, Q. Zhang, **D. Li**, et al. **<font color=BlueViolet>Journal of King Saud University-Computer and Information Sciences</font>**, **<font color=BlueViolet>2023</font>**. (SCI 2区) <span style="color:blue; cursor:pointer;" onclick="showAlert('2023GCANet')">[Bib]</span>

- [MFDNet: Collaborative Poses Perception and Matrix Fisher Distribution for Head Pose Estimation](https://ieeexplore.ieee.org/document/9435939). H. Liu, S. Fang, Z. Zhang, **D. Li\***, et al. **<font color=BlueViolet>IEEE Transactions Multimedia</font>**, **<font color=BlueViolet>2022</font>**. (SCI 1区Top, CCF B) <span style="color:blue; cursor:pointer;" onclick="showAlert('2022MFDNet')">[Bib]</span>

- [Precise head pose estimation on HPD5A database for attention recognition based on convolutional neural network in human-computer interaction](https://linkinghub.elsevier.com/retrieve/pii/S1350449521001122). H. Liu, **D. Li\***, et al. **<font color=BlueViolet>Infrared Physics & Technology</font>**, **<font color=BlueViolet>2021</font>**. (SCI 2区) <span style="color:blue; cursor:pointer;" onclick="showAlert('2021HPD5A')">[Bib]</span>


## 🔍 Reinforcement Learning

- [FHCPL: An Intelligent Fixed-Horizon Constrained Policy Learning System for Risk-Sensitive Industrial Scenario](https://ieeexplore.ieee.org/document/10368334/). K. Lin, **D Li**, et al. **<font color=BlueViolet>IEEE Transactions on Industrial Informatics</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF C) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024FHCPL')">[Bib]</span>

- [Motion Planner with Fixed-Horizon Constrained Reinforcement Learning for Complex Autonomous Driving Scenarios](https://ieeexplore.ieee.org/document/10120952/). K. Lin, Y. Li, S. Chen, **D. Li** and X. Wu. **<font color=BlueViolet>IEEE Transactions on Intelligent Vehicles</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024MPAD')">[Bib]</span>

- [TAG: Teacher-Advice Mechanism With Gaussian Process for Reinforcement Learning](https://ieeexplore.ieee.org/document/10093911). K. Lin, **D. Li**, et al. **<font color=BlueViolet>IEEE Transactions on Neural Networks and Learning Systems</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024TAG')">[Bib]</span>

- Reinforcement Learning-based Streaming Process Discovery under Concept Drift. Cai, C. Zheng, J. Wang, **D. Li**, et al. 36th International Conference on Advanced Information Systems Engineering (CAiSE 2024) (CCF B) 

- [Almost surely safe exploration and exploitation for deep reinforcement learning with state safety estimation](https://www.sciencedirect.com/science/article/abs/pii/S0020025524001749) K. Lin, Y. Li, Q. Liu, **D. Li**, et al. **<font color=BlueViolet>Information Sciences</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024SPPO')">[Bib]</span>

- [Attention-Based Deep Reinforcement Learning for Edge User Allocation](https://ieeexplore.ieee.org/document/10172271/). J. Chang, J. Wang, B. Li, Y. Zhao and **D. Li**. **<font color=BlueViolet>IEEE Transactions on Network and Service Management</font>**, **<font color=BlueViolet>2024</font>**. (SCI 2区) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024DSAM')">[Bib]</span>

- [A Deep Reinforcement Learning-Based Pointer Scoring Network for Edge Task Scheduling](https://ieeexplore.ieee.org/document/10248259). Y. Zhao, D. Jiang, B. Li, L. Fu, J. Wang and **D. Li**. **<font color=BlueViolet>ICWS</font>**, **<font color=BlueViolet>2023</font>**. (CCF B) <span style="color:blue; cursor:pointer;" onclick="showAlert('2023PSNet')">[Bib]</span>

- [Integrating deep reinforcement learning with pointer networks for service request scheduling in edge computing](https://linkinghub.elsevier.com/retrieve/pii/S0950705122010760). Y. Zhao, B. Li, J. Wang, D. Jiang, **D. Li**. **<font color=BlueViolet>Knowledge-Based Systems</font>**, **<font color=BlueViolet>2022</font>**. (SCI 1区Top, CCF C) <span style="color:blue; cursor:pointer;" onclick="showAlert('2022RLPNet')">[Bib]</span>

  
## 📠 Others
- [PBScaler: A Bottleneck-aware Autoscaling Framework for Microservice-based Applications](https://ieeexplore.ieee.org/document/10468626/). S. Xie, J. Wang, B. Li, Z. Zhang, **D. Li**, et al. **<font color=BlueViolet>IEEE Transactions on Services Computing</font>**, **<font color=BlueViolet>2024</font>**. (SCI 2区, CCF A) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024PBScaler')">[Bib]</span>

- [MDLR: A Multi-Task Disentangled Learning Representations for unsupervised time series domain adaptation](https://linkinghub.elsevier.com/retrieve/pii/S0306457323003758). Y. Liu, **D. Li\***, et al. **<font color=BlueViolet>Information Processing & Management</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B) <span style="color:blue; cursor:pointer;" onclick="showAlert('2024MDLR')">[Bib]</span>

- [Multi-information fusion based few-shot Web service classification](https://www.sciencedirect.com/science/article/abs/pii/S0167739X2100501X). Y. Liu, B. Li, J. Wang , **D. Li** , et al. **<font color=BlueViolet>Future Generation Computer Systems</font>**, **<font color=BlueViolet>2022</font>**. (SCI 2区Top, CCF C) <span style="color:blue; cursor:pointer;" onclick="showAlert('2022MIF-FWSC')">[Bib]</span>
  
- [Efficient Nodes Representation Learning with Residual Feature Propagation](http://link.springer.com/chapter/10.1007/978-3-030-75765-6_13). F. Wu, **D. Li\***, et al. **<font color=BlueViolet>PAKDD</font>**, **<font color=BlueViolet>2021</font>**. (CCF C) <span style="color:blue; cursor:pointer;" onclick="showAlert('2021RSGCN')">[Bib]</span>
