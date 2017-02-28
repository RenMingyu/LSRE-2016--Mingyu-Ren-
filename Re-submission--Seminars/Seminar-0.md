##Question:

####• What is large scale requirements engineering?

The complexity of software-intensive system is increasing nowadays [1]. The key features of large scale requirements engineering are large scale and high complexity. In large scale requirement engineering, the size of the requirements databases is less than ten thousand. The requirements databases which exceed ten thousand are called very large-scale requirements engineering (VLSRE) [2].

####• What are the challenges in large scale requirements engineering?

1.	The number of customer requirements is large, so that the challenges of requirements analyzing, specifying, managing are large [3].
2.	Since the number of requirements is large, the number of customer is large. So the communication with customers becomes more difficult. 
3.	It is difficult to manage such the large size and complex system for the customers’ expectation.
4.	During the process of requirements engineering, the involved technologies could change. Managing the changing technologies could be a challenge.
5.	The larger scale, the more the distributed teams. Many studies showed that the distribution could lead to many problems like coordination or communication challenges [3].
6.	The techniques or the team resources could not satisfy the requirements, large scale could meet high risk.
7.	The changing scope could influence the requirements engineering process. If the scope changed in large scale project, many things should be changes, it is a challenge.

####• What is the order of magnitude of the number of requirements we are discussing?

	The order of magnitude of large-scale requirements engineering (LSRE) is ~1000 requirements.
	
Small-scale requirements engineering (SSRE) is ~10 requirements. Medium-scale requirements engineering (MSRE) is ~100 requirements. Very large-scale requirements engineering (VLSRE) is ~10000 requirements.

####• Read up on and summarise [Strategic] Release Planning

	Release planning is the plan for next release: the things that need to complete and the estimated time for completing the things. 
	
In agile development project, release planning is an important part. Firstly, it can be able to evaluate the total time allocation, so that the manager could know about the deliverable time, as well as the milestones for risk evaluation and management. Secondly, the release planning usually indicates which features for each iteration and how many iterations we need to have. So the managers can allocate the developers for different iterations. Thirdly, good release planning could improve the efficiency of the project development. If team member knows what to do next, they would finish their current soon. At last, release planning can be able to show how many features should be finished in a iteration. The developers can know the priority of these features based on release planning.

##Article summary:

####– Ruhe “The art and science of release planning”, plus some more recent works on the EVOLVE methods.

	This paper introduced the release planning and what a good release planning is. Also, it described two approaches for release planning: the art of release planning and the science of release planning.

The art of release planning related to human intuition, communication, capabilities. It aims to negotiate conflicting objectives and constraints. This method for release planning is because the organization lack of emphasis on processes, and the process of release planning is immaturity. The science of release planning solves the problem by formalizing them. The specialized optimization problems could help developers to know about the specific problem, so that they can solve the problems flexibility and efficiency.

This paper also proposed some difficulties of creating a release planning. To create a release planning, we should totally understand the planning objectives and constraints. It is difficult to satisfy the feature preferences of important stakeholders. In addition, selecting the best features is complex [5].

The author created a synergy between the art and science of release planning. This approach performs some different tasks in three phases – modeling, exploration and consolidation of planning process. 

For the paper: Before the authors propose the approach, they considered the difficulties of creating release planning. If the developers know about the difficulties clearly, they can solve and try to avoid the possible difficulties. It is important to create a good release planning. In this paper, based on the analyzed difficulties, the developers would pay more attention to understand the planning objectives and constraints.

Against the paper: The author introduced the art and science of software release planning, also the combination of the two approach. For the new approach the author proposed, it is not very exhaustive, because a new approach have pros and cons. The author should analyze some limitations of the approach, such as the risk, possible difficulties and so on.

####– R: Berntsson Svensson, B. Regnell (2015) “A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements”, 21st International Working Conference on Requirements Engineering: Foundation for Software Quality (REFSQ’15), Essen, Germany, pp. 230-246, 2015.

This paper is a case study evaluation used QUPER model for quality requirements. QUPER is a model for release planning, it aims to support high-level decision-making for the quality requirements. This empirical case study shows the importance of the concrete guidelines and instructive examples in real practice. To elicit the quality requirements (QR), the author point to seven step about the guideline-supported QUPER model. The steps as follow:
	
Step 1: identify candidate QR. The quality requirements in release planning are important for the quality of project development. The QR need to be considered after the features have been identified.
	
Step 2: define scale and unit. The specific scale and unit are helpful to identify the QR. It could improve the accuracy of quality requirements.
	
Step 3: identify reference levels. According to actual products, the reference levels should be identified. For quality requirements, it can be able to calibrate the estimates and provide objective measures. 
	
Step 4: elicit quality breakpoints. Quality breakpoints defined for doing the market expectations.
	
Step 5: estimate cost barriers. From two aspects for the cost barriers, one aspect is about the software changes, the other one is about the new hardware components.
	
Steps 6: set candidate requirements. In order to know the requirements quality interval, defining Good target and Stretch target.
	
Step 7: identify cost dependencies. It is necessary to know the relationship of cost among QR, and some potential dependencies should be identified.

	In general, the paper shows the guidelines of QUPER model in detail. This paper mainly emphasizes the combination of the practical study and the guidelines for the QUPER model, as well as the importance of the combination.

For the paper: it is comprehensive and specific paper for introducing QUPER model. It is good to use a practical case study to practice the QUPER model. The method can be able to improve the accuracy of development, evolvement, and refinement process. According to this paper, it is important to combine the guidelines and practical condition; it is the improvement for future work.

Against the paper: maybe one case study has some limitations. This example and the data are not representative. We don’t know if QUPER model is suitable for other case. In addition, the empirical study could have incorrect data or deviation.

####– Berntsson Svensson & Olsson “Introducing support for release planning of quality requirements –an industrial evaluation of the QUPER model”

	This paper shows an industrial evaluation of the QUPER model. With the development of software industry, market-driven product development and release planning become more and more important. If the product development lack of a good release planning, it could lead to the customer dissatisfaction and market loss. So it is critical to use QUPER model for release planning. There are three steps to carry out QUPER model. Step 1 is problem definition, step 2 is model definition, step 3 is model validation. The author describes an industrial evaluation by introducing the QUPER model at Sony Ericsson. 

According to the evaluation, the author get conclusion that the QUPER model can be able to use in high-level decision making for quality requirements. Also, the industrial evaluation indicated it is easy to learn and use QUPER model. This model is feasible and suitable for most of domain, but we need to analyze the current market and practical condition. The challenge of the model is that the breakpoint value could not be identified accurately and specifically.

For the paper: based on the analysis of the practical industrial evaluation of QUPER model, the author shows that QUPER model can be use in different condition, and it would improve the product development. I think the research of Sony Ericsson is better than the case study of last paper. We can see the data and the steps, as well as the evaluation process in this research. The result is more accuracy and understandable.

Against the paper: the research is good in this paper, but the author still need to investigate more aspect of QUPER model, also more industrial evaluations in future work, and make the QUPER model suitable for more and more domain.

####– Regnell, Beremark, Eklundh, “A market-driven requirements engineering process: results from an industrial process improvement programme”

	This paper shows an industrial requirements engineering (RE) process: REPEAT (Requirements Engineering ProcEss At Telelogic). REPEAT is use to elicit, select, and manage the product requirements. The Telelogic for requirements engineering called Telelogic Tau. Telelogic Tau is an integration of COTS (Commercial off-the-shelf) components. It is an in-house development process. Based on different customers and market segment, it can tailor different specific requirements. REPEAT includes many requirements engineering activities, as well as the requirements selection and release planning. Some actors in REPEAT as follow: requirements management group (RQMG), issuer, customers and users, requirements team, construction team, test team, expert, and requirements database (RQDB). 
	
The milestones at pre-defined dates can separate the REPEAT into five phases:

1.	Elicitation Phase: collection and classification. It is made and gives a summary by the issuer.
2.	Selection Phase: this phase aims to select and specify the requirements, then to validate the requirements document.
3.	Change management phase: the RQMG could decide to change the RD.
4.	Construction and verification: the construction is separated from verification by Code Stop milestone.
5.	Conclusion phase: summary for REPEAT.

For the paper: as an old method for RE process, REPEAT is good for requirement engineering. And the specific activities could help the expert and developers to prioritize the requirements in each release. The method can be improved in future work.

Against the paper: as a baseline, the REPEAT-1 used in many requirements engineering. But it is an old method for RE process, it may not suitable for all projects nowadays. I think the author should list some risk or the limitation for REPEAT so that we can solve some possible problems and achieve the improvement.

##Reference

[1] Aaramaa, Sanja, et al. "Design for excellence in the context of very large-scale requirements engineering." Software Technologies (ICSOFT), 2015 10th International Joint Conference on. Vol. 1. IEEE, 2015.

[2] Wnuk, Krzysztof. "Visualizing, Analyzing and Managing the Scope of Software Releases in Large-Scale Requirements Engineering." Dissertation 39, 2012 (2012).

[3] Konrad, Sascha, and Michael Gall. "Requirements engineering in the development of large-scale systems." International Requirements Engineering, 2008. RE'08. 16th IEEE. IEEE, 2008.

[4] Regnell, Björn, Richard Berntsson Svensson, and Krzysztof Wnuk. "Can we beat the complexity of very large-scale requirements engineering?." International Working Conference on Requirements Engineering: Foundation for Software Quality. Springer Berlin Heidelberg, 2008.

[5] Regnell, Björn, Per Beremark, and Ola Eklundh. "A market-driven requirements engineering process: results from an industrial process improvement programme." Requirements engineering 3.2 (1998): 121-129.

