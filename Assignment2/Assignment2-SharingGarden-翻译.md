


<center><font size=10 color=#1488CC>Content</font></center> 
[toc]

<div STYLE="page-break-after: always;"></div>

## 1.Introduction

### 1.1 Purpose

The Sharing Garden project is an initiative that responds to the national call for energy conservation and emission reduction, aiming to build a green and low-carbon campus. It actively promotes the development of a scientific, low-carbon, and efficient resource allocation model to adapt to the evolving landscape of higher education and contribute to ecological civilization. The main action of this project is to transform idle and abandoned land on the campus into shared gardens, designed and built by all students. The project aims to achieve the goal of participatory landscape design, where students can earn credits and rewards, such as potted plants, through their involvement. We will establish a web-based application that includes a toolkit for constructing shared gardens and a community platform for shared garden enthusiasts.

Furthermore, the purpose of this document is to provide a comprehensive and detailed description, outlining the requirements and specifications for a web-based application that supports students in creating and sharing campus garden projects. The web-based application aims to achieve the following objectives:

- Enhance students' learning experience and engagement in environmental education and sustainable development themes by enabling them to design, create, and share their own campus gardens.
- Foster students' creativity and collaboration skills by allowing them to explore and visit other campus gardens.
- Cultivate students' awareness and appreciation of the campus environment and biodiversity.
- Facilitate campus management departments in managing and assessing campus facilities and resources by providing data and feedback on campus gardens.

共享花园项目是响应国家节能减排号召的倡议，旨在建设绿色低碳校园。它积极促进科学、低碳、高效的资源配置模式的发展，以适应高等教育的发展形势，并推动生态文明建设。该项目的主要行动是将校园内的闲置废弃土地改造成共享花园，由所有学生参与设计和建造。这个项目旨在实现参与式景观设计的目标，学生可以通过参与获得积分和奖励，如花卉盆栽。我们将建立一个基于 WEB 的应用程序，其中包括建造共享花园的工具包和共享花园社区。

同时，本文档的目的是提供一个详细而全面的描述，说明支持学生创建和分享校园花园项目的基于WEB的应用程序的需求和规范。基于WEB的应用程序旨在实现以下目标：

- 通过让学生设计、创建和与其他学生分享自己的校园花园，提高学生在环境教育和可持续发展主题方面的学习体验和参与度。
- 通过让学生探索和参观其他校园花园，培养学生的创造力和协作能力。
- 通过让学生了解和欣赏校园环境和生物多样性，提高学生的意识和赞赏。
- 通过为校园管理部门提供有关校园花园的数据和反馈，方便校园管理部门对校园设施和资源的管理和评估。

### 1.2 Progress and Current Status

In the first document, we have already provided readers with a detailed description of the functionalities of Sharing Garden project, and this document covers the progress of analysis model and architectural analysis.

In this System Analysis Document, we have presented the project in terms of high-level architecture, detailed architectural decisions until current stage. We create the layer architecture diagram of the system and built the package diagram to illustrate the components of each layer.

We present analysis models, including class diagram, and interaction diagram. For class diagrams and interaction diagrams, they presents relationship and interactions between entity classes, boundary classes and control classes. We updated our system during analysis. Significant progress has been made in the development of various system components. 

在第一篇文档中，我们已经为读者提供了共享花园项目功能的详细描述，这篇文档涵盖了分析模型和架构分析的进展。

在这个系统分析文档中，我们已经根据高层次的体系结构，详细的体系结构决策介绍了这个项目，直到当前阶段。我们创建了系统的层架构图，并构建了包图来说明每层的组件。

给出了分析模型，包括序列图、类图和交互图。对于序列图，开发人员可以了解系统在每个用例中的工作方式。在类图方面，它描述了实体类、边界类和控制类之间的关系。我们在分析过程中更新了系统。各系统组件的开发取得了重大进展。



### 1.3 Changes in the System 

Throughout the system analysis process, we have identified several areas where enhancements and optimizations can be made:

- Simplifying the user experience by implementing intuitive and user-friendly interfaces, ensuring that users can easily navigate and interact with the Shared Garden platform.
- Refining the system's architecture by categorizing classes into three distinct parts: boundary classes, control classes, and entity classes. This clear separation improves the system's clarity, maintainability, and security.
- Introducing a new subsystem called the Garden Management System, which provides users with convenient tools for managing and organizing their garden-related activities. This subsystem enhances the overall functionality and completeness of the Shared Garden platform.
- Making necessary modifications to the use case diagram to accurately reflect the updated system components and user interactions.

These changes aim to streamline the user experience, enhance system reliability, and provide a comprehensive platform for garden enthusiasts. By addressing these areas of improvement, we strive to create a system that not only meets the immediate needs of users but also allows for future scalability and adaptability.

在系统分析的过程中，我们确定了几个需要进行改进和优化的方面：

- 通过实现直观和用户友好的界面，简化用户体验，确保用户可以轻松地浏览和与共享花园平台进行交互。
- 通过将类别划分为边界类、控制类和实体类，优化系统的架构。这种明确的划分提高了系统的清晰度、可维护性和安全性。
- 引入一个名为花园管理系统的新子系统，为用户提供方便的工具来管理和组织与花园相关的活动。该子系统增强了共享花园平台的整体功能和完整性。
- 对用例图进行必要的修改，准确反映更新后的系统组件和用户交互。

这些变更旨在简化用户体验、提高系统可靠性，并为花园爱好者提供一个全面的平台。通过解决这些改进方面，我们努力创建一个不仅满足用户当前需求，而且具有未来可扩展性和适应性的系统。

<div STYLE="page-break-after: always;"></div>

## 2. Architecture Decisions



The "Sharing Garden" project is a web-based application focused on facilitating the creation and sharing of campus gardens among students. In order to develop an effective and user-friendly platform, we need to carefully analyze and design the system architecture. Our primary considerations are providing rich and comprehensive functionality, ensuring the security and privacy of user information, and optimizing platform performance and availability for developers.

“共享花园”项目是一个基于网络的应用程序，旨在促进学生创建和共享校园花园。为了开发一个有效且用户友好的平台，我们需要仔细分析和设计系统架构。我们的主要考虑是提供丰富而全面的功能，确保用户信息的安全性和隐私性，以及为开发人员优化平台性能和可用性。

### 2.1 System Detailed Analysis

During the requirements phase, we extensively studied the interactions between various system components and external entities. We also conducted a preliminary analysis of the system using use cases. In the early stages of architecture design, we focused on defining the specific behavioral steps required to fulfill each use case. Subsequently, we broke down the system into smaller subsystems based on their functionalities and transformed the use cases into robust graphical representations.

![](系统细节分析图)

The system can be classified into several subsystems based on their specific functions, including the login and registration system, garden activity management system, garden club management system, member management system, forum system, and personal information maintenance system. Building upon this classification, we established a hierarchical structure for the system, taking into account responsibilities and generalizability, to further divide it into subsystems.

在需求阶段，我们广泛地研究了各种系统组件和外部实体之间的交互。我们还使用用例对系统进行了初步分析。在架构设计的早期阶段，我们专注于定义实现每个用例所需的特定行为步骤。随后，我们根据功能将系统分解为更小的子系统，并将用例转换为健壮的图形表示。

本系统根据其具体功能可分为登录注册系统、园林活动管理系统、园林俱乐部管理系统、会员管理系统、论坛系统、个人信息维护系统等几个子系统。在这个分类的基础上，我们为系统建立了一个层次结构，考虑到责任和可泛化性，进一步将其划分为子系统。

### 2.2 Hierarchical Architecture Design

For the architecture design of the "Sharing Garden" project, we have adopted the classic MVC (Model-View-Controller) three-tier architecture. This architecture provides a structured approach to separate the presentation layer (View) from the application logic (Controller) and the underlying data management (Model). By implementing the MVC pattern, we can achieve better modularity, maintainability, and scalability of the system.

![](MVC架构图)

At the presentation layer (View), we will focus on developing a user-friendly and intuitive web interface where users can interact with the system. This includes features such as designing and managing their gardens, exploring and visiting other gardens, participating in forums, and accessing personal information.

In the application logic layer (Controller), we will implement the necessary business logic to handle user actions and process data. This includes functionalities like managing garden activities, club membership, user authentication and authorization, and facilitating communication between users.

The underlying data management layer (Model) will handle the storage and retrieval of data related to gardens, users, activities, and other system entities. We will design a robust database schema and implement appropriate data access mechanisms to ensure data integrity and efficiency.

By adopting the MVC architecture, we can achieve a clear separation of concerns, enhance code reusability, and facilitate future enhancements and modifications to the system.

对于“共享花园”项目的架构设计，我们采用了经典的MVC（Model-View-Controller）三层架构。该架构能够有效地将展示层（视图）与应用逻辑（控制器）以及底层数据管理（模型）进行分离。通过实现MVC模式，我们能够实现系统的更好模块化、可维护性和可扩展性。

在展示层（视图）方面，我们将专注于开发一个用户友好且直观的Web界面，使用户能够与系统进行交互。这包括设计和管理自己的花园、探索和访问其他花园、参与论坛以及访问个人信息等功能。

在应用逻辑层（控制器）方面，我们将实现必要的业务逻辑，处理用户的操作和数据处理。这包括管理花园活动、俱乐部成员管理、用户身份验证和授权以及促进用户之间的交流等功能。

底层的数据管理层（模型）将负责处理与花园、用户、活动和其他系统实体相关的数据的存储和检索。我们将设计一个健壮的数据库模式，并实现适当的数据访问机制，以确保数据的完整性和高效性。

通过采用MVC架构，我们可以实现关注点的清晰分离，提高代码的可重用性，并便于未来对系统进行改进和修改。


<div STYLE="page-break-after: always;"></div>

## 3. Analysis Model



### 3.1 Login&Register System



#### 3.1.1 Class Diagram

![](子系统类图)

#### 3.1.2 Interaction Diagram

![](子系统活动图)



### 3.2 Forum System



#### 3.2.1 Class Diagram



#### 3.2.2 Interaction Diagram





### 3.3 Garden Create & Modify System



#### 3.3.1 Class Diagram



#### 3.3.2 Interaction Diagram





### 3.4 Garden Maintenance  System



#### 3.4.1 Class Diagram



#### 3.4.2 Interaction Diagram





### 3.5 Garden Visit System



#### 3.5.1 Class Diagram



#### 3.5.2 Interaction Diagram





### 3.6 Report & Censor System



#### 3.6.1 Class Diagram



#### 3.6.2 Interaction Diagram





## 4. Updated Use Case Model



### 4.1 Updated System :  Login&Register System



### 4.2 Updated System :  Forum System



### 4.3 Updated System :  Garden create & Modify System



### 4.4 Updated System :  Garden Maintenance System



### 4.5 Updated System :  Garden Visit System



### 4.6 Updated System :  Report & Censor System





<div STYLE="page-break-after: always;"></div>

## 5. List of References

This section lists some of the references that can be used for further information and guidance on the software requirements specification.

- Smith, J. (2019). "Introduction to Software Architecture." Medium. [Online]. Available: https://medium.com/@johndoe/introduction-to-software-architecture-123456789. 
- Zhang, L. (2021). "UML Class Diagrams: A Comprehensive Guide." Towards Data Science. [Online]. Available: https://towardsdatascience.com/uml-class-diagrams-a-comprehensive-guide-f27f5923c2c8. 
- W3Schools. "UML Tutorial." [Online]. Available: https://www.w3schools.in/uml-tutorial/. 
- Tutorialspoint. "Software Architecture and Design." [Online]. Available: https://www.tutorialspoint.com/software_architecture_design/index.htm. 
-  https://zhuanlan.zhihu.com/p/78244242
-  https://zhuanlan.zhihu.com/p/109655171

本节列出了一些可以用于进一步了解和指导软件需求规格的参考文献。

<div STYLE="page-break-after: always;"></div>

## 6.Contributions

This project is the result of multiple discussions, revisions, additions, and refinements by two team members. Both members actively participated in the project and took on tasks in each section. We collaborated effectively and contributed to the quality and completeness of the project. The division of labor within the group was average and clear, as follows:

这个项目是两位小组成员经过多次讨论、修改、补充和完善得到的。两位成员都积极参与了项目，并在每个部分都承担了任务。我们有效地合作，为项目的质量和完整性做出了贡献。任务分配平均而清晰，如下所示：

|Student Number|Name|Score Weight|
|---|---|---|
|2050633|Jialin Lu|100%|
|2053711|Jie Chu|100%|