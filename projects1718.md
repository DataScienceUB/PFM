# Project Proposals (17/18)

## Title: Bodas.net. 
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

## Title: Deep Learning for the Detection and Characterization of the Carotid Artery in Ultrasound Imaging
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

## Title: Analysis of Multimodal Brain Data in Alzheimer disease.
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

## Title: GuruFinder
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
   
## Title: SEMANTIC SEGMENTATION USING DEEP LEARNING APPLIED TO FOOD ANALYSIS
  + State-of-art approaches for semantic segmentation are built on Fully Convolutional Neural Networks (FCNs), which are a natural 
  extension of Convolutional Neural Networks (CNNs) to tackle per pixel prediction problems. Their typical architecture is composed of a 
  downsampling path to extract coarse semantic features, an upsampling path to recover the input image resolution and, optionally, a post-
  processing module to refine model predictions. Moreover, attention models embedded into the deep learning approach improves additionally 
  the final performance. 
  The most recent methods in the field of semantic image segmentation provide great results with datasets that contain a relatively low 
  number of classes, such as CamVid (11 semantic classes) or Gatech (8 semantic classes). The number of categories used when dealing with 
  food analysis is much higher (tens of classes), thus increasing the difficulty of the task and providing not so satisfactory results. 
  Therefore, the purpose of this work is to provide solutions for semantic segmentation applied to food images in order to, for example, 
  estimate food consumption, extract ingredients or approximate food portions in images. 
  + Advisor: Petia Radeva (UB)
  + Requirements: project for 3 students.

## Title: Corrupció, política i xarxes socials. 
+ Alternativa 1: La corrupció al govern local: Aquest projecte consta de dues fases. En una primera fase es proposa la creació d’un algoritme per tal de classificar notícies a mitjans de comunicació i identificar aquelles que fan referència a un escàndol de corrupció. Per a aquest objectiu es disposa ja d’un training set que inclou notícies publicades des de l’any 1996 a diaris nacionals, regionals o locals sobre escàndols de corrupció local. L’objectiu serà crear un classificador de notícies que facin referència a escàndols de corrupció i automatitzar la recerca de noves notícies que vagin apareixent. En una segona fase del projecte es desenvoluparà un model d’aprenentatge supervisat per predir l’existència d’un escàndol de corrupció local. Es disposa de tres bases de dades que inclouen la següent informació: i) dades electorals i partits que formen els governs locals; ii) característiques personals dels polítics locals (edat, sexe, nivell educatiu); i iii) característiques sòcio-econòmiques del municipi. S’hi afegirà també una base de dades sobre les licitacions de contractes públics als governs locals. Les preguntes que es volen respondre són: de què depèn que en un municipi es descobreixi un nou cas de corrupció? Quins ajuntaments tenen més probabilitats de veure’s involucrats en un escàndol en el futur? Es pretén comparar els resultats d’un model estadístic tradicional amb les prediccions obtingudes per un model d’aprenentatge supervisat.
+ Alternativa 2: Anàlisi de preguntes orals al Congrés dels Diputats: Els textos polítics - com ara debats parlamentaris o programes electorals-  són una valuosa font d’informació quantitativa. Les paraules i el to que els polítics fan servir en els seus discursos revelen la seva ideologia, les seves preferències quant a polítiques públiques i el temes als que donen més prioritat. Aquest projecte pretén analitzar les preguntes orals realitzades per tots els parlamentaris al Congrés dels Diputats espanyol des de l’any 1982 fins l’actualitat, per a les que ja disposem del text transcrit. Les tasques que es proposen són obtenir les posicions ideològiques estimades (ideal points) de cada parlamentari, identificar el to i llenguatge que fan servir i els temes més debatuts per cada diputat. El projecte requereix aplicar diversos mètodes de classificació i predicció. La informació quantitativa obtinguda mitjançant l'anàlisi de text ajudarà a respondre preguntes com: s’ha polaritzat la política espanyola en els darrers anys? Les característiques individuals dels polítics (com ara bé l’educació o l’edat) influeixen en les seves preferències polítiques?”
+ Alternativa 3: El llenguatge sexista a Twitter: En aquest projecte es proposa crear un classificador de llenguatge sexista a Twitter basat en diccionaris existents de termes sexistes en castellà i en la classificació manual de missatges. A continuació, s’estudiarà la variació geogràfica en el llenguatge sexista a Espanya. El projecte estudiarà si existeix menys llenguatge sexista en zones en què per l’estructura familiar tradicional (nuclear o extensa) les dones històricament han treballat més fora de la llar. Finalment, centrant-nos en comptes de representants polítics en actiu (a Ajuntaments, Parlaments Autonòmics i Parlament Espanyol). Les preguntes que es pretén respondre són: A quines zones d’Espanya s’usa més llenguatge sexista a l’esfera pública? I a quines zones reben més comentaris sexistes les representants polítiques electes?
+ Advisor: Jesus Cerquides
+ Requirements: project for 3 students. You have to choose one of the 3 alternatives. 

## Title: Analysis and visualization of research and teaching data of University of Barcelona Professors
+ The students will be given anonymized data about research (publications and projects, input and output) and teaching (subjects, timetables, degree) of UB professors, and will have the opportunity to interview two heads of departaments and two degans. With this information they will be required to propose a dashboard that gives a global view of the administrative unit (department or faculty), detailed information about each professor, and a benchmark with the rest of the university. This project is a collaboration with the University of Barcelona and there will be a confidentiality agreement before accepting the work. Depending on the quality of the project it could have a real implementation within the university.
+ Coordinators: Oriol Pujol and Mireia Ribera
+ Requirements: project for 2 students. 

## Title: Analysis and visualization of research and teaching data of University of Barcelona Professors
Analysis and visualization of data from the Banc d'Aliments Foundation [https://www.bancdelsaliments.org/]. The students will be given access to a database of the recollection food campaigns and the distribution to social entitites all around Catalonia. They will be asked to propose how to visualize these data for raising awareness of the Foundation mission and accomplishments. This project is a collaboration with the Foundation and there will be a confidentiality agreement before accepting the work. Depending on the quality of the project it could have a real implementation within the public website of the Foundatin.
+ Coordinators: Eloi Puertas and Mireia Ribera 
+ Requirements: project for 2 students. 



