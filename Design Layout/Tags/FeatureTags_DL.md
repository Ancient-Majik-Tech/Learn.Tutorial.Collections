[Page]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md

[Page Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/README.md
[Page Proj Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/ProjectHome.md
[Page Sys Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/ProjectHome.md#system-layout
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Learn/Learn_Home.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Changes/ChangeLog.md
[Page DL Home]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/DesignLayouts_Home.md

[Sec Details]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#design-layout-details
[Sec Knowledge]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#required-knowledge-and-tools
[Sec Next]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#whats-next
[Sec Materials]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#additional-materials


[DL Docu DL]:link

# Realms Wiki Collections: "Realms Public Information Home" - Design Layouts - Tags - Feature Tags Design Layout

## Collection Index

- [Home][Page Home] 
	- [Project][Page Proj Home]
		- [Systems][Page Sys Home]
	- [Learning][Page Learn Home]
		- [Design Layout][Page DL Home]
			- Tags
				- Feature Tags (You are here)
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Design Layout Details][Sec Details]
	- [Required Knowledge and Tools][Sec Knowledge]
	- [What is a Feature tag][Sec What]
	- [Tag Categories][Sec Cat]
	- [Whats Next][Sec Next]
	- [Additional Materials][Sec Materials]

[Sec What]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#what-is-a-feature-tag
[Sec Categories]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#tag-categories

### Design Layout Details

This Design Layout conforms to [Design Layout Docu][DL Docu DL] Design Layout (V 1.1).

- Details
	- Full Name: Feature Tags
	- Layout Category: Tags
	- Version: V 1.0
	- Owner
		- Project: [E.AMT.Company.User][Proj Company.User]
		- System: Company.DyProjTagging
		- Feature: DyProjTagging.FeatTagDefBindFeat
	- Parent Layout: [Tri-Level Tagging][DL Proj TriLevel]
	- Sublayouts:

This design layout is designed to make the process of tagging project documentation easier by providing info for the tags.

[DL Proj TriLevel]:link

[Proj Company.User]:link

### Required Knowledge and Tools

- Requirements
	- Knowledge
		- (American) English
		- [Tri-Level Tagging][DL Proj TriLevel]
	- Tools
		- None

#### What is a Feature tag

A Feature tag is used to mark data at the Feature Level of a project. This is used to provide clearer bindings and placement of features within systems as data is bound to feature levels.

#### Tag Categories

- Categories
	- [Tag Defining][Sec TagDef]
	- [Default Tags Binding][Sec DefTags]
	- [Concept Registration And Linking][Sec ConceptRegisters]
	- [Design Layout Registration][Sec DLRegisters]
	- [Team Defining][Sec TeamDefining]
	- [Project Hosting and Linking][Sec ProjHosting]
	- [Build Release Definition][Sec BuildReleaseDef]
	- [Project Type Defining][Sec ProjTypeDef]
	
[Sec TagDef]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#tag-defining
[Sec DefTags]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#default-tags-binding
[Sec ConceptRegisters]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#concept-registration-and-linking
[Sec DLRegisters]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#design-layout-registration
[Sec TeamDefining]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#team-defining
[Sec ProjHosting]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#project-hosting-and-linking
[Sec BuildReleaseDef]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#build-release-defining
[Sec ProjTypeDef]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#project-type-defining


#### Tag Defining

This category is used for defining new project, system and feature tags for use by other projects.

- Tags
	- [DefineProjTag][Tag Feat DefineProjTag]
	- [DefineSysTag][Tag Feat DefineSysTag]
	- [DefineFeatTag][Tag Feat DefineFeatTag]

[Tag Feat DefineProjTag]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#tag-defineprojtag
[Tag Feat DefineSysTag]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#tag-defineprojtag
[Tag Feat DefineFeatTag]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Tags/FeatureTags_DL.md#tag-defineprojtag

#### Tag: DefineProjTag

This tag is used to bind a new project tag to a given feature.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|TagName|String|Required|The name of the given tag (nospaces)|
|TagArguments|[Tag Param Definition][DL Tags ParamDef]|MultiMin0|The argument definitions of the given tag that can handle|

- Info
	- Name: Project Level Tag Useage Definer
	- Version: V 1.0
	- Is Default: True
	- Required Proj Tag: [TagDefinitions][Tag Proj TagDefs]
	- Required Sys Tag: [TagDefiner][Tag Sys TagDefiner]
- Definer:
	- ProjectID: [E.AMT.Company.User][Proj Company.User]
	- SystemID: Company.DyProjTagging
	- FeatureID: DyProjTagging.ProjTagDefBindFeat
- [Return to Categories][Sec Categories]
- [Return To Parent][Sec TagDef]

#### Tag: DefineSysTag

This tag is used to bind a new System tag to a given feature.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|TagName|String|Required|The name of the given tag (nospaces)|
|TagArguments|[Tag Param Definition][DL Tags ParamDef]|MultiMin0|The argument definitions of the given tag that can handle|

- Info
	- Name: System Level Tag Useage Definer
	- Version: V 1.0
	- Is Default: True
	- Required Proj Tag: [TagDefinitions][Tag Proj TagDefs]
	- Required Sys Tag: [TagDefiner][Tag Sys TagDefiner]
- Definer:
	- ProjectID: [E.AMT.Company.User][Proj Company.User]
	- SystemID: Company.DyProjTagging
	- FeatureID: DyProjTagging.SysTagDefBindFeat
- [Return to Categories][Sec Categories]
- [Return To Parent][Sec TagDef]

#### Tag: DefineFeatTag

This tag is used to bind a new Feature tag to a given feature.

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|
|TagName|String|Required|The name of the given tag (nospaces)|
|TagArguments|[Tag Param Definition][DL Tags ParamDef]|MultiMin0|The argument definitions of the given tag that can handle|

- Info
	- Name: Feature Level Tag Useage Definer
	- Version: V 1.0
	- Is Default: True
	- Required Proj Tag: [TagDefinitions][Tag Proj TagDefs]
	- Required Sys Tag: [TagDefiner][Tag Sys TagDefiner]
- Definer:
	- ProjectID: [E.AMT.Company.User][Proj Company.User]
	- SystemID: Company.DyProjTagging
	- FeatureID: DyProjTagging.FeatTagDefBindFeat
- [Return to Categories][Sec Categories]
- [Return To Parent][Sec TagDef]

#### Default Tags Binding

- Tags
	- [BindDefaultTag][Tag Feat BindDefTag]


#### Tag: BindDefaultTag

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
	- Required Sys Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]


#### Concept Registration

- Tags
	- [RegConcept][Tag Feat RegConcept]
	- [LinkConcept][Tag Feat LinkConcept]

#### Tag: RegConcept

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
	- Required Sys Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Tag: LinkConcept

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
	- Required Sys Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Design Layout Registration

- [RegDesignLayout][Tag Feat RegDL]

#### Tag: RegDesignLayout

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [DesignLayoutDefinitions][Tag Proj DLDefs]
	- Required Sys Tag: [DesignLayoutDefiner][Tag Sys DLDefiner]
- Definer:
	- ProjectID: [E.AMT.Company.User][Proj Company.User]
	- SystemID: Company.DesignLayoutsConcept
	- FeatureID: DesignLayoutsConcept.DLTagsFeat
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]



#### Team Defining

- Subcategories
	- [User Groups Defining][Sec UserGroups]
	- [Entity User Teams Defining][Sec EntityTeams]

#### User Groups Defining

- Tags
	- [DefineGroup][Tag Feat DefineGroup]
	- [DefGroupSpecialist][Tag Feat DefGroupSpecialist]

#### Tag: DefineGroup

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
	- Required Sys Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Tag: DefGroupSpecialist

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
	- Required Sys Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Entity User Teams Defining

- Tags
	- [DefineTeam][Tag Feat DefTeam]
	- [DefTeamSpecialist][Tag Feat DefTeamSpecialist]

#### Tag: DefineTeam

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
	- Required Sys Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Tag: DefTeamSpecialist

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
	- Required Sys Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Project Hosting and Linking

- Tags
	- [ProjHost][Tag Feat ProjHost]

#### Tag: ProjHost

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
	- Required Sys Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]


#### Build Release Definitions

- Tags
	- [DefineBuildRelease][Tag Feat DefBuildRelease]

#### Tag: DefineBuildRelease

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
	- Required Sys Tag: [Tag]
- Definer:
	- ProjectID: [ProjID]
	- SystemID: [SystemID]
	- FeatureID: [FeatureID]
- [Return to Categories][Sec Categories]
- [Return To Parent][Cat [CatName]]

#### Project Type Defining

- Tags
	- [RegProjType][Tag Feat RegProjType]

#### Tag: RegProjType

[Tag Desc]

|Paramaters|Data Type|Modifiers|Desc|
|:---|:---|:---|:---|

- Info
	- Name: [Tag Full Name]
	- Version: V 1.0
	- Required Proj Tag: [Tag]
	- Required Sys Tag: [Tag]
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
