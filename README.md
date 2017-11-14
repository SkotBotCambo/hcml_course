![Photo of man caught in cog](http://lancemannion.typepad.com/.a/6a00d83451be5969e20168eab43dc9970c-pi){: .center-image }

By definition, Machine Learning provides software with a way to learn something 
that it was not explicitly programmed for. 
In practice, Machine Learning is often used to allow **people** to learn something they might not 
have been able to do otherwise (e.g. infer relationships from 
large scale high-dimensional data at potentially high speed) and allow computers 
to learn something that humans learn naturally (e.g.: speaking, hearing, seeing). 
These two broad application areas of 
Machine Learning not only have a large impact on human behavior, their success 
often depends on a nuanced 
understanding of human behavior and how people interact with technology 
(i.e.: sociotechnical behavior). Students of 
the Human-Centered Machine Learning course will help form a new way of 
understanding and practicing the application of
machine learning through a series of readings, discussions, design and 
prototyping assignments, and a final project.

## Introduction

## Prerequisite Education
* At least one Human-Computer Interaction or Design Thinking course
	* Specifically a familiarity of human factors and the emprical methods used to uncover them
* At least one Machine Learning, Artificial Intelligence, or Data Science course
	* Specifically students should be comfortable applying methods for supervised and unsupervised learning in a software application of their design.
* Ability to program at a level appropriate for EECS 349 (Machine Learning)
	* Specifically, you should be able to comfortably write code in Python without help from the TA or Professor

## Learning Objectives
Students who complete this course satisfactorally will...
* ...be comfortable discussing machine learning and artificial intelligence as part of a broader socio-technical system
* ...have an understanding of how the behavior of artificial intelligence and machine learning algorithms as well
as user task, intention, and understanding affect the overall user experience.
* ...understand how to identify design constraints and optimization criteria from both the user experience 
and algorithm research in a domain. 
	* In both cases, these may be more implicit than explicit requiring that students develop an eye for:
		* 1. translating UX research into design principles that can be addressed with tweaks to the learning algorithm.
		* 2. identifying assumptions that are made in the design of the learning algorithm and how they might (or might not) be challenged.

## Assignments
Students will be required to complete the following assignments

### HCML Project
Students will complete a final research paper (10 pages maximum)
that explores HCML in one of the following ways:
* researching a system of the students' creation which integrates user-centered design principles into
  the design of the machine learning components of the system to address a user experience challenge or a novel user task
* researching the design and implementation of an interactive machine learning system which might address
  some of the issues with automated learning systems discussed in class including (but not limited to) algorithmic bias, algorithmic accountability, and model transparency.
* makes explicit through proof or demonstration an assumption used in the design of a learning algorithm which can result in one of the issues with AI and ML algorithms discussed in class (e.g.: algorithmic bias)

Students may also propose an alternative to one of these research paper formats.

The HCML project will need to have a rough draft and a poster and/or demo completed by the 10th week
of class for a poster/demo session that will be open to the public. The final draft will need to be 
completed at the beginning of finals week so that students can exchange and review each others' work.

### Weekly Presentation
Students will lead discussion with a presentation twice in the quarter:
1. One presentation will be leading a 45 minute discussion and presentation
on research that is already included in the schedule. 
This presentation will also need to synthesize and incorporate reading responses from the 
other students.
2. One presentation will be leading a 20 minute discussion and presentation
on research, found by the student, that is related to the students' final project 
and enriches the conversation in human-centered machine learning. The purpose of this presentation
is to facilitate an on-going conversation about how the practice and research of machine learning
can be more "human-centered".

### Reading Response and Discussion
In order to better digest the readings, students will write a response to a weekly discussion
prompt (provided in the reading schedule) using the readings. This response will need to be uploaded 
by the Monday before class so that students will have a chance to read each others' responses
and the presenter can integrate them into the weekly presentation

## Schedule
### Week 1 : Introduction
#### Themes covered:
* Mental Models, Conceptual Models, System Image,
* Human-Centered Machine Learning as a broad topic of research
* Common mistakes in machine learning

#### Discussion Prompt : 
* **How can Machine Learning make an aspect of life better?** Don't overthink this. It can realy be any aspect of anybody's life.
* **Can you think of an example of someone doing/attempting to do this?**
* **How do we evaluate this example's performance in making this aspect of life better?**

#### Readings :
* [Human-Centered Machine Learning (The Google Approach)](https://medium.com/google-design/human-centered-machine-learning-a770d10562cd) (*Josh Lovejoy*, *Jess Holbrook*)
* [Human-Cent*r*ed Machine Learning (The Academic Approach)](https://medium.com/human-centered-machine-learning/what-is-human-centred-machine-learning-a2f8f8170f73) (*Marco Gillies*)
* [Mental Models, Chapter 1, Some Observations On Mental Models](https://ar264sweeney.files.wordpress.com/2015/11/norman_mentalmodels.pdf) (*Don Norman*)
* [A Few Useful Things To Know About Machine Learning](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) (*Pedro Domingos*)
* [Interactive Knowledge Discovery](https://link.springer.com/chapter/10.1007/978-3-319-69775-8_1)


### Week 2 : Interactive Machine Learning (IML)
#### Themes covered:
* Active Learning
* Machine Teaching
* Programming by Demonstration (PbD)
* Apprenticeship Learning
* Interactive Feature Selection / Model Selection

#### Discussion Prompt :
* What are some of the trade-offs that are made to make an ML model suitable for interactivity?
* Describe the user experience for data labeling.
* What are some kinds of model feedback and how do they affect user interaction? Why does feedback affect user interaction?
* What are some ways in which current machine learning algorithms and methods have been modified for suitability in IML?
#### Readings : 
* [Interactive Machine Learning](http://edithlaw.ca/cs889/2014/reading/InteractiveMachineLearning.pdf) (*Jerry Alan Fails*, *Dan R. Olsen Jr.*)
* [Power to the People: The Role of Humans in Interactive ML](https://www.aaai.org/ojs/index.php/aimagazine/article/view/2513/2456) (*Saleema Amershi, Maya Cakmak, Bradley Knox, Todd Kulesza*)
* [Effective End-User Interaction with Machine Learning](https://homes.cs.washington.edu/~jfogarty/publications/aaai2011.pdf)
* [Machine Teaching: An Inverse Problem to Machine Learning and an Approach Toward Optimal Education](http://pages.cs.wisc.edu/~jerryzhu/machineteaching/pub/MachineTeachingAAAI15.pdf) (*Xiaojin Zhu*)
* [Analysis of a Design Pattern for Teaching with Features and Labels](https://arxiv.org/pdf/1611.05950.pdf) (*Christopher Meek, Patrice Simard, Xiaojin Zhu*)
* [Apprenticeship Learning via Inverse Reinforcement Learning](http://ai.stanford.edu/~ang/papers/icml04-apprentice.pdf) (*Pieter Abeel*, *Andrew Ng*)
* [Programming By Demonstration](https://www.researchgate.net/profile/Craig_Nevill-Manning/publication/2701892_Programming_By_Demonstration/links/0912f507c157b05869000000.pdf) (*Craig Nevill-Manning*)

### Week 3 : Model Personalization
#### Themes covered:
* Semi-supervised learning
* Community Similarity
* reinforcement learning
* incremental and online learning

#### Readings:
* [Towards Health Recommendation Systems: An Approach for Providing Automated Personalized Health Feedback from Mobile Data](https://link.springer.com/chapter/10.1007/978-3-319-51394-2_26/fulltext.html) (*Mashfiqui Rabbi*, *Min Hane Aung*, *Tanzeem Choudhury*)
* [Personalized Spam Filtering with Semi-supervised Classifier Ensemble](https://dl.acm.org/citation.cfm?id=1249088)
* [Improving activity classification for health applications on mobile devices using active and semi-supervised learning](http://ieeexplore.ieee.org/abstract/document/5482296/) (*Brent Longstaff*, *Sasank Reddy*, *Deborah Estrin*)
* [Enabling large-scale human activity inference on smartphones using community similarity networks](http://www.cs.odu.edu/~cs441/Papers/sense-003.pdf) (*Nicholas Lane*, *Ye Xu*, *Hong Lu*, *Shaohan Hu*, *Tanzeem Choudhury*, *Andrew Campbell*, *Feng Zhao*)
* [Building Personalized Activity Recognition Models with Scarce Labeled Data Based on Class Similarities](https://link.springer.com/chapter/10.1007/978-3-319-26401-1_25)
* [Potential for Personalization](http://doi.acm.org/10.1145/2528394.2528395) (*Jaime Teevan*, *Susan T. Dumais*, *Eric Horvitz*)


### Week 4 : Model Transparency
#### Themes covered:
* Model / Data Visualization
* Model Interpretabiity
* Designing for uncertainty
* Explainable AI

#### Readings:
* [Interpretation and trust: designing model-driven visualizations for text analysis](https://dl.acm.org/citation.cfm?id=2207738) (*Jason Chuang*, *Daniel Ramage*, *Christopher Manning*, *Jeffrey Heer*)
* []

* Model Visualization (Jason Chuang)
* Model Interpretability (Amershi, Himabindu)
* Designing for Uncertainty (http://visualization.ischool.uw.edu/hci_uncertainty/)
	* http://social.cs.uiuc.edu/papers/Motahhare-CHIWorkshop17-CameraReady.pdf
* Data Visualization (Jessica Hullman http://ieeexplore.ieee.org/abstract/document/6064986/?part=1)
* Explainable AI (https://www.cc.gatech.edu/~alanwags/DLAI2016/(Gunning)%20IJCAI-16%20DLAI%20WS.pdf)
* [It's not a bug its a feature](https://www.researchgate.net/profile/Dennis_Eilers/publication/320508355_It%27s_not_a_Bug_it%27s_a_Feature_How_Visual_Model_Evaluation_can_help_to_incorporate_Human_Domain_Knowledge_in_Data_Science/links/59e9083ea6fdccfe7faffa8b/Its-not-a-Bug-its-a-Feature-How-Visual-Model-Evaluation-can-help-to-incorporate-Human-Domain-Knowledge-in-Data-Science.pdf)

### Week 5 : Crowd ML
* Democratizing ML Models
	* [Community-Guided Learning: Exploiting Mobile Sensor Users to Model Human Behavior](http://www.aaai.org/ocs/index.php/AAAI/AAAI10/paper/download/1933/2263)
* Collaborative Filtering
* Socially Guided ML (https://www.cc.gatech.edu/~athomaz/papers/ThomazBreazeal-ICDL06.pdf)
* Something from Crowd Flower?
* Mixed Iniative Systems
* adversarial participation
	* MS Tay
	* Resnick's cheap pseudonym's work
	* Hartline's work
	* Easley's online auction stuff? (not sure)
* Why does a user give up their data?
	* citizen science
		* eBird
	* captive audience
		* recaptcha
	* mutual benefit
		* duo lingo, new amershi mixed initiative stuff
	* bribery
		* amazon mTurk (Tufecki paper?)

### Week 6 : User-Centered Data Science & Quantitative UX Research
* [Human-Computer Interaction and Knowldedge Discovery (HCI-KDD): What Is the Benefit of Bringing Those Two
Fields to Work Together](https://link.springer.com/chapter/10.1007%2F978-3-642-40511-2_22) (*Andreas Holzinger*)

### Week 7 : Algorithmic Bias, Accountability, and Auditing
* [Auditing Algorithms: Research Methods for Detecting Discrimination on Internet Platforms](https://pdfs.semanticscholar.org/b722/7cbd34766655dea10d0437ab10df3a127396.pdf)
* [Algorithmic Accountability](http://www.tandfonline.com/doi/full/10.1080/21670811.2014.976411)

### Week 8 : Concept Evolution (Mismatch) (http://ieeexplore.ieee.org/abstract/document/5694063/)

### Week 9 : Design Principles for Intelligent User Interfaces

### Week 10 : Implenting User-Centered Design Principles
* Descriptive Keyphrases for Text Visualization http://idl.cs.washington.edu/papers/keyphrases


### Extra Themes : 
* Aligning Human understanding with model representation (Democratic ML)
	* http://idl.cs.washington.edu/papers/topic-model-diagnostics
	* Socially Guided ML
	* Domain Drive Data Mining (D3M) http://ieeexplore.ieee.org/abstract/document/4733924/
		* importance of domain expertise/knowledge in analytic task
		* Perceptual (Re)learning http://ieeexplore.ieee.org/abstract/document/4216985/
* Algorithmic Bias
	* http://web.engr.illinois.edu/~eslamim2/
* Algorithmic Authority (Catie Lustig)