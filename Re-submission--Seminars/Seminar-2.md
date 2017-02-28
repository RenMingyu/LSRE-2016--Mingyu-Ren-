##Questions:

• Read up on the Boston Matrix
   
   Boston Matrix, also known as market growth rate - the relative market share matrix, the Boston Consulting Group Act, the four-quadrant analysis, the product structure management law, etc. The essence of Boston Matrix is to achieve the cash flow balance of an enterprise based on the optimal combination of business [1]. There are four categories of business portfolio as follow:

  1. Stars refers to the product with high growth and high market share. It developed by the Question Marks based on the continuous investment and it can be considered as the leader of the high-speed growth market. It will become the Cash cows of the company in the future. Although the products in this area are in the high-speed growth market and a dominant market share, it doesn't mean that Stars can take the steady flow of cash to the company. With the high-speed development of market, company must invest continuously and keep pace with the market growth, then repel the competitors.
  2. Question Marks refers to the product with high growth and low market share. The product in this area are some speculative product with high risk. This is often a new business of a company. In order to develop Question Marks, the company must establish factory and set up equipment and staff. This can be use to follow the market with high-speed development. It is also means the large investment. The Question Marks can describe the attitude of the company for the business, because the company should reply whether continuous invest or not to develop this business. The business which can satisfy the long-term goal of company development, the company has useful resources, increase the core competitiveness of the company can get a positive answer. The Question Marks can be developed as Stars.
  3. Cash cows refers to the product with low growth and high market share. The product in this area can produce a large number of cash, but the growth prospects in the future are limited. This is a leader of mature market, it is the source of corporate cash. Because the market becomes maturely, the company doesn't have to invest a large number of investment to expand the scale of market. At the same time, as the leader of market, Cash cows have the advantages of scale and high margin, and bring a lot of cash flow to the company. Companies often use Cash cows to pay business accounts and support the other three businesses which required a lot of cash. Cash cows is suitable for the stability strategy mentioned in strategic framework.
  4. Dogs refers to the product with low growth and low market share. Normally, this kind of business often has low profit and occupies many resources. However, it may develop to other possible business.
    
    The essence of the Boston matrix is to combine strategic plan with capital budget, and to divide a complex enterprise behavior into four types by two important indicators. It helps a variety of operating companies to determine which products are suitable to invest, for which products operating at a profit, for which products removed from the business combination, so that the business combination to achieve the best operating results.
  
• How do you connect your requirements to your architecture?
    
   From the user's point of view, what the user want to get after using the product and the users' requirements for the features the product should have. And the architect should set up the architecture document based on the users' requirements and function description. The architecture focuses on support the result of system analysis. According to the designing, we need to combine the customers' requirements with final architecture and develop the product. In addition, the use case and scenarios describe the relationship among components, connect the four views in software architecture.
  
• Can you connect all requirements directly? What do you do if you cannot?
    
   No, I can't connect all requirements directly, but maybe I can connect them indirectly. As the users have different requirements, the requirements can be divided into different level according to users. If I cannot connect the requirements, as a developer of the product, I should analyze the all users in different area and know about their features, tasks, requirements clearly. Based on some prioritization methods, we can decide the order of requirements during the development.

##Article summary:

####– v.d. Weerd & Brinkkemper “Towards a reference framework for software product management”

This paper proposed a reference framework for software product management to manage the product. The software product management lack of specific research and educational purposes [2], so the paper provides a reference framework of the structure of software product management. The reference framework includes four parts, and it shows in a figure to help us to understand the process of reference framework clearly, the four main parts as follow:

1.	Portfolio management: on the top of the reference framework, the portfolio management has four processes: partnering & contracting, market trend identification, product lifecycle management, and product line identification. It is based on the company board, market and partner companies.
2.	Product roadmapping: roadmapping has dependency relationship with such as related product, technology changes, as well as the distributed development [3]. The product roadmapping works based on the product lines of portfolio management.
3.	Requirements management: the stakeholders are the most important basis of requirements management. The requirements need to be gathered, identified, revised, and organized in this phase.
4.	Release planning: the release planning prioritizes and selects the product requirements in reference framework. The validation in release planning is related to different stakeholders.

In this paper, the author proposed a reference framework to manage the software product. It ensures that the reference framework is important in industrial requirements engineering.

For the paper: the paper used a figure to show the overview of the reference framework, it is clear and straightforward for us to know about the whole process in detail. Also, the paper told us that the importance of reference framework for software product management.

Against the paper: the author should provide some case for the reference framework. The paper needs some practical project to research the reference framework, so that it can be able to provide some successful experience for future work.

####– Regnell & Brinkkemper “Market-Driven Requirements Engineering for Software Products” (Chapter 13 in Engineering and Management of Software Requirements) 

This paper introduced the Market-Driven Requirements Engineering (MDRE) in detail. It shows the characteristics and challenges of MDRE. MDRE consists of elicitation, specification, and validation of requirements engineering. It also includes the development processes activities such as release management and market analysis. 

The main characteristics of MDRE: the decisions always made by developing organization. In the product lifetime, the requirements have continuous flow. The requirements volume would become larger and larger. Most of the requirements described informally. The product could delivery in multiple releases. Time-to-market and return-on-investment are important points in release planning.

The main challenges in MDRE described in this paper divided into seven points as follow:

1.	Balancing market pull and technology. In MDRE, the practical condition and the technologies could change frequently. So the balancing is necessary.
2.	Chasm between marketing and development. In the process of development, the difference could appear between developers and customers. So the communication and management are important in MDRE. We need to try to reduce the difference and improve the quality of product.
3.	Organizational instability and market turbulence. Nowadays, the market is changing rapidly. The challenge is that we could not handle the changes. The structure of the organization should be flexible and ready to face the market problems.
4.	Simple tools for basic needs. If the tools can be used for the simple and basic activities, it is difficult to fix the complex problems.
5.	Requirements dependencies. Before the prioritization, we need to consider the dependencies among the requirements. It is complicated about the dependencies. And it’s hard to manage the requirements.
6.	Cost-value-estimation and release planning. The accurate estimation is important for release planning. But the estimation is difficult in MDRE.
7.	Overloaded requirements management. In MDRE, we pay more attention to the requirements management, it is often overload the requirements management. It is a challenge for preventing the overloaded requirements management.

The chapter lists many detailed challenges, processes, and characteristics about MDRE to let us know about the software product and the method of MDRE. 

For the paper: the paper is an exhaustive and comprehensive description of MDRE. The author summarizes many aspects and examples for MDRE. It is easy for us to understand and know the basis of MDRE, as well as what we should do in MDRE.

Against the paper: the projects in different types and different scales have different way to manage the requirement. The method the author proposed is not suitable for all types of project. Such as the estimation in the release planning, some other estimation approach should be considered with different conditions.

####– D. Leffingwell “Scaled Agile Framework” (Note, there is no good article on this, but his webpage provides some help).

The provided webpage is a figure of software development process for lean software and system engineering. Scaled Agile Framework (SAFe) has four levels and a foundation layer.

1.	Team level: based on the backlog in each team, they all need to define, build, and test stories. In each sprint, the team should deliver the value.
2.	Program level: SAFe team has a virtual program structure called the agile release train (ART). The team would plan, commit, execute, inspect, and adapt with the stakeholders together. 
3.	Value stream level: the value stream level can be able to support large development and complex solutions. The multiple and synchronized ARTs is good for the solutions.
4.	Portfolio level: the portfolio level gives the solution development funding by Lean-Agile budgeting.
5.	Foundation layer: the foundation layer has five elements: lean-agile leaders, communities of practice, core values, lean-agile mindset, and principles.

SAFe is in developing, and it will improve the business outcomes. For the practical case, it can increase the productivity and reduce the defects.

There are many advantages of SAFs, it is easy for us to use, and it can be used in many practical agile development project. It is evolving continuously with the development of the market. I don’ think SAFs has any disadvantages.

####– Wnuk et al. “Are You Biting Off More Than You Can Chew? A Case Study on Causes and Effects of Overscoping in Large-Scale Software Engineering”

It is a case study about the overscoping in large-scale software engineering. And it aims to know if agile requirements engineering affect overscoping. It is important to manage the scope of a software development project. Based on the interview, the author proposed seven causes of overscoping.

1.	Continuous requirements inflow from multiple channels. In large scale projects, the requirements are uncontrollable and potential, so it is hard to manage and balance the requirements.
2.	No overview of software resource availability. When the development capacity is low, it could cause the lack of overview, then cause the overscoping.
3.	Low development team involvement in early phases. The requirements engineering requires communication and management. But in early, the team could not achieve that, it leads to overscoping.
4.	Requirements not agreed with development team. Requirements would not have developed by the team, that would have huge impact on overscoping.
5.	Detailed requirements specification produced upfront. Because the requirement could change during the development, the detailed specification produced upfront could influence the quality of requirements.
6.	Unclear vision of overall goal. If the goals are unclear, the developing process would get more errors.
7.	Weak process adherence and scope and deadline dictated by management. 

According to a case study, the paper shows that overscoping is caused by fast-moving market-driven. The result of the paper can be used to identify potential factors.

For the paper: the paper uses a case study to research the overscoping in Large-Scale Software Engineering, and use interview and questionnaire, it is good for us to understand the overscoping easily. 

Against the paper: I did’ t found the advantages of this paper.

####– Wnuk et al. “Factors Affecting Decision Outcome and Lead-time in Large-Scale Requirements Engineering”

This paper shows a case study to confirm that lead-time is important factor for decision making in Large-Scale Requirements Engineering. For the analysis of decision making, the results are from a survey among 50 practitioners which come from several countries. The result can be summarized as seven points.

1.	More product could increase the lead-time to make a decision.
2.	If many products are affected, the request can be changed.
3.	The release of the product line and the decision lead-time from the statistical analysis have no relationship.
4.	Change requests in later releases is easy to be accepted.
5.	If the important customers issue the change requests, the lead-time for decision is short.
6.	Change requests from the important customers could be easy to accepted.
7.	Rejecting a decision takes much time than accepting a decision.

The result shows the important customers are critical for change requests.

For the paper: the author proposed the requirements engineering decision making characteristics, it is helpful for us to analyze the factors affecting in large-scale requirements engineering.

Against the paper: I think the decision characteristics should be considered in detail. Because in this paper, the lack of data could not give the research an accuracy result.

####– P. Carlshamre, K. Sandahl, M. Lindvall, B. Regnell, J. Natt och Dag, “An industrial survey of requirements interdependencies in software product release planning”, in Proceedings of the fifth IEEE International Symposium on Requirements Engineering, 2001.

The paper used a survey to find the requirements interdependencies of software product release planning from five different companies. The author proposed six interdependencies: AND, REQUIRES, TEMPORAL, CVALUE, ICOST, and OR. 

AND is R1 and R2 requires to function each other. It is traced in requirements management tool. REQUIRES is “on way” required to function. TEMPORAL is that R1 should be implemented before R2 and vice versa. CVALUE is that R2 could affect the value of R2 and the value could be positive or negative. ICOST is that R1could affect the cost of implementing R2, and the value could be positive or negative. OR is that only one of R1 or R2 could be implemented.

According to this research, we know the importance of release planning in market-driven software development. The survey showed that most of interdependencies are responsible for relatively requirements.

For the paper: the result of the survey confirms the proposed questions. And the practical case could give the readers directly expression. I have deep comprehension of interdependencies from this paper. 

Against the paper: the classification of interdependencies is based on the required to function. It would not suitable for all conditions. I think the author can use other types of approach for classification.

##Reference

[1] Zhang, Y. F., A. G. Yuan, and G. H. He. "Analysis on market competitive state of Sichuan inbound tourism based on Boston matrix." Ecological Economy 3 (2008): 95-

[2] P. Bourque and R. Dupuis, (ed.), Guide to the Software Engineering Body of Knowledge, 2004 edition, IEEE Computer Society, Los Alamitos, CA, USA, 2004.

[3] E. Carmel, Global Software Teams, Prentice Hall: Upper Saddle River, NK, 1999.

