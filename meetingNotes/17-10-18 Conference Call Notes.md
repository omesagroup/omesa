# Agreed decisions: #


- Use a real implementation as vehicle to showcase OMESA. Proposal on the table from Lucas.
-	Credits should be captured in a credit section within the home page
-	Use Trello or something similar to keep track of actions
-	Rota for OMESA coordinator. Change of “turch” agreed to 3 months 
-	Phil to take on next coordination role
-	Content to be created in a more dynamic way by better structuring GITHUB and getting rid of powerpoints and Excels. All content should be in markdown and structure in a way that it’s easy to contribute in parallel (like OpenSource projects work)
-	Better way to define capabilities. Some sort of glossary of terms is required

----------

# Round table: #

**Phil:**


- Additional definitions 
--	Vertical / horizontal integration
--	Illustrative examples to show explain (i.e. i.e. what does loosely couple mean)

**Danillo:**

-	We have a good overview and some good work on capabilities (i.e. semi-decoupled / fully-decoupled). Danilo using it in almost every API presentation and they have seen a lot of interest.
-	It’s a good start point, but do we have practical experiences on how to use it? are we using it in projects? recommendations to projects
-	We should share this experiences
-	We should include the serverless capabilities into the topic
-	API design best-practice

**Sven:**

-	Same opinion as Danillo. We have solid foundation but practical experience is required.
-	Incorporate feedback we receive from different discussions so it can be reflected in OMESA
-	Include some sort of recommendations. I.e. based on different scenarios/use cases when to use Microservices vs Serverless for example
-	Cover in more detail the Security. How to address it. I.e. OAuth 2.0

**Torsten:**

-	Series of articles describing OMESA architecture, and follow up on how to apply them. Short articles. I.e. 1 page long. Clear use case -practical. I.e. one article a week

**Lucas:**

-	Lucas likes what’s there, what was in OOW and glad to be in the call
-	Make sure we capture serverless in the architecture
	Caching across stateless layer. Elaborate more on the capability.
-	Mention bots in the architecture. i.e. in the UX ?
-	In the UI Lucas would like to add more. Home page shows the “composition” of UI-based Microservices. Lucas would like to add more to this.
-	For AMIS is very important to integrate with SaaS applications (in some way or other). Make this more explicit part of OMESA
-	Reference Implementation to something that we have actually built and run. Lucas will share and if we like it we can put it forward and build it. As first step we can describe how OMESA maps to technologies i.e. Oracle / Open Source / Amazon / Azure, etc

**Robert:**
 
-	Presented to National Police
-	Add more definitions so it’s easy to read. Then this can help 
-	Open source should definitely be covered
-	Would like to help with the reference architecture
-	Add serverless functions. Specially how to “orchestrate” functions.

**Arturo:**
 
-	Governance to the project. Be able to capture ideas and make sure we implement them.
-	Agreed with Lucas on using OMESA to build a system. This could be our reference model. Also agreed with writing the articles.

**Rolando:**

-	Presented OMESA to a few banks
-	Started persistence layer
-	Security is always popping up, not just on OAuth etc. But also security patterns.
-	Create content. He’ll create a set of videos talking about this
-	Jira / Trello

**Hajo:**

-	Tried to applied OMESA in a complex system that included Task Management. We should apply OMESA in concrete project, and reflect back our learnings into OMESA. We need to go deeper into the next layer of the tool box based on projects.


**Luis:**

- Make development of content more like open source code. Interactive and dynamic
-	Change the “torch” on the leading part. Today I organised the call, but we can rotate. Perhaps same person (depending on rota) takes also responsibility on rotation
-	Better way to represent the definitions 
-	Perhaps combine the idea of constant articles with building the solution?
-	Simplify how terms and content is generated
-	Have a rote to switch coordination responsibility



----------
 
# Actions: #

**Luis:**

-	I will create the rota sheet so we can track owns the truth
-	I will follow up with Arturo on the Github content restructuring

**Phil:**

-	Will work with Rolando in the documentation of the API layer
-	Will take the torch
-	Will create a contributors page in the OMESA page
-	Review Lucas proposal and provide feedback 

**Lucas:**

-	(assuming every agrees to his proposal for the reference implementation) he will coordinate the next steps for the implementation (i.e. identify microservices and owners as first step. Identifying people outside this forum to contribute, contribute with Jurgen/Jennifer)

**Robert:**

-	Will make the first draft of the glossary
-	Will setup something like Trello to keep track
-	Review Lucas proposal and provide feedback

**Arturo:**

-	Will take ownership of the GITHUB part of the governance and will work with Phil/Luis/Robert on the governance stuff
-	Will take a very good look at the proposal and provide feedback
-	Review Lucas proposal and provide feedback

**Rolando:**

-	Will finalise the API layer with Phil
-	Will create a video talking about OMESA
-	Review Lucas proposal and provide feedback

**Danilo:**

-	Will start with one of first articles and will look at Lucas proposal
-	Will contribute to the security component of OMESA based on a white paper he’s working on (first will share the draft)
-	Review Lucas proposal and provide feedback

**Sven:**

-	Will map concrete technologies to different layers on the Oracle perspective which will help validate the reference implementation
-	Review Lucas proposal and provide feedback

**Torsten:**

-	Will work together with Sven on the technology mapping
-	Will work on the caching concept
-	Review Lucas proposal and provide feedback

**Hajo:**

-	Will include description of workflow and ACM to OMESA
-	Review Lucas proposal and provide feedback
