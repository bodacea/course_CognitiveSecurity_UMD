# course_CognitiveSecurity_UMD
materials for cognitive security course.  Already need updating. 

# Course Description   

Cognitive security is the application of information security principles, practices, and tools to misinformation, disinformation, and influence operations.  It takes a socio-technical lens to high-volume, high-velocity, and high-variety forms of “something is wrong on the internet”. 

This course starts with the ways that users and groups are influenced online, from user experience, marketing, adtech and online political campaigns through to astroturfing, online psyops, disinformation campaigns.  We’ll look at the techniques and tactics used to create influence, the tools, methods and design patterns being created to detect, counter and mitigate against it, the emerging discipline of cognitive security and how it meshes with other work including information security, machine learning and geopolitics. 

The course is practical, arranged around a set of python notebooks and open-source tools, but also rooted in deep theories of why and how disinformation campaigns happen. 

## Learning Outcomes

After successfully completing the course, students will be able to

* Elaborate how information security and cognitive security interact
* Evaluate persuasive technology at different scales
* Evaluate influence operation mechanisms and tracking techniques
* Use tools to investigate account and network-level coordinated inauthentic activities
* Understand ethical behaviour around misinformation and disinformation response and research

Composition of grades

* In class activities: 50%
* Case studies: 3 case studies, 10% per study
* Problem challenge (20%): In this project, you will identify a problem, use the lens of one of the frameworks we studied in class to address it, and explore/analyze *theoretically* how to successfully measure and counter it. 
 
# Course Schedule

## week 1 class 1 course overview, introduction

 Outline:
* Introduces students to the contents of the course, and supporting materials needed to work on disinformation data. 
* History of cognitive security
* Working definitions of information operations, disinformation, and cognitive security
* Disinformation examples and common  myths
* Where to find more information		
* in-class exercise: definitions and examples of mis/disinformation, rumours, conspiracies, information operations

## week 1 class 2 disinformation reports, ethics

* Example disinformation analyses. 
* Students will comment on existing disinformation analyses, and start their own research outlines.
* How to investigate safely
* Ethics of handling data from and about people, and groups already working on disinformation. 
* Outcome: students will be able to articulate needs and pitfalls of disinformation research, and will have started their own research outlines. 

Lecture: researcher risks
* Potential risks to influence operations investigators, and mitigations for them. 
* Operational security
* Mental health
* Ethics and the golden rule (“first, do no harm”)
* Outcome:  mitigation strategies for personal risks inherent in investigating them. 	Read: 	Exercise: List and examine the risks in an existing influence operation. 

in-class exercise: comment on existing disinformation analyses

## Week 2

	NO CLASS
	
## Week 3 class 1 cognitive security fundamentals

Outline: 
* Assessing social media misuse - channels, influencers, groups and messaging 
* An introduction to actors, behaviours, techniques, tools
* The disinformation pyramid.  Example incidents, example narratives.
* Information operations as an information system
* 
Details:
* Introduces students to disinformation, misinformation, propaganda, information operations; their creators, outputs, mechanics and effects.  Also introduces students to live feeds of disinformation-containing data. 
* Outcome: students will be able to articulate disinformation campaign mechanics and motivations. 		In-class exercise: use Hypothes.is to track misinformation materials

Assignment:  Track a misinformation or disinformation narrative across the internet and/ or traditional media.

## Week 3 class 2 Cognitive security risks

* Risks created by misinformation and influence operations
* Frameworks for assessing cognitive security risks 
* Outcome: a framework for assessing influence operation risks		

## week 4 class 1 Human system vulnerabilities and patches

Outline: 
* From clicks to disinformation
* cognitive biases and their abuses
* the range of ways users and groups are influenced online (and offline via online means) - user experience, marketing and adtech, online political campaigns, astroturfing, online psyops, disinformation campaigns. 		

## Week 4 class 2 Psychology of influence

* Outcome: articulate common influence techniques. 
* Applying marketing models
* The medium is the message: Content vs Context		
* Exercise: List and categorise online and offline advertising seen in an hour

## Week 5 class 1 Frameworks for understanding cognitive security

Outline:
* Layer-based models
* Object-based models
* Behaviour-based models
* Introduces students to infosec-related models of information operations and disinformation, with examples of their use and connection to other information security practices. 
* Outcome: students will be able to evaluate disinformation incidents and their components		

## Week 5 class 2 Relational frameworks

* Group-based models
* (Network-flow models)		Exercise: apply frameworks to existing disinformation analyses. 

## Week 6 class 1 Building Landscapes

Outline:
* Building an information landscape
* Building a risk landscape
* Building a response landscape
* Landscape interactions
* Landscape patches

Details: 
* Introduces landscapes: assessments of the cognitive security situation in a region, country, vertical, or business. Gives examples of desk surveys, country-level investigations, and information interviews to improve models and knowledge of an area. Introduces cognitive security gap analysis. 
* Outcome: students will be able to assess disinformation risk in a country, business, or vertical
Case study assignment: 
* build a disinformation landscape assessment for a country, business, or vertical		

## Week 6 class 2 Exercise

Exercise: build landscapes from existing disinformation assessments (e.g. the Oxford Internet Institute’s annual country summaries)

## Week 7 class 1 Setting up an investigation

Outline:
* Setting up a process
* Choosing tools
* Collecting data (social, text, image)
* Building investigation communities
* Overlapping communities: cognitive security, OSINT, information security. 
* How to send data to responders

Practical:
* Introduces students to streaming data APIs, large datasets, and cleaning, exploration and storage methods for large data, including simpler automations
* Outcome: students will be able to access and store larger datasets, and have basic analysis tools for them		
* Read https://si.ma/fb-cib/

## Week 8 class 1 Misinformation data analysis

Outline:
* Setting up your notebooks
* Keeping track of what you’ve found
Details:
* Introduces techniques and tools for assessing misinformation artifacts: images, text, accounts, groups, domains etc. 
* Exercise: analyse a dataset containing misinformation artifacts
* Outcome: students will be able to track and assess misinformation artifacts		

## Week 8 class 2

* Artifact analysis
* Text analysis		

## Week 9 class 1 Disinformation data analysis

Outline:
* Social network analysis: Mapping and measuring relationships and information flows between people, groups, URLs, and other information entities.
Details:
* Introduces techniques and tools for assessing the relationships between disinformation artifacts, narratives, and other incident objects. 
* Outcome: students can apply network tools to find and assess anomalies in social media artifact relationships.		

## Week 9 class 2

Exercise: apply network analysis tools to a dataset containing potential disinformation

## Week 10 class 1 Disinformation responses

Outline:
* Responder types
* Building response communities
* Message-based responses: countermessaging, prebunking, debunking
* Action-based responses
* First, do no harm
Details:
* Describes the types of misinformation and disinformation response groups that exist, and the types of responses that they can and do implement.  Shows how to share information between responding groups. 
* Exercise: assess the capabilities of existing response groups
* Outcome: students can articulate response types available to different response groups, and potential effects from them. 
Case study assignment: gather datasets related to an existing disinformation narrative, and package them as an alert or report to be sent to a disinformation response group.		

## Week 10 class 2

Coursework

## Week 11 class 1 Monitoring and Evaluation

Outline:
* Measuring cognitive security effects and responses
* Applied cynicism: statistics and models

Details:
* Covers the measurement of disinformation risk, disinformation actions, and response actions, at tactical and organisational levels. 
* Exercise: M&E assessment of an existing misinformation response (e.g. WHO response to Covid19 infodemic)
* Outcome: students will have tools to assess how effective disinformation events and their responses are. 		

## Week 11 class 2

## Week 12 class 1 Games, red teaming and simulations

Outline:
* Games
* Disinformation red teams
* Simulations

Details:
* Introduces the use of games and other simulations to help understand disinformation tactics and potential responses to them.  
* Exercise: Test out a game, then red-team an existing disinformation incident. 
* Outcome: students can use tools and simulations to assess, plan, and change disinformation responses		Exercise: design a disinformation-based game

## Week 12 class 2 Cognitive Security red teaming

* Exercise: red-team a disinformation as a service business and potential counters to it		

## Week 13 class 1 Project work		
Proposal for end of term project.

## Week 13 class 2 NO CLASS: Thanksgiving
		
## week 14 class 1 Project work session	

## Week 14 class 2 Cognitive Security as a Business

Outline:
* Disinformation as a service models
* Financial motivations and estimates
* Business effects of disinformation
Details:
* Introduces business models behind disinformation and cognitive security. Goes into detail on the potential business attack vectors and effects from disinformation and hybrid campaigns that include disinformation (e.g. hacking, malware etc).
* Outcome: students can articulate disinformation business models 		

## Week 15 class 1 Future Possibilities

Outline: 
* Cognitive security and business - potential directions
* Health sector: medical misinformation trends in Covid19 and Vaccine hesitancy
* Elections: trends around the world
* Responses: trends around the world
Details
* Looks at potential future arcs for disinformation incidents and response.  
* Outcome: students can articulate potential futures in misinformation, disinformation, and responses to them.		Project presentations

## Week 15 class 2 Project Presentations

Outline:
* Students present their group projects
Details: 
* Students give 10-minute presentations on their group projects. 
* Outcome: students have performed an end-to-end misinformation or disinformation incident analysis. 		

## Week 16 class 1 Summary and connections		

final	TBD			
