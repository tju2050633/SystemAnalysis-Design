


<center><font size=10 color=#1488CC>Content</font></center> 
[toc]

<div STYLE="page-break-after: always;"></div>

## 1.Introduction

This section provides a brief overview of the Shared Garden project, which aims to transform unused and abandoned land on campus into shared gardens that are designed and built by all students. The section also defines the purpose, scope, and target reader, as well as the target readers and suggestions for using this document.

本节简要介绍了共享花园项目，该项目旨在将校园内的闲置废弃土地改造成由所有学生参与设计和建造的共享花园。本节还定义了项目的目的、范围和目标读者与建议，以及本文档的目标读者和使用建议。

### 1.1 Background

The sharing garden project is an initiative that aims to respond to the national call for energy conservation and emission reduction, by building a green and low-carbon campus. It actively promotes the development of a scientific, low-carbon, and efficient resource allocation model, to adapt to the development situation of higher education, and to promote the construction of an ecological civilization. The main action of this project is to transform the idle and abandoned land on campus into a sharing garden, which is designed and constructed by all students. This project aims to achieve the goal of participatory landscape design, and students can earn credits and rewards, such as potted plants, by participating. We will build a web-based application, which includes a sharing garden construction toolkit and a sharing garden community.

共享花园是一项旨在响应国家节能减排号召的倡议，旨在建设绿色低碳校园。它积极促进科学、低碳、高效的资源配置模式的发展，以适应高等教育的发展形势，并推动生态文明建设。该项目的主要行动是将校园内的闲置废弃土地改造成共享花园，由所有学生参与设计和建造。这个项目旨在实现参与式景观设计的目标，学生可以通过参与获得积分和奖励，如花卉盆栽。我们将建立一个基于 WEB 的应用程序，其中包括建造共享花园的工具包和共享花园社区。

### 1.2 Purpose

The purpose of this Software Requirements Specification (SRS) document is to outline the functional and non-functional requirements for the development of a web-based application that will serve as a toolkit for designing and building shared gardens, as well as a platform for a shared garden community. The SRS will serve as a guide for the developers, designers, and stakeholders involved in the Shared Garden project. This document aims to provide a clear and detailed description of the system's requirements, features, and functionality to ensure that the developed application meets the project's goals and objectives. It will also serve as a basis for testing and validating the application's functionality.

Also, purpose of this document is to provide a detailed and comprehensive description of the requirements and specifications for the web-based application that supports the project of creating and sharing campus gardens among students. The web-based application aims to achieve the following objectives:

- To enhance the students' learning experience and engagement in environmental education and sustainability topics.
- To foster the students' creativity and collaboration skills by allowing them to design, create, and share their own campus gardens with other students.
- To promote the students' awareness and appreciation of the campus environment and biodiversity by enabling them to explore and visit other campus gardens.
- To facilitate the campus administration's management and evaluation of the campus facilities and resources by providing them with data and feedback on the campus gardens.

这份软件需求规格说明（SRS）的目的是为开发基于Web的应用程序提供功能和非功能需求清单，该应用程序将作为一个设计和建造共享花园的工具包，同时也是共享花园社区的平台。SRS将为参与共享花园项目的开发人员、设计师和利益相关者提供指南。本文档旨在提供系统需求、功能和功能的清晰详细说明，以确保开发的应用程序符合项目的目标和目的。它还将为测试和验证应用程序的功能提供基础。

同时，本文档的目的是提供一个详细而全面的描述，说明支持学生创建和分享校园花园项目的基于WEB的应用程序的需求和规范。基于WEB的应用程序旨在实现以下目标：

- 通过让学生设计、创建和与其他学生分享自己的校园花园，提高学生在环境教育和可持续发展主题方面的学习体验和参与度。
- 通过让学生探索和参观其他校园花园，培养学生的创造力和协作能力。
- 通过让学生了解和欣赏校园环境和生物多样性，提高学生的意识和赞赏。
- 通过为校园管理部门提供有关校园花园的数据和反馈，方便校园管理部门对校园设施和资源的管理和评估。

### 1.3 Project Scope

The project scope defines the boundaries and limitations of the web-based application that supports the project of creating and sharing campus gardens among students. The project scope includes the following aspects:

- In Scope: The web-based application will provide the following features and functions for the students and the campus administration:
  - Students can register and log in to the web-based application using their campus email and password.
  - Students can create their own campus gardens by selecting a location on the campus map, choosing a garden template, and customizing the plants and decorations.
  - Students can share their campus gardens with other students by publishing them on the web-based application and inviting other students to visit them.
  - Students can explore and visit other campus gardens by browsing them on the web-based application and viewing them on the campus map.
  - Students can rate and comment on other campus gardens by giving them stars and writing feedback on the web-based application.
  - Campus administration can monitor and manage the campus gardens by accessing the web-based application and viewing the data and feedback on the campus gardens.
  - Campus administration can approve or reject the campus gardens by reviewing them on the web-based application and sending notifications to the students.

- Out of Scope: The web-based application will not provide the following features and functions for the students and the campus administration:
  - Students cannot physically plant or maintain their campus gardens by using the web-based application. They need to contact the campus administration for permission and assistance.
  - Students cannot interact with other students or chat with them by using the web-based application. They need to use other communication platforms or tools.
  - Campus administration cannot modify or delete the campus gardens by using the web-based application. They need to contact the students for consent and cooperation.

项目范围定义了支持学生创建和分享校园花园项目的基于WEB的应用程序的边界和限制。项目范围包括以下方面：

- 在范围内：基于WEB的应用程序将为学生和校园管理部门提供以下功能和特性：
  - 学生可以使用他们的校园邮箱和密码注册和登录基于WEB的应用程序。
  - 学生可以在校园地图上选择一个位置，选择一个花园模板，并自定义植物和装饰，来创建自己的校园花园。
  - 学生可以通过在基于WEB的应用程序上发布他们的校园花园，并邀请其他学生来参观，来与其他学生分享他们的校园花园。
  - 学生可以通过在基于WEB的应用程序上浏览和查看其他校园花园，来探索和参观其他校园花园。
  - 学生可以通过在基于WEB的应用程序上给其他校园花园打星和写反馈，来评价和评论其他校园花园。
  - 校园管理部门可以通过访问基于WEB的应用程序，并查看有关校园花园的数据和反馈，来监控和管理校园花园。
  - 校园管理部门可以通过在基于WEB的应用程序上审查校园花园，并向学生发送通知，来批准或拒绝校园花园。

- 超出范围：基于 Web 的应用程序不会为学生和校园管理提供以下功能和功能：
  - 学生不能通过使用基于 Web 的应用程序来实际种植或维护他们的校园花园。他们需要联系校园管理部门获得许可和协助。
  - 学生不能通过使用基于 Web 的应用程序与其他学生互动或聊天。他们需要使用其他通信平台或工具。
  - 校园管理不能通过使用基于 Web 的应用程序修改或删除校园花园。他们需要联系学生征得同意和合作。

### 1.4 Target Readers and Suggestions

This document is intended for the following readers:

- Project Team: The group of developers who are responsible for designing, developing, testing, and deploying the web-based application. This document provides the functional and non-functional requirements, as well as the design constraints and assumptions, for the web-based application.
- Campus Administration: The authority that manages and oversees the campus facilities and resources. This document provides the overview and scope of the project, as well as the benefits and risks, for the campus administration to evaluate and approve.
- Students: The users of the web-based application who are enrolled in a higher education institution and participate in the project. This document provides the user requirements, as well as the user interface design and user manual, for the students to understand and use the web-based application.

The suggestions for reading this document are as follows:

- Project Team: The project team should read this document thoroughly and carefully, and follow the requirements and specifications when developing the web-based application. The project team should also communicate with the campus administration and the students regularly to ensure that the web-based application meets their expectations and needs.
- Campus Administration: The campus administration should read this document selectively and critically, and focus on the overview and scope of the project, as well as the benefits and risks. The campus administration should also provide feedback and approval for the project team to proceed with the development of the web-based application.
- Students: The students should read this document selectively and casually, and focus on the user requirements, as well as the user interface design and user manual. The students should also provide feedback and suggestions for the project team to improve the web-based application.

本文档面向以下读者：

- 项目团队：负责设计、开发、测试和部署基于WEB的应用程序的开发者组。本文档提供了基于WEB的应用程序的功能性和非功能性需求，以及设计约束和假设。
- 校园管理部门：管理和监督校园设施和资源的权力机构。本文档提供了项目的概述和范围，以及利益和风险，供校园管理部门评估和批准。
- 学生：基于WEB的应用程序的用户，是一名在高等教育机构就读并参与项目的学生。本文档提供了用户需求，以及用户界面设计和用户手册，供学生了解和使用基于WEB的应用程序。

阅读本文档的建议如下：

- 项目团队：项目团队应该仔细地阅读本文档，并遵循需求和规范来开发基于WEB的应用程序。项目团队还应该定期与校园管理部门和学生沟通，以确保基于WEB的应用程序符合他们的期望和需求。
- 校园管理部门：校园管理部门应该选择性地、批判性地阅读本文档，并重点关注项目的概述和范围，以及利益和风险。校园管理部门还应该为项目团队提供反馈和批准，让他们继续开发基于WEB的应用程序。
- 学生：学生应该选择性地、随意地阅读本文档，并重点关注用户需求，以及用户界面设计和用户手册。学生还应该为项目团队提供反馈和建议，以改善基于WEB的应用程序。

<div STYLE="page-break-after: always;"></div>

## 2 Glossary of Terms

This section defines some of the terms that are used in this document.

|Terms|Definition|
|---|---|
|Shared Garden|A garden that is designed and built by students on campus using unused and abandoned land. Each shared garden has a theme and a name, and can be visited and enjoyed by anyone on campus.|
|Theme|The concept or idea that guides the design and decoration of a shared garden. Each theme has a name, a description, and a set of criteria, and can be chosen by the students from a predefined list or created by themselves.|
|Toolkit|A set of tools and resources that are provided by the web-based application to help students design and build their shared gardens. The toolkit includes a plant library, a material library, a decoration library, a layout editor, a budget calculator, and a progress tracker.|
|Community|A platform that is provided by the web-based application to facilitate communication and collaboration among students who participate in the project. The community includes a forum, a gallery, a rating system, a feedback system, and a suggestion system.|
|Student|A user of the web-based application who is enrolled in a higher education institution and participates in the project. Students can design and build their own shared gardens, as well as visit and rate other shared gardens.|
|Campus Administration|The authority that manages and oversees the campus facilities and resources. Campus administration is responsible for approving and allocating land for the project, as well as providing guidance and support for the students.|
|Point System|A system that is used by the web-based application to reward students for their participation and contribution to the project. Students can earn points by completing tasks, such as designing, building, maintaining, and rating shared gardens. Points can be redeemed for rewards, such as flower pots, seeds, tools, and vouchers.|
|Reward Mechanism|A mechanism that is used by the web-based application to motivate students to join and contribute to the project. The reward mechanism includes a leaderboard, a badge system, a certificate system, and a recognition system.|
|Rating|The score and feedback that a student gives to another shared garden after visiting it. Each rating has a value from 1 to 5 stars, and an optional comment. Ratings can be viewed by other students and the campus administration.|
|Badge|The reward and recognition that a student receives for achieving certain goals or milestones in the project. Each badge has a name, an icon, and a description, and can be displayed on the student's profile page.|
|Web-based Application|The software system that is developed by the project team to enable students to participate in the project. The web-based application consists of a front-end user interface and a back-end database and server. The web-based application can be accessed through any web browser on any device.|

本节定义了本文档中使用的一些术语。

- 共享花园：一种由学生在校园内利用闲置废弃土地设计和建造的花园。每个共享花园都有一个主题和一个名字，可以被校园内的任何人参观和欣赏。
- 主题：指导共享花园的设计和装饰的概念或想法。每个主题都有一个名字、一个描述和一套标准，可以由学生从预定义的列表中选择或自己创建。
- 工具包：一套由基于WEB的应用程序提供的工具和资源，用于帮助学生设计和建造他们的共享花园。工具包包括植物库、材料库、装饰品库、布局编辑器、预算计算器和进度跟踪器。
- 社区：一个由基于WEB的应用程序提供的平台，用于促进参与项目的学生之间的沟通和协作。社区包括论坛、画廊、评分系统、反馈系统和建议系统。
- 学生：基于WEB的应用程序的用户，是一名在高等教育机构就读并参与项目的学生。学生可以设计和建造自己的共享花园，也可以参观和评价其他的共享花园。
- 校园管理部门：管理和监督校园设施和资源的权力机构。校园管理部门负责批准和分配项目用地，以及为学生提供指导和支持。
- 积分系统：一个由基于WEB的应用程序用于奖励学生参与和贡献于项目的系统。学生可以通过完成任务，如设计、建造、维护和评价共享花园，来获得积分。积分可以兑换奖励，如花卉盆栽、种子、工具和优惠券。
- 奖励机制：一个由基于WEB的应用程序用于激励学生加入和贡献于项目的机制。奖励机制包括排行榜、徽章系统、证书系统和认可系统。
- 评分：学生在参观另一个共享花园后给予的分数和反馈。每个评分有一个从1到5星的值，和一个可选的评论。评分可以被其他学生和校园管理部门查看。
- 徽章：学生在项目中达到某些目标或里程碑时获得的奖励和认可。每个徽章都有一个名字、一个图标和一个描述，可以显示在学生的个人资料页面上。
- 基于WEB的应用程序：由项目团队开发的软件系统，使学生能够参与项目。基于WEB的应用程序由前端用户界面和后端数据库和服务器组成。基于WEB的应用程序可以通过任何设备上的任何网络浏览器访问。

<div STYLE="page-break-after: always;"></div>

## 3. Specific Requirement

### 3.1 Agile Development and Requirement Analysis

- Persona

  The Shared Garden project aims to convert unutilized and abandoned land on campus into shared gardens that are constructed and designed by all students. As part of the exploration of system functions, this document outlines several user personas based on different personality traits, living environments, and values.

  共享花园项目的目的是将校园上未被使用和废弃的土地转变为由所有学生共同建设设计的共享花园。作为探索系统功能的一部分，本文档根据不同的个性特征、生活环境和价值观概括了几个用户角色。

  

  |  Name   |     Age      |          Gender          |        Occupation        |                Personality Traits and values                 |        How the Shared Garden Project can help him/Her        |
  | :-----: | :----------: | :----------------------: | :----------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
  | Li Ming | 20 years old |           Male           |         Student          |    Concerned about environmental protection, loves nature    | As an Environmental Science major who is concerned about environmental protection, Li Ming believes that the Shared Garden Project can provide a beautiful campus landscape and promote sustainable living practices like vegetable planting. |
  | Li Fang | 35 years old |          Female          |    University Teacher    | Patient, knowledgeable,Prioritizes education and lifelong learning | As a university teacher, Emily understands the importance of continuous education and lifelong learning.  An online course platform that offers flexible schedules and a variety of courses can help her continue her education more easily and efficiently. |
  | Li Hua  | 45 years old | University Administrator | University Administrator | Organized, efficient,Prioritizes student success and academic excellence | As a university administrator responsible for managing multiple departments and staff, David needs to be organized and efficient in his daily work.  An appointment scheduling system that automates this process can help him save time and streamline his workflow. |

  

  姓名：李明

  年龄：20岁

  性别：男

  专业：环境科学

  个性特征：注重环保，热爱大自然

  共享花园项目对他的帮助：

  作为一个关注环保的环境科学专业学生，李明非常关注校园环境建设和可持续发展问题。他认为共享花园项目不仅能够提供一个美丽的校园景观，还能够通过种植蔬菜等方式促进可持续生活方式的实践。此外，参与到共享花园项目中，李明可以结识更多志同道合的朋友，在团队协作中提升自己的沟通和组织能力。因此，共享花园项目对于他来说既是一个实践环保理念的机会，又是一个开阔眼界、拓展社交圈的平台。

  

- User Story

  By summarizing and analyzing different personas and empathy maps, we have learned a lot about the expectations and needs of many various users for our system, and displayed the user needs through user stories.

  通过总结和分析不同的人物角色和共情地图，我们了解了许多用户对我们系统的期望和需求，并通过用户故事展示了用户需求。

  

  | As a...               | I want...                                                    | So that...                                                   |
  | --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | college student       | I want to learn about sustainable practices through hands-on activities in the campus garden. | so that I can apply these practices in my daily life and future career. |
  | college student       | I want to contribute to the beautification of the campus by planting flowers and maintaining the garden. | so that the campus becomes a more pleasant and welcoming environment for everyone. |
  | freshman              | I want to feel welcomed into the campus community by meeting other students who share my passion for gardening. | so that I can make new friends and establish connections with like-minded peers. |
  | Environmentalist      | I want to advocate for sustainable practices and raise awareness about environmental issues through the shared garden project. | so that more people become aware of and take action on important environmental issues. |
  | college administrator | I want to ensure that the shared garden project is accessible and inclusive to all students, regardless of their background or experience level. | so that every student has an opportunity to participate and benefit from the project. |
  | teacher               | I hope to introduce more hands-on and experiential learning in the classroom through participation in the shared garden project. | so that my students can better understand real-world applications of the concepts we cover in class. |
  |                       |                                                              |                                                              |

  作为一名大学生：

  - 我希望通过参与校园花园的亲手实践活动了解可持续性实践。
  - 我想通过种植花卉和维护花园来为美化校园做出贡献。

  作为新生：

  - 我希望通过结识其他和我有相同兴趣和梦想的学生，感受到被欢迎进入校园社区。

  作为环境主义者：

  - 我希望通过共享花园项目倡导可持续实践，提高环境意识。

  作为大学管理者：

  - 我希望确保共享花园项目对所有学生都是无障碍和包容的，不论他们的背景或经验水平如何。

  作为一个老师：

  - 我希望通过共享花园项目在课堂上引入更多的实践和体验式学习。

  

- Product Backlog

  | User Account Management                                      | Garden Design and Planning                                   | Resource Sharing                                             | Community Engagement                                         | Feedback and Rating System                                   |                         Gamification                         |
  | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------: |
  | Allow users to create and manage their accounts, including user profiles, preferences, and security settings. | Provide tools for users to design and plan their garden spaces, including features such as plant selection, layout, and irrigation. | Create a platform for users to share resources (e.g. gardening tools, seeds, compost) with each other. | Develop features that encourage community engagement and collaboration, such as events, forums, and social sharing. | Implement a system for users to provide feedback and ratings on the gardens and resources in the platform. | Add gamification elements to incentivize user participation and engagement, such as achievements, badges, and leaderboards. |

- Theme

   The theme of this product is "Transforming Campus Landscapes". The overall goal is to encourage students to come together and create shared green spaces on campus using unused or abandoned land.

- Epic:

  One epic could be "Garden Creation and Management", which would include features such as designing and planning a garden plot, selecting plants, managing water and nutrients, and tracking progress over time. This epic could also involve sub-epics such as "Plant Database and Information" and "Irrigation and Water Management".

  Product Backlog（产品特性列表）：

  1. 用户账户管理：允许用户创建和管理他们的账户，包括用户个人资料、偏好设置和安全设置。
  2. 花园设计和规划：提供工具让用户设计和规划自己的花园空间，包括植物选择、布局和灌溉等功能。
  3. 资源共享：创建一个平台，让用户彼此之间分享资源（例如园艺工具、种子、堆肥）。
  4. 社区参与：开发鼓励社区参与和协作的功能，比如活动、论坛和社交分享等。
  5. 反馈和评级系统：实现一个系统，让用户对平台上的花园和资源进行反馈和评级。
  6. 游戏化：添加游戏化元素，以激励用户参与和互动，例如成就、徽章和排行榜。

  Theme（主题）： 本产品的主题是“校园景观转型”。总体目标是鼓励学生们聚集在一起，利用未被使用或废弃的土地，在校园上创造共享的绿色空间。

  Epic（史诗）： 其中一个史诗可以是“花园创建和管理”，包括设计和规划花园、选择植物、管理水和营养、并随时间跟踪进度等功能。该史诗还可能涉及子史诗，例如“植物数据库和信息”和“灌溉和水管理”。

### 3.2 Actors

This system supports two types of user access: students from the school and management staff from the campus administration department.

- Student
  Students from the school can register and log in to their accounts in this system, apply for creating, modifying, maintaining, or removing gardens, browse relevant information about various gardens, rate and comment on them, interact in forums, apply for volunteer positions, and also report inappropriate content.

- Campus Administration
  The campus management department can process the applications from students for creating, modifying, maintaining, or removing gardens, as well as post volunteer recruitment information, give activity points to garden contributors, review and remove inappropriate content that has been reported.

本系统支持两种用户的访问，一种是学校里的学生，一种是校园管理部门的管理人员。

- 学校里的学生可以在本系统中注册、登陆账号，申请创建、修改、维护或铲除花园，浏览各个花园相关信息并打分与评论，在论坛中互动，应聘志愿者，同时也能举报不良内容等。

- 校园管理部门可以处理学生创建、修改、维护或铲除花园的申请，同时也能发布志愿者招募信息，给予花园贡献者活动积分，审核并删除被举报不良内容等。

### 3.3 Use Case Modeling



1. Global View on Use Case

   ​		![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/System_Overview.png)

2. Login&Register System
   ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Register&Login_System.png)
   
   | USE CASE         | REGISTER                                                     | LOGIN                                                        |
   | :--------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
   | Actor            | Student                                                      | Student                                                      |
   | Preconditions    | The user has accessed the registration page                  | The user has accessed the login page                         |
   | Postconditions   | The user successfully registers and is automatically redirected to the login page | The user successfully logs in and enters the system homepage |
   | Main Flow        | 1.The user enters their username, password, and other necessary information<br/>2. The system verifies the user and input information<br/>3. The user clicks the registration button<br/>4. The user successfully registers | 1.The user enters their username and password<br/>2. The system verifies the user information<br/>3. The user successfully logs in and enters the system homepage |
   | Alternative Flow | 1. The input information is invalid, and the user is prompted to modify it<br/>2. The username is already registered, and the user is prompted to re-enter the information | 1. The username or password is incorrect, and the user is prompted to re-enter the information<br/>2. The user enters incorrect information multiple times, and the system locks the account |
   | Exception Flow   | 1. The user has not entered required fields, and is prompted to enter them<br/>2. The user has entered an invalid email or phone number, and is prompted to re-enter | N/A                                                          |
   |                  |                                                              |                                                              |


3. Forum System
   ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Forum_System.png)
   
   | USE CASE         | View Forum Page                                                     |Forum Interaction                                                        |
   | :--------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
   | Actor            | Student                                                      | Student                                                      |
   | Preconditions    |The student has a valid account.|The student has a valid account and has successfully logged in to the forum interface|
   | Postconditions   | N/A|1. The student successfully leaves a message under their own or others' posts<br/>2. The student successfully publishes their own post<br/>3. The student successfully likes other posts or messages<br/>|
   | Main Flow        | 1. The student enters the main interface of the system and logs in<br/>2. The student browses the forum<br/>2.1. The student can scroll through the interface to browse the keywords of different posts<br/>2.2. The student can select a post of interest and click to enter<br/>2.3. The student can choose to block posts that are not of interest<br/>| 1. The student enters the message or post publishing box<br/>1.1. The student enters the comment area of the post and clicks on the comment box<br/>1.2. The student clicks on the plus sign in the upper right corner of the system interface to enter the post publishing box<br/>2. The system checks the validity of the student's account, and if passed, the student can edit the content of the message or post<br/>3. Click OK to publish the message or post<br/>4. Like their own or others' messages or posts|
   | Alternative Flow | 1. The student enters the forum but finds no posts of interest and exits the forum directly<br/>2. The student selects to switch accounts while browsing| 1. After entering the message or post publishing box, the student exits directly without publishing any content<br/>2. After editing the content in the post or message publishing box, the student exits the publishing box directly without publishing the content, and the system will automatically save the draft<br/>3. The student likes and then unlikes|
   | Exception Flow   | 1. The student selects to log in to the account repeatedly, and the system will prompt a failure<br/>2. The student selects to pull down the interface after the content has been browsed, and the system will prompt that there is no more content|1. The student posts or comments too frequently in a short period of time, and the system will consider it as suspected spam and restrict the posting or commenting for a certain period of time<br/>2. The student's post or comment has been successfully reported multiple times for illegal reasons, and their account will be locked and unable to post or comment normally<br/>3. The student's post or comment has been successfully reported and deleted<br/>|   
   
     | USE CASE         | Report Inappropriate Comments or Posts   | Limit Permission |
   | :--------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
   | Actor            | Student                                                      | Campus Administration                                                 |
   | Preconditions    | The student has a valid account and has successfully logged in to the forum interface                  | Campus administration receives reports from students regarding posts or comments   |
   | Postconditions   |1. The student successfully reports illegal posts or comments, and the corresponding posts or comments are deleted<br/>2. The student's report is unsuccessful<br/>3. The user whose post or comment was reported has violated the rules multiple times, and their account has been temporarily blocked<br/>| The permission for students to post, comment, or report will be locked for a period of time|
   | Main Flow        | 1. The student views a post or comment and discovers that it contains inappropriate content<br/>2. The student clicks "report" on the corresponding post or comment, fills in the reason for the report, and submits it<br/>3. The system reviews the reported post or comment<br/>3.1. If the post or comment violates forum rules, it will be deleted and the reporter will be notified<br/>3.2. If the post or comment does not violate forum rules, it will be referred to the campus administration for review. If it is found to be in violation, it will be deleted; if not, nothing will happen<br/>4. If the report is successful, the user whose post or comment was reported will have a record of their violation<br/>5. If the user whose post or comment was reported has multiple violations, their account will be blocked for a period of time, during which they cannot post or comment<br/> | 1. Campus administration receives reports from students regarding posts or comments<br/>2. Campus administration checks the reported content<br/>3. Implement corresponding permission restriction measures based on the truthfulness of the report<br/>3.1. If the reported user has posted inappropriate content multiple times in a short period, their permission to post or comment will be locked for a period of time<br/>3.2. If the reporter submits invalid or false reports multiple times, it will be considered as malicious reporting. In this case, the system will limit the user's reporting permission for a period of time<br/>4. Notify the user of the restricted permission<br/>|
   | Alternative Flow | 1. If the student submits a report and wishes to retract it before it has been reviewed by the system or campus administration, they may do so<br/>2. The student can check the progress of their report| 1. After restricting the user's relevant permission, it can be revoked depending on the situation<br/>2. If the report is invalid and the reporter does not constitute malicious reporting, the campus administration will not limit the user's relevant permission|
   | Exception Flow   | 1. If the student clicks "report" without filling in the reason, the report will not be submitted<br/>2. If the student submits multiple invalid reports within a short period of time, their reporting privileges will be restricted for a period of time| If the user is reported again during the period of restricted posting or commenting permission, the campus administration will not be able to restrict their permission again                                                      |


4. Maintainence System
   ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Garden_Maintenance_System.png)

   | USE CASE         | Submit garden information                             | Join Volunteer Even                                                        |Recruit volunteer |
   | :--------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
   | Actor            | Student                                                      | Student                                                      |campus administration|
   | Preconditions    | Students apply to submit information related to garden maintenance.           | Campus administration has published a volunteer recruitment information related to garden maintenance                     |The campus administration has decided to support the student's application as the submitted garden maintenance-related information is reasonable|
   | Postconditions   | The school publishes voluntary activities related to garden maintenance.| Successfully participate in volunteer events and obtain activity points|Volunteers who participate in the garden maintenance and upkeep activity receive corresponding activity points|
   | Main Flow        | 1. Students fill in the information related to the garden's current aging, deficiencies, or the need for additional flower pots and submit it<br/>2. Campus administration checks the garden-related information submitted by the student<br/>3. Campus administration publishes a volunteer recruitment activity for students to participate in garden maintenance based on the needs provided by the student<br/>4. The user successfully registers | 1. Students browse volunteer recruitment information on the system interface and select volunteer activities of interest<br/>2. Students fill in personal information and submit<br/>3. The system automatically checks the student's personal information and permissions, that is, whether it is suitable for participating in volunteer activities<br/>4. The system authorizes the student to become a member of the corresponding volunteer activity and participate in garden maintenance<br/>5. Campus administration checks the volunteer service output of students participating in garden maintenance and rewards activity points according to their service output<br/>|1. The campus administration publishes volunteer recruitment information for the garden maintenance and upkeep activity<br/>2. Students sign up for the volunteer activity and begin working<br/>3. The campus administration checks the completion status of the volunteer's work and awards corresponding activity points to the volunteers<br/>|
   | Alternative Flow | Students do not submit immediately after filling out the relevant information, and the system automatically saves the draft<br/>|  After becoming a member of a volunteer activity, students apply to withdraw from the activity, and the system approves it<br/>|1. If the garden maintenance and upkeep workload is small and the applicant is willing to complete the work on their own, the campus administration does not need to recruit additional volunteers<br/>2. If an applicant withdraws their garden maintenance and upkeep application midway, the campus administration can abandon the volunteer recruitment information<br/>|
   | Exception Flow   | Campus administration finds that the garden-related information submitted by the student is untrue and does not release relevant volunteer recruitment information<br/>| 1. Students participate in volunteer activities but refuse to work, which has no effect on garden maintenance. Campus administration will not award points and record one misconduct<br/>2. After students fill in personal information, the system finds that they have short-term past bad records and will not authorize them to participate in volunteer activities                        |1. If volunteer information is published but there are not enough people willing to serve as volunteers, the garden maintenance and upkeep plan may fail<br/>2. If the volunteers handle the work improperly, the garden maintenance and upkeep plan may also fail<br/>   |       


5. Visit System
   ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Visit_System.png)
   
      | USE CASE         |Score and Comment the Garden          |Report inappropriate Comments or Garden                              |
   | :--------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
   | Actor            | Student                                                      | Student                                                      |
   | Preconditions    | Students enter the garden access system and browse the relevant information of various gardens      |Students enter the garden access system and browse the relevant information of various gardens and their comment areas                |
   | Postconditions   | Students successfully score or leave comments on the garden| 1. Inappropriate comments are deleted<br/>2. Inappropriate garden configurations are rectified<br/>|
   | Main Flow        | 1. Students click on the garden they are interested in and view its related display information<br/>2. Students score or leave comments<br/>2.1. Students score, and if the total score of the corresponding garden is high enough, the main contributors to the garden's past creation and maintenance will be rewarded with a certain amount of activity points<br/>2.2. Students leave comments, and the system checks the user's permission to decide whether to allow the comment<br/>| 1. Students click on the homepage of the garden they are interested in and view its information and comment area<br/>2. Identify inappropriate garden configurations or comments, and fill out a report<br/>3. The system or campus administration handles the report<br/>3.1. If inappropriate comments are reported, the system first checks whether the comments violate the rules. If they do, the comments are automatically deleted. If not, the report is forwarded to the campus administration for review and decision-making<br/>3.2. If inappropriate garden configurations are reported, the relevant report information is sent directly to the campus administration. Once the information is verified, the administration will issue an order to rectify the inappropriate configurations<br/> |
   | Alternative Flow | Students simply browse garden information without scoring or commenting| 1. Students can choose to withdraw the report while the report information is being processed<br/>2. Students can view the review progress of the report information|
   | Exception Flow   | 1. Students enter an invalid score (exceeding the upper and lower limits), and the system prompts an error<br/>2. Students have a large number of recent misconduct records (such as multiple successful reports of their comments), and the system disables their permission to leave comments| Students make multiple invalid and groundless reports in a short period, and the system will restrict their report permission for a certain period                  |


6. Create&Modify System

   ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Garden_Create&Modify&Dismiss_System.png)
   | USE CASE         | Create or Modify or Remove a Garden               | Check Completion Status                                                        |
   | :--------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
   | Actor            | Student                                                      | campus administration                                 |
   | Preconditions    | The student applies to create, modify, or remove a garden           | The student's garden creation/modification/removal request is reasonable, and the campus administration has decided to support the student's application                      |
   | Postconditions   | The garden is successfully created, modified, or removed | Volunteers who participated in the garden creation/modification/removal activities received corresponding activity points rewards |
   | Main Flow        | 1. The student enters the garden creation, modification, or removal page, fills in and submits the reasons and relevant information<br/>2. The campus administration reviews the applicant's personal information and garden-related information<br/>3. If the review is passed, the campus administration publishes a volunteer recruitment information to create, modify, or remove the garden<br/> | 1. The campus administration publishes a volunteer recruitment information for the creation/modification/removal of gardens<br/>2. The student signs up for the volunteer activity and starts working<br/>3. The campus administration checks the completion status of the volunteers and awards them corresponding activity points accordingly |
   | Alternative Flow | 1. After submitting the application information, the student can withdraw the application before the campus administration executes it<br/>2. If the garden information submitted by the student and the reasons for creating, modifying, or removing the garden are not sufficient, the campus administration will reject the student's application and will not publish the volunteer recruitment information | 1. If the garden creation/modification/removal workload is not large and the applicant is willing to do it on their own, the campus administration does not need to recruit additional volunteers<br/>2. If the applicant withdraws the garden creation/modification/removal application in the middle, the campus administration abandons the recruitment information |
   | Exception Flow   | 1. If the volunteer information is published, but not enough people are willing to come and be volunteers, the garden creation, modification, or removal plan may fail<br/>2. If the volunteer's operation is improper, the garden creation, modification, or removal plan may fail| 1. If the volunteer information is published, but not enough people are willing to come and be volunteers, the garden creation, modification, or removal plan may fail<br/>2.  If the volunteer's operation is improper, the garden creation/modification/removal plan may fail     |


### 3.4 Activity Diagrams
1. Register

  ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Rgister.png)

  Students submit registration applications, fill in personal information, and submit them. Then, the application sends a verification code. The system checks the personal information filled in by the applicant. If it is illegal, the system requires the applicant to fill in the information again. If it is legal, the system sends a verification code. After receiving the verification code, the applicant enters it immediately. The system checks the verification code. If it is verified successfully, the system authorizes the applicant, and the applicant officially obtains an account. If the verification fails, the user is asked to reapply for the verification code. Note that each verification code sent by the system will expire after 2 minutes. The user must enter the verification code during this period, otherwise, the user must reapply for the verification code. Users can abandon the registration application at any time while filling in personal information or waiting for verification.

  学生提交注册申请，然后填写个人信息并提交，接着申请发送验证码。系统会随之检查申请者填写的个人信息，若是非法则会要求重新填写，若是合法则会发送验证码。申请者在收到验证码后，立即输入验证码，系统检查验证码，若是验证成功则给申请者授权，申请者正式得到一个账号，若是验证失败则要求用户重新申请验证码。注意每次系统向用户发送的验证码将于2分钟后过期，用户必须在此期间输入验证码，否则必须重新申请验证码。用户在填写个人信息或等待验证码的过程中可以随时放弃申请注册。

2. Login

  ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Login.png)

  Students enter the login interface, click to login, fill in the account ID and password, and the system checks the ID and password. If it is illegal, the system requires the user to fill in the information again. If it is legal, the user is allowed to log in, and the user enters the system main interface and successfully logs in. While filling in the ID and password, users can choose to abandon the login at any time.

  学生进入登陆界面，点击登陆并填写账号ID与密码，系统将检查ID与密码，若是非法则会要求用户重填，若是合法则会允许用户登陆，用户进入系统主界面，成功登陆。在填写ID与密码时，用户可以随时选择放弃登陆。

3. Comments in Forum

  ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Comment_in_Forum.png)

  Students click to enter the forum comment box, and the system checks the user's comment permission. If it does not pass, the user is refused to post a comment. If it passes, the user is allowed to post a comment. After the user posts a comment, the system will also check the content of the comment. If it violates the rules, the comment will be deleted. Otherwise, the comment is successfully published.

  学生点击进入论坛评论框，系统将检查用户的评论权限，若是不通过则拒绝用户发布评论，若是通过则允许用户发布评论。用户发布评论后，系统还将检查用户评论的内容，若是违规则删除评论，否则评论发布成功。

4. Score the Garden

  ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Score_Garden.png)

  Students enter the garden access interface, browse the information of various gardens, and score the gardens. After scoring, the system will check the average score of the garden. If it is high enough, the system will give corresponding activity points to the main contributors of the garden.

  学生进入花园访问界面，浏览各个花园的信息，并对花园进行打分。打分后，系统将查看花园得到的平均分，若是足够高则将对花园主要贡献者给予相应活动积分。

5. Report Inappropriate Comments

  ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Report Inappropriate Comments for the Garden.png)

  Students enter the garden access interface or the comment area of the forum and browse the content of the comment area. If they find any inappropriate comments and report them, the system will first check the reporting user's reporting permission. If it passes, the system will check whether the comment content violates the rules. If it violates the rules, the comment will be deleted. If it does not violate the rules, the comment will be handed over to the campus administration for review. If the campus administration finds the comment content to be inappropriate, the comment will be deleted. If it is not inappropriate, the comment content will be preserved. Once the comment content is deleted, the reporter will be informed that the report was successful.

  学生进入花园访问界面或者论坛的评论区，并浏览评论区内容。若是发现违规评论且将其举报，则系统将先检查举报者的举报权限，若是检查通过则系统将查看评论内容是否违规，若是违规则删除评论，若是不违规则将评论交由校园管理部门检查，若是校园管理部门检查评论内容违规则将评论删除，若是不违规则保存评论内容。一旦评论内容被删除，则举报者将被告知举报成功。

6. Create a New Garden

  ![](/Users/guolianglu/Desktop/courses/System/Assignment1/img/Create a new garden.png)

  Students enter the system interface, click to apply to create a new garden, and fill in garden information. The system checks the data format of the filled-in information. If it is not standardized, the applicant is required to fill in the information again. If it is standardized, the campus administration reviews the information for creating a new garden. If the campus administration finds the information to be unreasonable, the application will be rejected. If it is considered reasonable, the campus administration authorizes the applicant to fill in volunteer recruitment information and the system publishes the information to recruit volunteers to participate in creating a new shared garden. The campus administration also checks the completion status of the volunteer applicants and calculates the activity points based on their work effectiveness, which are rewarded to the volunteers.

  学生进入系统界面后，点击申请创建一个新的花园，然后填写花园信息，系统会查看填写的信息的数据格式，若是不规范则申请者重新填写，若是规范则交由校园管理部门审核创建新花园的信息。若是校园管理部门人为创建新花园的信息不合理则拒绝申请，若是觉得合理则授权申请者填写志愿者招募信息，并由系统发布信息以招募志愿者参与创建新的共享花园。校园管理部门还会查看报名参与的志愿者的工作完成情况，并视其工作效果计算出活动积分，奖励给志愿者。




<div STYLE="page-break-after: always;"></div>

## 4. Supplementary Specification

This section describes the functional and non-functional requirements that are not captured by the use case model. It also specifies the design constraints and assumptions that affect the system development. The supplementary specification complements the use case model by providing additional details and clarifications for the system requirements.

本节描述了用例模型未能捕捉到的功能性和非功能性需求。它还指定了影响系统开发的设计约束和假设。补充规范通过提供系统需求的额外细节和澄清，补充了用例模型。

### 4.1 Functional Requirements

This section lists the functional requirements that describe the system behavior and functionality. The functional requirements are derived from the use cases and the project scope. They are categorized by the main features of the system.

#### 4.1.1 Shared Garden Toolkit

- The system shall provide a web-based interface for students to design and build their own shared gardens on campus.
- The system shall allow students to select a location, size, shape, and layout for their - shared gardens.
- The system shall provide a database of plants and flowers that students can choose from to populate their shared gardens.
- The system shall provide information and guidance on how to plant and care for the plants and flowers in the shared gardens.
- The system shall allow students to save, edit, and share their shared garden designs with other students and the campus administration.
- The system shall calculate and display the environmental benefits of each shared garden, such as carbon dioxide reduction, oxygen production, and water conservation.
- The system shall award credits and rewards to students based on their participation and contribution to the shared garden project.

#### 4.1.2 Shared Garden Community

- The system shall provide a web-based platform for students to communicate and collaborate with other students who are involved in the shared garden project.
- The system shall allow students to create and join groups based on their interests, preferences, and goals related to the shared garden project.
- The system shall allow students to post messages, photos, videos, and feedback on their shared gardens and other shared gardens on campus.
- The system shall allow students to rate and review other shared gardens on campus based on various criteria, such as aesthetics, diversity, sustainability, and creativity.
- The system shall provide a leaderboard that ranks the shared gardens on campus based on their ratings, reviews, and environmental benefits.

本节列出了描述系统行为和功能的功能性需求。功能性需求是根据用例和项目范围推导出来的。它们按照系统的主要功能进行分类。

4.1.1 共享花园工具包

- 系统应提供一个基于 Web 的界面，让学生可以在校园内设计和建造自己的共享花园。
- 系统应允许学生选择共享花园的位置、大小、形状和布局。
- 系统应提供一个植物和花卉的数据库，让学生可以从中选择适合自己共享花园的植物和花卉。
- 系统应提供有关如何种植和照料共享花园中的植物和花卉的信息和指导。
- 系统应允许学生保存、编辑和分享他们的共享花园设计，与其他学生和校园管理部门进行交流。
- 系统应计算并显示每个共享花园的环境效益，如二氧化碳减排、氧气产生和水资源节约。
- 系统应根据学生对共享花园项目的参与和贡献，给予学生积分和奖励。

4.1.2 共享花园社区

- 系统应提供一个基于 Web 的平台，让学生可以与参与共享花园项目的其他学生进行沟通和协作。
- 系统应允许学生根据他们对共享花园项目的兴趣、偏好和目标，创建和加入不同的小组。
- 系统应允许学生在平台上发布关于他们自己或其他校园内共享花园的消息、照片、视频和反馈。
- 系统应允许学生根据不同的标准，如美观、多样性、可持续性和创意，对校园内的其他共享花园进行评价和评论。
- 系统应提供一个排行榜，根据共享花园的评分、评论和环境效益，对校园内的共享花园排名。

### 4.2 Non-Functional Requirements

This section lists the non-functional requirements that describe the system quality and performance. The non-functional requirements are derived from the project scope and the stakeholder expectations. They are categorized by the main attributes of the system.

#### 4.2.1 Usability

- The system shall provide a user-friendly and intuitive interface that is easy to navigate and operate.
- The system shall provide clear and consistent instructions, labels, and feedback to the users.
- The system shall provide help and documentation features that explain the system functionality and usage.
- The system shall support multiple languages, including English and Chinese.

#### 4.2.2 Reliability

- The system shall ensure the accuracy and completeness of the data stored and displayed.
- The system shall prevent unauthorized access and modification of the data.
- The system shall handle errors and exceptions gracefully and provide appropriate error messages to the users.
- The system shall recover from failures and resume normal operation as soon as possible.

#### 4.2.3 Efficiency

- The system shall respond to user requests within a reasonable time frame.
- The system shall optimize the use of network bandwidth and server resources.
- The system shall support concurrent access by multiple users without compromising the system performance or functionality.

#### 4.2.4 Maintainability

- The system shall be modular and well-documented to facilitate future changes and enhancements.
- The system shall follow coding standards and best practices to ensure the readability and consistency of the code.
- The system shall use open-source technologies and frameworks to reduce the dependency on proprietary software.

本节列出了描述系统质量和性能的非功能性需求。非功能性需求是根据项目范围和利益相关者的期望推导出来的。它们按照系统的主要属性进行分类。

4.2.1 可用性

- 系统应提供一个用户友好和直观的界面，易于导航和操作。
- 系统应提供清晰和一致的指示、标签和反馈给用户。
- 系统应提供帮助和文档功能，解释系统的功能和使用方法。
- 系统应支持多种语言，包括英语和中文。

4.2.2 可靠性

- 系统应确保存储和显示的数据的准确性和完整性。
- 系统应防止未经授权的访问和修改数据。
- 系统应优雅地处理错误和异常，并向用户提供适当的错误信息。
- 系统应能从故障中恢复，并尽快恢复正常运行。

4.2.3 效率

- 系统应在合理的时间范围内响应用户请求。
- 系统应优化网络带宽和服务器资源的使用。
- 系统应支持多个用户同时访问，而不影响系统的性能或功能。

4.2.4 可维护性

- 系统应是模块化和有良好文档的，以便于未来的变更和增强。
- 系统应遵循编码标准和最佳实践，以确保代码的可读性和一致性。
- 系统应使用开源技术和框架，以减少对专有软件的依赖。

### 4.3 Design Constraints and Assumptions

This section describes the design constraints and assumptions that affect the system development and operation.

- The system supports cross-platform deployment, including client-side, web-based, mobile, and WeChat mini-program applications. The system should be compatible with different operating systems, browsers, and devices.
- The system uses Oracle as the database technology for storing and retrieving the data of the system. The system should comply with the Oracle database standards and specifications.
- The system uses HTML, CSS, JavaScript, and Vue as the front-end technologies for developing the user interface of the system. The system should follow the best practices and guidelines of web development and design.

本节描述了影响系统开发和运行的设计约束和假设。

- 系统支持跨平台部署，包括客户端、Web端、移动端和微信小程序端应用。系统应该与不同的操作系统、浏览器和设备兼容。
- 系统使用Oracle作为数据库技术，用于存储和检索系统的数据。系统应该遵守Oracle数据库的标准和规范。
- 系统使用HTML、CSS、JavaScript和Vue作为前端技术，用于开发系统的用户界面。系统应该遵循Web开发和设计的最佳实践和指南。

<div STYLE="page-break-after: always;"></div>

## 5. List of References

This section lists some of the references that can be used for further information and guidance on the software requirements specification.

[1] Built In. (2022). What Is a Software Requirement Specification? Retrieved from https://builtin.com/software-engineering-perspectives/software-requirement-specification

This article provides an overview of what a software requirement specification is, why it is important, and what it should include. It also gives some tips and best practices for writing an effective SRS document.

[2] Enou. (2022). Best Guide on Software Requirements Specification 2023. Retrieved from https://enou.co/blog/software-requirements-specification/

This guide explains the purpose, benefits, and challenges of software requirements specification. It also provides a detailed outline of the SRS document structure and content, as well as some examples and templates.

[3] Perforce. (n.d.). How to Write a Software Requirements Specification (SRS). Retrieved from https://www.perforce.com/blog/alm/how-write-software-requirements-specification-srs-document

This blog post describes how to write a software requirements specification document that meets the needs of all stakeholders. It also covers the key elements and characteristics of an SRS document, as well as some common mistakes to avoid.

[4] Asana. (n.d.). How to write a software requirement document (with template). Retrieved from https://asana.com/resources/software-requirement-document-template

This resource offers a step-by-step guide on how to write a software requirement document that captures the scope, goals, and functionality of the project. It also provides a free template that can be customized and used for any software project.

本节列出了一些可以用于进一步了解和指导软件需求规格的参考文献。

Built In. (2022). 什么是软件需求规格？从 https://builtin.com/software-engineering-perspectives/software-requirement-specification 获取
这篇文章概述了什么是软件需求规格，它为什么重要，以及它应该包含什么。它还给出了一些编写有效SRS文档的提示和最佳实践。

Enou. (2022). 2023年软件需求规格最佳指南。从 https://enou.co/blog/software-requirements-specification/ 获取
这份指南解释了软件需求规格的目的、好处和挑战。它还提供了一个详细的SRS文档结构和内容的大纲，以及一些示例和模板。

Perforce. (n.d.). 如何编写软件需求规格（SRS）。从 https://www.perforce.com/blog/alm/how-write-software-requirements-specification-srs-document 获取
这篇博客文章描述了如何编写一个满足所有利益相关者需求的软件需求规格文档。它还涵盖了SRS文档的关键要素和特征，以及一些常见的错误要避免。

Asana. (n.d.). 如何编写软件需求文档（附模板）。从 https://asana.com/resources/software-requirement-document-template 获取
这个资源提供了一个如何编写软件需求文档的步骤指南，该文档捕捉了项目的范围、目标和功能。它还提供了一个免费的模板，可以根据任何软件项目进行定制和使用。

<div STYLE="page-break-after: always;"></div>

## 6.Contributions

This project is the result of multiple discussions, revisions, additions, and refinements by two team members. Both members actively participated in the project and took on tasks in each section. We collaborated effectively and contributed to the quality and completeness of the project. The division of labor within the group was average and clear, as follows:

这个项目是两位小组成员经过多次讨论、修改、补充和完善得到的。两位成员都积极参与了项目，并在每个部分都承担了任务。我们有效地合作，为项目的质量和完整性做出了贡献。任务分配平均而清晰，如下所示：

|Student Number|Name|Score Weight|
|---|---|---|
|2050633|Jialin Lu|100%|
|2053711|Jie Chu|100%|