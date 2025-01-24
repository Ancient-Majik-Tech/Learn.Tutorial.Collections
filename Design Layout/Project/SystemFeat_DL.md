[Page]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/SystemFeat_DL.md

[Page Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/README.md
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Learn/Learn_Home.md
[Page Project Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/ProjectHome.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Changes/ChangeLog.md
[Page DL Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/DesignLayouts_Home.md

[Sec Details]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/SystemFeat_DL.md#design-layout-details
[Sec Knowledge]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/SystemFeat_DL.md#required-knowledge-and-tools
[Sec Next]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/SystemFeat_DL.md#next-steps
[Sec Materials]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/SystemFeat_DL.md#additional-materials
[Sec What]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/SystemFeat_DL.md#what-is-a-system-feature
[Sec Define]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/SystemFeat_DL.md#defining-a-feature

[DL Docu DL]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Docu/DesignLayoutDocu_DL.md
[DL Docu Feature]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Docu/FeatureDocu_DL.md

[DL Proj Proj]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/RealmsProject_DL.md
[DL Proj System]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/LogicSystem_DL.md

[DL Design IDPieces]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Design/IDPieces_DL.md
[DL Design Namespace]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Design/Namespace_DL.md

# Realms Tutorial Collections: "Main Project" - Design Layouts - Project - System Features Design Layout

## Collection Index

- [Home][Page Home] 
	- [Project][Page Project Home]
	- [Learning][Page Learn Home]
		- [Design Layout][Page DL Home]
			- Project
				- System Features (You are here)
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Design Layout Details][Sec Details]
	- [Required Knowledge and Tools][Sec Knowledge]
	- [What is a System Feature][Sec What]
	- [Defining a Feature][Sec Define]
	- [Whats Next][Sec Next]
	- [Additional Materials][Sec Materials]



### Design Layout Details

This Design Layout conforms to [Design Layout Docu][DL Docu DL] Design Layout (V 1.0).

System Features Design Layout is designed to outline the basic concept of a feature within a given system as part of the [Realms Project][DL Proj Proj] Design process.

- Details
	- Layout Category: Project
	- Version: V 1.0
	- Parent Layout: [Logic System][DL Proj System]
	- Sublayouts:
		- [Feature Documentation][DL Docu Feature]
	- Owner
		- Project: E.AMT.Tutorials.Main
		- System: Tutorial.DesignLayouts
		- Feature: DesignLayouts.Realms

### Required Knowledge and Tools

- Requirements
	- Knowledge
		- (American) English
		- [Realms Project][DL Proj Proj]
		- [Logic Systems][DL Proj System]
	- Tools
		- None

### What is A System Feature

What is a "System Feature", for the sake of projects a System is a piece of a system, this is a collection of data, fields, properties, logic/methods which are used to provide a piece of functionality to the given system. Features are designed to allow building on other system's features. This allows us the ability to keep our data organized but also dynamic. 

For example say you have a "Base System Feature" which provides a basic code object which can be extended as part of the given system. And systems build thier object around the Base to provide the base functionality but also provide the system spesific implimentation. 

### Defining a Feature

First you will want to choose a name for the given feature. After that you will want a [Feature ID Piece][DL Design IDPieces] for the feature. this requires it to end in "Feat" to show its different then a system ID when together. This will be combined in a [Namespaced ID][DL Design Namespace] with the owner system's ID piece.

Finally you will want a description of the purpase of the given system.

### Whats Next

Now you understand features. Please check out [Feature Documentation][DL Docu Feature] Design Layout to understand how to document your new feature.

### Additional Materials

- Next Steps
	- [Feature Documentation][DL Docu Feature]
- Topic Reading
	- [Realms Project][DL Proj Proj]
	- [Logic Systems][DL Proj System]
	- [ID Pieces][DL Design IDPieces]
	- [Namespaces][DL Design Namespace]
- Sublayouts
	- [Feature Documentation][DL Docu Feature]


