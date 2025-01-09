[Page]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/LogicSystem_DL.md

[Page Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/README.md
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Learn/Learn_Home.md
[Page Project Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/ProjectHome.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Changes/ChangeLog.md
[Page DL Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/DesignLayouts_Home.md

[Sec Details]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/LogicSystem_DL.md#design-layout-details
[Sec Knowledge]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/LogicSystem_DL.md#required-knowledge-and-tools
[Sec Next]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/LogicSystem_DL.md#whats-next
[Sec Materials]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/LogicSystem_DL.md#additional-materials
[Sec What]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/LogicSystem_DL.md#what-is-a-logic-system
[Sec Breakdown]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/LogicSystem_DL.md#why-the-breakdown
[Sec Define]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/LogicSystem_DL.md#defining-a-logic-system

[DL Docu DL]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Docu/DesignLayoutDocu_DL.md

[DL Proj Proj]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/RealmsProject_DL.md
[DL Proj Features]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/SystemFeat_DL.md
[DL Proj Changes]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/Changes_DL.md
[DL Design IDPieces]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Design/IDPieces_DL.md
[DL Design CamelCase]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Design/CamelCaseNaming_DL.md
[DL Design Versions]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Design/Versions_DL.md
[DL Design Continual]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Design/ContinualDevelopment_DL.md
[DL User User]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/User/RealmsUser_DL.md
[DL User Entity]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/User/RealmsEntityUser_DL.md
[DL User Teamwork]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/User/UserTeamwork_DL.md
[DL 3RDParty User Categories]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/ThirdParty/UserDefinedCategories_DL.md
[DL Docu System]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Docu/SystemDocu_DL.md

# Realms Tutorial Collections: "Main Project" - Design Layouts - Projects - Logic Systems Design Layout

## Collection Index

- [Home][Page Home] 
	- [Project][Page Project Home]
	- [Learning][Page Learn Home]
		- [Design Layout][Page DL Home]
			- Projects
				- Logic Systems (You are here)
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Design Layout Details][Sec Details]
	- [Required Knowledge and Tools][Sec Knowledge]
	- [What is a Logic System][Sec What]
	- [Why the Breakdown][Sec Breakdown]
	- [Defining a Logic System][Sec Define]
	- [Whats Next][Sec Next]
	- [Additional Materials][Sec Materials]



### Design Layout Details

This Design Layout conforms to [Design Layout Docu][DL Docu DL] Design Layout (V 1.0).

Logic System Design Layout is designed to explain the first stage of our project breakdown. These systems make up projects.

- Details
	- Layout Category: Project
	- Version: V 1.0
	- Owner
		- Project: E.AMT.Tutorials.Main
		- System: Tutorial.DesignLayouts
		- Feature: DesignLayouts.Realms

### Required Knowledge and Tools

- Requirements
	- Knowledge
		- (American) English
		- [Realms Project Design Layout][DL Proj Proj], Basic Understanding
	- Tools
		- None

### What is a Logic System

A Logic System is a group of one or more [System Features][DL Proj Features] which provide a given [Realms Project][DL Proj Proj] its functionality. Logic systems are independent but can rely on other systems and features of other systems.

### Why the breakdown

You may be wondering why projects are broken into systems and then into features. To answer that we should explain that each step is designed to keep systems smaller and also to make things easier to track and understand.

We design our systems to be focus on the task at hand. and design around allowing our systems to depend on user implimentation. For example we have a Dynamic Complete Parsing and Processing command packages system thus allowing a dynamic framework for handling for one of our projects, But as part of that it leaves error handling to the user. instead focusing on the packages and dynamic framework for it instead.

### Defining a Logic System

So you have a project and planned systems. Now for each system you will follow the same general theme. First you will want a name, we choose to use long names as the ID's will be the main reference point. 

Next you will want to describe your system in basic details. Use words that make sense to you. 

Your next step will be choosing a [System ID Piece][DL Design IDPieces] for the given system. This ID Piece will be used with the Project ID Piece of the project to format the system ID. For example for this tutorial and the design layouts system the ID would be TutHome.DesignLayouts. 

### Whats Next

First think of your basic systems you want your project to have. then break the system down into smaller parts with these smaller parts check the [System Features][DL Proj Features] to form those parts into features as you build up your project.

### Additional Materials

- Next Steps
	- [System Features][DL Proj Features]
	- [System Documentation][DL Docu System]
	- [Changes][DL Proj Changes]
- Topic Reading
	- [System Features][DL Proj Features]
	- [Realms Project][DL Proj Proj]
	- [Camel Case Naming][DL Design CamelCase]
	- [Versions][DL Design Versions]
	- [Continual Development][DL Design Continual]
	- [Realms User][DL User User]
	- [Realms Entity User][DL User Entity]
	- [User Teamwork][DL User Teamwork]
	- [User Third Party Project Categories][DL 3RDParty User Categories]
- Sublayouts
	- [System Features][DL Proj Features]
	- [System Documentation][DL Docu System]

