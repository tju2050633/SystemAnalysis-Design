


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

### 1.5 Document Structure

This document is divided into six chapters and two appendices, as follows:

Chapter 1: Introduction
This chapter provides an overview of the project, including its purpose, background, and scope. It also includes information on the intended audience for this document.

Chapter 2: Glossary of Terms
This chapter defines key terms and concepts that are used throughout this document.

Chapter 3: System Architecture Design
This chapter provides an overview of the system architecture design. It includes a high-level description of the system components, their interactions, and their relationships.

Chapter 4: Analysis Model
This chapter provides a detailed analysis of the system requirements. It includes use case models, activity diagrams, and other relevant information.

Chapter 5: Updated Use Case Model
This chapter presents the updated use case model based on the revised requirements.

Chapter 6: System Snapshots
This chapter includes screenshots of the system in use, illustrating its key features and functionality.

Appendix A: List of References
This appendix lists the sources used in the creation of this document.

Appendix B: Contributions
This appendix acknowledges the contributions of the individuals involved in the creation of this document.

Compared to the previous version of the SRS document, this revised version includes the following additions and modifications:

- The document structure has been revised to include new chapters on Architecture Design and Analysis Model.
- The Glossary of Terms chapter has been retained from the previous version.
- The Introduction chapter has been revised to provide more detailed information about the project, its background, and purpose.
- The Actors chapter has been retained from the previous version.
- The Use Case Modeling chapter has been updated to reflect changes in the system's functionality and requirements.
- A new chapter on System Snapshots has been added to provide visual representations of the system's user interface and functionality.

These changes were made to provide a more comprehensive understanding of the system's architecture and functionality, and to better align the SRS document with the needs and goals of the project stakeholders.

本文档分为六个章节和两个附录，具体如下：

第1章：介绍
本章概述项目的目的、背景和范围。还包括本文档的预期读者群体等信息。

第2章：术语表
本章定义本文档中使用的关键术语和概念。

第3章：系统架构设计
本章概述系统的架构设计。它包括系统组件、它们的交互和关系的高级描述。

第4章：分析模型
本章提供系统需求的详细分析。它包括用例模型、活动图和其他相关信息。

第5章：更新的用例模型
本章根据修订后的需求介绍了更新的用例模型。

第6章：系统快照
本章包括系统使用的截图，展示其主要功能和功能。

附录A：参考文献列表
本附录列出了本文档创建过程中使用的来源。

附录B：贡献者
本附录确认参与本文档创建的个人的贡献。

相对于上一份SRS文档，本次修订后的文档增添和修改了以下内容：

修订了文档结构，增加了Architecture Design和Analysis Model两个新章节。
Glossary of Terms章节保留不变。
Introduction章节进行了修订，提供了更详细的项目背景和目的信息。
Actors章节保留不变。
Use Case Modeling章节进行了更新，以反映系统功能和需求的变化。
新增了System Snapshots章节，以提供系统用户界面和功能的视觉表现。
这些修改和增添是为了提供对系统架构和功能的更全面的理解，并更好地满足项目利益相关者的需求和目标。

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

## 3. System Architecture Design



### 3.1 System Overview



### 3.2 Architecture Design Principles



### 3.3 System Components and Interactions



### 3.4 Physical Deployment




<div STYLE="page-break-after: always;"></div>

## 4. Analysis Model



### 4.1 Use Case Model



### 4.2 Activity Diagrams



### 4.3 Sequence Diagrams



### 4.4 Class Diagrams





<div STYLE="page-break-after: always;"></div>

## 5. Updated Use Case Model





<div STYLE="page-break-after: always;"></div>

## 6. System Snapshots





<div STYLE="page-break-after: always;"></div>

## 7. List of References

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

## 8.Contributions

This project is the result of multiple discussions, revisions, additions, and refinements by two team members. Both members actively participated in the project and took on tasks in each section. We collaborated effectively and contributed to the quality and completeness of the project. The division of labor within the group was average and clear, as follows:

这个项目是两位小组成员经过多次讨论、修改、补充和完善得到的。两位成员都积极参与了项目，并在每个部分都承担了任务。我们有效地合作，为项目的质量和完整性做出了贡献。任务分配平均而清晰，如下所示：

|Student Number|Name|Score Weight|
|---|---|---|
|2050633|Jialin Lu|100%|
|2053711|Jie Chu|100%|