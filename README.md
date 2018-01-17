# Master on Fundamentals of Data Science: Final Project

## Guidelines to Master’s Project Proposal

In most of the cases, the Master Project is a teamwork project of 3 students working on a subject. Individual projects can be 
considered only in special cases. Projects will naturally be expected to require an effort proportional to the number of team members (300 hours per student). Students may choose a project from a list of suggested projects (see below) or propose one of their own ideas. 

### Stages of Development of Master’s Project
+ Form a team of 3 students.
+ Choose the topic for your Master’s Project in collaboration with Master’s Project Coordinators (jordi.vitria@ub.edu & ligual@ub.edu). 
+ Discuss the research questions, goals, approach you intend to take, methodology, data needed and time plan with your project supervisor. 
+ Construct a logical outline for the project. Include analysis steps and expected outcomes. 
+ Define a clear role for all members of the group. This role will be considered in your personal student assessment.  
+ Fill in details of the project + role definition in a short document (max 2 pages). 
+ Hand in this document to your supervisors and start the project development! 

The Master Project must be concluded before 1/7/2018. 

The project delivery must include:
+ all code produced in a GitHub repository.
+ a project report (see the Report Template directory). 
+ a high level description of the completed project (jupyter notebook and/or blog entry)

See this example: https://github.com/axelbrando/Mixture-Density-Networks-for-distribution-and-uncertainty-estimation

### Project Assessment
The quality of the projects will be graded by using three sources of information:
+ The delivered information at the end of the project.  We will use a [“Project Evaluation Rubric”](https://docs.google.com/spreadsheets/d/1g9foCpIxRSuA414hjeqWZNniJl_QC81W2x0P44_kngw/edit?usp=sharing) to assign a mark to the project.
+ A presentation of your project. Your presentation should be professional enough to give at a technical conference (e.g. organized approach, prepared slides, a short demo or video if appropriate). 
+ [Peer-evaluation](https://docs.google.com/document/d/1iYwW6xOXSaQ9ApzYHpk-GdLONF9VGV17rOod2ifFkQs/edit?usp=sharing). Team members will assess other members of the team as well as themselves. Peer assessment provides data that will be used in assigning individual grades for team members.

### Calendar (2017/2018)
+ Feb. 18: Limit for official course enrollment.
+ Feb. 20 - 24: Assignment of projects & supervisors to student groups.
+ Mar. 3: Limit for delivering the project proposal short document to your advisors.
+ Jul. 1: Limit for final delivery of your project. 
+ Jul. 3-7: Presentations.

### Project proposals (2017/2018)
+ Title: Bodas.net. 
  + Descripción: Bodas.net es el portal de bodas líder en el mundo con el gran objetivo de ayudar a parejas a organizar su
  boda. Gestiona un total de 11 millones de usuarios únicos, 3 millones de recomendaciones, 5 millones de bodas, 400.000 empresas 
  anunciadas siendo un total de 800 empleados presentes en 15 países. Con un historial de casi 10 años en algunos de los países, el 
  objetivo del proyecto es:
    + Categorizar los usuarios que ya se han casado en grupos según su historial de leads en el portal y su propia información (fecha de 
    alta, fecha de boda, etc). Existen diferentes categorías de empresas que ofrecen sus servicios y los usuarios realizan leads a estas 
    empresas para contratar sus servicios. En base a las distintas categorías de empresas de los leads de un usuario y de la frecuencia 
    de éstos extraer diferentes categorías de comportamientos de los usuarios.
    + Dado que el período medio de conexión de un usuario estándar en nuestro portal es de aproximadamente 12 meses (tiempo medio para 
    organizar una boda) el objetivo es crear un modelo que, usando las categorías del apartado anterior junto con los datos del usuario, 
    determine mediante predicción si el usuario generará o necesitará un lead en el futuro y podernos anticipar a sus necesidades 
    (determinar la posible siguiente acción del usuario). 
  + Requisitos técnicos: Python, MySQL 
  + Condiciones: Parte del proyecto debe ser realizado en las oficinas de Bodas.net (en Sant Cugat) por temas de privacidad de los 
  datos. Proyecto Individual.
  + Advisors: Jordi Vitrià (UB) + David Guillament (Bodas.net)

 + Title: Deep Learning for the Detection and Characterization of the Carotid Artery in Ultrasound Imaging
   + The project proposes to study longitudinal ultrasound images of the carotid artery of a set of subjects (~4.000) with and without
   atherosclerosis diseases. The main objective is to develop a Deep Learning approaches for the detection and characterization of
   atherosclerotic plaques (fatty material partially or totally blocking the blood flow). It also proposes to investigate the 
   relationship between imaging features extracted from the artery and various biomarkers, as well as determining the plaque 
   vulnerability and the
   likelihood of developing cardiovascular events (labels recorded in the database).
   + Advisor: Laura Igual. The work will be developed in the Faculty of Mathematics and Computer Science of UB in collaboration with 
   Group
   of Epidemiology and Cardiovascular Genetics of the Institut Hospital del Mar;Investigacions Mèdiques de Barcelona (IMIM) and
   Biomedical Research Institute of Lleida Dr. Pifarré Foundation (IRBLleida).
   + Requirements: Project for 3 students, developing the following tasks: Task 1: To develop an Deep Learning method for the detection 
   and quantification of the plaque / Task 2: Develop a Deep Learning method to characterize the different components of the plaque / 
   Task
   3: Develop a Deep Learning method based in the image information to predict the plaque vulnerability and the cardiovascular events.

+ Title: Analysis of Multimodal Brain Data in Alzheimer disease.
   + In this project, we will develop a multimodal analysis of a rich data set of subjects who have memory problems. The general 
   objective is to define profiles based on different markers to measure, from subjects with subjective memory complains, some link to 
   the onset of the Alzheimer&#39;s disease. Given the multimodal data set we will explore different machine learning techniques to 
   extract clusters from the data set and study them in relation with profiles based on memory and cognition characteristics. We will 
   also statistically analyze if the data correlate with memory characteristics. The project is related with data science and 
   computational intelligence. The data set contains 200 subjects including: - Brain imaging data (different modalities, already 
   processed) - Data from Genome-Wide Association Study (GWAS) - Neuropsychology and clinical data - Scores from Memory tests.
   + Advisor: Laura Igual. The project will be developed in collaboration with the Fundació ACE from Barcelona providing the data, 
   involving the GWAS from the genomic imputation and measures from the preprocessed neuroimaging data.
   + Requirements: project for 1 student.

+ Title: GuruFinder
   + In the Information Age, where tons of documents are generated every day, to find relevant information for a given topic has become 
   a challenge. Researchers in the field of Information Retrieval have been working to solve this challenge by combining different 
   disciplines, from Artificial Intelligence to Cognitive Psychology or Library Sciences. Significant advances in the field have been 
   achieved in the last decades, in topics like Recommender Systems, Text Mining or Knowledge Management Systems. This proposal presents 
   a different approach to the ones mentioned above: instead of having a system that assists on searching and filtering information, we 
   suggest to know who has the relevant information. Those people, that we call Gurus, have knowledge enough about the topic to detect, 
   filter and curate the contents that are worthy to share.  
   The main idea of this project is very simple: take a piece of text that is relevant to you, and this tool will identify who are the 
   most influent users in Twitter to follow. Despite being conceptually simple, the tool can be very helpful in many different scenarios 
   and applications beyond Twitter users as it is explained in the Potencial Tecnològic section. Take for example a PhD student that is 
   reading a paper related to her thesis. After reading a section about Convolutional Neuronal Networks (CNN), she decides that is 
   something worth to try in her research and wants to learn more about it, so she selects the section, clicks on the GuruFinder button 
   and the tool proposes her a list of Twitter users to follow. Thus, she can access to people that are publishing relevant information 
   about CNNs: new papers, conferences, etc. 
   Imagine now that you are reading an online newspaper. After reading an article about the Rohingya Refugee Crisis, you want to know   
   more about the conflict, so you select the text and ask the tool to tell you which users to follow on Twitter: the opinion of 
   different experts on the matter will provide you with different points of view.    
   The concept may be easy but the technology required underneath implies the combination of different disciplines. In the present work, 
   we will explore state of the art techniques on the field of text mining and social network analysis to create, on the one hand, 
   representations of texts that ease the task of indexing the timelines and perform searches based on the selected texts, and on the 
   other hand, create influencer detection systems that allow the tool to rank the selected Twitter users based on their relevance. All 
   this will be running upon a platform that must be able to handle and process big volumes of tweets and offer real-time responses to 
   the users. 
   The results of the project will include a working version of the tool based on a Google Chrome Add-on, that will serve as a 
   demonstrator of the capabilities of the platform. The back-end of the tool will be deployed at Eurecat’s private cloud, bearing in 
   mind that it must be easily replicated on other potential providers. The results of the study, including the design of the 
   architecture, the different models included in the tool, the datasets produced for their validation and possible analysis derived 
   from its usage will be published in relevant journals and publications. A business model for the exploitation of the tool will also 
   be delivered, and potential patents of some of the results obtained will be studied.
   + Advisor: José Mena (EURECAT) & Jordi Vitrià (UB). 
   + Requirements: project for 2 students. The project will be developed in collaboration with EURECAT (https://eurecat.org/).
