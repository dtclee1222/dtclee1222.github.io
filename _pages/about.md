---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}



<span class='anchor' id='about-me'></span>

Dr. Lee at IEEE Transactions on Neural Networks and Learning Systems, IEEE Transactions on Network and Service Management, IEEE Transactions on Intelligent Vehicles,  IEEE Transactions on Services Computing, IEEE Transactions on Multimedia, Information Processing & Management,  Future Generation Computer Systems, Knowledge Based Systems, Information Sciences,  Engineering Applications of Artificial Intelligence, Infrared Physics & Technology, Neurocomputing, CAiSE, NAACL, ICWS,  PAKDD and other journals & conferences published a number of papers and served as the Reviewer of the above journals & conferences. He research interest includes recommended system, knowledge graph, reinforcement learning, automated driving, large language model, computer vision, video understanding, etc. He has published more than 30+ papers at the top Journals and international conferences with total <a href='https://scholar.google.com/citations?user=VDzqb5UAAAAJ'>google scholar citations <strong><span id='total_cit'>500+</span></strong></a>. 

Dr. Lee is also currently the Director of the Data Analysis and Cognitive Inference (DACI) Laboratory, The [DACI Laboratory](https://www.dacilab.com) focus on solving practical problems in intelligent education, digital humanities, sports & health, and smart factory. 




<html>
<head>
    <title>点击弹出文本框</title>
    <style>
        /* 模态框样式 */
        .modal {
            display: none; /* 默认隐藏模态框 */
            position: fixed; /* 固定位置 */
            z-index: 1; /* 设置在页面最前面 */
            padding-top: 100px; /* 位置调整 */
            left: 0;
            top: 0;
            width: 100%; /* 宽度占满屏幕 */
            height: 100%; /* 高度占满屏幕 */
            overflow: auto; /* 超出时可以滚动 */
            background-color: rgb(0,0,0); /* 背景颜色 */
            background-color: rgba(0,0,0,0.4); /* 透明度 */
        }

        /* 模态内容样式 */
        .modal-content {
            background-color: #fefefe;
            margin: auto;
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
        }

        /* 关闭按钮样式 */
        .close {
            color: #aaaaaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }

        .close:hover,
        .close:focus {
            color: #000;
            text-decoration: none;
            cursor: pointer;
        }
    </style>
</head>
<body>



<!-- 模态框 -->
<div id="myModal" class="modal">

  <!-- 模态内容 -->
  <div class="modal-content">
    <span class="close">&times;</span>
    <pre id="modalText">文本内容将在这里显示</pre>
  </div>

</div>

<script type="text/javascript">
    const responses = {
        "SD": "@article{2024MRSR,\n title = {Joint inter-word and inter-sentence multi-relation modeling for summary-based recommender system},\n journal = {Information Processing & Management},\n author = {Duantengchuan Li and Ceyu Deng and Xiaoguang Wang and Zhifei Li and Chao Zheng and Jing Wang and Bing Li}",
        "你好": "hello",
        "喝喝茶": "斤斤计较",
        "111": "不好办",
        "bib": "参考文献",
        "和承诺不错": "达达调查"
    };

    // 显示模态框
    function showModal(key) {
        document.getElementById('modalText').innerText = responses[key];
        document.getElementById('myModal').style.display = "block";
    }

    // 获取关闭按钮并添加关闭事件
    var span = document.getElementsByClassName("close")[0];
    span.onclick = function() {
        document.getElementById('myModal').style.display = "none";
    }

    // 点击窗口外关闭模态框
    window.onclick = function(event) {
        if (event.target == document.getElementById('myModal')) {
            document.getElementById('myModal').style.display = "none";
        }
    }
</script>

</body>
</html>


<p>点击下面的文本:</p>
<span style="color:blue; cursor:pointer;" onclick="showModal('SD')">123</span>

# 🔥 News
- *2024.03*: &nbsp;🎉🎉 One papers are accepted by IEEE Transactions on Services Computing
- *2024.03*: &nbsp;🎉🎉 One papers are accepted by Information Sciences
- *2024.01*: &nbsp;🎉🎉 One papers are accepted by Information Processing & Management
- *2023.12*: &nbsp;🎉🎉 Two papers are accepted by Information Processing & Management
- *2023.11*: &nbsp;🎉🎉 One papers are accepted by Knowledge-Based Systems
- *2023.05*: &nbsp;🎉🎉 One papers are accepted by IEEE Transactions on Intelligent Vehicles
- *2023.04*: &nbsp;🎉🎉 One papers are accepted by IEEE Transactions on Neural Networks and Learning Systems

# 📝 Publications 

**Joint first authors are indicated using #, and corresponding authors using \***.

## 🤖 Recommender System

- [Joint inter-word and inter-sentence multi-relation modeling for summary-based recommender system](https://linkinghub.elsevier.com/retrieve/pii/S0306457323003680). **D. Li**, et al. **<font color=BlueViolet>Information Processing & Management</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B)

- [Integrating user short-term intentions and long-term preferences in heterogeneous hypergraph networks for sequential recommendation](https://linkinghub.elsevier.com/retrieve/pii/S0306457324000402). B. Liu<sup>#</sup>, **D. Li<sup>#</sup>**, et al. **<font color=BlueViolet>Information Processing & Management</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B)

- [BGCL: Bi-subgraph network based on graph contrastive learning for cold-start QoS prediction](https://linkinghub.elsevier.com/retrieve/pii/S0950705123000461). J. Zhu, B. Li, J. Wang, **D. Li**, et al. **<font color=BlueViolet>Knowledge-Based Systems</font>**, **<font color=BlueViolet>2023</font>**. (SCI 1区Top, CCF C)

- [EDMF: Efficient Deep Matrix Factorization With Review Feature Learning for Industrial Recommender System](https://ieeexplore.ieee.org/document/9616457). H Liu, C Zheng, **D Li\***, et al. **<font color=BlueViolet>IEEE Transactions on Industrial Informatics</font>**, **<font color=BlueViolet>2022</font>**. (SCI 1区Top, CCF C)

- [Multi-perspective social recommendation method with graph representation learning](https://linkinghub.elsevier.com/retrieve/pii/S0925231221015368). H. Liu, C. Zheng, **D. Li**, et al. **<font color=BlueViolet>Neurocomputing</font>**, **<font color=BlueViolet>2022</font>**. (SCI 2区Top, CCF C)

- [EAMR: An Emotion-aware Music Recommender Method via Mel Spectrogram and Arousal-Valence Model](https://ieeexplore.ieee.org/document/9969215). Z. Fu, Z. Zhang, J. Zheng, K. Lin and **D. Li**. 2022 International Conference on Frontiers of Artificial Intelligence and Machine Learning (FAIML), Hangzhou, China, 2022, pp. 57-64.

- [CARM: Confidence-aware recommender model via review representation learning and historical rating behavior in the online platforms](https://linkinghub.elsevier.com/retrieve/pii/S0925231221005142). **D. Li**, et al. **<font color=BlueViolet>Neurocomputing</font>**, **<font color=BlueViolet>2021</font>**. (SCI 2区Top)


## 🌐 Knowledge Graph
- [Multi-perspective knowledge graph completion with global and interaction features](https://linkinghub.elsevier.com/retrieve/pii/S0020025524003517). **D. Li**, et al. **<font color=BlueViolet>Information Sciences</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B)

- [SDFormer: A shallow-to-deep feature interaction for knowledge graph embedding](https://linkinghub.elsevier.com/retrieve/pii/S095070512301002X). **D. Li**, et al. **<font color=BlueViolet>Knowledge-Based Systems</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF C)
 
- [Knowledge graph representation learning with simplifying hierarchical feature propagation](https://linkinghub.elsevier.com/retrieve/pii/S0306457323000857). Z. Li, Q. Zhang, F. Zhu, **D. Li\***, et al. **<font color=BlueViolet>Information Processing & Management</font>**, **<font color=BlueViolet>2023</font>**. (SCI 1区Top, CCF B)

- [Knowledge graph embedding model with attention-based high-low level features interaction convolutional network](https://linkinghub.elsevier.com/retrieve/pii/S0306457323000870). J. Wang, Q. Zhang, F. Shi, **D. Li\***, et al. **<font color=BlueViolet>Information Processing & Management</font>**, **<font color=BlueViolet>2023</font>**. (SCI 1区Top, CCF B)


## 📚 Large Language Model

- Prompt Space Optimizing Few-shot Reasoning Success with Large Language Models. F. Shi, P. Qing, D. Yang, N. Wang, Y. Lei, H. Lu, X. Lin, **D. Li**. **<font color=BlueViolet>NAACL</font>** Findings **<font color=BlueViolet>2024</font>**. (CCF B)

  
## 📷 Computer Vision

- [DADL: Double Asymmetric Distribution Learning for head pose estimation in wisdom museum](https://linkinghub.elsevier.com/retrieve/pii/S1319157823004238). W. Zhao, S. Wang, X. Wang, **D. Li\***, et al. **<font color=BlueViolet>Journal of King Saud University-Computer and Information Sciences</font>**, **<font color=BlueViolet>2024</font>**. (SCI 2区)

- [GCANet: Geometry cues-aware facial expression recognition based on graph convolutional networks](https://linkinghub.elsevier.com/retrieve/pii/S1319157823001593). S. Wang, A. Zhao, C. Lai, Q. Zhang, **D. Li**, et al. **<font color=BlueViolet>Journal of King Saud University-Computer and Information Sciences</font>**, **<font color=BlueViolet>2023</font>**. (SCI 2区)

- [MFDNet: Collaborative Poses Perception and Matrix Fisher Distribution for Head Pose Estimation](https://ieeexplore.ieee.org/document/9435939). H. Liu, S. Fang, Z. Zhang, **D. Li\***, et al. **<font color=BlueViolet>IEEE Transactions Multimedia</font>**, **<font color=BlueViolet>2022</font>**. (SCI 1区Top, CCF B)

- [Precise head pose estimation on HPD5A database for attention recognition based on convolutional neural network in human-computer interaction](https://linkinghub.elsevier.com/retrieve/pii/S1350449521001122). H. Liu, **D. Li\***, et al. **<font color=BlueViolet>Infrared Physics & Technology</font>**, **<font color=BlueViolet>2021</font>**. (SCI 2区)


## 🔍 Reinforcement Learning

- [FHCPL: An Intelligent Fixed-Horizon Constrained Policy Learning System for Risk-Sensitive Industrial Scenario](https://ieeexplore.ieee.org/document/10368334/). K. Lin, **D Li**, et al. **<font color=BlueViolet>IEEE Transactions on Industrial Informatics</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF C)

- [Motion Planner with Fixed-Horizon Constrained Reinforcement Learning for Complex Autonomous Driving Scenarios](https://ieeexplore.ieee.org/document/10120952/). K. Lin, Y. Li, S. Chen, **D. Li** and X. Wu. **<font color=BlueViolet>IEEE Transactions on Intelligent Vehicles</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区)

- [TAG: Teacher-Advice Mechanism With Gaussian Process for Reinforcement Learning](https://ieeexplore.ieee.org/document/10093911). K. Lin, **D. Li**, et al. **<font color=BlueViolet>IEEE Transactions on Neural Networks and Learning Systems</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B)

- Reinforcement Learning-based Streaming Process Discovery under Concept Drift. Cai, C. Zheng, J. Wang, **D. Li**, et al. 36th International Conference on Advanced Information Systems Engineering (CAiSE 2024) (CCF B)

- [Almost surely safe exploration and exploitation for deep reinforcement learning with state safety estimation](https://www.sciencedirect.com/science/article/abs/pii/S0020025524001749) K. Lin, Y. Li, Q. Liu, **D. Li**, et al. **<font color=BlueViolet>Information Sciences</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B)

- [Attention-Based Deep Reinforcement Learning for Edge User Allocation](https://ieeexplore.ieee.org/document/10172271/). J. Chang, J. Wang, B. Li, Y. Zhao and **D. Li**. **<font color=BlueViolet>IEEE Transactions on Network and Service Management</font>**, **<font color=BlueViolet>2024</font>**. (SCI 2区)

- [A Deep Reinforcement Learning-Based Pointer Scoring Network for Edge Task Scheduling](https://ieeexplore.ieee.org/document/10248259). Y. Zhao, D. Jiang, B. Li, L. Fu, J. Wang and **D. Li**. **<font color=BlueViolet>ICWS</font>**, **<font color=BlueViolet>2023</font>**. (CCF B)

- [Integrating deep reinforcement learning with pointer networks for service request scheduling in edge computing](https://linkinghub.elsevier.com/retrieve/pii/S0950705122010760). Y. Zhao, B. Li, J. Wang, D. Jiang, **D. Li**. **<font color=BlueViolet>Knowledge-Based Systems</font>**, **<font color=BlueViolet>2022</font>**. (SCI 1区Top, CCF C)

  
## 📠 Others
- [PBScaler: A Bottleneck-aware Autoscaling Framework for Microservice-based Applications](https://ieeexplore.ieee.org/document/10468626/). S. Xie, J. Wang, B. Li, Z. Zhang, **D. Li**, et al. **<font color=BlueViolet>IEEE Transactions on Services Computing</font>**, **<font color=BlueViolet>2024</font>**. (SCI 2区, CCF A)

- [MDLR: A Multi-Task Disentangled Learning Representations for unsupervised time series domain adaptation](https://linkinghub.elsevier.com/retrieve/pii/S0306457323003758). Y. Liu, **D. Li\***, et al. **<font color=BlueViolet>Information Processing & Management</font>**, **<font color=BlueViolet>2024</font>**. (SCI 1区Top, CCF B)

- [Multi-information fusion based few-shot Web service classification](https://www.sciencedirect.com/science/article/abs/pii/S0167739X2100501X). Y. Liu, B. Li, J. Wang , **D. Li** , et al. **<font color=BlueViolet>Future Generation Computer Systems</font>**, **<font color=BlueViolet>2022</font>**. (SCI 2区Top, CCF C)
  
- [Efficient Nodes Representation Learning with Residual Feature Propagation](http://link.springer.com/chapter/10.1007/978-3-030-75765-6_13). F. Wu, **D. Li\***, et al. **<font color=BlueViolet>PAKDD</font>**, **<font color=BlueViolet>2021</font>**. (CCF C)





# 🎖 Honors and Awards
- *2023.04* 'Internet+' Competition (Bronze award), Person in charge
- *2019.12* National Scholarship
- *2017.06* Provincial outstanding graduates
- *2016.11* Network Engineer (intermediate level), Qualification Certification of Computer and Software Technology Proficiency
- *2015.12* Provincial Government Scholarship
- *2015.06* Provincial Merit Student

  
# 📖 Educations
- *2022 - now*, Wuhan University, Assistant researcher. 
- *2021 - 2024*, Doctor, Wuhan University, Major: Software engineering. 
- *2018 - 2021*, Master, Central China Normal University, Major: Computer science and Technology.

# 💻 Internships
- *2022.04*, Autonomous Driving Decision Planning Engineer, IN-DRIVING


# 🖥️ DACI Lab

The members in Data Analysis and Cognitive Inference (DACI) Laboratory are mainly from Wuhan University, Huazhong University of Science and Technology, Harbin Institute of Technology (Shenzhen), Fudan University, Central China Normal University, China University of Geosciences (Wuhan), Hubei University, Hubei University of Technology, Wuhan Sports University, Beijing Sport University, and China Institute of Sport Science, etc. 

The main research interests of DACI Lab include: recommendation system, representation learning, natural language processing, intention recognition, pattern recognition, computer vision and their applications in software engineering, intelligent education, digital humanities, sports & health, and smart factory. The team has published more than 40 SCI papers and high-level conference and journal papers. The laboratory has more than 40 doctors and masters, focusing on solving practical theoretical and engineering problems through new technologies. The team has established long-term cooperation with Zhongnan Hospital of Wuhan University, China University of Geosciences (Wuhan), Huazhong University of Science and Technology, Chongqing University of Posts and Telecommunications, Hubei University, Hubei University of Technology, Jiangxi Normal University and other universities.

More info about Data Analysis and Cognitive Inference (DACI) Laboratory can be found in [THIS](https://www.dacilab.com). 

Welcome to join us! let's "Play" together!!!

# 🤝 Join DACI

目前大多数大学与研究生课程主要是以通识课为主，由于学制限制和其他原因，很难做到对每门课程以及最新前沿技术有非常细致的讲解。因此，实验室面向有志于将来从事相关领域科研工作的小伙伴提供学习与深造的机会，要求学生积极主动、有上进心。对于有意愿选择数据分析与认知推理（DACI）实验室作为学习和深造的小伙伴，为帮助您更加确信您的选择是否明智，请耐心阅读如下说明：

1.您需要在实验室主页了解我们相关的研究方向。在对相关方向了解后，您是否确实对您所选择的方向感兴趣？研究之路可能充满挫败感，如果没有足够的兴趣支撑，可能会感到痛苦，难以坚持下来。

2.您是否愿意将大部分精力投入于研究工作中？如果您有兼职工作或其他事情会占据您绝大多数时间，DACI实验室可能不是您的最佳选择。

3.实验室主要面向本科生（主要面向大一、大二本科生）、研究生（主要面向研一学生）因为这给了我们更多时间规划更为**长远而有意义、有趣的和好玩的工作**，并进行更为系统的科研训练。当然，这并不意味着我们不欢迎其他年级的学生。**由于实验室处于武汉市，遂主要面向的是武汉高校（省外学生如果进入实验室意愿极其强烈并且愿意花时间学习也可考虑）**。

4.对我们来说，理想的申请者大致是这样的：扎实的数学基础、熟练的英文读写能力、过硬的编程能力，同时逻辑思维清晰、表达能力强，最好还能乐观积极、坚韧不拔、亲和力强。当然理想和现实我们也是分得清的，但是只要你愿意花时间专研、不惧困难、踏实努力，我们都非常欢迎您成为我们的一员，因为我们认为态度决定一切！在实验室培养中也会非常重视上述能力的建设。

5.所有申请者都需要经过DACI实验室组织的面试才能被接受。面试的目的是给我们双方一个面对面了解对方的机会，以此来帮助您判断是否适合到DACI实验室学习。因此，被接受并不意味着成功，没被接受也不意味着失败。

6.进入实验室的学生需要了解和履行的要求请阅读（[DACI实验室招生说明](https://dtclee1222.github.io/_pages/DACI实验室招生说明.pdf)）。

7.申请材料（申请材料建议使用PDF格式）
- DACI实验室招生说明
- 带普通生活照的个人简历；
- 本科成绩单（硕士生提供）；
- 一页纸的“研究动机说明”；
- 其他有助于增进对您了解的材料（论文、专利、获奖等证明材料）
  
请将以上申请材料压缩发送至邮箱dacilab@aliyun.com，邮件标题命名为“学校-姓名.zip”格式命名，如“武汉大学-李四.zip”。

>DACI实验室鼓励大家参加各种运动，篮球🏀、足球⚽️、骑行🚵🏻‍♂️、羽毛球🏸、网球🎾、健身💪⛹️🏋️ 等(实验室有很多各种专项的专业运动员和健身教练，实验室每周都会组织一些集体运动)。 除此之外，每个月我们都至少举行一场小型音乐live，唱唱歌玩玩乐器，当然，实验室也有各种乐器，电钢🎹、吉他🎸、罗兰CUBE音箱🎶🎤、萨克斯🎷、还有雅马哈的一些编曲设备等，也欢迎喜欢玩音乐和编曲的小伙伴们加入DACI一起玩🎵。此外，实验室很鼓励大家阅读，实验室会定期购买不同领域的书籍（文史哲偏多），也希望大家能扩充自己的见解，扩展自己的知识面，从书中吸取养分。

**科研和项目不是生活的全部，一定需要诗和远方🪀🎶！！**

# 🗺️ Visitor Map
<script type="text/javascript" src="//rf.revolvermaps.com/0/0/8.js?i=5n3vikrc6v5&amp;m=8&amp;c=ff0000&amp;cr1=ffffff&amp;f=arial&amp;l=33" async="async"></script>


