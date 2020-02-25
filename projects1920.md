
# Project Proposals (19/20)

# Project Assignments 

| Student   |      Title      |  Tutor|
|----------|:---------:|----------:|
| Bernat Esquirol | Classification algorithms for ego-networks in online social Networks | Albert Diaz-Guilera |
| Alfons Córdoba | Classification of patterns in animal mobility                         | Albert Diaz-Guilera  |
| Laia Domingo | Identification and classification of bearing faults                     | Jordi Vitrià  |
| Michael Depasse | Brain Functional Connectivity of Motivated States: A Computational Analysis | Ignasi Cos & Antonio Donaire (Institute of Neuroscience, UB)  |
| Albert Garcia & Pere Gilabert | Endoluminal image classification: Human explainability through an auxiliary network | Santi SeguÌ  |
| Núria Sánchez Font | Predicting Chaos | Oriol Pujol |
| Jordi Ventura Banqué & Xavier López | Deep Learning with Noisy Labels | Petia Radeva |
| Alejandro González Álvarez & Alejandro Hernandez | New data science techniques for multi-centre and multi-type biomedical data platforms |  Karim Lekadir, Oliver Diaz, Xenia Gkontra |
| Àlex Arcas Cuerda | ML for white matter hyperintensities detection | Quim Radua & Eloi Puertas |
| Petar Tonchev & Mariya Mladenova | DeepFood: Deep-(Learning)-Diving into the Food Data World | Petia Radeva |
| Jordi Solé | HP project | Mariano Yagüez Insa | 



# Original Project Proposals

## Predicting Chaos
Summary: Recent advances in machine learning have heavily influenced other areas of knowledge. One of these advances concerns the predictability of chaotic dynamical systems. Chaotic systems are characterized for presenting very different outcomes to very small variations of initial conditions. So far this looks quite abstract and complex, but is far easier. Recently, thanks to machine learning the horizon of prediction of chaotic dynamical systems has been extended by an order of magnitude. This incredible advance makes chaos far more predictable. See for reference https://www.quantamagazine.org/machine-learnings-amazing-ability-to-predict-chaos-20180418/. In this TFM we want to understand the basis of reservoir computing, the kind of technique that allows this incredible feature to be performed. We will apply this to a real scenario to define with the candidate.

Advisor: Oriol Pujol

Requirements: project for one student.


## From the Visual Analysis of Movement to Principled Models of Motivated Movement
Description: Movement is our only channel to interact and communicate with the environment. Motor actions, as a function of the intended goal and of our internal state, are executed in different fashions. For example, professional athletes tend to reduce their movement variability when competing vs when they are training, although their instruction may be the same. Likewise, we tend to perform more energetic action when the stakes are high or when there is an urgency to attain a specific target (Schmidt et al., 2008), strongly suggesting a fundamental link between the motivational and the motor systems.
State-of-the-art generative models of motor control are capable of finding the correct sequence of muscle activations associated to a specific movement. However, their fundamental shortcoming is that they are disconnected from motivation and emotional phenomena. In a different order or things, recent advances in image processing have proven the distinct possibility of extracting markers of the emotional/motivational state of a subject via algorithms of image analysis.
The ultimate goal of the project here introduced is to relate both perspectives, the model based approach of motor control theory with the model-free approach of image processing, as to established principled connections between the inference methods used to extract motivational/emotional information from gait/movement image analysis and extended models of motor control that could incorporate motor control theory in a principled fashion.
To that end, we propose to perform a set of controlled experiments with healthy human subjects, to record kinematic data and infer their motivational data one the grounds of visual arm movement and gait image analysis. The participant will have to make reaching and pointing movements from first dot on the screen to the next by sliding his/her index finger onto a tablet, or to perform stereotypical walking movements in a controlled fashion. Movements are performed in exchange for a score. In a covered fashion, a careful analysis of their movements should allow us to establish not only whether and how motivation and effort are constraints for their motor responses, but would also to provide a quantitative understanding of whether the laws of motor control also apply.
RGB-Depth sensors will be used to capture visual information from the environment, and computer vision and machine learning approaches will be used to compute and analyse behaviour of the participants.

Advisors: Ignasi Cos, Sergio Escalera

Requirements: project for 2 students.


## Brain Functional Connectivity of Motivated States: A Computational Analysis
Our movements depend on our motivational states. However, our understanding of how our engagement varies,
or how our degree of motivation reflects both on neural brain activity and on the interconnectivity across brain
areas, it all remains poorly understood. For example, when human participants perform a decision-making task
between reaching movements, their movement parameters and their selection between movements is clearly
different when playing solo than when playing in the company of another partner, irrespective of whether they
were instructed not to compete among themselves. Specifically, the participants’ aiming error decreased
alongside the skill of their partner, and their selection of motor movements adjusted consistently with a
devaluation of effort and an overvaluation of reward. This is corroborated by a theoretical assessment of the
subjects’ behaviour. Although this supports the influence of social pressure on our concern for reward, causing
a re-scaling their overall motivated state, and confirming the social relativity of their internal reward valuation
system, we do not know this occurs in the brain.
During these experiments, we recorded surface Electro-Encephalographic (EEG) signals from each part of the
cortex. Preliminary analyses of these recordings have shown that different mental states, associated to different
mental states associated to motivation may be identified via machine learning techniques, such as k-means or
logistic regression. The question remains, whether specific changes of functional connectivity may formally
recognise from this dataset.
In summary, the project we propose aims at the following goal: if we transform the EEG signals from sensory
to source space (Hindriks et al., 2017), can we identify differences in functional/effective brain connectivity
as a function of the motivated state?
The student’s goal would be that of developing computational models of the brain, to identify and quantify
differences of neural connectivity across brain areas as a function of the person’s level of task engagement
(motivated state). The student will also be at charge of the preparation of scientific manuscripts for publication
and of presenting these results at scientific conferences.
References:
Gilson M, Moreno-Bote R, Ponce-Alvarez A, Ritter P, Deco G (2016) Estimation of Directed Effective Connectivity from fMRI
Functional Connectivity Hints at Asymmetries of Cortical Connectome. PLoS Comput. Biol. 12
Hindriks R, Schmiedt J, Arsiwalla XD, Peter A, Verschure PFMJ, Fries P, Schmid MC, Deco G (2017) Linear distributed source
modeling of local field potentials recorded with intra-cortical electrode arrays. PLOS ONE 12:e0187490

Advisor: Ignasi Cos

Requirements: project for 2 students.


## Would Barcelona Low Emissions Zone deliver?

Next January 1st the new Barcelona Low Emissions Zone (LEZ) will enter into force (https://www.zbe.barcelona/). This means that most polluting vehicles will not be able to circulate in an area of more than 95 km2, inside the Barcelona Ring Roads. 
Evaluating the success/failure of the LEZ in terms of pollution reduction is a non-trivial question because pollution measured levels depend on a high number of factors, both related to emissions and diffusion of the pollutants. Some of them are highly variable (i.e. weather conditions). As a consequence, a direct comparison between 2020 pollution levels and previous years’ values is not a proper method to evaluate LEZ effects.

The main objective of this project is to develop an automated evaluation method based on official pollution data provided by the Catalan air quality measurement network, atmospheric data, and other relevant information, to continuously evaluate the results of the Low Emissions Zones. One possible approach is to learn a prediction model of the pollution of the city of Barcelona based on the measurements of the metropolitan area (historical data) and use it for comparison with the current values.

The project outcomes will include an evaluation report and a website/dashboard. 
The results of the continuous assessment will be publicly available in www.contaminacio.barcelona website. They will also be presented to the “evaluation team“ that Barcelona Municipality is setting to evaluate the results of Low Emission Zone. If both methodology and results are robust enough a paper in a peer-review journal will be prepared.  

Advisors: Laura Igual (UB) & Miquel Ortega (ENT Foundation).

> Miquel Ortega studied physics at the UB and holds a PhD on Environmental Sciences from the UAB. He is currently working in ENT Foundation and leads the website “Contaminacio.Barcelona”. From 2016 to 2019 he was the main sustainability advisor of Barcelona City Council, where he was responsible for coordinating the development of pollution policies. 

Requirements: project for 1-3 students.


## Deep Learning for early-stage embryo image analysis
During the last decades, artificial reproduction technologies (ART) have tried to solve the problem of artificially inducing a pregnancy. Among the different challenges of these technologies, the characterization of the obtained embryos stands out due to its potential impact on the outcome of the ART treatments. So far, physicians have manually annotated different characteristics of the embryos at different development stages, known to be related with correct embryo maturation, after a costly visual inspection using a microscope.
Modern culturing devices incorporate multiple cameras that continuously monitor embryos during their whole culturing process. Thus, nowadays, video images of cultured embryos are commonly available in ART laboratories. The popularity of these devices rocketed in parallel to the explosion of deep neural network (DNN) models, which has become the leading paradigm in the field of image analysis.  
In this work, the student will have to learn, propose and apply different DNN models to the analysis of early-stage embryo images. The main objective is to automate the process of feature extraction-selection and learn models that potentially exploit all the information available in the images to assist physicians in the process of decision-making.

Advisors: Jerónimo Hernández González (jeronimo.hernandez@ub.edu, momo@iiia.csic.es) & Jesús Cerquides Bueno (cerquide@iiia.csic.es)

Requirements: individual project.

## Neural Natural Language Processing for prediction of political violence

The conflict literature has made significant progress in understanding which countries are more at risk of suffering an armed conflict. However, many factors that have been identified as leading to increased risk, like mountainous terrain or ethnic polarization, are time invariant or very slow moving, and therefore not useful in predicting the timing of conflict. Other factors, like GDP levels or political institutions, still vary more between countries than within countries over time. This means it is easier to predict whether a country is at risk in general rather than when a country is particularly at risk. Yet, understanding the timing of conflict is critical for policy.

An additional problem of forecasting the timing of armed conflict is that it is rare and at the same time relatively concentrated in some countries. This is problematic because it implies that the variation between countries can dominate the analysis unless the between- and within-country variations are separated explicitly. Empirical models that are overall quite accurate can therefore be of little use on the time dimension. As a solution to this problem, Mueller and Rauh propose data generated from news sources. To this end, they implement an automated method to quantify the content of news using the latent Dirichlet allocation (LDA) model, which they apply to over 700,000 newspaper articles from English-speaking newspapers. There are two advantages that topics have over existing methods of analyzing text. First, topics provide depth because, by design, they put words into context. The context can be useful for forecasting. Second, topics provide width because they allow them to use the whole text, including stabilizing factors, when forecasting conflict. This means they can let the data speak without losing interpretability of the results.

Recently, neural methods have rushed the NLP landscape with models such as BERT and its derivatives. In this work we propose to study, evaluate and compare neural NLP technonologies as an alternative to LDA for the feature extraction process in the problem of prediction of the arising of political violence in countries from Newspaper text data. 

This project will be coordinated with Prof. Hannes Mueller of the Institut d’Anàlisi Econòmica and Prof. Christopher Rauh from University of Montreal.

Advisors: Jerónimo Hernández González (jeronimo.hernandez@ub.edu, momo@iiia.csic.es) & Jesús Cerquides Bueno (cerquide@iiia.csic.es)

Requirements: individual project.


## Haar like features for fast  computer vision

The Viola-Jones algorithm is still used in many applications. During the past years, data augmentation techniques have shown great results improving computer vision algorithms. This project aims to improve the quality of the algorithm using data augmentation and other techniques that have been paramount to achieve better results in computer vision pipelines. The project will involve coding the Viola Jones algorithm in Julia and test in different object detection applications. For example, face detection, small boat detection, etc...

The improvements of "face swapping" quality is starting to be problematic. Face detection is a crucial part needed in order to verify if a face was "swapped" or not in an image. We propose to first build a face detector which can be used, for example, as a pre-process to gather faces from a video stream. Then face identification can be done with a cropped image of the face.

Advisors: Eloi Puertas & David Buchaca

Requirements: project for 2 students


## High performance machine learning on commodity hardware

We propose to implement, from scratch, machine learning algorithms in Julia target Big data on budget hardware. The goal of the project is to implement high performant machine learning code in Julia that is not practical to implement in scikit-learn or tensorflow. The final objective of the project is to implement a bunch of out of core algorithms that can be trained on big datasets with commodity harware (a modern laptop). 

Algorithms that should be implemented:

- Classical Adaboost

- Gradient boosting

- Random Forest

Machine learning is a field where the speed of the code is paramount in order to facilitate rapid experimentation and iteration of results. Julia is a high performance and high productivity language that delivers ease of use and high productivity to coders.  Machine learning practitioners face a big challange when they want to implement new ideas in real code.  There is a big dichotomy between productivity and performant code (should I use python or C ?).

http://ucidatascienceinitiative.github.io/IntroToJulia/
https://julia.quantecon.org/index_toc.html

Advisors: Eloi Puertas & David Buchaca

Requirements: project for 2 students


## New data science techniques for multi-centre and multi-type biomedical data platforms
The big data revolution continues to have a transformative effect on research and innovation in a wide range of scientific and societal domains. In biomedicine, however, the promise of big data has been faced with legal, operational and financial obstacles, which have made it a very hard challenge to establish large-scale research databases covering multiple data types and populations. 
euCanSHare (www.eucanshare.eu) is an EU-funded large-scale research project coordinated by the University of Barcelona, which is building a big data platform for integrating and co-analysing multiple databases across Europe and beyond. The multi-centre resource comprises medical images (e.g. cardiac MRI, radiomics, brain imaging), biological/omics data (e.g. genomics, biomarkers), lifestyle/exposure information (diet, exercise, pollution, etc) and clinical information (blood pressure, disease status, etc). 
With the availability of such heterogeneous database, there is a need for new data science techniques not only for processing the large volumes of datasets, but also for building new machine learning models to stratify patients and estimate disease risk and stage.
As part of euCanSHare, we offer an MSc project that will be composed of four distinct but linked tasks:
1.	Multi-centre image segmentation using deep neural networks (1 or 2 student(s)).
2.	Disease prediction using interpretable artificial intelligence (1 student).
3.	Patient stratification using hierarchical clustering and machine learning (1 student).
4.	Multi-source data integration and visual analytics (1 student).
If interested, please contact karim.lekadir@ub.edu for more details.

Advisors: Karim Lekadir, Oliver Diaz, Xenia Gkontra (Universitat de Barcelona). 
Collaborations: Queen Mary University of London, UK (Steffen Petersen), University Medical Centre Hamburg-Eppendorf, Germany (Mahir Karakas), McGill University Health Centre, Canada (Matthias Friedrich) and Vall d’Hebron Hospital, Barcelona (José F. Rodríguez Palomares).

Renumeration: 1,000 Euros for each student.


## DeepFood: Deep-(Learning)-Diving into the Food Data World

Rationale: Human relationship with food is truly unique. Food has a strong impact on human health, life and wellbeing. Malnutrition, overweight and obesity are one of the major risk factors for various chronic diseases, such as diabetes that today affects 415 million people worldwide. Food images imply facing strong Computer Vision and Machine Learning (ML) challenges, like the dish being mixed or composed of many foods, different food dishes can look very similar, the same dish could be presented quite differently, or the same dish can be named in different ways, thus adding an extra complexity to the high number of dishes to be recognized. Moreover, food labels are ambiguous and interrelated (e.g. is mayonnaise a dish, a sauce or an ingredient?). Food terms and concepts appear at different levels of generalization (pasta vs. paella), there is no strict definition of all foods (e.g. a dish can be called “confit de canard”, “duck with honey and lemon”, “duck” or “chicken”) and terms can be highly correlated or anti-correlated. We need a food ontology as a formal theory for the food domain to specify the meaning of terms within a vocabulary, and to provide a taxonomic structure as well as the relations of the food entities. Besides, how to organize and extract all this huge and unstructured food information available from different sources as images, text recipes, web pages?!
ope: One of the big Deep Learning strengths is capability to allow applying Transfer Learning (TL) in order to bring knowledge from one domain/problem/task/dataset to any other as required, thus improving learning performance, while decreasing the need for large datasets. However, in the Food Computing context, the Transfer Learning potential is still heavily underexplored, limited just to fine-tuning pre-trained models from a generic perspective to the food domain; its capacity to achieve the desired accuracy and CV and ML challenges, like the dish being mixhes coverage is underexplored. As main limitations of Food Computing, most authors consider only a quite limited number of dishes. Furthermore, they are limited to classical fine-tuning neural Networks, ignoring that the nutritional information in images can be much richer and ambiguous than just a single label of a dish. Moreover, all of them only consider a well-defined, but limited list of dishes/classes to be recognized, usually 101 or 256.

Main goals:
1.       The first goal is related to constructing a food ontology to organize large amount of food text in a graph network to show relations of food terms. This graph will be constructed by scrapping large amount of food web pages and using word embedding to obtain the distance between the vocabulary words.
2.       Second goal is related to embed the graph network to a deep learning model. We will explore different alternatives and implement the best architecture.
3.       Third goal is related to explore how graphical neural networks can help recognizing food categories (dishes, types, ingredients, cuisines) using the graph network. Different graph neural networks works will be explored and the optimal one will be implemented.
4.       Last goal (optional) will be related to make a broader analysis of how food recognition can be benefitted by transfer learning (domain adaptation, or multi-task learning). If time allows we will extend and compare to different transfer-learning techniques as domain adaption and/or multi-task learning.

References:
1.      Aguilar, Eduardo, Marc Bolaños, and Petia Radeva. "Food recognition using fusion of classifiers based on cnns." International Conference on Image Analysis and Processing. Springer, Cham, 2017.
2.      Bolanos, Marc, and Petia Radeva. "Simultaneous food localization and recognition." 2016 23rd International Conference on Pattern Recognition (ICPR). IEEE, 2016.
3.      Bolaños, Marc, Aina Ferrà, and Petia Radeva. "Food ingredients recognition through multi-label learning." International Conference on Image Analysis and Processing. Springer, Cham, 2017.
4.      Sarker, Md Mostafa Kamal, et al. "CuisineNet: Food Attributes Classification Using Multi-Scale Convolution Network." CCIA. 2018.
5.      Martinel, Niki, Gian Luca Foresti, and Christian Micheloni. "Wide-slice residual networks for food recognition." 2018 IEEE Winter Conference on Applications of Computer Vision (WACV). IEEE, 2018.
6.      Salvador, Amaia, et al. "Inverse cooking: Recipe generation from food images." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2019.
7.      Nguyen, T. Binh, et al. "A deep learning based food recognition system for lifelog images." (2018).
8.      Min, Weiqing, et al. "A survey on food computing." ACM Computing Surveys (CSUR) 52.5 (2019): 92.

Advisor: petia Radeva

Requirements: This project ideally should be developed by a team of 3 persons. In case the team is of less members it will be properly rescaled considering only some of the goals.


## Using Lifelogging to Analyze People’s Environment and Activity and their Relation to Poverty and Health
Rationale: Poverty and housing quality are powerful factors that shape health across the lifecourse.1 Socio-economic position (SEP), a broad term referring to social and environmental factors that indicate the position of individuals or households within a society,2 is multi-dimensional and difficult to measure. SEP is also highly correlated with several environmental exposures, and therefore, is an important confounder in environmental epidemiology. For example, access to clean household energy is tightly linked with poverty, and fully accounting for confounding by poverty in studies of household air pollution remains a challenge.3

The scale of available image-based data sources and analytical methods for deriving information from these images is opening new opportunities for measurement of environmental exposures and essential covariates like SEP. Recently, with the huge advances in Deep learning, Computer Vision algorithms achieved huge advances in image interpretation [Krizhevsky’12]. Today Computer Vision algorithms are able to detect and recognize up to 1000 different objects in images although their different appearance, bad contrast, occlusions are other artefacts. In addition, Computer Vision algorithms are able to automatically analyze and recognize more than 365 different environments and places [Zhou’14].

Scope: We will apply Deep learning and Computer Vision algorithms in order to extract and describe the different environments in terms of the objects and places appearing them. By combining photograph data with questionnaire data on household assets, surrounding land use, surrogates of urbanicity (e.g. NTL), we will use automatic summary extraction approaches to identify clusters of SEP based on topic models [Lonn’19, Steyvers’07]. These clusters will provide more finely resolved classification of SEP, integrating information on the multiple dimensions comprising SEP.

More detailed information on assets, housing quality and household environment, social environment, and individual activities will be derived from wearable camera data collected in a subset of the study population. We will use images acuired by a Narrative wearable camera, that provides a first-person point of view image automatically every 30s without user intervention. Wearable cameras are small and light cameras that used to be worn as a pin acquiring images in a time-lapse mode all the day. In this way, images captured can explain in which environment the person has been during the day and how long, what activities he/she has done, with whom he/she interacted and so on. Analyzing manually 280K is a slow process. To this purpose we will apply automatic egocentric algorithms for places analysis [Peris’16], activities detection)[Cartas’17], interaction characterization) [Aghaei’16,Aghaei’18] and visual summarization [Bolanos,’16, Dimiccoli’17].

Data will be analysed for each user separately to extract information on: 

1) the presence of objects, that used to be part of the environment of each person  [Dimiccoli’17]; 

2) characteristics of the place, housing and immediate environment surrounding the participant[Sarker’18], 

3) specific activities (e.g. eating, working, travelling)[Cartas’17].  Analysis will be conducted by the Machine Learning and Computer Vision consolidated research group at University of Barcelona.

The information derived from the wearable cameras will be used to define clusters of perfils in the population.

References:
 Tusting, L. S.; Bisanzio, D.; Alabaster, G.; Cameron, E.; Cibulskis, R.; Davies, M.; Flaxman, S.; Gibson, H. S.; Knudsen, J.; Mbogo, C.; et al. Mapping changes in housing in sub-Saharan Africa from 2000 to 2015. Nature 2019, 568 (7752), 391–394.
Mok, T. M.; Cornish, F.; Tarr, J. Too Much Information: Visual Research Ethics in the Age of Wearable Cameras. Integr. Psychol. Behav. Sci. 2015, 49 (2), 309–322.
Kelly, P.; Marshall, S. J.; Badland, H.; Kerr, J.; Oliver, M.; Doherty, A. R.; Foster, C. An ethical framework for automated, wearable cameras in health behavior research. Am. J. Prev. Med. 2013, 44 (3), 314–319.
[Krizhevsky’12] Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks." Advances in neural information processing systems. 2012.
[Zhou’14] Zhou, Bolei, et al. "Learning deep features for scene recognition using places database." Advances in neural information processing systems. 2014.
[Bolanos,’16] Bolanos, Marc, Mariella Dimiccoli, and Petia Radeva. "Toward storytelling from visual lifelogging: An overview." IEEE Trans. Human-Machine Systems 47.1 (2016): 77-90.
[Dimiccoli’17] Dimiccoli, Mariella, et al. "Sr-clustering: Semantic regularized clustering for egocentric photo streams segmentation." CVIU 155 (2017): 55-69.
[Peris’16] Peris, Álvaro, et al. "Video description using bidirectional recurrent neural networks." International Conf. on Artificial Neural Networks. Springer, Cham, 2016.
[Cartas’17] Cartas, Alejandro, Mariella Dimiccoli, and Petia Radeva. "Batch-based activity recognition from egocentric photo-streams." Proceedings of the IEEE International Conference on Computer Vision. 2017.
[Steyvers’07] Steyvers, Mark, and Tom Griffiths. "Probabilistic topic models." Handbook of latent semantic analysis 427.7 (2007): 424-440.
[Sarker’18] Sarker, Mostafa Kamal, et al. "MACNet: Multi-scale atrous convolution networks for food places classification in egocentric photo-streams." ECCV. 2018.
[Lonn’19] Lonn, Stefan, Petia Radeva, and Mariella Dimiccoli. "Smartphone picture organization: A hierarchical approach." Computer Vision and Image Understanding 187 (2019): 102789

Advisors: Petia Radeva (UB), Catheryn Thonne (ISGlobal)  

Requirements: This project ideally should be developed by a team of 3 persons. In case the team is of less members the project will be properly rescaled considering only some of the goals.

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



## Uncovering the role of air chemistry in Kawasaki Disease

Rationale: Kawasaki disease (KD) is a long known self-limited vasculitis of unknown origin that affects children worldwide, and that may have serious consequences if left untreated. It was discovered by Dr. Kawasaki in the 1960s and genètic susceptibility has been claimed as an underlying predisposing factor. However, in the last few years a consortium led by the ISGlobal Climate & Health Program has set the basis for a revolutionary hypothesis pointing to an airborne cause of this mysterious syndrome.
The current proposal seeks to test whether air quality, in particular the composition of metal elements, can be associated to KD etiology. A weekly record of unprecedented air samples taken in Japan in 2014 and 2015, covering 1,5 years has been fully derived for its air chemistry. Concomittantly other daily chemistry records will have to be compared to daily KD records as a proof-of-concept. The student will have at hand an extense database of over 50 different metal elements and the objective is to check what relationships there are among them and to understand which ones are associated among themselves and whether they are, on certain ocasions, associated also with KD incidence. To accomplish these objectives, it is expected that the datasets can be analyzed with a variety of classification, ordination and other data statistical techniques.

Advisors: Xavier Rodó (ISGlobal) & Santi Seguí & Laura Igual

Requirements: project for 1-2 students.


## Are weather stations in Barcelona well placed or should they have been placed elsewhere? How many more are there missing and where they should be placed?

Rationale: There are seven meteorological measurement stations in the city of Barcelona. When they were located throughout the recent and not so recent history of the city, the reasons for choosing their location were diverse and, of course, they did not always meet the criteria of scientific suitability. It is for this reason that this master project proposes an objective analysis of their suitability in comparison with the high resolution data from an urban climate model (UrbClim), currently implemented by the CLIMA program of ISGlobal. By using supervised and unsupervised machine learning systems it is intended to answer such questions as:
1- What is the average global temperature per day for anyone in Barcelona based on the data measured and how do they compare with those on the ISGlobal model?
2- Do they adequately estimate the tmin, tmax, tmean of these stations in the city or should they be relocated elsewhere? And what would be these locations if the criterion is that they best describe the variance in the data generated by the model?
3- If we wanted to achieve 90%, 95% or 99% of the variance explained, how many more stations should we put and where would we place them?
From data from the city of Barcelona (both from Barcelona City Council itself, from ISGlobal and other institutions or initiatives) it is possible to understand how the city is reacting to the challenges of climate change and to predict how it can be adapted to these. The project poses a challenge with the exercise of Data Science with the ultimate goal of transforming data into useful information for managing the city in order to increase the information requested by citizens and how to increase their well-being. For this study it will be possible to have besides the data of the 7 public stations, 26 private stations of Barcelona and 26 private stations of the AMB.
The proposal's developers (s) are expected to create a web environment that describes the work they have done.

Advisors: Xavier Rodó (ISGlobal) & Santi Seguí & Laura Igual

Requirements: project for 1-2 students.

## Identification and classification of bearing faults

Predict failure and its root case in rotating equipment (specially pumps). Such machines can be rotating under different operating conditions (different rotational speed and different loads). The goal is to develop a predictive  maintenance  program which is able to diagnose early failure modes for all operating conditions and with few data samples. Deep convolutional networks will be used along with other techniques such as Nuisance Attribute Projection and Triplet learning. This project will be developed at Accenture.

Advisor: Jordi Vitrià

Requirements: project for one student.

## UViu: multispectral smartphone imaging for personalised sun protection

UViu is a smartphone-based, cost-effective multispectral imaging platform currently being developed
at ICFO, the Institute of Photonics Sciences in Barcelona, with the aim of creating a spin-off company.
The UViu team consists of Kevin Schädler, physicist/engineer with a PhD in photonics from ICFO, and
Montse Mussons, an economist with a background in tech startups.
One of UViu’s most promising applications is to fight skin cancer, the most common form of cancer
worldwide today. Most skin cancer is caused by insufficient sun protection, which is hard for users to
understand. Here, UViu’s imaging capabilities will enable anyone to see and quantifyi their personal
degree of sun protection to reduce this risk.
Our technology enables simultaneous and real-time ultraviolet (UV), visible (VIS) and near-infrared
(NIR) imaging on any smartphone using a combination of an app and clip-on optics attached to the
smartphone’s camera (below left image). At present, we have developed a hardware prototype to
demonstrate the multispectral imaging capabilities on a basic app, including UV imaging to visualise
sunscreen coverage (below right image).

To further develop UViu’s capability of quantifying personal sun protection, we are currently looking
for highly motivated students with an expertise in computer vision and deep learning. In particular, we
are looking for candidates interested in one or more of the following tasks:
1. Real-time measurement of sunscreen coverage by combining feature recognition in different
spectral regions (e.g. detection of facial area in the visible / NIR + coverage measurement in
that area in the UV) under solar illumination.
2. UV index measurement by measurement and calibration of the UV signal.
3. Quantification of effective sun protection. This combines an assessment of the user’s skin type
(e.g. by body feature recognition + VIS/UV reflection) and the UV contrast provided by a given
sunscreen.
These functionalities would ideally be directly implemented on a mobile platform (e.g. Android), but
could initially also be developed on a stationary platform as a proof of concept. 

We are also looking for **longer-term involvement** if the candidate/s are interested.

Advisors: Kevin Schädler & Jordi Vitrià

Requirements: project for one student.

## ML for white matter hyperintensities detection

Magnetic resonance imaging (MRI) scans of patients with specific mental disorders (e.g. bipolar disorder) have been reported to show increased white matter hyperintensities (WMH), especially when using the fluid-attenuated inversion recovery (FLAIR) sequence. However, the detection of WMH is currently still conducted by visual inspection by a neuroradiologist, thus requiring human work and commonly resulting in imprecise reports about their size and localization. Several machine learning methods have been begun to use to conduct automated detection of WMH, but they were usually developed for other aims and their accuracy is little known. The aim of this project is to properly evaluate and compare the accuracy of the different methods to detect WMH in order to provide guidance. This work will benefit from a unique database of 9,705 WMH precisely located and sized by an expert neuroradiologist from 162 brains (95 from individuals with bipolar disorder and 67 from healthy controls). This work may be used for a PhD.

Advisors: Quim Radua & Eloi Puertas

Requirements: project for one student.

