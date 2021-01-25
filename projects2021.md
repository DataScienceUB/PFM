
# Project Assignments (June 2021)



| Student   |      Title      |  Tutor|
|----------|:---------:|----------:|
| Àlex Martínez Miguel  | Classification of travel offers for shared mobility applications | Ludovico Boratto (Eurecat), Cristian Consonni (Eurecat), Oriol Pujol |
| Emilio Tylson Baixauli | Realistic Satellite Imagery with Progressive Structured Conditional GAN | Javier Marin (Satellogic) and Sergio Escalera|
| Muriel Rovira Esteva   |  Machine Learning Copies as a Means for Black Box Model Evaluation  |  David Zeber (Mozilla Applied Machine Learning) & Oriol Pujol|
| Irene Acero   | Contribution to the improvement of the cry translation algorithm by Zoundream | Ana Laguna Pradas (Zoundream) & Jordi Vitrià |
| Pablo Álvarez Cabrera   |  ONCOTHROMB  | Jose Manuel Soria (Hospital de Sant Pau) y Oriol Pujol |
| Carla Sendra |  Multi-centre and multi-scanner cardiac LGE-MRI segmentation using deep learning | Karim Lekadir, Victor Campello, Carlos Martin-Isla|
| Blai Ras | Forecasting with cannibalization due to sales peaks (promos, events) and New Launches | Riste Gjorgjiev (Accenture Applied Intelligence) & Jordi Vitrià |
| Montserrat Comas | Deep Learning the Structure of Brain States of Motivation  | Ignasi Cos & Oriol Pujol |
| Alvaro Villamarin| Deep Learning for content-based indexing of TV programs | Jordi Vitrià & Paula Gómez |
| Aitor Lucas Castellano & Noel Rabella Gras | Multimodal biomedical data integration for atrial fibrillation diagnosis using deep learning | Polyxeni Gkontra, Akis Linardos, Karim Lekadir |
| David Farré Gil |  From the Visual Analysis of Movement to Principled Models of Motivated Movement | Ignasi Cos & Sergio Escalera |
| Fritz Pere Nobbe Fisas |  The Brain Network of Motivation: A Topological Approach | Ignasi Cos & Carles Casacoberta |
| Ling Zhu |  Deep learning-based radiomics for multi-centre cancer image quantification | Laura Igual, Lidia Garrucho, Karim Lekadir |
| Adrián Torres Martín | Deep Learning for early-stage embryo image analysis  | Jerónimo Hernández & Jesús Cerquides |
| Joana Reuss | Endoluminal image classification  | Santi Seguí |
| Rachel Trimble | Biomarker Data Analysis to Support Early Stage Alzheimer's Diagnosis | Sergio Escalera , Lorena Rami (IDIBAPS) & Pau Buch-Cardona |
| Alex padrós | TBA | Jerónimo Hernández |
| Pablo Granatiero | TBA | Jerónimo Hernández|
| Adrià Torralba Agell & Marcos Moreno Blanco | RecSys Challenge Competition | Santi Seguí |





# Project Proposals (20/21)


## Pattern Recognition in mice behaviours using machine learning.


The study of mouse behavior is key in many fields of biomedical research. In the context of neurological diseases, such as Alzheimer's, Parkinson's and Huntington's disease, assessing cognitive and motor behavior in animals allows us to observe the progression of symptoms as well as the effects of experimental treatments [1]. These types of studies are usually done manually, analyzing the different behaviors of video-recorded mice. Today, thanks to computer vision techniques it is possible to analyze the behaviors of mice in a more automated way. Using tools such as DeepLabCut [2] it is possible to estimate the various poses that mice make from the recorded videos. The main objective of this work is to find complex behaviors of mice in a model of Huntington's disease based on the different poses that the animal performs spontaneously through Machine Learning.

This work is done together with the research group led by Dr. Masana, Professor of the Department of Biomedicine, Institute of Neurosciences, Faculty of Medicine and Health Sciences. The research line consists of developing techniques for monitoring and modulating in vivo brain circuits in a non-invasive way, and is part of a European Union FET-open project, consisting of developing a non-invasive technology to treat degenerative diseases (www .neuropaproject.com).

[1] Books and Dunnett (2009). Nature review neuroscience (10) 519-529 
[2] http://www.mousemotorlab.org/deeplabcut) 

Supervisors: Eloi Puertas i Prats (Facultat de Matemàtiques i Informàtica - UB), Mercé Masana i Nadal (Facultat de Medicina i Ciències de la Salut -UB) 

Requeriements: Have taken the elective subject Deep Learning. project for 1 student.




## The Brain Network of Motivation: A Topological Approach

Motivation is an essential link between physiology and movement. Parkinson's disease is a
neurodegenerative disorder characterized by cognitive degeneration and a specific motor
symptomatology. While these symptoms are consistent with a lesser than normal movement
invigoration, it remains to be determined whether they are consequence of a motor system
weakening, or whether by contrast, its origin is more of a motivational nature. To this end, we
performed psychophysical experiments and recorded EEGs from PD patients, under different
levels of controlled motivation, both on and off medication.
The study of the brain as a whole is about relations. Relations are a central concept of neuroscience,
thus capturing fundamental aspects of the organization of the nervous system and their links to
physiology, perception and behavior. In this context, previous studies focused on the analyses of
electro-encephalogram temporal series to characterize the brain network of motivation. These were
based on classifying brain motivated states based on local and network dynamics by means of brain
source power and Pearson correlation across sources. Building on this knowledge, the goal of the
project here proposed is to gain access to the backbone that captures the structure of this
classification, by using topology. In brief, we propose the use of persistent homology, a
fundamental method from applied topology that builds a global descriptor of system structure by
chronicling the evolution of cavities as we move through a weighted network. How descriptive is
this characterization in the case of the brain network? Are there specific differences based on
medication?
In summary, the student's goal would be that of identifying and quantify differences of neural
connectivity across brain areas as a function of the person's level of task engagement (motivated
state). The student will also be at charge of the preparation of scientific manuscripts for publication
and of presenting these results at scientific conferences.

References:
Gilson M, Moreno-Bote R, Ponce-Alvarez A, Ritter P, Deco G (2016) Estimation of Directed
Effective Connectivity from fMRI Functional Connectivity Hints at Asymmetries of Cortical
Connectome. PLoS Comput. Biol. 12

Hindriks R, Schmiedt J, Arsiwalla XD, Peter A, Verschure PFMJ, Fries P, Schmid MC, Deco G
(2017) Linear distributed source modeling of local field potentials recorded with intra-cortical
electrode arrays. PLOS ONE 12:e0187490

Sizemore, A. E., Phillips-Cremins, J. E., Ghrist, R. & Bassett, D. S. The importance of the whole:
Topological data analysis for the network neuroscientist. Netw Neurosci 3, 656Ð673 (2019)
Curto, C. What can topology tell us about the neural code? arXiv:1605.01905 [q-bio] (2016).

Advisors: Ignasi Cos & Carles Casacoberta

Contact: ignasi.cos@ub.edu


## From the Visual Analysis of Movement to Principled Models of Motivated Movement

Movement is our only channel to interact and communicate with the environment. Motor actions,
as a function of the intended goal and of our internal state, are executed in different fashions. For
example, professional athletes tend to reduce their movement variability when competing vs when
they are training, although their instruction may be the same. Likewise, we tend to perform more
energetic action when the stakes are high or when there is an urgency to attain a specific target
(Schmidt et al., 2008), strongly suggesting a fundamental link between the motivational and the
motor systems.
State-of-the-art generative models of motor control are capable of finding the correct sequence of
muscle activations associated to a specific movement. However, their fundamental shortcoming is
that they are disconnected from motivation and emotional phenomena. In a different order or
things, recent advances in image processing have proven the distinct possibility of extracting
markers of the emotional/motivational state of a subject via algorithms of image analysis.
The ultimate goal of the project here introduced is to relate both perspectives, the model based
approach of motor control theory with the model-free approach of image processing, as to
established principled connections between the inference methods used to extract
motivational/emotional information from gait/movement image analysis and extended models of
motor control that could incorporate motor control theory in a principled fashion.
To that end, we propose to perform a set of controlled experiments with healthy human subjects,
to record kinematic data and infer their motivational data one the grounds of visual arm movement
and gait image analysis. The participant will have to make reaching and pointing movements from
first dot on the screen to the next by sliding his/her index finger onto a tablet, or to perform
stereotypical walking movements in a controlled fashion. Movements are performed in exchange
for a score. In a covered fashion, a careful analysis of their movements should allow us to establish
not only whether and how motivation and effort are constraints for their motor responses, but
would also to provide a quantitative understanding of whether the laws of motor control also apply.

Advisors: Ignasi Cos & Sergio Escalera 

Contact: ignasi.cos@ub.edu


## Deep Learning the Structure of Brain States of Motivation

Parkinson's disease (PD) is a neurodegenerative disorder characterized by cognitive degeneration
and a specific motor symptomatology. While these symptoms are consistent with a lesser than
normal movement invigoration, it remains to be addressed whether they are consequence of a
motor system weakening, or whether by contrast, its origin is more of a motivational nature. To
answer this question, we performed an experiment with PD patients in which they performed
movements and decisions between movements of different energetic cost and under different
motivated conditions, both on and off medication. Electro-encephalographic (EEG) signals were
recorded during these sessions. Our behavioural analyses showed that there are clear motivational
factors involved in their symptomatology.
Previous research showed that we could identify mental states associated to different motivational
levels while performing a motor task between precision reachings. However, little is known about
the specifics of the network underlying the neuro-dynamics of motivation. In this context, the goal
of project is to design and train deep learning networks to reproduce the neural dynamics observed
on our neural recordings, and to attain a network characterization of these dynamics.
In summary, the student's goal would be that of developing computational models of the brain, to
identify and quantify differences of neural connectivity across brain areas as a function of the personÕs
level of task engagement (motivated state). The student will also be at charge of the preparation of
scientific manuscripts for publication and of presenting these results at scientific conferences.

References:
Gilson M, Moreno-Bote R, Ponce-Alvarez A, Ritter P, Deco G (2016) Estimation of Directed Effective Connectivity from fMRI
Functional Connectivity Hints at Asymmetries of Cortical Connectome. PLoS Comput. Biol. 12

Hindriks R, Schmiedt J, Arsiwalla XD, Peter A, Verschure PFMJ, Fries P, Schmid MC, Deco G (2017) Linear distributed source
modeling of local field potentials recorded with intra-cortical electrode arrays. PLOS ONE 12:e0187490

Advisors: Ignasi Cos & Oriol Pujol

Contact: ignasi.cos@ub.edu


## Deep Learning for content-based indexing of TV programs.

While digitization has changed the workflow of professional media production, the content-based indexing of video footage, necessary for subsequent stages of television production including recommendation, is typically still performed manually and thus quite time-consuming. This project will explore novel algorithms for visual concept detection, metric learning, and face detection combined in a multimedia tool for TV recommendation.  This project will be a collaboration with  PICAE Ris3Cat project (https://comunitatmedia.cat/portfolio/projecte-picae/) and training data will be all video footage from TV3 during the last 3 years.
 
- Supervisors: Jordi Vitrià (UB), Paula Gómez (UB)

- Requirements: Programming in Pytorch. 1 or 2 students. 


## Crowd learning for SDGs

During the last years, the advances of the information technologies allowed the development of the so-called citizen science, where enthusiastic communities get involved in the solution of scientific tasks. Even more general, crowdsourcing approaches to machine learning aim to obtain data from a community of collaborators who are not required to be experts or knowledgeable in the project in which they participate. Thus, this type of (altruistic or paid) citizen collaboration has been commonly used to tag images, text, audio and other type of data sets. 

Under the name of crowd learning, different methods have been proposed for learning from this type of data during the last years. These methods focus mainly on solving the problem of label aggregation (combining different opinions for the same data point) for machine learning. Although the data provided by these collaborators (a.k.a., labelers) might be imprecise, several studies have determined the mean number of labelers required for each data point so that the combination of their labels competes in terms of reliability with the label that an expert would have provided. 

In this work, the student will work on an equivalent problem where the labels for the data points are not single values but somehow structured. They will learn the classical approaches, as well as propose and apply different models for learning from this alternative type of data. The objective is to determine to which extent it is worthy to try to model complex label structures in the process of crowd learning.

Contact:
Jerónimo Hernández González jeronimo.hernandez@ub.edu
Jesús Cerquides Bueno cerquide@iiia.csic.es



## Deep Learning for early-stage embryo image analysis

During the last decades, artificial reproduction technologies (ART) have tried to solve the problem of artificially inducing a pregnancy. Among the different challenges of these technologies, the characterization of the obtained embryos stands out due to its potential impact on the outcome of the ART treatments. So far, physicians have manually annotated different characteristics of the embryos at different development stages, known to be related with correct embryo maturation, after a costly visual inspection using a microscope.

Modern culturing devices incorporate multiple cameras that continuously monitor embryos during their whole culturing process. Thus, nowadays, video images of cultured embryos are commonly available in ART laboratories. The popularity of these devices rocketed in parallel to the explosion of deep neural network (DNN) models, which has become the leading paradigm in the field of image analysis.  

In this work, the student will have to learn, propose and apply different DNN models to the analysis of early-stage embryo images. The main objective is to automate the process of feature extraction-selection and learn models that potentially exploit all the information available in the images to assist physicians in the process of decision-making.


Contact:
Jerónimo Hernández González jeronimo.hernandez@ub.edu
Jesús Cerquides Bueno cerquide@iiia.csic.es




## A recommender system for restaurants


The start-up that develops the app Velada, which is specialized in the recommendation and management of bookings in restaurants, wants to explore the use of new recommender systems based on machine learning. The objective is to explore the possibilities and needs of the app to incorporate advanced automated recommender systems.

The appÕs user will be given a suggestion of the best restaurant at the right moment. Apart from recommending a restaurant that matches userÕs preferences and needs, the objective is to guess when they are going to be interested in having lunch/dinner out and to offer them a recommendation just in time such that they do not find themselves in the unpleasant situation in which their favorite restaurant is already full and there is no available table.

The company offers access to all the data that it is currently being collected. There are two sets of information. First of all, any appÕs usage is saved: filters applied by users, their selected restaurants, food and other preferences, location, etc. Secondly, the availability of restaurants is provided thanks to the company's agreement with one of the leader booking providers.

Velada is a mobile-phone application that seeks to revolutionize restaurant bookings by means of a new generation of food guides. In our app, the recommender system is expected to play a key role, for which the prototype that may be obtained in this project would be a first stage.
Video Demo: https://youtu.be/f3g3RTLyiu0
Web Velada: https://appvelada.com
AppStore: https://apple.co/2GWIFDX


Contact:
Jerónimo Hernández González jeronimo.hernandez@ub.edu 
David Martín Suarez (Velada) david@velada.io




## Biomarker Data Analysis to Support Early Stage Alzheimer's Diagnosis

Want to help advance the day Alzheimer's Disease (AD) will be defeated before it manifests?
AD is the most prevalent neurodegenerative
 disease among the aged population and it is calculated that most of the people over 80 years of age are affected by the disease either directly (will develop AD), or else become caregivers unwillingly.  Besides, since life expectancy increases year after year,
 it is forecasted that within the following years, the number of people affected by a neurodegenerative disease will grow dramatically along with the associated personal (1out3 seniors currently die with dementia) and huge economical costs (818 billion USD
 estimated by WHO).
Current diagnosis is based on the evaluation
 of a clinician that rules out other diseases with similar symptoms of cognitive decline (memory loss) prior to confirming a patient with AD. However, when these symptoms appear, it is too late for any available treatment to stop/revert this biological process
 of neuronal loss known as 'neuronal death cascade'.
From the
HuPBA's
 group (in UB) dementia line of research we offer the possibility to work in a multidisciplinary team, developing data-driven means of AD early diagnosis (detecting the disease before it is clearly manifested) by applying data engineering and data science methodologies.
 In collaboration with the 'Malaltia d'Alzheimer i altres trastorns cognitius' group from IDIBAPS - Hospital Clínic, the assigned researchers will perform varied data-related tasks such as data cleaning, dealing with missing data, working with heterogeneous
 data sources, feature selection, learning from few samples, classification vs regression in diagnosis and prognosis scenarios and experimenting with different learning strategies, among others.

Advisors:
 Sergio Escalera (UB),  Lorena Rami (IDIBAPS) & Pau Buch-Cardona (UB)

Requirements:
 project for 1 student




## Endoluminal image classification
Capsule endoscopy is a procedure that uses a tiny wireless camera to take pictures of your digestive tract. A wireless capsule endoscopy (WCE) camera sits inside a vitamin-size capsule you swallow and takes more than 50.000 images which are sent to an external device in order to be analyzed.

Although this is an amazing non-invasive product that allows the full visualization of the entire endoluminal track, its application is limited due to one main problem: the diagnosis, visualization of more than 60.000 images, is a hard and tedious task that must be done by experts. So, WCE needs AI to become a real clinical procedure.
In this project, the student will study and apply self-supervised models (using deep Learning) for the problem of WCE.

- Supervisors: Santi Seguí

- Requirements: 1-2 students


## RecSys Challenge Competition
Every year in the scope of the International RecSys Conference (https://recsys.acm.org/recsys21/) a new real RecSys challenge is proposed. Each year the challenge is organized by a different company (twitter 2020; trivago 2019; spotify 2018).
The goal of this Master Thesis not to win (that would be amazing) the challenge but study and participate in it. Last year, a master's student participated, finishing in 9th place.
Information on the challenge is expected to be released by the end of the year and the challenge will begin in mid-February.

- Supervisors: Santi Seguí

- Requirements: 1-2 students



## BiblioPRO review automatization

The growing boom and research in Natural Language Processing (NLP) has opened up great possibilities for automating systems that were previously very expensive to implement. The project that we present consists of automating through NLP the search for health questionnaires that are published every year.
BiblioPRO (https://www.bibliopro.org) is a virtual library of Patient-Reported Outcomes (PRO) instruments in Spanish, whose mission is to promote the measurement of PROs in research, clinical practice and healthcare management.
This library is updated every year through a systematic review designed to identify articles published with information on new PRO instruments in Spanish through 3 phases: 1) automatic search in PubMed; 2) manual review of abstracts; and 3) manual review of full-text articles. The number of articles identified has been increasing in such a way that it is currently necessary to automate the review of the articles abstracts and full text.
To achieve this, we have a large database with information from the searches carried out since 2005 that would allow training the algorithms: 1,020 articles selected from the 10,891 references found in PubMed in the 2005-2010 period; 2,193 of 17,544 in 2011-2015; and 2,325 selected out of 8,996 in 2016-2017. A second step would be identifying which of the PRO instruments found are already included in our library and, for the PROs which are not included, extracting certain characteristics from the articles.

Tutors: Itxaso Alayo (IMIM), Laura Igual (UB) and Yolanda Pardo (IMIM)

Requirements: it can be carried out by a group of 2 students.



## Deep learning-based radiomics for multi-centre cancer image quantification

Radiomics is an emerging and relatively new research field which refers to extracting large-scale quantitative features (big data) from medical images with the goal of developing predictive and/or prognostic models for personalised cancer care. Most radiomics strategies lie within the field of Machine Learning, having two types, mathematically defined radiomics and deep learning-based radiomics. Radiomics is expected to become a critical component for integration of image-derived information for personalised treatment in clinical oncology, however there are some limitations regarding its robustness in multi-centre and multi-scanner data.
EuCanImage is an EU-funded large-scale research project coordinated by the University of Barcelona, which is building an European cancer image platform linked to biological and health data for next-generation artificial intelligence and precision medicine in oncology. The multi-centre resource comprises medical images (e.g. MRI, CT, MMG) and clinical information (biomarkers, disease status, etc). With the availability of such rich database, a comprehensive study of mathematically defined and deep learning based radiomics can be developed in order to study the generalisation power of the different radiomic strategies across clinical centre for cancer care. 
We offer an MSc project framed within EuCanImage to evaluate and enhance the potential of deep learning for radiomics based cancer quantification. In particular, the project comprises the following tasks:
-	Extraction and analysis of existing radiomics for cancer quantification.
-	Extraction and analysis of new deep learning radiomics for cancer quantification.
-	Machine learning models for fusing existing and novel radiomics features.
-	Benchmarking the robustness of the developed radiomics in multi-centre datasets (from Spain, USA, UK and Netherlands)

If interested, please contact ligual@ub.edu for more details.

Advisors: Laura Igual, Lidia Garrucho, Karim Lekadir (Universitat de Barcelona).

Number of students: 1 or 2 students.


## Disease prediction using synthetic images from Generative Adversarial Networks (GANs)

Nowadays, deep learning methods have achieved state-of-the-art performance in a variety of prediction tasks. Ever since the astonishing performance reported on image classification in a seminal paper by Krizhevsky et al (2012), the capabilities of deep learning continue to open new avenues for original research and innovation in a wide range of scientific and societal domains. In medicine, however, the promises of deep learning have been faced with various obstacles comprising privacy and legal issues, alongside difficulties in technology adoption and data availability. Therefore, introducing and establishing deep learning models in clinical practice continues to be a tough challenge. EuCanImage addresses this challenge in the realm of cancer imaging. EuCanImage is an EU-funded large-scale research project coordinated by the University of Barcelona,  which is building a data platform for next-generation artificial intelligence and precision medicine in oncology. The platform's multi-centre resources comprise medical imaging data (e.g. MRI, CT, mammography, radiomics), and biological (biomarkers, genomics) and clinical information (disease status, tumour stages, outcome, etc).
Such resources contain patient data and, therefore, methods need to be provided to preserve patient privacy. Also, cancer imaging data is inherently heterogenous, as tumours can vary strongly in size, shape, affected organs, genes and pathway mutations. This is challenging as data heterogeneity enforces the need to train models on larger amounts of data while privacy requirements constrain the possibility of retrieving large amounts of cancer imaging data from hospitals. 
Theoretically, the solution to these problems could be to generate high-quality synthetic training data. As part of EuCanImage, we offer an MSc project that investigates whether this theory actually works in practice by implementing and evaluating a generative adversarial deep learning model focusing on one of the following tasks.
1.	Balancing unbalanced medical datasets using Generative Adversarial Networks and SMOTE (One student)
2.	Preserving patient privacy through deep learning models trained exclusively on generated data (One student)

If interested, please contact oliver.diaz@ub.edu for more details.

Advisors: Oliver Diaz, Richard Osuala, Karim Lekadir (Universitat de Barcelona).



## Multimodal biomedical data integration for atrial fibrillation diagnosis using deep learning

Atrial fibrillation (AF) is the most common arrhythmia and an important risk factor for heart failure and coronary heart disease. Therefore, early detection of AF can greatly enhance the capability to prevent the onset of other diseases. Due to the complexity of AF, its early diagnosis is currently being hampered by the use of solely one type of information, e.g. electrocardiogram. With the advent of machine learning and the acquisition of large amount of heterogeneous biomedical data, new opportunities for accurate diagnosis are presented. 
In this context, this MSc project will focus on multimodal heterogenous data integration by means of machine/deep learning to improve AF diagnosis. We will use large-scale data from the UK Biobank (www.ukbiobank.ac.uk), an international research resource that includes data from over half a million participants recruited from across the UK and build models that can accurately diagnose the disease by extracting features and integrating data from:
¥	Cardiac magnetic resonance imaging (MRI), the reference modality in cardiology to assess the cardiac structure and function
¥	Radiomics information extracted from MRI (shape, size, intensity, and texture)
¥	Electrocardiogram (ECG), the diagnostic tool routinely used to assess heartÕs rhythm and electrical activity
¥	Lifestyle and environmental factors
¥	Biomarkers and lab tests 
¥	Clinical and family history
¥	Genomic data
The project will be part of the H2020 euCanSHare project (www.eucanshare.eu), which is building a multi-centre big data platform for cardiovascular personalised medicine research.

If interested, please contact polyxeni.gkontra@ub.edu for more details.

Supervisors: Polyxeni Gkontra, Akis Linardos, Karim Lekadir

Number of students: 2 students.


## Multi-centre, multi-scanner and multi-disease cardiac image quantification using machine and deep learning
In the recent years, many machine/deep learning models have been proposed to accurately segment and quantify cardiac structures in magnetic resonance imaging. However, when these models are tested on unseen datasets acquired from distinct MRI scanners or clinical centres, the quantification accuracy can be greatly reduced due to over-fitting. This makes it difficult for these tools to be applied consistently across multiple clinical centres, especially when subjects are scanned using different MRI protocols or machines. 
We propose an Msc project for cardiac image segmentation and quantification combining data from different centres, vendors, diseases and countries at the same time. We will evaluate the generalisation ability of machine/deep learning and cross-domain transfer learning techniques for cardiac image segmentation and quantification, by testing these on a cohort of 375 cardiac MRI studies comprising healthy, hypertrophic and dilated hearts, acquired in three different countries (Spain, Germany and Canada) and by using four distinct MRI vendors (Siemens, Philipps, General Electric and Canon). The project will be part of the H2020 euCanSHare project (www.eucanshare.eu), which is building a multi-centre big data platform for cardiovascular personalised medicine research. 

If interested, please contact karim.lekadir@ub.edu for more details.

Supervisors: Karim Lekadir, Victor Campello, Carlos Martin-Isla

Number of students: 2 students (one for segmentation, one for diagnosis)

## Segmentation of cardiac MRI in multi-centric and multi-vendor images using deep learning with uncertainty estimation

Segmentation of heart MRI images is a crucial step in diagnosing various cardiovascular diseases. Manually segmenting the left ventricle (LV), myocardium (MYO), and the right ventricle (RV) of the heart is a time-consuming task. Therefore, there is a high demand in automated segmentation methods that are robust to variations in images from different centres and MRI scanners.
A recent international cardiac image segmentation challenge (www.ub.edu/mnms) has received the attention of the research community in developing domain invariant deep learning techniques. However, there is still a lack of automated segmentation tools that could be used in clinical scenarios. Moreover, majority of the deep learning based approaches in the literature do not consider predictive model uncertainty in their segmentation results. This limits the application of such approaches in clinical practice. 
Goal of the MSc project: Development of an automated deep learning pipeline/toolbox for LV, MYO, RV segmentation from MRI images with a human-in-the-loop strategy for error correction. The contributions of this project are three-fold:
1.	Development of a deep learning based approach for accurate and robust segmentation of the LV, MYO, and RV from cardiac MRI images.
2.	Model uncertainty estimation to guide the human operator to rapidly assess and correct the low confidence regions in the automated segmentation masks.
3.	Active learning with the corrected masks to continuously improve the segmentation performance.
These contributions will be compiled into a toolbox/application with an intuitive graphical user interface that can be used in a clinical practice.

If interested, please contact kaisar.kushibar@ub.edu for more details.

Advisors: Kaisar Kushibar, Petia Radeva, Karim Lekadir (University of Barcelona)


## Domain Adaptation for Synthetic Data Generation

Most supervised deep learning approaches rely heavily on huge amounts of
annotated data which might not be available all the time. Data augmentation is one of the
approaches that can alleviate this problem to a certain extent [1]. To effectively use the vast amount of unlabeled and unstructured data, we need some kind of prior knowledge which
can be exploited to train deep learning algorithms on the unlabeled data. In many cases, the better labeled and poorly labeled domains share abstraction at task level, for example, for identifying vehicles in two datasets, one of which is accurately labeled and the other one is poorly labeled, the task is the same but the datasets might be acquired in different conditions. This kind of approach is sometimes referred to as semi-supervised learning [2,3]. This project aims at using the better labeled domain to generate synthetic data for the poorly labeled domain by aligning these two domains which share common tasks [4,5]. To be more specific, this project aims at using domain alignment/adaptation to use the vast amounts of annotated X-Ray datasets available on public domain to generate synthetic CT scan datasets for supervised deep learning on CT scans.

[1] Shorten, Connor, and Taghi M. Khoshgoftaar. "A survey on image data augmentation for deep learning." Journal of Big Data 6.1 (2019): 60.
[2] Zhu, Xiaojin Jerry. Semi-supervised learning literature survey . University of Wisconsin-Madison
Department of Computer Sciences, 2005.
[3] Zhu, Xiaojin, and Andrew B. Goldberg. "Introduction to semi-supervised learning." Synthesis
lectures on artificial intelligence and machine learning 3.1 (2009): 1-130.
[3] Mahmood, Faisal, Richard Chen, and Nicholas J. Durr. "Unsupervised reverse domain adaptation
for synthetic medical images via adversarial training." IEEE transactions on medical imaging 37.12
(2018): 2572-2581.
[4] Bousmalis, Konstantinos, et al. "Using simulation and domain adaptation to improve efficiency of
deep robotic grasping." 2018 IEEE international conference on robotics and automation (ICRA) . IEEE,
2018.
[5] Wilson, Garrett, and Diane J. Cook. "A survey of unsupervised deep domain adaptation." ACM
Transactions on Intelligent Systems and Technology (TIST) 11.5 (2020): 1-46.

Advisor: Petia radeva


## Deep Learning with Noisy Labels

Rationale: One of the key reasons why deep neural networks (DNNs) have been so successful in image classification is the collections of massive labeled datasets such as COCO and ImageNet. However, it is time-consuming and expensive to collect such high-quality manual annotations. A single image often requires agreement from multiple annotators to reduce label error. On the other hand, there exist other less expensive sources to collect labeled data, such as search engines, social media websites, or reducing the number of annotators per image. However, those low-cost approaches introduce low-quality annotations with label noise. Many studies have shown that label noise can significantly affect the accuracy of the learned classifiers [2, 23, 32]. In this Master work, we will address the problema of how to effectively train on noisy labeled datasets?

Scope: The prominent issue in training DNNs on noisy labeled data is that DNNs often overfit to the noise, which leads to performance degradation. We will addresses this issue by optimizing for a model’s parameters that are less prone to overfitting and more robust against label noise. Specifically, for each mini-batch, we will propose a meta-objective to train the model, such that after the model goes through conventional gradient update, it does not overfit to the label noise. The proposed meta-objective encourages the model to produce consistent predictions after it is trained on a variety of synthetic noisy labels. The key idea of our method is: a noise-tolerant model should be able to consistently learn the underlying knowledge from data despite different label noise.

Main tasks:
1.       Study state of the art
2.       Propose a noise-tolerant training algorithm, where a meta-objective is optimized before conventional training. The method should be theoretically applied to any model trained with gradient-based rule.
3.       Aim to optimize for a model that does not overfit to a wide spectrum of artificially generated label noise.
4.       Formulate the meta-objective as: train the model such that after it learns from various synthetic noisy labels using gradient update, the updated models give consistent predictions with a teacher model.
5.       Adapt a self-ensembling method to construct the teacher model, which gives more reliable predictions unaffected by the synthetic noise.
6.       Perform experiments on datasets with synthetic and real-world label noise, and demonstrate the advantageous performance of the proposed method in image classification tasks compared to state-of-the-art methods.
7.       Conduct extensive ablation study to examine different components of the proposed method.

BIBLIOGRAPHY:
1. Li at.el., Learning to Learn from Noisy Labeled Data, 2019
2. Yi, et.al., Probabilistic End-To-End Noise Correction for Learning With Noisy Labels CVPR’2019,
3. Zhu et.al., A Generative Adversarial Approach for Zero-Shot Learning from Noisy Texts: CVPR02018.
4. Xiao, et.al., Learning from Massive Noisy Labeled Data for Image Classification, CVPR’2019.

Advisor: Petia Radeva

Requirements: This project ideally should be developed by a team of 3 persons. In case the team is of less members the project will be properly rescaled considering only some of the goals. 



