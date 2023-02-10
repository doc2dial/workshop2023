---
layout: single
title: DialDoc Workshop
author_profile: false
toc: true
toc_sticky: true
---
***co-located with ACL 2023***

## About

Welcome to the Third DialDoc Workshop co-located with [ACL 2023](https://2023.aclweb.org).

The DialDoc workshop focuses on Document-Grounded Dialogue and Conversational Question Answering.
Given the vast amount of content created every day in various mediums, it is a meaningful yet challenging task not only
to make such content _accessible_ to end users via various conversational interfaces, but also to make sure the responses
provided by the models are `grounded` and `faithful` with respect to the knowledge sources. 

<span style="color:#d65d0e"> ***Special Theme*** </span> For our third workshop, we would like to highlight the theme of **_Factual Consistency_**. With recent advances of large language models, a major issue may arise when systems generate responses that include factual inconsistencies with respect to external sources, creating implications on user trust and safety. We seek submissions that tackle challenges around this issue, including, but not limited to, automatic evaluation methods, human evaluation, modeling techniques and datasets.


***Shared Task*** We also host a shared task on grounded dialogue based on multilingual documents, which aims to extend the current advances to languages other than English.

Topics of interests include, but are not limited to:

- Document-grounded dialogue and conversational machine reading;
- Knowledge-grounded dialogue generation with pre-trained language models;
- Open domain dialogue and conversational QA;
- Topical open-domain conversational chat;
- Parsing semi-structured document content for dialogue and conversational QA, table reading;
- Evaluation for document-grounded dialogue;
- Interpretability and faithfulness in dialogue modeling;
- Dialogue summarization and query-based summarization.

## Call for Papers

We welcome submissions of original work as long or short papers, as well as non-archival papers. We also accept papers
submitted via ARR as either archival or non-archival submissions. All accepted papers will be presented at the workshop.

We will have the Best Paper Award and Best Student Paper Award, which will be announced during the workshop.

### Submission Instructions

Formatting Guidelines:
We accept long (eight pages plus unlimited references) and short (four pages plus unlimited references) papers, which
should conform to ARR CFP guidelines.

Non-Archival Submissions:
The accepted papers can opt to be non-archival.

The submission site on OpenReview is available [here](https://openreview.net/group?id=aclweb.org/ACL/2023/Workshop/DialDoc).

### Review Process

All submissions will be peer-reviewed by at least two reviewers. The reviewing process will be two-way anonymized.
Authors are responsible for anonymizing their submissions.

### Important Dates

- Direct paper submissions: April 24, 2023
- Paper submissions with ARR reviews: April 24, 2023
- Notification of Acceptance: May 22, 2023
- Camera-ready Paper Due Date: May 30, 2023
- Pre-recorded video due: June 12, 2023
- Workshop Date: July 13 or 14, 2023


## Shared Task

### Task1 Mixed-lingual Document-grounded Dialogue

We will provide annotated data in English, Chinese, French, and Vietnamese for training; and then evaluate models in all
four languages.

Training: document set contains 4 languages and we have sample conversations grounded on documents of 4 languages.
Testing: testing conversations in 4 languages which contain evidences in documents of 4 languages

### Task2 Cross-lingual Document-grounded Dialogue

We will provide sizable annotated data in a source language (e.g. English) and limited data in the target language for
training; then evaluate the models in the target language for the settings such as English-to-Chinese and
Chinese-to-Vietnamese.

Training: document set and conversation set with grounding labels in English and/or Chinese.
Testing: testing conversations in French and/or Vietnamese which contain evidences in documents of 2 source languages (
English, Chinese)

### Important Dates

The challenge includes leaderboards for two task settings with two phases, Dev (TestDev) and Test phase,

- Datasets ready & Baseline Models : February 6, 2023
- Dev Phase Start : February 13, 2023
- Test Phase Start : March 25, 2023
- Date of Leaderboard submission：March 31, 2023
- Paper submission: April 24, 2023

## Invited Speakers

{% include committee-member.html
name="Greg Durrett"
picture="./assets/images/speakers/greg_durrett.jpg"
site="https://www.cs.utexas.edu/~gdurrett/"
institution="The University of Texas at Austin"
%}

{% include committee-member.html
name="Hannaneh Hajishirzi"
picture="./assets/images/speakers/hannaneh_hajishirzi.jpg"
site="https://homes.cs.washington.edu/~hannaneh/"
institution="University of Washington"
%}

{% include committee-member.html
name="Xiang Ren"
picture="./assets/images/speakers/xiang_ren.jpg"
site="https://shanzhenren.github.io/"
institution="University of Southern California"
%}

{% include committee-member.html
name="Rui Yan"
picture="./assets/images/speakers/rui_yan.jpg"
site="http://ai.ruc.edu.cn/english/GSAI_FACULTY/28026f7425324f61991c70d279372d13.htm"
institution="Renmin University of China"
%}

## Organization

### Workshop Organizers

{% include committee-member.html
name="Roee Aharoni"
picture="./assets/images/organizers/roee_aharoni.jpg"
site="http://roeeaharoni.com"
institution="Google Research"
%}

{% include committee-member.html
name="Nouha Dziri"
picture="./assets/images/organizers/nouha_dziri.jpg"
site="https://webdocs.cs.ualberta.ca/~dziri/"
institution="AllenAI"
%}

{% include committee-member.html
name="Song Feng"
picture="./assets/images/organizers/song_feng.jpg"
site="https://songfeng.github.io"
institution="AWS AI Labs"
%}

{% include committee-member.html
name="Yongbin Li"
picture="./assets/images/organizers/yongbin_li.jpg"
site=""
institution="DAMO Academy, Alibaba Group"
%}

{% include committee-member.html
name="Yu Li"
picture="./assets/images/organizers/yu_li.jpg"
site="http://yooli.me"
institution="Columbia University"
%}

{% include committee-member.html
name="Hui Wan"
picture="./assets/images/organizers/hui_wan.jpg"
site="https://sites.google.com/view/hui-wan/"
institution="IBM Research AI"
%}

### Shared Task Organizers

{% include committee-member.html
name="Haiyang Yu"
picture="./assets/images/organizers/haiyang_yu.jpg"
site=""
institution="DAMO Academy, Alibaba Group"
%}

{% include committee-member.html 
name="Cam-Tu Nguyen" 
picture="./assets/images/organizers/nguyencamtu.jpg" 
site="" 
institution="State Key Laboratory for Novel Software Technology, Nanjing University" 
%}

{% include committee-member.html 
name="Bowen Yu" 
picture="./assets/images/organizers/bowenyu.jpg"
site="https://yubowen-ph.github.io/" 
institution="DAMO Academy, Alibaba Group" 
%}

{% include committee-member.html 
name="Haomin Fu" 
picture="./assets/images/organizers/fuhaomin.jpg" 
site="" 
institution="State Key Laboratory for Novel Software Technology, Nanjing University" 
%}

{% include committee-member.html 
name="Yeqin Zhang"
picture="./assets/images/organizers/zhangyeqin.jpg" 
site="" 
institution="State Key Laboratory for Novel Software Technology, Nanjing University" 
%}
### Program Committee

Srijan Bansal	(Carnegie Mellon University)  \
Daniele Bonadiman	(Amazon) \
Pengshan Cai	(University of Massachusetts - UMass Amherst) \
Danish Contractor	(IBM Research AI) \
Le Anh Cuong	(Ton Duc Thang University, Vietnam \
Nico Daheim	(Technische Universität Darmstadt) \
Sam Davidson	(UC Davis) \
Wanyu Du	(University of Virginia) \
Hao Fang	(Microsoft) \
Jatin Ganhotra	(IBM Research AI) \
Chang Gao	(The Chinese University of Hong Kong) \
Chulaka Gunasekara	(IBM Research AI) \
Ankita Gupta	(University of Massachusetts - UMass Amherst) \
Han He	(Emory University) \
Xiangkun Hu	(Amazon) \
Etsuko Ishii	(Hong Kong University of Science and Technology) \
Ehsan Kamalloo	(University of Alberta) \
Zichao Li	(McGill / Mila) \
Xing Han Lu	(McGill / Mila) \
Tran Thi Oanh	(Vietnam National University, Vietnam) \
Baolin Peng	(Microsoft) \
Xuan-Hieu Phan	(Vietnam National University, Vietnam) \
Kun Qian	(Columbia University) \
Le Hoang Quynh	(Vietnam National University, Vietnam) \
Min Yang	(Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences) \
Bowen Yu	(DAMO Academy Alibaba Group)


## Contact

Please join our [Google Group](https://groups.google.com/g/dialdoc) for the updates!

Please email us at [dialdoc2023-organizers@@googlegroups.com](dialdoc2023-organizers@@googlegroups.com) for questions
and suggestions.
