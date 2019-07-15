<a name='assembly'></a>
# TestCoordinator.Model

## Contents

- [Area](#T-TestCoordinator-Model-Area 'TestCoordinator.Model.Area')
  - [#ctor()](#M-TestCoordinator-Model-Area-#ctor 'TestCoordinator.Model.Area.#ctor')
  - [Assignee](#P-TestCoordinator-Model-Area-Assignee 'TestCoordinator.Model.Area.Assignee')
  - [Feature](#P-TestCoordinator-Model-Area-Feature 'TestCoordinator.Model.Area.Feature')
  - [FeatureId](#P-TestCoordinator-Model-Area-FeatureId 'TestCoordinator.Model.Area.FeatureId')
  - [ParentId](#P-TestCoordinator-Model-Area-ParentId 'TestCoordinator.Model.Area.ParentId')
  - [Priority](#P-TestCoordinator-Model-Area-Priority 'TestCoordinator.Model.Area.Priority')
  - [TestCases](#P-TestCoordinator-Model-Area-TestCases 'TestCoordinator.Model.Area.TestCases')
- [Attachment](#T-TestCoordinator-Model-Attachment 'TestCoordinator.Model.Attachment')
  - [FileName](#P-TestCoordinator-Model-Attachment-FileName 'TestCoordinator.Model.Attachment.FileName')
  - [FilePath](#P-TestCoordinator-Model-Attachment-FilePath 'TestCoordinator.Model.Attachment.FilePath')
  - [Id](#P-TestCoordinator-Model-Attachment-Id 'TestCoordinator.Model.Attachment.Id')
  - [Type](#P-TestCoordinator-Model-Attachment-Type 'TestCoordinator.Model.Attachment.Type')
- [ContentItemBase](#T-TestCoordinator-Model-ContentItemBase 'TestCoordinator.Model.ContentItemBase')
  - [#ctor()](#M-TestCoordinator-Model-ContentItemBase-#ctor 'TestCoordinator.Model.ContentItemBase.#ctor')
  - [DateCreated](#P-TestCoordinator-Model-ContentItemBase-DateCreated 'TestCoordinator.Model.ContentItemBase.DateCreated')
  - [Description](#P-TestCoordinator-Model-ContentItemBase-Description 'TestCoordinator.Model.ContentItemBase.Description')
  - [Id](#P-TestCoordinator-Model-ContentItemBase-Id 'TestCoordinator.Model.ContentItemBase.Id')
  - [LastModified](#P-TestCoordinator-Model-ContentItemBase-LastModified 'TestCoordinator.Model.ContentItemBase.LastModified')
  - [Locked](#P-TestCoordinator-Model-ContentItemBase-Locked 'TestCoordinator.Model.ContentItemBase.Locked')
  - [LockedBy](#P-TestCoordinator-Model-ContentItemBase-LockedBy 'TestCoordinator.Model.ContentItemBase.LockedBy')
  - [ParentId](#P-TestCoordinator-Model-ContentItemBase-ParentId 'TestCoordinator.Model.ContentItemBase.ParentId')
  - [Title](#P-TestCoordinator-Model-ContentItemBase-Title 'TestCoordinator.Model.ContentItemBase.Title')
  - [Type](#P-TestCoordinator-Model-ContentItemBase-Type 'TestCoordinator.Model.ContentItemBase.Type')
- [Feature](#T-TestCoordinator-Model-Feature 'TestCoordinator.Model.Feature')
  - [#ctor()](#M-TestCoordinator-Model-Feature-#ctor 'TestCoordinator.Model.Feature.#ctor')
  - [Areas](#P-TestCoordinator-Model-Feature-Areas 'TestCoordinator.Model.Feature.Areas')
  - [ParentId](#P-TestCoordinator-Model-Feature-ParentId 'TestCoordinator.Model.Feature.ParentId')
  - [Product](#P-TestCoordinator-Model-Feature-Product 'TestCoordinator.Model.Feature.Product')
  - [ProductId](#P-TestCoordinator-Model-Feature-ProductId 'TestCoordinator.Model.Feature.ProductId')
- [FieldLengthAttribute](#T-TestCoordinator-Model-Attributes-FieldLengthAttribute 'TestCoordinator.Model.Attributes.FieldLengthAttribute')
  - [#ctor(minimum,maximum)](#M-TestCoordinator-Model-Attributes-FieldLengthAttribute-#ctor-System-Int32,System-Int32- 'TestCoordinator.Model.Attributes.FieldLengthAttribute.#ctor(System.Int32,System.Int32)')
- [ISearchable](#T-TestCoordinator-Model-ISearchable 'TestCoordinator.Model.ISearchable')
  - [Id](#P-TestCoordinator-Model-ISearchable-Id 'TestCoordinator.Model.ISearchable.Id')
  - [Title](#P-TestCoordinator-Model-ISearchable-Title 'TestCoordinator.Model.ISearchable.Title')
  - [Type](#P-TestCoordinator-Model-ISearchable-Type 'TestCoordinator.Model.ISearchable.Type')
- [LifecycleStatus](#T-TestCoordinator-Model-Enums-LifecycleStatus 'TestCoordinator.Model.Enums.LifecycleStatus')
  - [Master](#F-TestCoordinator-Model-Enums-LifecycleStatus-Master 'TestCoordinator.Model.Enums.LifecycleStatus.Master')
  - [Temp](#F-TestCoordinator-Model-Enums-LifecycleStatus-Temp 'TestCoordinator.Model.Enums.LifecycleStatus.Temp')
- [Priority](#T-TestCoordinator-Model-Enums-Priority 'TestCoordinator.Model.Enums.Priority')
  - [High](#F-TestCoordinator-Model-Enums-Priority-High 'TestCoordinator.Model.Enums.Priority.High')
  - [Low](#F-TestCoordinator-Model-Enums-Priority-Low 'TestCoordinator.Model.Enums.Priority.Low')
  - [Medium](#F-TestCoordinator-Model-Enums-Priority-Medium 'TestCoordinator.Model.Enums.Priority.Medium')
  - [Urgent](#F-TestCoordinator-Model-Enums-Priority-Urgent 'TestCoordinator.Model.Enums.Priority.Urgent')
- [Product](#T-TestCoordinator-Model-Product 'TestCoordinator.Model.Product')
  - [#ctor()](#M-TestCoordinator-Model-Product-#ctor 'TestCoordinator.Model.Product.#ctor')
  - [Features](#P-TestCoordinator-Model-Product-Features 'TestCoordinator.Model.Product.Features')
  - [ParentId](#P-TestCoordinator-Model-Product-ParentId 'TestCoordinator.Model.Product.ParentId')
- [RequiredFieldAttribute](#T-TestCoordinator-Model-Attributes-RequiredFieldAttribute 'TestCoordinator.Model.Attributes.RequiredFieldAttribute')
  - [#ctor()](#M-TestCoordinator-Model-Attributes-RequiredFieldAttribute-#ctor 'TestCoordinator.Model.Attributes.RequiredFieldAttribute.#ctor')
- [Status](#T-TestCoordinator-Model-Enums-Status 'TestCoordinator.Model.Enums.Status')
  - [Deprecated](#F-TestCoordinator-Model-Enums-Status-Deprecated 'TestCoordinator.Model.Enums.Status.Deprecated')
  - [Fail](#F-TestCoordinator-Model-Enums-Status-Fail 'TestCoordinator.Model.Enums.Status.Fail')
  - [KnownIssue](#F-TestCoordinator-Model-Enums-Status-KnownIssue 'TestCoordinator.Model.Enums.Status.KnownIssue')
  - [NotImplemented](#F-TestCoordinator-Model-Enums-Status-NotImplemented 'TestCoordinator.Model.Enums.Status.NotImplemented')
  - [NotTested](#F-TestCoordinator-Model-Enums-Status-NotTested 'TestCoordinator.Model.Enums.Status.NotTested')
  - [Pass](#F-TestCoordinator-Model-Enums-Status-Pass 'TestCoordinator.Model.Enums.Status.Pass')
  - [Regression](#F-TestCoordinator-Model-Enums-Status-Regression 'TestCoordinator.Model.Enums.Status.Regression')
- [TestCase](#T-TestCoordinator-Model-TestCase 'TestCoordinator.Model.TestCase')
  - [Area](#P-TestCoordinator-Model-TestCase-Area 'TestCoordinator.Model.TestCase.Area')
  - [AreaId](#P-TestCoordinator-Model-TestCase-AreaId 'TestCoordinator.Model.TestCase.AreaId')
  - [Attachments](#P-TestCoordinator-Model-TestCase-Attachments 'TestCoordinator.Model.TestCase.Attachments')
  - [Automated](#P-TestCoordinator-Model-TestCase-Automated 'TestCoordinator.Model.TestCase.Automated')
  - [AutomatedTests](#P-TestCoordinator-Model-TestCase-AutomatedTests 'TestCoordinator.Model.TestCase.AutomatedTests')
  - [Bugs](#P-TestCoordinator-Model-TestCase-Bugs 'TestCoordinator.Model.TestCase.Bugs')
  - [Environment](#P-TestCoordinator-Model-TestCase-Environment 'TestCoordinator.Model.TestCase.Environment')
  - [Given](#P-TestCoordinator-Model-TestCase-Given 'TestCoordinator.Model.TestCase.Given')
  - [ParentId](#P-TestCoordinator-Model-TestCase-ParentId 'TestCoordinator.Model.TestCase.ParentId')
  - [Priority](#P-TestCoordinator-Model-TestCase-Priority 'TestCoordinator.Model.TestCase.Priority')
  - [ProductVersion](#P-TestCoordinator-Model-TestCase-ProductVersion 'TestCoordinator.Model.TestCase.ProductVersion')
  - [Status](#P-TestCoordinator-Model-TestCase-Status 'TestCoordinator.Model.TestCase.Status')
  - [Then](#P-TestCoordinator-Model-TestCase-Then 'TestCoordinator.Model.TestCase.Then')
  - [When](#P-TestCoordinator-Model-TestCase-When 'TestCoordinator.Model.TestCase.When')

<a name='T-TestCoordinator-Model-Area'></a>
## Area `type`

##### Namespace

TestCoordinator.Model

##### Summary

Represents an area of a feature.

<a name='M-TestCoordinator-Model-Area-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [Area](#T-TestCoordinator-Model-Area 'TestCoordinator.Model.Area') class.

##### Parameters

This constructor has no parameters.

<a name='P-TestCoordinator-Model-Area-Assignee'></a>
### Assignee `property`

##### Summary

Gets or sets the assignee.

<a name='P-TestCoordinator-Model-Area-Feature'></a>
### Feature `property`

##### Summary

Gets or sets the feature.

<a name='P-TestCoordinator-Model-Area-FeatureId'></a>
### FeatureId `property`

##### Summary

Gets or sets the feature identifier.

<a name='P-TestCoordinator-Model-Area-ParentId'></a>
### ParentId `property`

##### Summary

Gets the parent identifier.

<a name='P-TestCoordinator-Model-Area-Priority'></a>
### Priority `property`

##### Summary

Gets or sets the priority.

<a name='P-TestCoordinator-Model-Area-TestCases'></a>
### TestCases `property`

##### Summary

Gets or sets the test cases.

<a name='T-TestCoordinator-Model-Attachment'></a>
## Attachment `type`

##### Namespace

TestCoordinator.Model

##### Summary

Represents an attachment.

<a name='P-TestCoordinator-Model-Attachment-FileName'></a>
### FileName `property`

##### Summary

Gets or sets the name of the file.

<a name='P-TestCoordinator-Model-Attachment-FilePath'></a>
### FilePath `property`

##### Summary

Gets or sets the file path.

<a name='P-TestCoordinator-Model-Attachment-Id'></a>
### Id `property`

##### Summary

Gets or sets the identifier.

<a name='P-TestCoordinator-Model-Attachment-Type'></a>
### Type `property`

##### Summary

Gets or sets the type.

<a name='T-TestCoordinator-Model-ContentItemBase'></a>
## ContentItemBase `type`

##### Namespace

TestCoordinator.Model

##### Summary

Base class for all content types in the system.

<a name='M-TestCoordinator-Model-ContentItemBase-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [ContentItemBase](#T-TestCoordinator-Model-ContentItemBase 'TestCoordinator.Model.ContentItemBase') class.

##### Parameters

This constructor has no parameters.

<a name='P-TestCoordinator-Model-ContentItemBase-DateCreated'></a>
### DateCreated `property`

##### Summary

Gets or sets the date created.

<a name='P-TestCoordinator-Model-ContentItemBase-Description'></a>
### Description `property`

##### Summary

Gets or sets the description.

<a name='P-TestCoordinator-Model-ContentItemBase-Id'></a>
### Id `property`

##### Summary

Gets or sets the identifier.

<a name='P-TestCoordinator-Model-ContentItemBase-LastModified'></a>
### LastModified `property`

##### Summary

Gets or sets the last modified.

<a name='P-TestCoordinator-Model-ContentItemBase-Locked'></a>
### Locked `property`

##### Summary

Gets or sets a value indicating whether this [ContentItemBase](#T-TestCoordinator-Model-ContentItemBase 'TestCoordinator.Model.ContentItemBase') is locked.

<a name='P-TestCoordinator-Model-ContentItemBase-LockedBy'></a>
### LockedBy `property`

##### Summary

Gets or sets the client which locked the item.

<a name='P-TestCoordinator-Model-ContentItemBase-ParentId'></a>
### ParentId `property`

##### Summary

Gets the parent identifier.

<a name='P-TestCoordinator-Model-ContentItemBase-Title'></a>
### Title `property`

##### Summary

Gets or sets the title.

<a name='P-TestCoordinator-Model-ContentItemBase-Type'></a>
### Type `property`

##### Summary

Gets the type.

<a name='T-TestCoordinator-Model-Feature'></a>
## Feature `type`

##### Namespace

TestCoordinator.Model

##### Summary

Represents a product feature.

<a name='M-TestCoordinator-Model-Feature-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [Feature](#T-TestCoordinator-Model-Feature 'TestCoordinator.Model.Feature') class.

##### Parameters

This constructor has no parameters.

<a name='P-TestCoordinator-Model-Feature-Areas'></a>
### Areas `property`

##### Summary

Gets or sets the areas.

<a name='P-TestCoordinator-Model-Feature-ParentId'></a>
### ParentId `property`

##### Summary

Gets the parent identifier.

<a name='P-TestCoordinator-Model-Feature-Product'></a>
### Product `property`

##### Summary

Gets or sets the product.

<a name='P-TestCoordinator-Model-Feature-ProductId'></a>
### ProductId `property`

##### Summary

Gets or sets the product identifier.

<a name='T-TestCoordinator-Model-Attributes-FieldLengthAttribute'></a>
## FieldLengthAttribute `type`

##### Namespace

TestCoordinator.Model.Attributes

##### Summary

Attribute specifying minimum and maximum length of a field.

<a name='M-TestCoordinator-Model-Attributes-FieldLengthAttribute-#ctor-System-Int32,System-Int32-'></a>
### #ctor(minimum,maximum) `constructor`

##### Summary

Initializes a new instance of the [FieldLengthAttribute](#T-TestCoordinator-Model-Attributes-FieldLengthAttribute 'TestCoordinator.Model.Attributes.FieldLengthAttribute') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| minimum | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The minimum. |
| maximum | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The maximum. |

<a name='T-TestCoordinator-Model-ISearchable'></a>
## ISearchable `type`

##### Namespace

TestCoordinator.Model

##### Summary

Denotes content that could be searched.

<a name='P-TestCoordinator-Model-ISearchable-Id'></a>
### Id `property`

##### Summary

Gets or sets the identifier.

<a name='P-TestCoordinator-Model-ISearchable-Title'></a>
### Title `property`

##### Summary

Gets or sets the title.

<a name='P-TestCoordinator-Model-ISearchable-Type'></a>
### Type `property`

##### Summary

Gets the type.

<a name='T-TestCoordinator-Model-Enums-LifecycleStatus'></a>
## LifecycleStatus `type`

##### Namespace

TestCoordinator.Model.Enums

##### Summary

Defines different lifecycle statuses for an object.

<a name='F-TestCoordinator-Model-Enums-LifecycleStatus-Master'></a>
### Master `constants`

##### Summary

This is the primary state of an item and always exists.

<a name='F-TestCoordinator-Model-Enums-LifecycleStatus-Temp'></a>
### Temp `constants`

##### Summary

This is a copy of the item that exists to mark changes in an edit screen. It marks the item as locked.

<a name='T-TestCoordinator-Model-Enums-Priority'></a>
## Priority `type`

##### Namespace

TestCoordinator.Model.Enums

##### Summary

Denotes different priorities.

<a name='F-TestCoordinator-Model-Enums-Priority-High'></a>
### High `constants`

##### Summary

The high

<a name='F-TestCoordinator-Model-Enums-Priority-Low'></a>
### Low `constants`

##### Summary

The low

<a name='F-TestCoordinator-Model-Enums-Priority-Medium'></a>
### Medium `constants`

##### Summary

The medium

<a name='F-TestCoordinator-Model-Enums-Priority-Urgent'></a>
### Urgent `constants`

##### Summary

The urgent

<a name='T-TestCoordinator-Model-Product'></a>
## Product `type`

##### Namespace

TestCoordinator.Model

##### Summary

Represents a product in the system.
This is the entry point of functional object hierarchy.

<a name='M-TestCoordinator-Model-Product-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [Product](#T-TestCoordinator-Model-Product 'TestCoordinator.Model.Product') class.

##### Parameters

This constructor has no parameters.

<a name='P-TestCoordinator-Model-Product-Features'></a>
### Features `property`

##### Summary

Gets or sets the features.

<a name='P-TestCoordinator-Model-Product-ParentId'></a>
### ParentId `property`

##### Summary

Gets the parent identifier.

<a name='T-TestCoordinator-Model-Attributes-RequiredFieldAttribute'></a>
## RequiredFieldAttribute `type`

##### Namespace

TestCoordinator.Model.Attributes

##### Summary

Attribute specifying that field is required.

<a name='M-TestCoordinator-Model-Attributes-RequiredFieldAttribute-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [RequiredFieldAttribute](#T-TestCoordinator-Model-Attributes-RequiredFieldAttribute 'TestCoordinator.Model.Attributes.RequiredFieldAttribute') class.

##### Parameters

This constructor has no parameters.

<a name='T-TestCoordinator-Model-Enums-Status'></a>
## Status `type`

##### Namespace

TestCoordinator.Model.Enums

##### Summary

Denotes different statuses.

<a name='F-TestCoordinator-Model-Enums-Status-Deprecated'></a>
### Deprecated `constants`

##### Summary

The deprecated

<a name='F-TestCoordinator-Model-Enums-Status-Fail'></a>
### Fail `constants`

##### Summary

The fail

<a name='F-TestCoordinator-Model-Enums-Status-KnownIssue'></a>
### KnownIssue `constants`

##### Summary

Known Issue

<a name='F-TestCoordinator-Model-Enums-Status-NotImplemented'></a>
### NotImplemented `constants`

##### Summary

The not implemented

<a name='F-TestCoordinator-Model-Enums-Status-NotTested'></a>
### NotTested `constants`

##### Summary

The not tested

<a name='F-TestCoordinator-Model-Enums-Status-Pass'></a>
### Pass `constants`

##### Summary

The pass

<a name='F-TestCoordinator-Model-Enums-Status-Regression'></a>
### Regression `constants`

##### Summary

The regression

<a name='T-TestCoordinator-Model-TestCase'></a>
## TestCase `type`

##### Namespace

TestCoordinator.Model

##### Summary

Represents each test case object.

<a name='P-TestCoordinator-Model-TestCase-Area'></a>
### Area `property`

##### Summary

Gets or sets the area.

<a name='P-TestCoordinator-Model-TestCase-AreaId'></a>
### AreaId `property`

##### Summary

Gets or sets the area identifier.

<a name='P-TestCoordinator-Model-TestCase-Attachments'></a>
### Attachments `property`

##### Summary

Gets or sets the attachments list.

<a name='P-TestCoordinator-Model-TestCase-Automated'></a>
### Automated `property`

##### Summary

Gets or sets a value indicating whether this [TestCase](#T-TestCoordinator-Model-TestCase 'TestCoordinator.Model.TestCase') is automated.

<a name='P-TestCoordinator-Model-TestCase-AutomatedTests'></a>
### AutomatedTests `property`

##### Summary

Gets or sets the automated test cases.

<a name='P-TestCoordinator-Model-TestCase-Bugs'></a>
### Bugs `property`

##### Summary

Gets or sets the bugs.

<a name='P-TestCoordinator-Model-TestCase-Environment'></a>
### Environment `property`

##### Summary

Gets or sets the environment.

<a name='P-TestCoordinator-Model-TestCase-Given'></a>
### Given `property`

##### Summary

Gets or sets the given.

<a name='P-TestCoordinator-Model-TestCase-ParentId'></a>
### ParentId `property`

##### Summary

Gets the parent identifier.

<a name='P-TestCoordinator-Model-TestCase-Priority'></a>
### Priority `property`

##### Summary

Gets or sets the priority.

<a name='P-TestCoordinator-Model-TestCase-ProductVersion'></a>
### ProductVersion `property`

##### Summary

Gets or sets the product version.

<a name='P-TestCoordinator-Model-TestCase-Status'></a>
### Status `property`

##### Summary

Gets or sets the status.

<a name='P-TestCoordinator-Model-TestCase-Then'></a>
### Then `property`

##### Summary

Gets or sets the then.

<a name='P-TestCoordinator-Model-TestCase-When'></a>
### When `property`

##### Summary

Gets or sets the when.
