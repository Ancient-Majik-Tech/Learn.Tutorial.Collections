[Page]:link

[Page Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/README.md
[Page Proj Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/ProjectHome.md
[Page Sys Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/ProjectHome.md#system-layout
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Learn/Learn_Home.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Changes/ChangeLog.md
[Page DL Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/DesignLayouts_Home.md

[Sec Details]:link
[Sec Knowledge]:link
[Sec Next]:link
[Sec Materials]:link


[DL Docu DL]:link

# Realms Wiki Collections: "Realms Public Information Home" - Design Layouts - Tags - Project Tags Design Layout

## Collection Index

- [Home][Page Home] 
	- [Project][Page Proj Home]
		- [Systems][Page Sys Home]
	- [Learning][Page Learn Home]
		- [Design Layout][Page DL Home]
			- Tags
				- Project Tags (You are here)
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Design Layout Details][Sec Details]
	- [Required Knowledge and Tools][Sec Knowledge]
	- [Layout Extras]
	- [Whats Next][Sec Next]
	- [Additional Materials][Sec Materials]



### Design Layout Details

This Design Layout conforms to [Design Layout Docu][DL Docu DL] Design Layout (V 1.0).

[Description]

- Details
	- Full Name: Project Level Tags
	- Layout Category: [DL Category]
	- Version: V 1.0
	- Owner
		- Project: E.AMT.Company.User
		- System: Company.DyProjTagging
		- Feature: DyProjTagging.ProjTagDefBindFeat
	- Parent Layout: [Tri-Level Tagging][DL Proj TriLevel]
	- Sublayouts:

### Required Knowledge and Tools

- Requirements
	- Knowledge
		- (American) English
		- [Tri-Leveled Tagging][DL Design TriTag]
	- Tools
		- None

### Tag Categories

- Categories
	- [Project Info Hosting][Cat InfoHost]
	- [Loading Declare][Cat Load]

### Project Info Hosting

The following sets of tags for user and or entity info hosting which will be used to have data loadable from user projects but still maintain security.

|Hosting Type|Short Desc|
|:---|:---|
|Realms User Info Hosting|Used to use a project to help users understand each other by providing ways to bind info to given user.|
|Realms Entity User Info Hosting|Used to help users to understand about the entities that are registered Realms Entity User to project to host the infomation.


#### Realms Entity User Info Hosting

The following tags are used to provide Realms Entity User's tags to dedicate a project to hosting information about the company.

- Tags
	- [RealmsEntityUser][Tag Proj EntityUser]
	- [EntityOwner][Tag Proj EntityOwner]
	- [EntityType][Tag Proj EntityType]
	- [EntityRegistered][Tag Proj EntityReg]
	- [EntityLegalShortName][Tag Proj EntityLegalShortName]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat InfoHost]

#### Tag: RealmsEntityUser

This tag is used to define the User Data for the Realms entity User.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|Name|String|Required|The full name of the given Entity|
|ShortID|String|Required|The short ID used as part of the user|

- Info
	- Name: Realms Entity User Register Tag
	- Version: V 1.0
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat InfoHost]

#### Tag: EntityOwner

This tag is used to assign a given user/users as the owners of given entity.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|EntityID|String|Required|The userID of the entity that the users are being assigned as owners|
|UserIDs|String|DynamicMin1|The user id(s) of the given users to be assigned as owners|

- Info
	- Name: User Entity Ownership Asignment Tag
	- Version: V 1.0
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat InfoHost]

#### Tag: EntityType

This tag is used to register what the given type is of the company entity. Defaults to SolePropritorship if not given.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|EntityID|String|Required|The entity being assigned a type|
|Type|String|Required(ShortCode)|The short code of the given entity type|

- Info
	- Name: Entity Type Assignment Tag
	- Version: V 1.0
	- DefaultIfMissing: SolePropritorship
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat InfoHost]

#### Tag: EntityRegistered

This Tag is used to assign the basic information about where the entity is legally registered, taken as not registered if missing.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|EntityID|String|Required|The entity being marked as legally registered|
|Address|MixedStrings|DynamicMin4|The address of the registration info|

- Info
	- Name: Entity Offical Registration Address Tag
	- Version: V 1.
	- DefaultIfMissing: NotRegistered
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat InfoHost]

#### Tag: EntityLegalShortName

This tag is used to mark any legal registered names (TradeNames) of a given company.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|EntityID|String|Required|The Entity to which the trade names belong.|
|TradeNames|String|DynamicMin1|The trade name(s) the company uses|

- Info
	- Name: Trade Name Marking Tag
	- Version: V 1.0
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat InfoHost]

### Loading Declare

The following tags are used to mark projects as needing given loading/tag handling enabled durring load to be handled more effeciently.

- Tags
	- [TagDefinitions][Tag Proj TagDefs]
	- [DesignLayoutDefinitions][Tag Proj DLDefs]
	- [ReleaseMaker][Tag Proj ReleaseMark]
	- [ConceptDefinitions][Tag Proj ConceptDefs]
	- [ProjectHosting][Tag Proj ProjHosting]
	- [TeamworkDefining][Tag Proj TeamworkDefining]



#### Tag: TagDefinitions

This tag marks a project as defining tags that can be used by any of the Tri-Level

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Tag Defining Functionality Marker Tag
	- Version: V 1.0
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: DyProjTagging.TriStageTagDefsFeat
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat Load]
	

#### Tag: DesignLayoutDefinitions

This tag is designed to mark projects of needing the Design Layout functionaility.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Design Layout Functionality Marker
	- Version: V 1.0
- Definer:
	- ProjectID: E.AMT.Company.User
	- SystemID: Company.DesignLayoutsConcept
	- FeatureID: DesignLayoutsConcept.DLTagsFeat
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat Load]

#### Tag: ReleaseMarker

This tag is used to mark a given Release code that can be used by other projects and versioning.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Versioning Build Releases Marking Tag
	- Version: V 1.0
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat Load]

#### Tag: ConceptDefinitions

This tag is used to mark that a given project needs functionality around concept registry.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Concept Registry Functionality Marker
	- Version: V 1.0
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat Load]

#### Tag: ProjectHosting

This tag is used to show that a project is linked to another project by either being hosted or by being linked as a hosted project.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Project Concept Hosting and Linking Tag
	- Version: V 1.0
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat Load]

#### Tag: TeamDefining

This tag is used to show that a project defines teamwork data within one or more of the projects systems.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|None||||

- Info
	- Name: Teamwork Defining Acceleration Tag
	- Version: V 1.0
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat Load]

### Whats Next

### Additional Materials

- Next Steps
- Topic Reading
- Sublayouts
