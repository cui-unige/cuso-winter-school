---
title: CUSO Winter School in Computer Science
---

## Data Science in Information Society: From Data Acquisition to Data Analysis

January 30 - February 3, 2017
Champéry, Switzerland


### Overview

This Winter School presents in the form of tutorials (for non-specialists) the challenges, problems, and solutions in various areas of Data Sciences. The five topics covered include: Data management, Distributed Storage, HPC and Big Data, Security and Blockchain, and Data Wrangling and Viz. Each tutorial will be presented by invited speakers who are specialists in these research areas.

Furthermore, student participants are asked to bring a poster of their research work, either existing results or ongoing research that they are currently conducting.

### Organizers

* Prof. Pascal Felber, University of Neuchâtel
* Prof. Peter Kropf, University of Neuchâtel
* Prof. Jacques Savoy, University of Neuchâtel
* Prof. Philippe Cudré-Mauroux, University of Fribourg

### Important Dates

* Registration deadline:	December 9, 2016 (closed)
* Winter School:	January 30 - February 3, 2017

### Venue

The winter school will take place at hotel Hotel Suisse in Champéry in the Swiss Alps. From Champéry, you will find an easy acces to one of the largest ski arena in the world: [Portes du Soleil](http://www.portesdusoleil.com/hiver.html).

![Portes du Soleil](http://members.unine.ch/peter.kropf/ws17/images/portes-du-soleil.jpg)

### Access

Hotel Suisse,Champéry

* Address : Rue du Village 55, 1874 Champéry, Switzerland
* Phone number : 0041 24 479 07 07

<iframe src="https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d3893.4204013840267!2d6.86716834987195!3d46.17817944599105!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e6!4m5!1s0x478ea56cb10eb37d%3A0xc30e690fb59a80fd!2zQ2hhbXDDqXJ5!3m2!1d46.174951!2d6.871504!4m5!1s0x478ea57b8a4574a3%3A0xd76e0e7340431bcf!2sH%C3%B4tel+Suisse%2C+Rue+du+Village+55%2C+1874+Champ%C3%A9ry!3m2!1d46.177886099999995!2d6.8695740999999995!5e0!3m2!1sen!2sch!4v1479916932042" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

### Program

Student participants are asked to bring a poster of their research work, either existing results or ongoing research that they are currently conducting. Further instructions of how their work will be showcased during the Winter School will be sent by email to everyone closer to the event.
Programme

The program includes presentations of six speakers:

1. Introduction to Data Science and Big Data

   Prof. Philippe Cudre-Mauroux, University of Fribourg

   In this talk, I will give a general introduction to the topics of Data Science and Big Data. I will start by giving some motivation, and then give an overview of both Big Data infrastructures and recent advances in Data Science. Finally, I will delve into one topic close to my heart: the third V of Big Data (Variety) and how recent advances combining Big Data, NLP and Machine-Learning technologies can bring us one step closer to being able to integrate heterogeneous pieces of information automatically.

2. Data Management and Analysis as a Service

   Prof. Bettina Kemme, McGill University, Canada

   As data gets generated with unprecedented growth, and with it the desire to analyze and mine it, a wide range of platforms have been developed for its storage, management, transformation, dissemination and analysis. Given the complexity of the tasks at hand, these platforms are not simple press-the-button-and-all-works tools. Instead, users need a good understanding in order to deploy the right tools, with the data models and query languages that best suit the applications' need, and in order to configure these platforms so that they achieve the best possible performance. In this tutorial, we give an overview of well-known data storage and analysis platforms. We present their fundamental building blocks, and the techniques that are used to provide reliable, scalable and performant query execution. Platforms that are likely to be covered are the Hadoop Framework (including the Hbase data management system and the map-reduce data processing framework), Spark (enhanced distributed analysis), and the publish/subscribe paradigm for data dissemination. The challenges involved in deploying such platforms in the cloud will be discussed.

3. Codes for Cloud and Networked Distributed Storage

   Prof. Daniel Enrique Lucani Roetter, Aalborg University, Denmark

   This tutorial surveys traditional coding techniques for cloud and networked distributed storage systems as well as cutting-edge research results and recent developments in the topic. Providing robust and repairable storage capabilities originally started in a single computer, e.g., using RAID systems, to be able to withstand the loss of storage disks. The idea to distribute data across multiple storage nodes, which are interconnected over a network, e.g., within one or multiple data centers, is quite natural as it provides a much higher robustness to the loss of individual disks and even entire computers with multiple disks. Although the simplest technique to provide this reliability is to replicate (keep multiple copies of the file), the cost in storage space is large. The key goal of coding techniques in these systems is to achieve fault tolerance efficiently by being able to repair losses with controlled network and storage use in order to ensure data durability/survival over time. Given the abundance of cloud storage systems and massive content generated each year, reducing storage costs and exploiting storage beyond controlled data centers settings, e.g., leveraging mobile devices, have become a must. This tutorial has two parts. The first part provides the fundamentals of cloud and networked distributed storage, including, key concepts and performance metrics as well as fundamental trade-offs. This first part will also provide key code constructions and examples of codes specifically designed for repairability, including locally repairable codes and network codes. We shall cover both static, centralized designs suitable for current cloud storage systems as well as dynamic, distributed designs at the edge of current research for exploiting wireless mobile devices for storage systems. The latter introduces interesting constraints and higher node unavailability, which makes the design of very structured codes near impossible. Random code designs are presented as a way to cope with these new challenges. The second part of the course focuses on more practical and application specific designs, particularly, looking at effects of download and access time, data update, and security. This part will be grounded on real-world systems, implementation details, and measurements.

4. HPC and Big Data Convergence

   Prof. Jesus Carretero, University Carlos III of Madrid, Spain

   Traditional solutions for HPC and Big Data have followed separate paths for several years. However, since 2014 there is a strong effort to unify both worlds due to the strong interest in science and industry to get more insights from data stored in huge data vaults, to enhance their typical solutions entering data from previous experiences, and to create complex processes (presented as workflows) to solve multistage problems. All this trends, included under the name "data-intensive computing", are changing both worlds. However, convergence is not easy, as current Big Data solutions are mostly focused to a small part the the problems that a HPC system may face. In this tutorial, we´ll show the specifics of data-intensive computing problems, requirements, and major paradigms used in Big Data and HPC worlds to cope with them. Then, we´ll show the major effort being made to promote convergence between both worlds, and some of the lessons learned from the adaptation of real-world problems.

5. Technologies for Blockchain - Consensus and Cryptography

   Dr Christian Cachin, IBM Research - Zurich

   A blockchain is a public ledger for recording transactions, maintained by many nodes without central authority through a secure cryptographic protocol. All nodes validate the information to be appended to the blockchain, and the protocol ensures that the nodes agree on a unique order in which entries are appended.

   This tutorial introduces some fundamental abstractions for programming distributed applications that tolerate faults, including reliable broadcast and consensus. It illustrates protocols that realize these concepts in systems subject to uncertainty and failures, and extends them to environments where malicious attacks may occur (so-called Byzantine faults). Applications of Byzantine consensus and distributed cryptography to blockchains are discussed, with focus on current efforts to build a blockchain for the enterprise under the Hyperledger Project.

6. Data Wrangling and Viz

   Dr Michele Catasta, EPFL

   Many industry experts report that "Data scientists spend up to 80% of their time on data wrangling". Being such a time consuming task, pre-processing the data before performing in-depth analysis is often considered a frustrating experience, with little appeal compared to machine learning and data mining. In this tutorial, you will learn the techniques and the tools of the trade to perform efficiently data wrangling. Moreover, you will see examples of when taking shortcuts and rushing the data wrangling process can badly affect all the subsequent steps in the data science pipeline. The ultimate goal of this tutorial is to shine a positive light over data wrangling, as it can be leveraged to assess the quality of the pre-processing step in your data science pipeline. Such quality checking process is iterative in nature and requires a solid background in visualization, so this tutorial will also include a live demo and a crash course on the best practices in viz. To conclude, you will get an overview of the most promising research projects in the field.

### Schedule

| Day | Hour | Title | Speaker |
| --- | --- | --- | --- |
| Monday,   30 | 14h00 - 15h30 | Introduction to Data Science and Big Data | Philippe Cudre-Mauroux |
|              | 16h00 - 19h30 | Data Management and Analysis as a Service | Bettina Kemme |
| Tuesday,  31 | 08h30 - 12h00 | Codes for Cloud and Networked Distributed Storage | Daniel Enrique Lucani Roetter |
|              | 17h00 - 19h00	| PhD student presentations | Veronica Estrada, Dimitri Percia David, Mostafa Karimzadeh, Silvina Caino-Lores, Andrei Lapin, Xavier Ouvrard, Yarco Hayduk, Alexandre DeMasi, Roberta Barbi, Davide Alocci |
| Wednesday, 1 | 08h30 - 12h00 | HPC and Big Data Convergence | Jesus Carretero |
|              | 17h00 - 19h00	| PhD student presentations | Jonnahtan Saltarin, Paolo Rosso, Bertil Chapuis, Clément Labadie, Vaibhav Kulkarni, Pascal Gremaud, Arnaud Durand, Oumaima Ajmi, Dana Naous |
| Thursday,  2 | 08h30 - 12h00 | Technologies for Blockchain - Consensus and Cryptography | Christian Cachin |
|              | 17h00 - 19h00	| PhD student presentations | Allan Berrocal, Laura Rettig, Aurelien Havet, Aziza Merzouki, Dina Elikan, Simin Jabbari, Selena Baset, Rafael Pires, Mirco Kocher |
| Friday,    3 | 08h30 - 12h00 | Data Wrangling and Viz | Michele Catasta |
|              | 08h30 - 12h00 | Wrap-up |  |

### Speakers

* Prof. Philippe Cudre-Mauroux, University of Fribourg

  Philippe Cudre-Mauroux is a Full Professor and the Director of the eXascale Infolab at the University of Fribourg in Switzerland. He received his Ph.D. from the Swiss Federal Institute of Technology EPFL, where he won both the Doctorate Award and the EPFL Press Mention in 2007. Before joining the University of Fribourg, he worked on information management infrastructures at IBM Watson Research (NY), Microsoft Research Asia, and MIT. He recently won the Verisign Internet Infrastructures Award, a Swiss National Center in Research award, a Google Faculty Research Award, as well as an ERC research grant. His research interests are in next-generation, Big Data management infrastructures for non-relational data.

* Prof. Bettina Kemme, McGill University, Canada

  Bettina Kemme is an Associate Professor and the Director of the School of ComputerScience of McGill University, Montreal, where she leads the distributed information systems lab. She holds a PhD degrees in Computer Science from ETH Zurich. Her research focuses on large-scale distributed data management with a main focus on adaptive data processing and data dissemination. Bettina has published over 80 publications in the major journals and conferences in the areas of database and distributed systems as well as served as General Chair, area program chair and PC member of the major conferences such as IEEE ICDE, IEEE ICDCS, ACM Middleware, IEEE SRDS, ACM SIGMOD etc. She received the 10-year Test-of-Time Paper award at VLDB 2010. Bettina is area editor of Elsevier Information Systems and a senior member of IEEE.

* Prof. Daniel Enrique Lucani Roetter, Aalborg University, Denmark

  Daniel E. Lucani is an Associate Professor in the department of Electronic Systems, University of Aalborg, Denmark and the CEO and co-founder of Chocolate Cloud ApS, a start-up focused on developing and deploying distributed storage solutions using erasure codes. Dr. Lucani is a Senior Member of IEEE and he is the recipient of the IEEE ComSoc 2015 Outstanding Young Researcher Award for the EMEA region, Aalborg University's Talent Management Award in 2016, and a Best Paper Award in ISWCS 2016. Dr. Lucani has authored over 130 Journal and Conference papers and 7 patents focused on network coding. His research interests lie in the general areas of communications and networks, network coding, information theory and their applications to communication networks and distributed storage, focusing on issues of robustness, reliability, delay, energy, and resource allocation. Dr. Lucani received his B.S. (summa cum laude) and M.S. (with honors) degrees in Electronics Engineering from Universidad Simón Bolívar, Venezuela in 2005 and 2006, respectively, and the Ph.D. degree in Electrical Engineering from the Massachusetts Institute of Technology (MIT) in 2010. He was the general co-chair of the Network Coding Applications and Protocols Workshop (NC-Pro 2011) and was the general co-chair of the 2014 International Symposium on Network Coding. Dr. Lucani has also served as reviewer for high impact international journals and conferences, such as, the IEEE Journal of Selected Areas in Communications, IEEE Transactions on Information Theory, IEEE Transactions on Communications, IEEE Transactions on Wireless Communications, IEEE Transactions on Vehicular Technology, IEEE Journal of Oceanic Engineering.

* Prof. Jesus Carretero, University Carlos III of Madrid, Spain 

  Jesus Carretero is a Full Professor of Computer Architecture and Technology at Universidad Carlos III de Madrid (Spain), where he is responsible for that knowledge area since 2000. His research activity is centred on high-performance computing systems, large-scale distributed systems and real-time systems. He is Action Chair of the IC1305 COST Action "Network for Sustainable Ultrascale Computing Systems (NESUS)", and he is also currently involved in the FP7 program REPARA "Reengineering and Enabling Performance And poweR of Applications" and RePHRASE, Refactoring Parallel Heterogeneous Resource-Aware Applications - a Software Engineering Approach. He has participated and leaded several national and international research projects in these areas, founded by Madrid Regional Government, Spanish Education Ministry and the European union. Prof. Carretero more than 230 papers in journals and international conferences, editor of several books of proceedings, and guest editor for special issues of journals as International Journal of Parallel Processing, Cluster Computing, Computers and Electrical Engineering, Journal of Supercomputing, and New Generation Computing. He is also co-author of several text books related to Operating Systems and Computer Architecture. He has participated in many conference organization committees, and he has been General chair of HPCC 2011 and MUE 2012,  Program Chair of ISPA 2012, EuroMPI 2013, C4Bio 2014, and ESAA 2014, and Finantial Chair of CCGRID 2016. Prof. Carretero is a senior member of the IEEE Computer Society and member of the ACM.

* Dr Christian Cachin, IBM Research - Zurich 

  Christian Cachin is a cryptographer and computer scientist interested in distributed computing, cryptographic protocols, and security, working at IBM Research - Zurich. He graduated with a Ph.D. in Computer Science from ETH Zurich and has held visiting positions at MIT and at EPFL. An IEEE Fellow, ACM Distinguished Scientist, and recipient of multiple IBM Outstanding Technical Achievement Awards, he has co-authored a textbook on distributed computing titled "Introduction to Reliable and Secure Distributed Programming". Currently he serves as the President of the International Association for Cryptologic Research (IACR). In addition to many cryptographic protocols that he has developed, particularly for achieving consensus and for executing distributed cryptographic operations over the Internet, he has also contributed to standards in storage security and key management. His current research addresses blockchains, the security of cloud computing, secure protocols for distributed systems, and cryptography.

* Dr Michele Catasta, EPFL 

  Michele Catasta is a research scientist and lecturer in Data Science at EPFL, Switzerland. During his PhD (EPFL, 2015), he let human memories and information systems have their first dance. To make this debut happen, he added new bells and whistles (human computation, machine learning, psychology) to his original researcher hat (big data analytics, information retrieval, semantic technologies). Michele was in the founding team of Sindice.com, the largest Semantic Web search engine (now SIREn Solutions). He also worked for MIT Media Lab, Google and Yahoo Labs. In the past years, he received several awards and recognitions - among them, a focused grant from Samsung Research USA.

### Registration

All the students, researchers and professors registered at CUSO universities (Universities of Fribourg, Geneva, Lausanne, Bern and Neuchâtel) are eligible to apply. Priority will be given to students ; PostDocs and senior researchers will be selected according to their scientific activity and closeness to the field of the winter school. Those selected for participation will be notified by email and will be asked to pay a registration fee of CHF 100.

For members of the CUSO, accommodation costs for four nights in a double-room, breakfasts, coffee breaks and dinners will be paid for directly by the organizers. The Winter School will also reimburse travel costs for half-price second class SBB tickets. You will receive reimbursement instructions during the school. Midday lunch is not included and has to be paid by the participants.

For external participants (includung EPFL), accommodations and meals are to be paid by the participants.

Cancellation should be announced to the organizers at least until the 9th of January, 2017 (3 weeks before the start of the School). Already paid registration fees will not be reimbursed for cancellation after January 22, 2017.

Please register before Friday, December 9th, 2016. After this date we can not guarantee you a room in the hotel

The link for registration at the CUSO site is: here

NOTE: Since double rooms for PhD students will be shared between two students, in the "Comments and Response to Message" field, please indicate the name of another student with whom you would like to share a room.

Reimbursement of travel costs (closed): 1/2 prize train ticket. Please fill in the form and send it to the contact address below the latest on February 10th.

### Contact

```
Prof. Peter Kropf
Computer Science Department
University of Neuchatel
Rue Emile Argand 11
CH-2000 Neuchâtel
E-mail: Peter.Kropf@unine.ch
Fax: +41 32 718 2701
```
