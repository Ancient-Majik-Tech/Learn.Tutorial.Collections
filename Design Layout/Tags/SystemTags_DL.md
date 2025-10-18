[Page]:link

[Page Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/README.md
[Page Proj Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/ProjectHome.md
[Page Sys Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/ProjectHome.md#system-layout
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Learn/Learn_Home.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Changes/ChangeLog.md
[Page DL Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/DesignLayouts_Home.md

[Sec Details]:[Page]#design-layout-details
[Sec Knowledge]:[Page]#required-knowledge-and-tools
[Sec Next]:[Page]#whats-next
[Sec Materials]:[Page]#additional-materials


[DL Docu DL]:link

# Realms Wiki Collections: "Realms Public Information Home" - Design Layouts - Tags - System Tags Design Layout

## Collection Index

- [Home][Page Home] 
	- [Project][Page Proj Home]
		- [Systems][Page Sys Home]
	- [Learning][Page Learn Home]
		- [Design Layout][Page DL Home]
			- [DL Category]
				- [DL Name] (You are here)
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Design Layout Details][Sec Details]
	- [Required Knowledge and Tools][Sec Knowledge]
	- [Layout Extras]
	- [Whats Next][Sec Next]
	- [Additional Materials][Sec Materials]



### Design Layout Details

This Design Layout conforms to [Design Layout Docu][DL Docu DL] Design Layout (V 1.1).

- Details
	- Full Name: System Tags
	- Layout Category: Tags
	- Version: V 1.0
	- Owner
		- Project: [E.AMT.Company.User][Proj Company.User]
		- System: Company.DyProjTagging
		- Feature: DyProjTagging.SysTagDefBindFeat
	- Parent Layout: [Tri-Level Tagging][DL Proj TriTag]
	- Sublayouts:

This design layout is designed to make system handling quicker and more flexiable using tags to help focus loading based on tagging.

### Required Knowledge and Tools

- Requirements
	- Knowledge
		- (American) English
		- [Tri-Level Tagging][DL Proj TriLevel]
	- Tools
		- None

#### What are System Tags

System tags are like project tags except then are used to help when loading and handling features by requiring project tags to use a system tag. then also requiring system tags to use certian feature tags. This will/is used for dynamic and flexable loading and more organized project development as a whole.

#### Load Info Tags

- Tags
	- [ConceptRegister][Tag Sys ConceptRegister]
	- [TagDefiner][Tag Sys TagDefiner]
	- [DesignLayoutDefiner][Tag Sys DLDefiner]
	- [BuildReleaseDefiner][Tag Sys BuildReleaseDefiner]
	- [ProjHoster][Tag Sys ProjHoster]
	- [ProjTypeRegister][Tag Sys ProjTypeRegister]
	- [TeamRegister][Tag Sys TeamRegister]

#### Tag: ConceptRegister

This system tag marks that the given system's features uses the concept database functionality to register and link concepts. 

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Advanced Concept Handling Registry Tag
	- Version: V 1.0
	- Required Proj Tag: [ConceptDefinitions][Tag Proj ConceptDefinitions]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Tag: TagDefiner

This system tag is used to allow features to use the Tag Defining functionality allowing dynamic tag creation framework, allowing code for tags and tags to be seperate but still work together.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Dynamic Advanced Tagging Functionality
	- Version: V 1.0
	- Required Proj Tag: [TagDefinitions][Tag Proj TagDefs]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Tag: DesignLayoutDefiner

This System tag marks that one or more features in the system use Design Layout Defining Functionality.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Advanced Design Layouts Framework Tag
	- Version: V 1.0
	- Required Proj Tag: [DesignLayoutDefinitions][Tag Proj DLDefs]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Tag: BuildReleaseDefiner

This tag marks that the given system has one or more features that define new build Releases used with our versioning system.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Versioning Build Release Defining Functionality Tag
	- Version: V 1.0
	- Required Proj Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Tag: ProjHoster

This tag is used to mark that the given system has one or more features that host the concept behind a given project.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Project Concept Hosting Marker Tag
	- Version: V 1.0
	- Required Proj Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Tag: ProjTypeRegister

This tag is used to mark that a given system hosts a Realms Project Type within its features.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Tag: TeamRegister

This tag marks that a system has one or more features that define Teams or Groups, also includes the ability to define specializations.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Teamwork Handling Marker Tag
	- Version: V 1.0
	- Required Proj Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

### Whats Next

### Additional Materials

- Next Steps
- Topic Reading
- Sublayouts
