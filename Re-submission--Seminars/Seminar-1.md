##Question:

####• Read up on GAP / CVA / IVA Analysis!

Gap analysis: Gap analysis refers to in the implementation process, the comparative analysis between the actual performance of customers and expectations of the performance, then conduct strategic evaluation and revision. The gap analysis is mainly to analyze the reason of the gap and propose ways to reduce or eliminate the gap. This can be achieved by changing the goal or changing the business layer strategy. Before we do the gap analysis, we need to consider modifying the strategy of the company. Gap analysis is divided into four perspectives to be conducted: organization, business direction, business processes, and information technology.

CVA analysis: Customer value analysis. It is similar to gap analysis [1]. The Customer Value Added is a measurement of the customers’ satisfaction. When CVA<1, the company could lose market share, when CVA=1, the company neither gain nor lose market share. When CVA>1, the company could gain market share.

IVA analysis: internal value analysis. It aims to identify and evaluate the organization’s specific characteristics, such as, resource, capabilities, core competencies. Internal audit is an important approach of IVA analysis. The internal audit can be able to assess the organization’s resources and capabilities.

####• What tools are available for Continuous Integration? – Try one out (build something, have it run tests automatically, . . .), and write up your experiences.

	As an important part in agile software development, continuous integration (CI) can help the developers avoid some code errors and improve the quality of the code. There are some open source continuous integration tools, such as, Jenkins, Buildbot, Travis CI, Strider, Go, Integrity and so on. 

	According to my experience, Travis CI is one of the easiest continuous integration server used in our own server. It can be able to link the GitHub account to get the relevant permissions and update the travis. Buildbot is developed in Python, it can allow us to grow with our own requirements. The processes is simple and the unique needs can be satisfied.

####• What is technical product management?

	In Market-Driven Requirements Engineering (MDRE), the modern enterprises must produce products in line with social needs promptly, in order to obtain the corresponding economic benefits. So the enterprise must have large number of technical staff. 

	The technical product management must have technical product managers. They often have deep technical expertise. A good technical product manager could responsible for strategy, ideation, roadmapping, features, and go-to-market. The technical product management usually used to plan, develop and implement technical capabilities, in order to complete organizational strategy and operational objectives.

####• What is roadmapping? How can you do it large scale?

	Roadmapping is a technology of matching short-term and long-term goals in order to achieve the goals [2]. The plan applies to emerging technology [3]. The roadmapping can helps to reach a consensus of all the requirements. And the mechanism is helpful for forecast technology development. Also, the framework can coordinate the technology development [4]. The process of roadmapping has three phases: preliminary phase, development phase, and follow-up activity phase.

	To build the roadmapping, the participants should have professional knowledge and skills. For the large scale, the requirements engineering and roadmapping are complex. So the participants should analyze the needs, products, technology clearly to ensure the accuracy of roadmapping

##Article summary:

####– Gorschek & Wohlin “Requirements Abstraction Model”

	With the development of market-driven requirements engineering, the product managers have the challenge about how to make the different stream requirements ranging from abstract to technically detail. This paper introduces a model called Requirements Abstraction Model (RAM) to solve the challenge. There are some benefits of RAM as follow: 

1.	The product strategies could provide an assurance for all requirements, so that the requirements could not violate the overall goals of the management.
2.	All the requirements are in an abstraction for initiating a development project. This ensures the projects can be able to satisfy the requirements.
3.	The requirements are formulated on the same level. They have close relationship to compare and set together. The requirements should have release planning and prioritization before comparison.
4.	According to different levels of abstraction, the requirements can be given better understanding. So it is good for the developers to make decision.

The RAM of requirements engineering have three basic steps: specify, place, and abstraction. Specify step is an initial step. It aims to get an overview of the raw requirements so that the product manager could understand and carry out the continuous requirements engineering. There are four attributes in specify step: description, reason/benefit/rationale, restrictions/risks, and title. The place step has four abstraction levels for the requirements: product level (goal), feature level (features), function level (functions/actions), component level (details-consists of). The abstraction step is a work-up process. There are rules for the process, the requirements should have connection with product level and all requirements should break down to function level. In addition, the validation of RAM can be divided into static validation and dynamic validation.

For the paper: the comparison of all the requirements and their abstraction level could give the managers and developers a good understanding of the requirements, thus they can improve the quality of the product and satisfy the customers’ needs. The RAM is effective for managing quality requirements [5]. It is a good and necessary model.

Against the paper: the requirements abstract model is good for requirements engineering, but the process is too complicated for project. If the project is large-scale, the model may spend much time and have excessive cost. So I think this model should be simplified and optimized in future work.

####– Khurum & Gorschek “A method for early requirements triage and selection utilizing product strategies”

	This paper describes a method for selecting the requirements and utilizing strategies of early requirements triage. In market driven requirements engineering (MDRE), the method for early requirements triage and selection (MERTS) aims to create product strategies from both strategic and technical views. Also, the requirements could be triaged by MERTS method and the managers could select the suitable requirements for realization. 

	The paper points out three parts of MERTS:　

1.	Early requirements triage: this part use three steps to build the initial product strategy for the requirements triage. The three steps are: specify, assign weights, and compare requirements. 
2.	Requirements selection for release: in this part, there are two steps for requirements selection. First we need to specify product-technology roadmap, and then estimate resources.
3.	Strategy rationale: after answer the strategic questions, it is necessary to summary the strategy rationale and successful experience. That’s good for future improvement.

The author shows that the MERTS could work with organizational directions of strategies. It is still need to invest resources and time for the strategies.

For the paper: when creating MERTS, they didn’t use one-size-fit-all philosophy, so it can achieve the product specific goals and objectives. The MERTS is suitable for any organization, not matter small, medium, and large companies.

Against the paper: the validation of MERTS has limitations in scope. In future work, the author should involve static and dynamic validation for the improvement of MERTS.

####– Gorschek & Davis “Requirements Engineering. In search of dependent variables”

	The paper describes a framework of dependent variables for the requirements engineering quality assessment. The targets assessment in many companies based on the requirements process and the primary product. The requirements process change dependent variables have five levels: 

1.	Requirements phase: this phase includes the requirements cost and time, the requirements quality.
2.	Project: in this phase, the project level equated with project success. The dependent variables related to project cost and time, project estimates, and degree of requirements change.
3.	Product: the dependent variables related to the quality of product. We need to select the requirements know about the degree of impact.
4.	Company: to know if the adversely affected project would influence the company’s success, the measurement of the company level should have portfolio management, strategic alignment, and degree of impact.
5.	Society: because a company has the responsibility of society, and a project may influence the company’s bottom line, we need to consider the positive and negative externalities.

The projects are not the only impact of successful requirements engineering. The process changes succeed in the requirements phase and project levels. According to this paper, we know about the multidisciplinary and multi-perspective impacts in taxonomy. And the paper improved the strategies of company level and product level.

For the paper: I think the contributions the author proposed are useful for the future work of requirements engineering. Such as, the taxonomy of the five levels dependent variables. Based on the taxonomy, we can clearly understand the different dependent variables in different level.

Against the paper: the requirements engineering quality assessment is complex process. And the impacts are more than project level. Therefore, we still need to improve the capability of assessment and frameworks.

####– R. Berntsson Svensson, T. Gorschek, B. Regnell, R. Torkar, A. Shahrokni, R. Feldt (2012) “Quality Requirements in Industrial Practice – an extended interview study at eleven companies”, IEEE Transactions on Software Engineering, vol.38(4), pp. 923-935
	
	To ensure the quality of the product, it is important to balance the competing quality requirements (QR). The paper collected data from 11 software companies for the interview study. There are four contributions of this interview study:

1.	The comparison of how to handle QR in two cases and the impact in handling process.
2.	The comparison of the perceptions and priorities of the product and project management.
3.	The practitioners to exam the interdependencies among QR.
4.	The selection and management of QR.

In addition, the author analyzes four research questions in detail:

1.	RQ1: important quality aspects. B2B companies have well safety and accuracy and B2C companies have good portability. B2B and B2C have different prioritization with different customers.
2.	RQ2: interdependencies. The common interdependency of QR are REQUIRES, CVALUE, and ICOST. B2B viewed REQUIRES and B2C viewed CVALUE. 
3.	RQ3: cost estimations. The interview showed a problem that the estimating QR could impact larger parts of a system. We should analyze the complexity of QR continually and use some different resource and method to estimate it.
4.	RQ4: dismissal of quality requirements. Based on the interview, the author showed the consequence of that if QR is dismissed and if QR is measurable or not.

In conclusion, the result of the empirical study shows that the QR is different in different types of companies (B2B and B2C).

For the paper: the interview study of eleven software companies has got many practical data, it is easy to understand and summary the result of QR in industrial practice. The interview approach is good, the data result is simple and accuracy.

Against the paper: the 11 companies are very limited to get the accuracy result, and it cannot stand for all software companies, so the author should interview more types of companies to improve the result.

####– J. Karlsson, K. Ryan, “A cost-value approach for prioritizing requirements”, IEEE Software, 1997.
	
	This paper describes a cost-value approach to manage and prioritize the requirements. To satisfy the customers’ needs, the process of prioritizing the software requirement should be fast and simple, as well as having trustworthy results. The three factors to meet the stakeholders’ satisfaction are quality, cost, and delivery [6]. The cost-value approach focuses on the relative value and cost of stakeholders. This approach has five steps for prioritizing requirements.

1.	The requirements engineers should review the requirements carefully in order to clear the statement.
2.	AHP’s pairwise comparison method should be use to assess the relative value.
3.	Experienced software engineers estimate the relative cost by using AHP’s pairwise comparison.
4.	The software engineer should calculate and plots the relative value and implementation cost.
5.	Stakeholder analyzes and discuss candidate by using cost-value diagram.

The author refers to two case studies: the RAN project and the PMR project to research the approach. The studies showed that the cost-value approach is suitable for prioritizing requirements.

For the paper: because the prioritization is an important part of software development, the cost-value approach is simple and useful for prioritizing. It can meet more customers’ need so that it can be able to improve the quality of the product. Besides, the case studies in this paper give a good understanding of the approach for the reader.

Against the paper: for this approach, I think the dependency relationship of the requirements should be considered, the author should think about the dependency before prioritizing. It is necessary for managing and prioritizing the requirements. 

##Reference

[1] Gorschek, Tony. Requirements engineering supporting technical product management. Diss. Blekinge Institute of Technology, 2006.

[2] Garcia, Marie L., and Olin H. Bray. Fundamentals of technology roadmapping. Albuquerque, NM: Sandia National Laboratories, 1997.

[3] Phaal, Robert, Clare Farrukh, and David Probert. "Technology Roadmapping: linking technology resources to business objectives." Centre for Technology Management, University of Cambridge (2001): 1-18.

[4] Laube, T., and T. Abele. "Technologie-Roadmap: Strategisches und taktisches Technologiemanagement." Ein Leitfaden. Fraunhofer IPA edition, Stuttgart (2005).

[5] Mahmood, Farrukh, and Waqas Rasheed. "Quality Requirement Abstraction Model (QRAM)." (2014).

[6] S. Shiba, A. Graham, and D. Walden, A New American TQM: Four Practical Revolutions in Management, Productivity Press, Portland, Ore., 1993.

