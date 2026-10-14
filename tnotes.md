# TTT Notes

**Speakers:**

- **Dandy:** Owner of Data & AI role-based training (Worldwide Learning)
- **Chris Tassone:** Owner of Data Engineering content and certification (Worldwide Learning)

**Dandy:** Hi everyone and thank you for joining us today. My name is Dandy and I own the Data and AI role-based training as part of Worldwide Learning. And I'm here with Chris. Chris?

**Chris Tassone:** I'm Chris Tassone and I own the Data Engineering content and certification for Worldwide Learning.

**Dandy:** We know that if you're being a Microsoft certified trainer and you're about to go teach the curriculum that we developed, it might be quite challenging to make that transition from what we consider to be the traditional DBA, teaching a lot of these SQL trainings. So we're going to spend some time with you going through the entire curriculum, bring you the rationalization on the materials, how we developed it, right Chris?

  

**Chris:** Sure. Absolutely.

  

**Dandy:** And then drill down into that a bit more. And Chris, you were a SQL MVP prior, correct?

  

**Chris:** Yeah, absolutely. A SQL MVP for a while, but have transitioned into the world of data engineering through the AI engineering team. So I spent a couple of years working in that role, so I kind of see data engineering through the prism of data science and artificial intelligence these days rather than the traditional transactional roles that we previously had.

  

**Dandy:** Yeah, and that is actually quite an interesting topic because we, if you look on the roles available within the world of data and AI, there's a set of roles that you probably are very familiar with when you think about the ability to drive an architecture in an architect role. Being a data analyst, you then drill down into an analyzing data, bring that into visualization. So there's a couple of roles within that space that are key. For part of the video series and the content to be created, we're really going to be specifically drilling down into the data engineering role. We're going to look at AI engineering as well, and we're going to have a look at the Azure data scientist role. So when we think about those roles, which are currently sitting as part of the curriculum, that's going to be the core focus of the presentation that we're going to be bringing you today. Why, why those roles are core priority? Chris, what are your observations around those roles specifically?

  

**Chris:** So specifically with regards to data engineering, at the end of the day, the cloud has brought about opportunities that now means we're working with technologies that we previously haven't had in the past. A really good example of this is streaming data, for example. You know, previously where it was really cost-prohibitive to do, now with a few clicks we can have that up and running. What this means that there's new opportunities to work with data in different ways. That means our skill sets have to broaden as a result of that. So we're working with a broader range of technologies. Back in the day of SQL Server, you would have been a database administrator or a database developer or a business intelligence developer, right? Because you're in your specific areas, but typically it was within one technology stack. Now as a data engineering, a data engineer, we're working with multiple technologies, Cosmos DB for NoSQL solutions, relational solutions with SQL data warehouse or SQL database, but also with real-time streaming data with technologies such as Stream Analytics. So as a result with data engineering, we're having to look at data in a new way, in the prism of the way it can be processed as well as the new technologies that can handle that.

  

**Dandy:** So then it kind of makes me feel like when you think about those roles specifically, you think about how do you design a solution and it's more prominent that you're going to have to go into the space of NoSQL, getting to areas of data processing, which I think what you're saying is is very different from the traditional data management role. I would, I would think that data management role itself is not going to go away. Later this year, we have SQL Server 2019 coming up. There's a lot of hybrid play in that space as well, and, and as we rationalize that curriculum, that is of course something that we need to build into our content creation plan as well. But the data engineering is certainly a strong opportunity out there to go deliver.

  

**Chris:** There's, there's massive opportunities and it just keeps growing, right? And you mentioned that we have to think about the design of this and we will, we will look at that in depth as we look at DP201. But before you can even look at design, you have to at least understand the capability of each of these technologies, and that's exactly what the DP200 exam is about, right? It's not the deep dive of knowing the internals of how Cosmos DB works, or how SQL Data Warehouse works. No, no, we're not looking at that level. For us, we just need you to understand what is the fundamental capabilities of these technologies and how are they different to each other and when would I use one over the other in a different situation?

  

**Dandy:** So how about we have a closer look into the roles and let's see that data engineering the way we actually define it as part of a certification exam where we said an Azure data engineer is responsible for the design, the implementation of a data solution using the full stack of Azure services available. And yeah, as you know, within those Azure data services, looking at, hey, what is really the best technology to choose in order to drive a business need or business requirements, and then fulfill those requirements with the capabilities that we have around Azure, correct?

  

**Chris:** Exactly. And, and your direction there to all of us in the team was like having the case study which we'll, we'll go into in more depth because we thought very carefully about how can we position this into such a way that it could tell a story. And, you know, at the end of the day, yes, the skills are to design and implement, whether it's the technology itself, whether it's the security of it, whether it's the management of the monitoring, but ultimately it's better if we do that in the context of a case study. So the case study is pretty fundamental to a lot of the courses that we've developed and it's really important that while they teach this curriculum as an MCT you become very, very conversant with what that case study is about.

  

**Dandy:** Yeah. And so when, when Chris, when you're mentioning that case study, do you want to things that we actually did as part of the course and that I scoped the team with is I really holistically want you to think about that case study from the role of a data engineer, want you to think about what that means to data science and then also what that means to AI engineering. And so when we think about AI engineering, I can have like leading the pack in terms of industry when it comes to the definition of that role, really drilling down into how to use cognitive services or using machine learning and things like knowledge mining to really architect and again implement Microsoft AI solution using things like natural language processing, Lewis comes into play as well, things like computer vision and predefined APIs, using bots and building intelligent agents, wrapping that all together, I think we have a very strong point bringing that into a solution where these roles interact and interject with each other. So the AI engineer will be working with the data engineer.

  

**Chris:** Exactly. Exactly. I mean, at the end of the day, there is a lot of capabilities in cognitive services, right? Um, the key thing to remember with AI, right, it's about the cognitive capabilities, right? So let's not forget this is about either vision, our speech, our knowledge, and the question then becomes to what level do you want to apply those capabilities, because that really is the first decision point, right, as to whether you go with an AI engineers out-of-the-box custom vision service, or maybe you go one step further and go into the data science custom AI where you develop your own custom vision solution. So the AI engineering is about understanding the capabilities of the cognitive services, the knowledge mining and the machine learning capabilities that are there, but equally just as important at which point you hit the limitation to go into the world of data science.

  

**Dandy:** Yeah, and I don't necessarily like the word limitations in that, because you're like really writing that fine line between using a pre-defined, pre-configured, pre-created service versus really starting to explore where it goes beyond those typical pre-configured capabilities, right?

  

**Chris:** Exactly, which is no different to like the import-export wizard back in the day, when you hit that limit, you move to SQL Server Integration Services.

  

**Dandy:** That's a very fair point, actually. I like that. Yeah. And so yeah, when we think about those AI capabilities, we think about an Azure data scientist being someone that knows how to do data science, right? We're not going to define and say, hey, here's everything you need to know about data science, but then really apply Azure's machine learning and data science techniques and capabilities where the Azure machine learning service comes into play to then build out custom models, deploy them, again, really related to business problems or the case studies or the requirements that we need to go drive around that specifically.

  

**Chris:** And again, it's about, it's about capability, right? It's about capability across the team data science process, understanding the team data science process and understanding the capabilities of whether it's Azure machine learning service or Azure machine learning studio, you know, what task would you use to do validation of data, training, scoring, all those kind of things, right? So fundamentally, I guess what I'm trying to say is the whole point of these exams and these courses is we are not deep diving into each of the capabilities. We don't expect you to know the ins and outs of hyperparameter tuning. We don't expect you to know the nuances of polybase and how you can optimize that for greater speed, loss. But we do expect you to understand when you should use SQL Data Warehouse over Cosmos DB and when you should use a custom vision over a Lewis. You know, you should understand that basic capability for these exams, whether it's an AI engineering, data science, or indeed data engineering.

  

**Dandy:** Yeah. And so we talked about the certification exams quite a bit already as part of this presentation. Let's have a look on what that means from a Azure data and AI certifications, and then like you mentioned, when we look at some of the pre-requisites that are considered to be optional, I think one of the core foundations is that if you understand the fundamentals of Azure compute, networking, storage, what you can do with pass services and so on, or with things like Azure functions, for example, then seeing that as one of the core foundations, I think is, is kind of key, correct?

  

**Chris:** Absolutely. You really if, if you're going into a classroom teaching any of the, the, the role-based curricula that we've just discussed, you really don't want to be in the classroom explaining what a resource group is, right? This is why we have Azure fundamentals. It is optional, but it is highly recommended that, that you put that as a prerequisite to any of these courses, and that just gives a, a better experience for the students really. So that you can focus in, whether it's AI engineering, you're not, you're not holding up the group by saying, well, this is what a subscription is and this is what a resource group is and this is how it works. How storage works, for example. That should really, the basics should be known. So the fundamentals, although it is optional, I would highly recommend it. And then, and then really the thing to say about the certifications is there is one exam, isn't there, for AI engineering and data science, but the data engineering has two exams, which is the DP200 and 201.

  

**Dandy:** Yeah, and we had some lengthy discussions around that when we envisioned these exams on hey, how can we bring these associate level certifications into the least amount of exams possible to give somebody a meaningful and incredible certification? When you look at the, the, the broad skill set that we have in that world of data engineering with each of the services that we have, I think it was nearly impossible to slot that into a single certification exam, so we decided to then split up the designing as well as the implementation portion into two separate exams. The great thing about it, when we think about some of the training materials that we released also available on our WackLearn portal where people could go for self-based learning, really using a set of micro-learning capabilities, you could pretty much use that skill set to get into that design and implementation, and you should be able to become one of those Azure data engineer associates.

  

**Chris:** And to be fair, Dandy, you raise a really, really good point there from the perspective that if, if you do have students that go, hey, you want me to do Azure fundamentals, where do you do it? Send them to [www.microsoft.com/learn](https://www.google.com/search?q=https%3A%2F%2Fwww.microsoft.com%2Flearn). They can find the Azure fundamentals there and they can study it at self-pace.

  

**Dandy:** Speaking about the data and AI course where providing some of the details here, we have some availability slides in here as well on, on what's coming. One of the things that we actually discovered is there is beyond role-based certification, there's always going to need for some dedicated workloads. Yes. We did prioritize some of the migration workloads that we have seen. So we looked at migrating SQL workloads to Azure, migrating no SQL workloads to Azure Cosmos DB, and then also working with open source data and bring those open source data to Azure. One of the things we'll be focusing on as part of these is really focus on those role-based certifications that we have on the top, going into the implementing an Azure data solution, getting into the design, also in one of the other videos will then be focusing on designing and implementing an Azure AI solution as well as the designing and implementation a data solution on Azure. What stands center there is Azure core motion that we see happening with a lot of our customers, especially in our what we call our strategic accounts, is that huge need for building out skills and assessing those skills when it comes to dealing with data on top of Azure.

  

**Chris:** It's the biggest feedback piece to Microsoft. That the, the, the, the biggest area that a lot of organizations are struggling with is skill sets. The content you've seen here is designed to address that, that gap, and I think there's a huge opportunity as Microsoft certified trainers to take these courses and go out and and teach your customers how they can make use of these technologies in Azure.

  

**Dandy:** Yeah, so one of the things that we also talked about and I think becomes kind of prominent on this is like, wow, we talked about data engineering, we already identified that a database administrator is not a data engineer. Look at that workload that would fall into what we would likely categorized as data management. That data engineering, when you think about it from a Microsoft certified trainer perspective, and I mean, I've been a Microsoft certified trainer for 20 years this year, built, built a lot of my career on SQL Server based training, the querying courses, the admin, the designing data models, you name it. That's a mind shift in a lot of ways, right?

  

**Chris:** Yeah, sure. It certainly has been for me when I, you know, at the end of the day, as you mentioned right at the top of the show, right, you know, I worked with SQL Server for a long time and not just as a trainer, right, I, I have been a production DBA for a Fortune 500 company. I have been there with a, a, a CTO hanging over your saying, my job is on the line if we don't get this fixed, so I understand the pressures of a DBA, I've developed BI solutions. The one I would have said I've done the least is development in the traditional sense of SQL development because I went into BI development. But the reality is is that, you know, it is a mindset shift, and my way in really was through analysis services data mining extension because I've worked on a project there, I've been exposed to machine learning so to speak through the data mining and analysis services. That kind of, I wouldn't say accelerated my path, but gave me an appreciation that in the world of AI and data science, it is definitely a different mindset that you need to make. Uh, one example of this is, is very simple, you know, in BI, you may argue that, that you'll go do a lot of descriptive analytics for the organization where you're delivering those month-end reports and so forth, but really with data science and AI, it's iterative. It's constantly changing, you are changing the parameters of your analysis, particularly when it comes to predictive analytics. But it's not just about predictive analytics as well, it's about categorization, text analytics, and as we move more into the AI space of data science, then of course you're looking at image recognition and speech recognition and so forth. So a lot of it is dependent on, um, on a mindset shift. However, it's also worth mentioning as well, if you ask, you know, a data scientist what the biggest pain point is for them, and I and I spent two years, as you know, working in the, the data science and AI team here in Microsoft, in the, uh, AI engineering team. You know, they, they, they would all say hands down the biggest pain point they would have is data preparation. You know, and that's where even in the previous traditional roles, we fit that bill really, really well, so there is a job, you just have to kind of change the shift a little bit in your mindset in the world of data engineering to account for the different types of technologies that you can use to facilitate that. But also you could say don't get upset if a data scientist says thanks for preparing all that, and then does more preparation as well, that's normal.

  

**Dandy:** Now, when we think about that, because you mentioned it a couple of times and I hear you talk about machine learning and I hear you talk about data science and so on, if we really focus and narrow down on data engineering, I feel that personally coming from that world of strong relational background, SQL performance tuning, you name it, I look at that as like, hey, I get this brand new world of no SQL with things that we do with Cosmos DB and then all the APIs around that as well. I also, I mean, yeah, I used to be the technical product manager for SQL Parallel Data Warehouse, so okay. You're not data warehouse pretty well, but well, I understand the transitioning to, uh, SQL data warehouse, of course, that's kind of like a logical step because it still sits within that relational bucket.

  

**Chris:** Yeah, it does, yeah, it, yeah.

  

**Dandy:** When we think about preparing for this is, is how do I prepare myself to be able to teach that data engineering course that you authored and, and, and what are some of the things that I should go discover beyond what's sitting inside the training materials, because I can see myself having a little bit of a challenge with that, and I kind of have, I've always had the approach like, hey, I cannot just teach what's on every slide, on every page in the curriculum. I need to know much more in order to satisfy the need of my students. What are some tips that I could go do, what are some focus areas?

  

**Chris:** Without getting into specifics because we'll focus on that in the individual sessions for our DP200 and 201. Um, I was very fortunate to join the company with the growth mindset initiative being pushed very, very hard. So I would say keep an open mind number one. Um, suspend your, um, belief system in relational and be open-minded to the fact that data works in different ways, uh, particularly with streaming as well. So the first thing I would say, keep an open mind. Uh, number two, if you have the opportunity to play, use these technologies. It, it, it does become second nature quite quickly. It kind of reminded me a little bit with the transition in, in SQL 2005, you know, from, from enterprise manager into SQL Server Management Studio and Visual Studio. Do you remember all the resistance that was there back in the day where, oh, I'm not touching that, I'm not touching that, but, you know, particularly with the world of DTS, within two weeks of using that, people loved it. And, and I would say it doesn't take two weeks, but it, it takes a little bit longer, but if you start getting into the daily habit of, of, of, you know, I'm going to provision a data lake store and I'm going to upload data into it, it becomes second nature rather quickly.

  

**Dandy:** One of the things we talked about as well as, uh, whack learn being our online platform for learning. Yeah, I think we made a very strong, uh, strategic decision there to go build out these learning paths for consumption. If you look on the visitors that we're getting there, people drilling down into the content, already brought it up that, that module you did on data lake store was like really hot off the press when we announced data lake gen two. What we actually did with whack learn is give you a set of learning paths associated to the role as well for you as a Microsoft certified trainer to go in and prepare you for the instructor-led trainings, but also for your audiences to go in to find out the basics around some of these technologies, how they fit together. So let's have a look and go out to whack learn and discover these learning paths specifically as they relate to our curriculum as well and give you some insights in the concepts.

  

### Microsoft Learn Portal Walkthrough

**Dandy:** So what we wanted to show you is the Microsoft Learn portal on which we actually identified learning specific to the role-based certifications as well. So if you navigate to learn, you're going to see that on the portal here you have each of the roles identified, so I have the ability to go into AI engineer, data engineer, data scientist. And so let's have a look at the data engineer here specifically and click on to the role. Now, what you see here is role-relevant information that is covers in what we call learning path and module, and the idea around this is that from a module perspective, you would be interested into a specific topic that is broken down into multiple lessons or units that you could then consume. So one of the examples here would be the upload data to Azure data lake store, which we also covered as part of the instructor-led training. But what's really neat about this is that you have these real tracking of micro-learning assets for which you can receive points, and then based on those points you'll be able to keep track of which learning paths and modules you completed to add into your, uh, overall learning plan. I'm going to filter, uh, quickly here on the learning paths, and so what you see within the data engineering role is there's 10 learning paths. One intro, uh, learning path has covered the Azure for the data engineer, which is very similar to what we had in that first module as part of the data engineering course, but you're also going to find some real specific things like how do you perform large-scale data processing with data lake storage generation two. You have the link to the Azure fundamentals training in there too because we identified as, uh, one of the core requirements and opportunities that we have for this. Uh, if you look on that tagging, uh, up here, you'll see that we have things like the role-based, or the each of those learning paths is then also tagged specifically to a role, and you can actually see that, hey, Azure fundamentals is relevant for data engineering, data scientist, and AI engineering. We really considered that to be a prerequisite. My advice to you as, especially when you're preparing for delivering the training is, uh, yeah, go through these learning paths that we did identify as part of the data engineering curriculum, and you might some, uh, might find some other, uh, titles out there, right? Like, for example, I could filter on the AI engineering learning paths as well, um, and really point that out to your students as well, that they can start navigating this, going through this, uh, work with your, uh, uh, learning partner or or with your students to actually if there's any follow-up on any additional questions they might have around let's say a topic of security, that they can then go into these learning paths as well.

  

**Dandy:** So as you can see, uh, looking at these online learning capabilities, there's a great amount of assets available to you. Uh, definitely go ahead and use those, drill down into each of those topics. It is going to help you a lot with preparing. You'll see that in the future as we evolve these as part of our fiscal year, sustained engineerments and updates, we'll bring in things like sandbox environments to actually let you discover the technology a bit more. I think what we did with the knowledge checks on that was great as well to kind of validate your knowledge at the end of the module. And, uh, yeah, as we wrap up this, uh, this video, we'll see you in the next chapters to drill down specifically on any of the courses you're going to be teaching. Thanks for joining.

  

**Chris:** Thank you.

- interactive
www.menti.com

## Module 01 - Explore core data concepts

- Lots of definitions, take your time
- Use storytelling and examples
  - e.g. store and transaction when the card is swiped
- Longest module in the course, be careful with your timing
  - Cover high-level overview
  - Details will be covered in subsequent modules
  - Only high-level demos
  
## Module 02 - Explore relational data in Azure

- Difference b/w IaaS and PaaS
  - Azure has mostly PaaS and few IaaS
- Difference between SQL Services
  - IaaS
    - VM
      - Multiple databases per instance
  - PaaS
    - Azure SQL Service
      - Only 1 database in the instance
    - SQL Server Managed Instances
      - allows multiple databases
  - MySQL - PaaS
  - PostgreSQL - PaaS
  - Oracle - IaaS
- Don't focus only on SQL Server
- Describe AD basic concepts before RBAC

## Module 03 - Explore non-relational data in Azure

- CosmosDB
  - Multipe APIs/models
    - Columnar database - Cassandara
  - Multiple reads/writes from different regions
  - Consistencies (MSDN pages have animations)
    - Strong
    - Session
    - Eventual
    - https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels
    - https://parveensingh.com/cosmosdb-consistency-levels/#:~:text=Table%20Summary%20%20%20%20Levels%20%20,%20%20Moderate%20%201%20more%20rows%20
- Storage account
  - Types
    - table
    - queue
    - file
    - blob
  - Show quick demos

## Module 04 - Explore modern data warehouse

- components of a data warehouse
- difference b/w data warehouse and Azure Synapse Analytics Service
  - Data warehouse
    - Generic term that can be implemented in on-prem
  - Synapse
    - Data warehouse on steroid powered by Azure Cloud
    - Cloud-based and no restrictions on data size and compute power
- Power BI and other reporting solutions

## Demos

- general Azure Portal

## Reference materials

- Online documentation
- MS Learn
  - learn.microsoft.com
- Azure Blog
- Azure Forums
- Microsoft hands-on labs
- Reference Architectures
- Articles
- Videos
