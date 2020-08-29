# VLDB2020: Sponsor Talks

## Megagon Labs (Day 1, Block 2) [05S]

> Start at <span class="timeUTC">2020-09-01T12:00:00Z</span>

### Research on semantic types and language models at Megagon Labs
* Speakers: Çağatay Demiralp (presenting Sato) and Yuliang Li (presenting Ditto)

#### Abstract
Sato: Detecting the semantic types of data columns in relational tables is useful for myriad data preparation and information retrieval tasks such as data cleaning, schema matching, data discovery, and semantic search. We introduce Sato, a new learned model to automatically detect the semantic types of columns in tables, exploiting the signals from the context as well as the column values. Sato combines a deep learning model trained on a large-scale table corpus with topic modeling and structured prediction, outperforming the state-of-the-art by a large margin.

Ditto: We present Ditto, a novel entity matching (EM) system based on pre-trained language models. Ditto fine-tunes the language models and casts EM as a sequence-pair classification problem with a simple architecture. With optimizations such as injecting domain knowledge and data augmentation, Ditto achieves new state-of-the-art matching accuracies while being 2X more label-efficient than existing EM solutions.

#### Profiles of speakers:

Çağatay Demiralp is Senior Research Scientist at Megagon Labs. Çağatay’s research at Megagon focuses on solving problems at the intersection of Data Systems + Artificial Intelligence + Human-Computer Interaction at scale. Previously, he was a visiting researcher with the data systems group at MIT CSAIL and a research staff member at IBM Research. Between 2012-2014, Çağatay was a postdoctoral scholar at Stanford University and a member of IDL at the University of Washington. He obtained his Ph.D. from Brown University.

Yuliang Li is a senior research scientist at the Megagon Labs. He received his Ph.D. degree in computer science from UC San Diego where he was a member of the DB Lab. His research interests include data management, database theory, formal verification, and data mining.

----

## NEC (Day 1, Block 4) [19S]

> Start at <span class="timeUTC">2020-09-02T06:00:00Z</span>

### Data Management R&D at NEC
* Speakers: Jianquan Liu and Masafumi Oyamada

#### Abstract
Data Management R&D at NEC: Database Engages with Multimedia for Video Analysis
In this talk, Dr. Liu will give an overview of the research topics that are currently conducted at the Biometrics Research Laboratories of NEC Corporation, such as processing and analysis on multimedia big data. The talk will mainly focus on how NEC was/is engaging the techniques of database and multimedia for large-scale video surveillance in the past, present, and future, based on the related researches conducted in NEC. A series of our work published at MM'14, SIGGRAPH'16, MM'16, MM'17, SIGMOD'17, ICMR'18, MIPR'19, CBMI'19, BigMM'19, and MM'19, WACV'20, MM'20 will be highlighted with interesting insights. Finally, Dr. Liu will pick up some challenging issues and share some future directions of video analysis for surveillance, and the key applications of surveillance video search. Such directions would be helpful to guide the research of multimedia big data in the near future. 

Data Management R&D at NEC: How our service discovers insights from heterogeneous data
At NEC Corporation, our knowledge-based learning research team is developing a novel DataOps service that discovers insights from heterogeneous data in DataLakes without any pains. In this talk, we introduce our product and briefly introduce recently published research, such as semantic understanding of tabular data (AAAI'19)  and entity-attribute prediction on heterogeneous networks (ICDM'17). We also introduce exciting career opportunities at NEC Corporation by showing how researchers develop a new business at our companies.

#### Profiles of speakers:

Jianquan Liu is currently a principal researcher at the Biometrics Research Laboratories of NEC Corporation, working on the topics of multimedia data processing. He is also an adjunct assistant professor at Graduate School of Science and Engineering, Hosei University, Japan. Prior to NEC, he was a development engineer in Tencent Inc. from 2005 to 2006, and was a visiting researcher at the Chinese University of Hong Kong in 2010. His research interests include high-dimensional similarity search, multimedia databases, web data mining and information retrieval, cloud storage and computing, and social network analysis. He has published 50+ papers at major international/domestic conferences and journals, received 20+ international/domestic awards, and filed 40+ PCT patents. He also successfully transformed these technological contributions into commercial products in the industry. Currently, he is/was serving as the General Co-chair of IEEE MIPR 2021; the PC Co-chair of IEEE ICME 2020, AIVR 2019, BigMM 2019, ISM 2018, ICSC 2018, ISM 2017, ICSC 2017, IRC 2017, and BigMM 2016; the Workshop Co-chair of IEEE AKIE 2018 and ICSC 2016; the Demo Co-chair of IEEE MIPR 2019 and MIPR 2018. He is a member of ACM, IEEE, IPSJ, and the Database Society of Japan (DBSJ), a member of expert committee for IEICE Mathematical Systems Science and its Applications, and IEICE Data Engineering, and an associate editor of IEEE MultiMedia Magazine and the Journal of Information Processing (JIP). Dr.  Liu received the M.E. and Ph.D. degrees from the University of Tsukuba, Japan.

Masafumi Oyamada is a principal researcher in the Data Science Research Laboratories at NEC Corporation, leading knowledge-based learning research team. He is also a product manager of business innovation unit at NEC Corporation, managing BizDev of a novel DataOps service. His research focuses on extracting insights from heterogeneous data using data management technologies and machine learning technologies. He has published papers at leading venues, such as ICDM, AAAI, VLDB Journal, IEEE BigData, PAKDD, and SIGAPP ACR and received 10+ international/domestic awards. He is a member of AAAI, IPSJ, and the Database Society of Japan (DBSJ). He received the M.E. and Ph.D. degrees from the University of Tsukuba, Japan.

----

## Google (Day 2, Block 1) [25S]

> Start at <span class="timeUTC">2020-09-02T12:00:00Z</span>

### Building ML infra: A Database Perspective
* Speaker: Mingsheng Hong (hongm@google.com, twitter: @mingshenghong)

#### Abstract
ML infrastructure such as TensorFlow and PyTorch has been a strong center for research and engineering innovations over the past few years. These software systems share a number of common elements with SQL query engines, such as a declarative programming abstraction, a set of operators with rich algebraic properties, and a concurrent / distributed dataflow execution engine. At the same time, ML infra requirements feature a number of significant departures from relational / structure data processing, where the former often place a larger focus on supporting richer data types (e.g. texts, audio and video, additional to tabular data), involve different access patterns (e.g. repeated, shuffled scans over training data) and call for a more complex programming model (e.g. backprop support via Automatic Differentiation).

In this talk, we will cover a set of research and engineering problems in building ML infra, which we believe could benefit from the database community's insights and contributions.

#### Profiles of speaker:

Dr. Mingsheng Hong is the eng lead of TensorFlow runtime, Google's AI infrastructure. Prior to this role, Mingsheng worked in data infra eng leadership roles at Google, Hadapt and Vertica. Mingsheng obtained his Computer Science Ph.D. degree at Cornell University, and co-founded the Microsoft CEDR research project, commercialized as SQL Server StreamInsight.

----

## Alibaba Group (Day 3, Block 1) [45S]

> Start at <span class="timeUTC">2020-09-03T12:00:00Z</span>

### Introduction to the Data Analytics and Intelligence Lab at Alibaba
* Speakers: Bolin Ding, Kai Zeng, and Wenyuan Yu

#### Abstract
The Data Analytics and Intelligence Lab in Alibaba is committed to the research and development of next-generation systems and algorithms for data management, query processing, analytics, and machine learning on massive and heterogeneous data. The lab aims to provide intelligent, efficient, secure, and reliable algorithm and engine support for various important data-intensive scenarios, e.g., search, recommendation, and advertising. In this talk, we will give an overview of our recent research directions and introduce some of our on-going projects.

#### Profiles of speakers:

Dr. Bolin Ding completed his Ph.D. in Computer Science at University of Illinois at Urbana-Champaign. His research focuses on the management and analytics of large-scale data, including real-time approximate query algorithms and systems, data privacy, and machine learning. More recently, he is also interested in EconML and SysML. He has published papers in database and machine learning conferences and journals, including SIGMOD, VLDB, ICDE, KDD, CHI, AAAI, NIPS, ICLR, and ICML.

Dr. Zeng received his Ph.D. in Computer Science from the University of California Los Angeles. Before joining Alibaba, he was a Senior Scientist at Microsoft Cloud and Information Service Lab, and a postdoc researcher at AMPLab, Univeristy of California Berkeley before that. He is committed to the research of large-scale distributed systems and database systems. He has published papers in top database journals and conferences (including SIGMOD, VLDB, ICDE, TODS, and so on). He has received the Best Paper Award in 2012 and the Best Demonstration Award in 2014 from SIGMOD and was nominated for this Best Demonstration Award in 2010.

Dr. Wenyuan Yu received his Ph.D in Informatics from University of Edinburgh. Prior to joining Alibaba, he was the CEO of 7bridges Ltd, and a research scientist at Facebook. He is a recipient of the SIGMOD best paper award in 2017, the VLDB best demo award in 2017 and the VLDB best paper award in 2010. His research interests include data quality management and graph data processing.

----

## Oracle (Day 3, Block 2) [50S]

> Start at <span class="timeUTC">2020-09-03T19:00:00Z</span>

### JSON and the Moon Landing: The 50-year Journey to Autonomous JSON database
* Speaker: Beda Hammerschmidt

#### Abstract
Today's developers love JSON. Its schema flexible nature increases productivity: "change your app, not your database schema". Avoiding normalization into rows and columns yields low latency – critical for web apps.

What's been forgotten is that we've been there: 50 years ago, JSON was called IMS and its shortcomings lead to relational databases.

At Oracle, we want to combine the benefits of both data models in one converged database: We allow the storage of schema-less JSON with simple no-SQL style CRUD operations as well as SQL – at the same time we derive the schema from instance documents and automatically generate relational views over JSON. Similarly, the result of a SQL query can be returned as a JSON aggregate – for instance to serve a micro-service. As a consequence, 'schema' becomes somewhat ‘fluid' – with each database user able to select the rigidness based on her requirements. This talk gives an overview how JSON and rows'n columns play well together in Oracle Autonomous JSON Database – the latest offering in Oracle's autonomous and converged database cloud portfolio.

#### Profiles of speaker:

Senior Developer in the Oracle database team, working on JSON features, co-author of the SQL/JSON standard.

----

