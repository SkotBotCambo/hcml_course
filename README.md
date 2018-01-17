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
machine learning through a series of readings, discussions, and a final project.

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

## Assignments and Grading
Below are the requirements and expectations of the class with the respective grade proportions.
* Final Project (40%)
* Class Presentation and Leading Discussion (20%)
* Reading Response (20%)
* Attendance and Class Participation (20%)

### HCML Project
Students will complete a final research paper
that explores HCML in one of the following ways:
* researching a system of the students' creation which integrates user-centered design principles into
  the design of the machine learning components of the system to address a user experience challenge or a novel user task
* researching the design and implementation of an interactive machine learning system which might address
  some of the issues with automated learning systems discussed in class including (but not limited to) algorithmic bias, algorithmic accountability, and model transparency.
* makes explicit through proof or demonstration an assumption used in the design of a learning algorithms which can result in one of the issues with AI and ML algorithms discussed in class (e.g.: algorithmic bias, concept evolution)

Students may also propose an alternative to one of these research paper formats.

The schedule and ruberic for the HCML project is as follows:
* **5th week of class**: Students submit an introduction and literature review and/or methods section by the 
	* This will be reviewed by the instructor as well as two other students in the class as part of a paper feedback exchange
	* 5/5 points of the final grade for submitting a draft of reasonable enough quality to get helpful feedback
	* 2/5 points for submitting a draft which is not of reasonable enough quality to get helpful feedback
	* 0/5 points for not submitting
* **7th week of class**: Students submit a methods section along with working code
	* for an analytic project this generally means the jupyter notebooks or R Studio code describing the analytic process and working data pipeline. 
	* For a systems project this will mean a prototype that is working well enough that the idea can be demonstrated even if further iterations are needed to effectively study that which will be the contribution of the final paper.
	* 5/5 points for a methods section which communicates the process well enough for the feedback to focus on the process and not the writing. For 5 points, the students will also have a data pipeline or system that is working well enough to begin providing good analytic or design feedback.
	* 4/5 points for a methods section which still requires feedback on how the method is communicated. For 4 points, the data pipeline or system should be demonstrable.
	* 3/5 points for submitting any methods section and code
	* Project
* **9th week of class**: Students submit a full draft of their project
	* 5/5 points for a draft which can yield good feedback
	* 3/5 points for including all complete sections
	* 1/5 points for submissions which do not include all major sections (introduction, methods, results, discussion, conclusion)
* **Final week**: Complete submission

The HCML project will need to have a rough draft and a poster and/or demo completed by the 10th week
of class for a poster/demo session that will be open to the public. The final draft will need to be 
completed at the beginning of finals week so that students can exchange and review each others' work.

### Class Presentation and Leading Discussion
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

### Reading Response
In order to better digest the readings, students will write a response to each weekly discussion
prompt (provided in the reading schedule) by making appropriate citations and connections to the current
week's readings and those of previous weeks. Students should feel free to cite other sources, but these
should not be a replacement for the required readings of the week. This response will need to be uploaded 
by the Monday (subject to change) before class so that students will have a chance to read each others' responses
and the presenter can integrate them into the weekly presentation. This exercise will provide
students with the opportunity to get more comfortable with the writing and reflecting component of the class.

### Class Attendance and Participation
In order to fully make the connections between the human-focused research and
technology focused research in each week's readings it is important to participate in
class discussion. Class discussion also helps students to practice communicating
their understanding of the material to members of the class whose research focus
and educational background skews toward human subjects and factors and those 
who skew toward computational research. Students will be required to 
attend each class and participate in discussion
by asking thoughtful questions and communicating their opinions, ideas, and understanding on a topic
clearly to everyone in the class.

## Schedule
### Week 1 : Introduction
#### Themes covered:
* Mental Models, Conceptual Models, System Image,
* Human-Centered Machine Learning as a broad topic of research
* Common mistakes in machine learning

#### Discussion Prompt : 
* What are the different ways that people envision using AI and how does machine learning fit into
these ideas?
* How do you see users and their mental models relate to machine learning and AI?
* What are the common pitfalls of machine learning that Domingos' presents and how
might a "user" address or remedy these challenges?

#### Readings :
* [Human-Centered Machine Learning (The Google Approach)](https://medium.com/google-design/human-centered-machine-learning-a770d10562cd) (*Josh Lovejoy*, *Jess Holbrook*)
* [Human-Cent*r*ed Machine Learning (The Academic Approach)](https://medium.com/human-centered-machine-learning/what-is-human-centred-machine-learning-a2f8f8170f73) (*Marco Gillies*)
* [Mental Models, Chapter 1, Some Observations On Mental Models](https://ar264sweeney.files.wordpress.com/2015/11/norman_mentalmodels.pdf) (*Don Norman*)
* [A Few Useful Things To Know About Machine Learning](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) (*Pedro Domingos*)
* [When Fitness Trackers Don'T 'Fit': End-user Difficulties in the Assessment of Personal Tracking Device Accuracy](https://dl.acm.org/citation.cfm?id=2804269) (*Rayoung Yang*, *Eunice Shin*, *Mark Newman*, *Mark Ackerman*)
* [Human Computer Integration *versus* Powerful Tools](https://dl.acm.org/citation.cfm?id=3051137) (*Umer Farooq*, *Jonathan Grudin*, *Ben Shneiderman*, *Patti Maes*, *Xiangshi Ren*)
* (optional) [Machine Bias: *There’s software used across the country to predict future criminals. And it’s biased against blacks.*](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) (*Julia Angwin*, *Jeff Larson*, *Surya*, *MattuLauren Kirchner*)

### Week 2 : Interactive Machine Learning 1 : Introduction
#### Themes Covered:
* Interactive ML
* Machine Teaching

#### Discussion Prompt:
* What are some of the trade-offs that are made to make an ML model suitable for interactivity?
* Describe some of the user experiences for data labeling.


#### Readings:
* [Power to the People: The Role of Humans in Interactive ML](https://www.aaai.org/ojs/index.php/aimagazine/article/view/2513/2456) (*Saleema Amershi, Maya Cakmak, Bradley Knox, Todd Kulesza*)
* [Effective End-User Interaction with Machine Learning](https://homes.cs.washington.edu/~jfogarty/publications/aaai2011.pdf)
* [Designing Interactions for Robot Active Learners](http://edithlaw.ca/cs889/2015/reading/SL/cakmak10_tamd_active.pdf) (*Maya Cakmak*, *Crystal Chao*, *Andrea L. Thomaz*)
* [Machine Teaching: An Inverse Problem to Machine Learning and an Approach Toward Optimal Education](http://pages.cs.wisc.edu/~jerryzhu/machineteaching/pub/MachineTeachingAAAI15.pdf) (*Xiaojin Zhu*)
* [Machine Teaching: A New Paradigm for Building Machine Learning Systems](https://arxiv.org/abs/1707.06742) (*Patrice Y. Simard*, *Saleema Amershi*, *David M. Chickering*, *Alicia Edelman Pelton*, *Soroush Ghorashi*, *Christopher Meek*, *Gonzalo Ramos*, *Jina Suh*, *Johan Verwey*, *Mo Wang*, *John Wernsing*)
* [Structured Labeling for Facilitating Concept Evolution in Machine Learning](https://www.microsoft.com/en-us/research/publication/structured-labeling-for-facilitating-concept-evolution-in-machine-learning/) (*Todd Kulesza*, *Saleema Amershi*, *Rich Caruana*, *Danyel Fisher*,*Denis Charles*)
* [Interactive Machine Learning](http://edithlaw.ca/cs889/2014/reading/InteractiveMachineLearning.pdf) (*Jerry Alan Fails*, *Dan R. Olsen Jr.*)
* [Toward harnessing user feedback for machine learning](https://dl.acm.org/citation.cfm?id=1216316)

### Week 3 : Interactive Machine Learning 2 : Active Learning
#### Themes covered:
* Active Learning
* Machine Teaching
* Interactive Feature Selection / Model Selection

#### Discussion Prompt :
* What are some kinds of model feedback and how do they affect user interaction? Why does feedback affect user interaction?
* What are some ways in which current machine learning algorithms and methods have been modified for suitability in IML?
* What are some of the drawbacks to Active Learning and why might (or might not) they be addressed in the UI/UX design?

#### Readings : 
* [Analysis of a Design Pattern for Teaching with Features and Labels](https://arxiv.org/pdf/1611.05950.pdf) (*Christopher Meek, Patrice Simard, Xiaojin Zhu*)
* [What’s It Going to Cost You?: Predicting Effort vs. Informativeness for Multi-Label Image Annotations](http://edithlaw.ca/cs889/2015/reading/vijayanarasimhan_grauman_cvpr2009.pdf)
* [Designing Interactions for Robot Active Learners](http://edithlaw.ca/cs889/2015/reading/SL/cakmak10_tamd_active.pdf) (*Maya Cakmak*, *Crystal Chao*, *Andrea L. Thomaz*)
* [Interactive Optimization for Steering Machine Classification](http://edithlaw.ca/cs889/2015/reading/Steering_Classification_2010.pdf) (*Ashish Kapoor*, *Bongshin Lee*, *Desney Tan*, *Eric Horvitz*)
* [Active Learning with Real Annotation Costs](http://edithlaw.ca/cs889/2015/reading/settles.nips08.pdf) (*Burr Settles*, *Mark Craven*, *Lewis Friedland*)
* [CueFlik: interactive concept learning in image search](https://dl.acm.org/citation.cfm?id=1357061) (*James Fogarty*, *Desney Tan*, *Ashish Kapoor*, *Simon Winder*)


### Week 4 : Interactive Machine Learning 2: Reinforcement Learning
#### Themes covered:
* Programming by Demonstration / Learning By Example / Apprenticeship Learning
* reinforcement learning 
* inverse reinforcement learning

#### Discussion Prompts:
* From a user perspective, what makes apprenticeship learning so different from active learning?
* Describe the state and action space represent in each of these papers.

#### Readings:
* [A survey of robot learning from demonstration](http://edithlaw.ca/cs889/2015/reading/09ras-brenna.pdf)
* [Towards Health Recommendation Systems: An Approach for Providing Automated Personalized Health Feedback from Mobile Data](https://link.springer.com/chapter/10.1007/978-3-319-51394-2_26/fulltext.html) (*Mashfiqui Rabbi*, *Min Hane Aung*, *Tanzeem Choudhury*)
* [Apprenticeship Learning via Inverse Reinforcement Learning](http://ai.stanford.edu/~ang/papers/icml04-apprentice.pdf) (*Pieter Abeel*, *Andrew Ng*)
* [Programming By Demonstration](https://www.researchgate.net/profile/Craig_Nevill-Manning/publication/2701892_Programming_By_Demonstration/links/0912f507c157b05869000000.pdf) (*Craig Nevill-Manning*)

### Week 5 : Model Personalization
#### Themes:
* Semi-supervised learning
* Community Similarity
* incremental and online learning

#### Discussion Prompt:
* What is incremental learning and what is online learning? Why do these areas of ML research aid the model personalization process?
* How might we decide to use either active learning, semi-supervised learning, or community similarity approaches for the purpose
of model personalization? To help reason about this choose a specific application domain (many of these papers chose activity recognition) to reason about the decision.

#### Readings:
* [Personalized Spam Filtering with Semi-supervised Classifier Ensemble](https://dl.acm.org/citation.cfm?id=1249088)
* [Improving activity classification for health applications on mobile devices using active and semi-supervised learning](http://ieeexplore.ieee.org/abstract/document/5482296/) (*Brent Longstaff*, *Sasank Reddy*, *Deborah Estrin*)
* [Enabling large-scale human activity inference on smartphones using community similarity networks](http://www.cs.odu.edu/~cs441/Papers/sense-003.pdf) (*Nicholas Lane*, *Ye Xu*, *Hong Lu*, *Shaohan Hu*, *Tanzeem Choudhury*, *Andrew Campbell*, *Feng Zhao*)
* [Building Personalized Activity Recognition Models with Scarce Labeled Data Based on Class Similarities](https://link.springer.com/chapter/10.1007/978-3-319-26401-1_25)
* [Potential for Personalization](http://doi.acm.org/10.1145/2528394.2528395) (*Jaime Teevan*, *Susan T. Dumais*, *Eric Horvitz*)
* [Bootstrapping Personalised Human Activity Recognition Using Online Active Learning](http://homepages.cs.ncl.ac.uk/paolo.missier/doc/tudor-Liverpool.pdf) (*Tudor Miu*, *Paolo Missier*, *Thomas Plotz*)

### Week 6 : Model Transparency
#### Themes:
* Model / Data Visualization
* Model Interpretabiity
* [Designing for uncertainty](http://visualization.ischool.uw.edu/hci_uncertainty/)

#### Discussion Prompts:
* What roles do interpretability and visualization play in helping a model to be truly "transparent"?
* How do multiple "views" help users to better understand data and models based on it.

#### Readings:
* [Interpretation and trust: designing model-driven visualizations for text analysis](https://dl.acm.org/citation.cfm?id=2207738) (*Jason Chuang*, *Daniel Ramage*, *Christopher Manning*, *Jeffrey Heer*)
* [Statistical Modeling: The Two Cultures](https://projecteuclid.org/download/pdf_1/euclid.ss/1009213726%20) (*Leo Breiman*)
* [Interpretable Decision Sets: A Joint Framework for Description and Prediction](https://dl.acm.org/citation.cfm?id=2939874) (*Himabindu Lakkaraju*, *Stephen H. Bach*, *Jure Leskovec*)
* [Keeping Multiple Views Consistent: Constraints, Validations, and Exceptions in Visualization Authoring](http://faculty.washington.edu/jhullman/VIS17_Consistency_CR.pdf) (*Zening Qu*, *Jessica Hullman*)
* [It's not a bug its a feature](https://www.researchgate.net/profile/Dennis_Eilers/publication/320508355_It%27s_not_a_Bug_it%27s_a_Feature_How_Visual_Model_Evaluation_can_help_to_incorporate_Human_Domain_Knowledge_in_Data_Science/links/59e9083ea6fdccfe7faffa8b/Its-not-a-Bug-its-a-Feature-How-Visual-Model-Evaluation-can-help-to-incorporate-Human-Domain-Knowledge-in-Data-Science.pdf)
* [Transparency and Socially Guided Machine Learning](https://www.cc.gatech.edu/~athomaz/papers/ThomazBreazeal-ICDL06.pdf) (*Andrea L. Thomaz*, *Cynthia Breazal*)

### Week 7 : Algorithmic Bias, Accountability, and Auditing
#### Themes:
* Algorithmic Bias,
* Algorithmic Accountability
* Algorithmic Auditing

#### Discussion Prompts:
* What is the difference between "user-centered" and "human-centered" and which best describes
	each of the papers for this week?
* What can we "audit" an algorithm for?
* What is a good description of how biases can manifest themselves in the implementation or design of an automated or 
algorithm driven system.

#### Readings:
* [Auditing Algorithms: Research Methods for Detecting Discrimination on Internet Platforms](https://pdfs.semanticscholar.org/b722/7cbd34766655dea10d0437ab10df3a127396.pdf)
* [Algorithmic Accountability](http://www.tandfonline.com/doi/full/10.1080/21670811.2014.976411)
* [“Be careful; things can be worse than they appear”: Understanding Biased Algorithms and Users’ Behavior around Them in Rating Platforms](http://social.cs.uiuc.edu/papers/eslami-ICWSM17-CameraReady.pdf) (*Motahhare Eslami*, * Kristen Vaccaro*, *Karrie Karahalios*, *Kevin Hamilton*)
* [It's not a bug, it's a feature: how misclassification impacts bug prediction](https://dl.acm.org/citation.cfm?id=2486840) (*Kim Herzig*, *Sascha Just*, *Andreas Zeller*)

### Week 8 : Crowd ML 1
#### Themes:
* Community-guided Learning
* Citizen Science

#### Discussion Prompts:
* What are benefits to the user or the model that we derive from combining information from more than one user?
	* What are the challenges?
* What (if anything) do the users get in exchange for their effort or privacy violation when giving up information?
* If some subset of the users in a crowd are providing incorrect or inadequate information (either because of malicious intent or misinformation), what kind of effect will this have on the system's ability to achieve it's purpose? First,
think through the purpose of the system, then think through likely ways information could be incorrect or inadequate considering user intent, then think through the effect this will have on the model, finally how will the ultimate model effect the initial purpose.

#### Readings:
* [Local algorithms for interactive clustering](http://www.jmlr.org/papers/volume18/15-085/15-085.pdf) (*Pranjal Awasthi*, *Maria Florina Balcan*, *Konstantin Voevodski*)
* [Crowd Synthesis: Extracting Categories and Clusters from Complex Data](http://www.cs.cmu.edu/afs/cs/Web/People/spdow/files/crowdsynthesis-cscw2014.pdf) (*Paul Andre*, *Aniket Kittur*, *Steven P. Dow*)
* [Adaptively Learning the Crowd Kernel](http://edithlaw.ca/cs889/2015/reading/2011_ICML_TamLiuBelShamKal.pdf) (*Omer Tamuz*, *Ce Liu*, *Serge Belongie*, *Ohad Shamir*, *Adam Tauman Kalai*)
* [Community-Guided Learning: Exploiting Mobile Sensor Users to Model Human Behavior](http://www.aaai.org/ocs/index.php/AAAI/AAAI10/paper/download/1933/2263)
* [eBird: A Human/Computer Learning Network for Biodiversity Conservation and Research](https://www.aaai.org/ocs/index.php/IAAI/IAAI-12/paper/viewFile/4880/5433) (*Steve Kelling*, *Jeff Gerbracht*, *Daniel Fink*, *Carl Lagoze*, *Weng-Keen Wong*, *Jun Yu*, *Theodoros Damoulas*, *Carla Gomes*)

### Week 9 : Crowd ML 2
#### Themes:
* Crowd Work
* Grounded Theory
* Model Diagnostics

#### Discussion Prompts:
* Why is it important to make turk work salient in the automated systems that depend on crowd workers?
* How can human knowledge compliment automated knowledge discovery and vice versa.
* What are important design decisions that should be made when eliciting high quality information from the crowd for the 
purpose of training a model.

#### Readings:
* [Human Intelligence *Needs* Artificial Intelligence](http://edithlaw.ca/cs889/2015/reading/weld-hcomp11.pdf)
* [Turkopticon: Interrupting Worker Invisibility in Amazon Mechanical Turk](http://edithlaw.ca/cs889/2015/reading/turkopticon.pdf) (*Lilly Irani*, *M. Six Silberman*)
* [Human-Computer Interaction and Knowledge Discovery (HCI-KDD): What Is the Benefit of Bringing Those Two
Fields to Work Together](https://link.springer.com/chapter/10.1007%2F978-3-642-40511-2_22) (*Andreas Holzinger*)
* [CrowdFlower: What I learned from labeling 1 million images](https://s3.amazonaws.com/cambo-general/crowdflower_image_annotation_guide.pdf)
* [Machine Learning and Grounded Theory Method: Convergence, Divergence, and Combination](https://dl.acm.org/citation.cfm?id=2957280)
* [Topic Model Diagnostics: Assessing Domain Relevance via Topical Alignment](http://idl.cs.washington.edu/papers/topic-model-diagnostics/)

### Week 10 : Design Principles for Intelligent User Interfaces
#### Themes:
* Keyphrases
* User Feedback
* Explanatory Debugging

#### Discussion Prompts:
* What is an intelligent user interface and what effect does user feedback have on the system behavior?
* How could keyphrases be made practical in applications of text mining? Be explicit about what this work process might look like.
* How can the research process used to create design principles for explanatory debugging be applied to other 
	domains we have discussed throughout this course?

#### Readings:
* [Integrating Rich User Feedback into Intelligent User Interfaces](http://openaccess.city.ac.uk/14847/8/stumpfIUI08_camera_amended.pdf)
* [Descriptive Keyphrases for Text Visualization](http://idl.cs.washington.edu/papers/keyphrases
)
* [Principles of Explanatory Debugging to Personalize Interactive Machine Learning](Principles of Explanatory Debugging to Personalize Interactive Machine Learning)

### Additional Resources:
* [*Fairness In Machine Learning*](https://fairmlclass.github.io/) class taught by Moritz Hardt at UC Berkeley
* [*A Course on Fairness, Accountability and Transparency in Machine Learning*](https://geomblog.github.io/fairness/) curriculumn by the GIAN program of the Government of India
* [*Human-in-the-loop Systems*](http://edithlaw.ca/cs889/2014/index.html) class taught by Edith Law at University of Toronto
* [*Interactive Machine Learning*](http://iml.media.mit.edu/) class taught at MIT
* [*How Quantitative UX Research Differs from Data Analytics*](https://medium.com/facebook-research/how-quantitative-ux-research-differs-from-data-analytics-1bbf0903768b) a blog post by Facebook employees.
* [AlgorithmTips.org](http://algorithmtips.org/) a website that Professor Nick Diakopolous started to keep tracking of where algorithms are used in government.

### Additional Themes : 
* [Look here for inspiration on experiments to run](https://experiments.withgoogle.com/ai)
* Aligning Human understanding with model representation (Democratic ML)
	* http://idl.cs.washington.edu/papers/topic-model-diagnostics
	* Domain Drive Data Mining (D3M) http://ieeexplore.ieee.org/abstract/document/4733924/
		* importance of domain expertise/knowledge in analytic task
		* Perceptual (Re)learning http://ieeexplore.ieee.org/abstract/document/4216985/
* Algorithmic Bias
	* http://web.engr.illinois.edu/~eslamim2/
* Algorithmic Authority (Catie Lustig)
* User-Centered Data Science & Quantitative UX Research
* Concept Evolution, Drift, and Mismatch (http://ieeexplore.ieee.org/abstract/document/5694063/)
* [Comparing Grounded Theory and Topic Modeling: Extreme Divergence or Unlikely Convergence?](https://www.shionguha.net/wp-content/uploads/2016/04/asi23786.pdf) (*Eric P.S. Baumer*, *David Mimno*, *Shion Guha*, *Emily Quan*, *Geri K. Gay*)
* [Curriculum Learning](https://ronan.collobert.com/pub/matos/2009_curriculum_icml.pdf) (*Yoshua Bengio*)
* [FlowingData.com blog on Visualizing Uncertainty](https://flowingdata.com/2018/01/08/visualizing-the-uncertainty-in-data/?imm_mid=0fa832&cmp=em-data-na-na-newsltr_20180117)
* Ethics
	* [*what if we asked a super-intelligent AI to make paperclips?*](https://www.theverge.com/tldr/2017/10/11/16457742/ai-paperclips-thought-experiment-game-frank-lantz)
	* [Paperclips Game](http://www.decisionproblem.com/paperclips/index2.html)