<a name='assembly'></a>
# TestCoordinator.Utilities

## Contents

- [AreasStringResources](#T-TestCoordinator-Utilities-Content-AreasStringResources 'TestCoordinator.Utilities.Content.AreasStringResources')
  - [AllItemsPageTitle](#P-TestCoordinator-Utilities-Content-AreasStringResources-AllItemsPageTitle 'TestCoordinator.Utilities.Content.AreasStringResources.AllItemsPageTitle')
  - [ChildItemsRouteFormat](#P-TestCoordinator-Utilities-Content-AreasStringResources-ChildItemsRouteFormat 'TestCoordinator.Utilities.Content.AreasStringResources.ChildItemsRouteFormat')
  - [CreateItemPageTitle](#P-TestCoordinator-Utilities-Content-AreasStringResources-CreateItemPageTitle 'TestCoordinator.Utilities.Content.AreasStringResources.CreateItemPageTitle')
  - [EntitiesNamePlural](#P-TestCoordinator-Utilities-Content-AreasStringResources-EntitiesNamePlural 'TestCoordinator.Utilities.Content.AreasStringResources.EntitiesNamePlural')
  - [EntityNameSingular](#P-TestCoordinator-Utilities-Content-AreasStringResources-EntityNameSingular 'TestCoordinator.Utilities.Content.AreasStringResources.EntityNameSingular')
  - [NoItemsPageTitle](#P-TestCoordinator-Utilities-Content-AreasStringResources-NoItemsPageTitle 'TestCoordinator.Utilities.Content.AreasStringResources.NoItemsPageTitle')
- [CollectionExtensions](#T-TestCoordinator-Utilities-CollectionExtensions 'TestCoordinator.Utilities.CollectionExtensions')
  - [GetSorted\`\`1(items,sortOption)](#M-TestCoordinator-Utilities-CollectionExtensions-GetSorted``1-System-Collections-Generic-IEnumerable{``0},TestCoordinator-Utilities-Enums-SortOptions- 'TestCoordinator.Utilities.CollectionExtensions.GetSorted``1(System.Collections.Generic.IEnumerable{``0},TestCoordinator.Utilities.Enums.SortOptions)')
- [ContentStringResourcesMap](#T-TestCoordinator-Utilities-Content-ContentStringResourcesMap 'TestCoordinator.Utilities.Content.ContentStringResourcesMap')
  - [Get(type)](#M-TestCoordinator-Utilities-Content-ContentStringResourcesMap-Get-System-Type- 'TestCoordinator.Utilities.Content.ContentStringResourcesMap.Get(System.Type)')
  - [Get\`\`1()](#M-TestCoordinator-Utilities-Content-ContentStringResourcesMap-Get``1 'TestCoordinator.Utilities.Content.ContentStringResourcesMap.Get``1')
- [DateTimeExtensions](#T-TestCoordinator-Utilities-DateTimeExtensions 'TestCoordinator.Utilities.DateTimeExtensions')
  - [ToFormattedString(dateTime,format)](#M-TestCoordinator-Utilities-DateTimeExtensions-ToFormattedString-System-DateTime,System-String- 'TestCoordinator.Utilities.DateTimeExtensions.ToFormattedString(System.DateTime,System.String)')
- [EnumExtensions](#T-TestCoordinator-Utilities-EnumExtensions 'TestCoordinator.Utilities.EnumExtensions')
  - [GetAttributeValue\`\`1(enumValue,property)](#M-TestCoordinator-Utilities-EnumExtensions-GetAttributeValue``1-System-Enum,System-String- 'TestCoordinator.Utilities.EnumExtensions.GetAttributeValue``1(System.Enum,System.String)')
- [FeaturesStringResources](#T-TestCoordinator-Utilities-Content-FeaturesStringResources 'TestCoordinator.Utilities.Content.FeaturesStringResources')
  - [AllItemsPageTitle](#P-TestCoordinator-Utilities-Content-FeaturesStringResources-AllItemsPageTitle 'TestCoordinator.Utilities.Content.FeaturesStringResources.AllItemsPageTitle')
  - [ChildItemsRouteFormat](#P-TestCoordinator-Utilities-Content-FeaturesStringResources-ChildItemsRouteFormat 'TestCoordinator.Utilities.Content.FeaturesStringResources.ChildItemsRouteFormat')
  - [CreateItemPageTitle](#P-TestCoordinator-Utilities-Content-FeaturesStringResources-CreateItemPageTitle 'TestCoordinator.Utilities.Content.FeaturesStringResources.CreateItemPageTitle')
  - [EntitiesNamePlural](#P-TestCoordinator-Utilities-Content-FeaturesStringResources-EntitiesNamePlural 'TestCoordinator.Utilities.Content.FeaturesStringResources.EntitiesNamePlural')
  - [EntityNameSingular](#P-TestCoordinator-Utilities-Content-FeaturesStringResources-EntityNameSingular 'TestCoordinator.Utilities.Content.FeaturesStringResources.EntityNameSingular')
  - [NoItemsPageTitle](#P-TestCoordinator-Utilities-Content-FeaturesStringResources-NoItemsPageTitle 'TestCoordinator.Utilities.Content.FeaturesStringResources.NoItemsPageTitle')
- [Guard](#T-TestCoordinator-Utilities-Guard 'TestCoordinator.Utilities.Guard')
  - [AgainstNull\`\`1(obj)](#M-TestCoordinator-Utilities-Guard-AgainstNull``1-``0- 'TestCoordinator.Utilities.Guard.AgainstNull``1(``0)')
- [IContentStringResources](#T-TestCoordinator-Utilities-Content-IContentStringResources 'TestCoordinator.Utilities.Content.IContentStringResources')
  - [AllItemsPageTitle](#P-TestCoordinator-Utilities-Content-IContentStringResources-AllItemsPageTitle 'TestCoordinator.Utilities.Content.IContentStringResources.AllItemsPageTitle')
  - [ChildItemsRouteFormat](#P-TestCoordinator-Utilities-Content-IContentStringResources-ChildItemsRouteFormat 'TestCoordinator.Utilities.Content.IContentStringResources.ChildItemsRouteFormat')
  - [CreateItemPageTitle](#P-TestCoordinator-Utilities-Content-IContentStringResources-CreateItemPageTitle 'TestCoordinator.Utilities.Content.IContentStringResources.CreateItemPageTitle')
  - [EntitiesNamePlural](#P-TestCoordinator-Utilities-Content-IContentStringResources-EntitiesNamePlural 'TestCoordinator.Utilities.Content.IContentStringResources.EntitiesNamePlural')
  - [EntityNameSingular](#P-TestCoordinator-Utilities-Content-IContentStringResources-EntityNameSingular 'TestCoordinator.Utilities.Content.IContentStringResources.EntityNameSingular')
  - [NoItemsPageTitle](#P-TestCoordinator-Utilities-Content-IContentStringResources-NoItemsPageTitle 'TestCoordinator.Utilities.Content.IContentStringResources.NoItemsPageTitle')
- [ProductsStringResources](#T-TestCoordinator-Utilities-Content-ProductsStringResources 'TestCoordinator.Utilities.Content.ProductsStringResources')
  - [AllItemsPageTitle](#P-TestCoordinator-Utilities-Content-ProductsStringResources-AllItemsPageTitle 'TestCoordinator.Utilities.Content.ProductsStringResources.AllItemsPageTitle')
  - [ChildItemsRouteFormat](#P-TestCoordinator-Utilities-Content-ProductsStringResources-ChildItemsRouteFormat 'TestCoordinator.Utilities.Content.ProductsStringResources.ChildItemsRouteFormat')
  - [CreateItemPageTitle](#P-TestCoordinator-Utilities-Content-ProductsStringResources-CreateItemPageTitle 'TestCoordinator.Utilities.Content.ProductsStringResources.CreateItemPageTitle')
  - [EntitiesNamePlural](#P-TestCoordinator-Utilities-Content-ProductsStringResources-EntitiesNamePlural 'TestCoordinator.Utilities.Content.ProductsStringResources.EntitiesNamePlural')
  - [EntityNameSingular](#P-TestCoordinator-Utilities-Content-ProductsStringResources-EntityNameSingular 'TestCoordinator.Utilities.Content.ProductsStringResources.EntityNameSingular')
  - [NoItemsPageTitle](#P-TestCoordinator-Utilities-Content-ProductsStringResources-NoItemsPageTitle 'TestCoordinator.Utilities.Content.ProductsStringResources.NoItemsPageTitle')
- [RandomGenerator](#T-TestCoordinator-Utilities-RandomGenerator 'TestCoordinator.Utilities.RandomGenerator')
  - [#ctor()](#M-TestCoordinator-Utilities-RandomGenerator-#ctor 'TestCoordinator.Utilities.RandomGenerator.#ctor')
  - [GetRandomDateTimeValue()](#M-TestCoordinator-Utilities-RandomGenerator-GetRandomDateTimeValue 'TestCoordinator.Utilities.RandomGenerator.GetRandomDateTimeValue')
  - [GetRandomInt(min,max)](#M-TestCoordinator-Utilities-RandomGenerator-GetRandomInt-System-Int32,System-Int32- 'TestCoordinator.Utilities.RandomGenerator.GetRandomInt(System.Int32,System.Int32)')
  - [GetRandomString()](#M-TestCoordinator-Utilities-RandomGenerator-GetRandomString 'TestCoordinator.Utilities.RandomGenerator.GetRandomString')
- [SortOptions](#T-TestCoordinator-Utilities-Enums-SortOptions 'TestCoordinator.Utilities.Enums.SortOptions')
  - [AlphabeticallyAsc](#F-TestCoordinator-Utilities-Enums-SortOptions-AlphabeticallyAsc 'TestCoordinator.Utilities.Enums.SortOptions.AlphabeticallyAsc')
  - [AlphabeticallyDesc](#F-TestCoordinator-Utilities-Enums-SortOptions-AlphabeticallyDesc 'TestCoordinator.Utilities.Enums.SortOptions.AlphabeticallyDesc')
  - [DateCreatedAsc](#F-TestCoordinator-Utilities-Enums-SortOptions-DateCreatedAsc 'TestCoordinator.Utilities.Enums.SortOptions.DateCreatedAsc')
  - [DateCreatedDesc](#F-TestCoordinator-Utilities-Enums-SortOptions-DateCreatedDesc 'TestCoordinator.Utilities.Enums.SortOptions.DateCreatedDesc')
  - [DateModifiedAsc](#F-TestCoordinator-Utilities-Enums-SortOptions-DateModifiedAsc 'TestCoordinator.Utilities.Enums.SortOptions.DateModifiedAsc')
  - [DateModifiedDesc](#F-TestCoordinator-Utilities-Enums-SortOptions-DateModifiedDesc 'TestCoordinator.Utilities.Enums.SortOptions.DateModifiedDesc')
- [StringExtensions](#T-TestCoordinator-Utilities-StringExtensions 'TestCoordinator.Utilities.StringExtensions')
  - [ToPlural(str)](#M-TestCoordinator-Utilities-StringExtensions-ToPlural-System-String- 'TestCoordinator.Utilities.StringExtensions.ToPlural(System.String)')
  - [ToSingular(str)](#M-TestCoordinator-Utilities-StringExtensions-ToSingular-System-String- 'TestCoordinator.Utilities.StringExtensions.ToSingular(System.String)')
- [TestCasesStringResources](#T-TestCoordinator-Utilities-Content-TestCasesStringResources 'TestCoordinator.Utilities.Content.TestCasesStringResources')
  - [AllItemsPageTitle](#P-TestCoordinator-Utilities-Content-TestCasesStringResources-AllItemsPageTitle 'TestCoordinator.Utilities.Content.TestCasesStringResources.AllItemsPageTitle')
  - [ChildItemsRouteFormat](#P-TestCoordinator-Utilities-Content-TestCasesStringResources-ChildItemsRouteFormat 'TestCoordinator.Utilities.Content.TestCasesStringResources.ChildItemsRouteFormat')
  - [CreateItemPageTitle](#P-TestCoordinator-Utilities-Content-TestCasesStringResources-CreateItemPageTitle 'TestCoordinator.Utilities.Content.TestCasesStringResources.CreateItemPageTitle')
  - [EntitiesNamePlural](#P-TestCoordinator-Utilities-Content-TestCasesStringResources-EntitiesNamePlural 'TestCoordinator.Utilities.Content.TestCasesStringResources.EntitiesNamePlural')
  - [EntityNameSingular](#P-TestCoordinator-Utilities-Content-TestCasesStringResources-EntityNameSingular 'TestCoordinator.Utilities.Content.TestCasesStringResources.EntityNameSingular')
  - [NoItemsPageTitle](#P-TestCoordinator-Utilities-Content-TestCasesStringResources-NoItemsPageTitle 'TestCoordinator.Utilities.Content.TestCasesStringResources.NoItemsPageTitle')
- [TestEntitiesFactory](#T-TestCoordinator-Utilities-TestEntitiesFactory 'TestCoordinator.Utilities.TestEntitiesFactory')
  - [CreateRandomContentItem\`\`1()](#M-TestCoordinator-Utilities-TestEntitiesFactory-CreateRandomContentItem``1 'TestCoordinator.Utilities.TestEntitiesFactory.CreateRandomContentItem``1')
  - [CreateRandomContentItems\`\`1(count)](#M-TestCoordinator-Utilities-TestEntitiesFactory-CreateRandomContentItems``1-System-Int32- 'TestCoordinator.Utilities.TestEntitiesFactory.CreateRandomContentItems``1(System.Int32)')
- [TestEntitiesHierarchyContainer](#T-TestCoordinator-Utilities-TestEntitiesHierarchyContainer 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer')
  - [#ctor()](#M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-#ctor 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.#ctor')
  - [AllEntitiesCount](#P-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-AllEntitiesCount 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.AllEntitiesCount')
  - [Areas](#P-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-Areas 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.Areas')
  - [Features](#P-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-Features 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.Features')
  - [Products](#P-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-Products 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.Products')
  - [TestCases](#P-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-TestCases 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.TestCases')
  - [DeleteAllEntities()](#M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-DeleteAllEntities 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.DeleteAllEntities')
  - [DeleteProductHierarchy(productId)](#M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-DeleteProductHierarchy-System-Int32- 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.DeleteProductHierarchy(System.Int32)')
  - [WithAreas(count,productIndex,featureIndex)](#M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-WithAreas-System-Int32,System-Int32,System-Int32- 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.WithAreas(System.Int32,System.Int32,System.Int32)')
  - [WithFeatures(count,productIndex)](#M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-WithFeatures-System-Int32,System-Int32- 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.WithFeatures(System.Int32,System.Int32)')
  - [WithProduct()](#M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-WithProduct 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.WithProduct')
  - [WithTestCases(count,productIndex,featureIndex,areaIndex)](#M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-WithTestCases-System-Int32,System-Int32,System-Int32,System-Int32- 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer.WithTestCases(System.Int32,System.Int32,System.Int32,System.Int32)')
- [TypeNameResolver](#T-TestCoordinator-Utilities-TypeNameResolver 'TestCoordinator.Utilities.TypeNameResolver')
  - [GetChildItemsControllerName(type)](#M-TestCoordinator-Utilities-TypeNameResolver-GetChildItemsControllerName-System-Type- 'TestCoordinator.Utilities.TypeNameResolver.GetChildItemsControllerName(System.Type)')
  - [GetControllerName(type)](#M-TestCoordinator-Utilities-TypeNameResolver-GetControllerName-System-Type- 'TestCoordinator.Utilities.TypeNameResolver.GetControllerName(System.Type)')
  - [GetTypeDisplayName(type,pluralForm,lowerCase)](#M-TestCoordinator-Utilities-TypeNameResolver-GetTypeDisplayName-System-Type,System-Boolean,System-Boolean- 'TestCoordinator.Utilities.TypeNameResolver.GetTypeDisplayName(System.Type,System.Boolean,System.Boolean)')
- [UrlParameterResolver](#T-TestCoordinator-Utilities-UrlParameterResolver 'TestCoordinator.Utilities.UrlParameterResolver')
  - [ResolveSortOption(sortOption)](#M-TestCoordinator-Utilities-UrlParameterResolver-ResolveSortOption-System-String- 'TestCoordinator.Utilities.UrlParameterResolver.ResolveSortOption(System.String)')

<a name='T-TestCoordinator-Utilities-Content-AreasStringResources'></a>
## AreasStringResources `type`

##### Namespace

TestCoordinator.Utilities.Content

##### Summary

String resources for areas.

##### See Also

- [TestCoordinator.Utilities.Content.IContentStringResources](#T-TestCoordinator-Utilities-Content-IContentStringResources 'TestCoordinator.Utilities.Content.IContentStringResources')

<a name='P-TestCoordinator-Utilities-Content-AreasStringResources-AllItemsPageTitle'></a>
### AllItemsPageTitle `property`

##### Summary

Gets all items page title.

<a name='P-TestCoordinator-Utilities-Content-AreasStringResources-ChildItemsRouteFormat'></a>
### ChildItemsRouteFormat `property`

##### Summary

Gets the child items route format.

<a name='P-TestCoordinator-Utilities-Content-AreasStringResources-CreateItemPageTitle'></a>
### CreateItemPageTitle `property`

##### Summary

Gets the create item page title.

<a name='P-TestCoordinator-Utilities-Content-AreasStringResources-EntitiesNamePlural'></a>
### EntitiesNamePlural `property`

##### Summary

Gets the entities name plural.

<a name='P-TestCoordinator-Utilities-Content-AreasStringResources-EntityNameSingular'></a>
### EntityNameSingular `property`

##### Summary

Gets the entity name singular.

<a name='P-TestCoordinator-Utilities-Content-AreasStringResources-NoItemsPageTitle'></a>
### NoItemsPageTitle `property`

##### Summary

Gets the no items page title.

<a name='T-TestCoordinator-Utilities-CollectionExtensions'></a>
## CollectionExtensions `type`

##### Namespace

TestCoordinator.Utilities

##### Summary

Extension methods on collections.

<a name='M-TestCoordinator-Utilities-CollectionExtensions-GetSorted``1-System-Collections-Generic-IEnumerable{``0},TestCoordinator-Utilities-Enums-SortOptions-'></a>
### GetSorted\`\`1(items,sortOption) `method`

##### Summary

Gets the collection of items sorted by specified option.

##### Returns

Sorted collection.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| items | [System.Collections.Generic.IEnumerable{\`\`0}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{``0}') | The items collection. |
| sortOption | [TestCoordinator.Utilities.Enums.SortOptions](#T-TestCoordinator-Utilities-Enums-SortOptions 'TestCoordinator.Utilities.Enums.SortOptions') | The sort option. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the items in the collection. |

<a name='T-TestCoordinator-Utilities-Content-ContentStringResourcesMap'></a>
## ContentStringResourcesMap `type`

##### Namespace

TestCoordinator.Utilities.Content

##### Summary

Holds a map of string resources per type

<a name='M-TestCoordinator-Utilities-Content-ContentStringResourcesMap-Get-System-Type-'></a>
### Get(type) `method`

##### Summary

Gets a content string resources instance

##### Returns

The type of content to retrieve resources for

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| type | [System.Type](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Type 'System.Type') | The type. |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.ArgumentException](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.ArgumentException 'System.ArgumentException') | Invalid type. |

<a name='M-TestCoordinator-Utilities-Content-ContentStringResourcesMap-Get``1'></a>
### Get\`\`1() `method`

##### Summary

Gets a content string resources instance

##### Returns

The content string resources instance

##### Parameters

This method has no parameters.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of content to retrieve resources for |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.ArgumentException](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.ArgumentException 'System.ArgumentException') | Invalid type. |

<a name='T-TestCoordinator-Utilities-DateTimeExtensions'></a>
## DateTimeExtensions `type`

##### Namespace

TestCoordinator.Utilities

##### Summary

Extension methods for DateTime

<a name='M-TestCoordinator-Utilities-DateTimeExtensions-ToFormattedString-System-DateTime,System-String-'></a>
### ToFormattedString(dateTime,format) `method`

##### Summary

Returns a date-time value in specified format.

##### Returns

Formatted date-time.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| dateTime | [System.DateTime](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.DateTime 'System.DateTime') | The date time. |
| format | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The format. |

<a name='T-TestCoordinator-Utilities-EnumExtensions'></a>
## EnumExtensions `type`

##### Namespace

TestCoordinator.Utilities

##### Summary

Extension methods for Enumerations.

<a name='M-TestCoordinator-Utilities-EnumExtensions-GetAttributeValue``1-System-Enum,System-String-'></a>
### GetAttributeValue\`\`1(enumValue,property) `method`

##### Summary

Gets an attribute value.

##### Returns

The resolved attribute value.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| enumValue | [System.Enum](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Enum 'System.Enum') | The enumeration value. |
| property | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The attribute property. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| TAttr | The type of the attribute. |

<a name='T-TestCoordinator-Utilities-Content-FeaturesStringResources'></a>
## FeaturesStringResources `type`

##### Namespace

TestCoordinator.Utilities.Content

##### Summary

String resources for features

##### See Also

- [TestCoordinator.Utilities.Content.IContentStringResources](#T-TestCoordinator-Utilities-Content-IContentStringResources 'TestCoordinator.Utilities.Content.IContentStringResources')

<a name='P-TestCoordinator-Utilities-Content-FeaturesStringResources-AllItemsPageTitle'></a>
### AllItemsPageTitle `property`

##### Summary

Gets all items page title.

<a name='P-TestCoordinator-Utilities-Content-FeaturesStringResources-ChildItemsRouteFormat'></a>
### ChildItemsRouteFormat `property`

##### Summary

Gets the child items route format.

<a name='P-TestCoordinator-Utilities-Content-FeaturesStringResources-CreateItemPageTitle'></a>
### CreateItemPageTitle `property`

##### Summary

Gets the create item page title.

<a name='P-TestCoordinator-Utilities-Content-FeaturesStringResources-EntitiesNamePlural'></a>
### EntitiesNamePlural `property`

##### Summary

Gets the entities name plural.

<a name='P-TestCoordinator-Utilities-Content-FeaturesStringResources-EntityNameSingular'></a>
### EntityNameSingular `property`

##### Summary

Gets the entity name singular.

<a name='P-TestCoordinator-Utilities-Content-FeaturesStringResources-NoItemsPageTitle'></a>
### NoItemsPageTitle `property`

##### Summary

Gets the no items page title.

<a name='T-TestCoordinator-Utilities-Guard'></a>
## Guard `type`

##### Namespace

TestCoordinator.Utilities

##### Summary

Used for arguments validation.

<a name='M-TestCoordinator-Utilities-Guard-AgainstNull``1-``0-'></a>
### AgainstNull\`\`1(obj) `method`

##### Summary

Guards against using a nullable object.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| obj | [\`\`0](#T-``0 '``0') | The object. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the object. |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.ArgumentNullException](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.ArgumentNullException 'System.ArgumentNullException') | Thrown if object is NULL. |

<a name='T-TestCoordinator-Utilities-Content-IContentStringResources'></a>
## IContentStringResources `type`

##### Namespace

TestCoordinator.Utilities.Content

##### Summary

Denotes content string resources.

<a name='P-TestCoordinator-Utilities-Content-IContentStringResources-AllItemsPageTitle'></a>
### AllItemsPageTitle `property`

##### Summary

Gets all items page title.

<a name='P-TestCoordinator-Utilities-Content-IContentStringResources-ChildItemsRouteFormat'></a>
### ChildItemsRouteFormat `property`

##### Summary

Gets the child items route format.

<a name='P-TestCoordinator-Utilities-Content-IContentStringResources-CreateItemPageTitle'></a>
### CreateItemPageTitle `property`

##### Summary

Gets the create item page title.

<a name='P-TestCoordinator-Utilities-Content-IContentStringResources-EntitiesNamePlural'></a>
### EntitiesNamePlural `property`

##### Summary

Gets the entities name plural.

<a name='P-TestCoordinator-Utilities-Content-IContentStringResources-EntityNameSingular'></a>
### EntityNameSingular `property`

##### Summary

Gets the entity name singular.

<a name='P-TestCoordinator-Utilities-Content-IContentStringResources-NoItemsPageTitle'></a>
### NoItemsPageTitle `property`

##### Summary

Gets the no items page title.

<a name='T-TestCoordinator-Utilities-Content-ProductsStringResources'></a>
## ProductsStringResources `type`

##### Namespace

TestCoordinator.Utilities.Content

##### Summary

String resources for products

##### See Also

- [TestCoordinator.Utilities.Content.IContentStringResources](#T-TestCoordinator-Utilities-Content-IContentStringResources 'TestCoordinator.Utilities.Content.IContentStringResources')

<a name='P-TestCoordinator-Utilities-Content-ProductsStringResources-AllItemsPageTitle'></a>
### AllItemsPageTitle `property`

##### Summary

Gets all items page title.

<a name='P-TestCoordinator-Utilities-Content-ProductsStringResources-ChildItemsRouteFormat'></a>
### ChildItemsRouteFormat `property`

##### Summary

Gets the child items route format.

<a name='P-TestCoordinator-Utilities-Content-ProductsStringResources-CreateItemPageTitle'></a>
### CreateItemPageTitle `property`

##### Summary

Gets the create item page title.

<a name='P-TestCoordinator-Utilities-Content-ProductsStringResources-EntitiesNamePlural'></a>
### EntitiesNamePlural `property`

##### Summary

Gets the entities name plural.

<a name='P-TestCoordinator-Utilities-Content-ProductsStringResources-EntityNameSingular'></a>
### EntityNameSingular `property`

##### Summary

Gets the entity name singular.

<a name='P-TestCoordinator-Utilities-Content-ProductsStringResources-NoItemsPageTitle'></a>
### NoItemsPageTitle `property`

##### Summary

Gets the no items page title.

<a name='T-TestCoordinator-Utilities-RandomGenerator'></a>
## RandomGenerator `type`

##### Namespace

TestCoordinator.Utilities

##### Summary

Provides different random values for different types.

<a name='M-TestCoordinator-Utilities-RandomGenerator-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [RandomGenerator](#T-TestCoordinator-Utilities-RandomGenerator 'TestCoordinator.Utilities.RandomGenerator') class.

##### Parameters

This constructor has no parameters.

<a name='M-TestCoordinator-Utilities-RandomGenerator-GetRandomDateTimeValue'></a>
### GetRandomDateTimeValue() `method`

##### Summary

Gets a random DateTime value.

##### Returns

DateTime value.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Utilities-RandomGenerator-GetRandomInt-System-Int32,System-Int32-'></a>
### GetRandomInt(min,max) `method`

##### Summary

Gets a random integer.

##### Returns

Random integer value.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| min | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The minimum value. |
| max | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The maximum value. |

<a name='M-TestCoordinator-Utilities-RandomGenerator-GetRandomString'></a>
### GetRandomString() `method`

##### Summary

Gets a random string.

##### Returns

Random string.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Utilities-Enums-SortOptions'></a>
## SortOptions `type`

##### Namespace

TestCoordinator.Utilities.Enums

##### Summary

Enumeration that holds different sorting options.

<a name='F-TestCoordinator-Utilities-Enums-SortOptions-AlphabeticallyAsc'></a>
### AlphabeticallyAsc `constants`

##### Summary

Alphabetically, Ascending

<a name='F-TestCoordinator-Utilities-Enums-SortOptions-AlphabeticallyDesc'></a>
### AlphabeticallyDesc `constants`

##### Summary

Alphabetically, Descending

<a name='F-TestCoordinator-Utilities-Enums-SortOptions-DateCreatedAsc'></a>
### DateCreatedAsc `constants`

##### Summary

Date Created, Ascending

<a name='F-TestCoordinator-Utilities-Enums-SortOptions-DateCreatedDesc'></a>
### DateCreatedDesc `constants`

##### Summary

Date Created, Descending

<a name='F-TestCoordinator-Utilities-Enums-SortOptions-DateModifiedAsc'></a>
### DateModifiedAsc `constants`

##### Summary

Date Modified, Ascending

<a name='F-TestCoordinator-Utilities-Enums-SortOptions-DateModifiedDesc'></a>
### DateModifiedDesc `constants`

##### Summary

Date Modified, Descending

<a name='T-TestCoordinator-Utilities-StringExtensions'></a>
## StringExtensions `type`

##### Namespace

TestCoordinator.Utilities

##### Summary

Extension methods for String

<a name='M-TestCoordinator-Utilities-StringExtensions-ToPlural-System-String-'></a>
### ToPlural(str) `method`

##### Summary

Converts a string to its plural form.

##### Returns

The plural form.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| str | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The string. |

<a name='M-TestCoordinator-Utilities-StringExtensions-ToSingular-System-String-'></a>
### ToSingular(str) `method`

##### Summary

Converts a string to its singular form.

##### Returns

The singular form.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| str | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The string. |

<a name='T-TestCoordinator-Utilities-Content-TestCasesStringResources'></a>
## TestCasesStringResources `type`

##### Namespace

TestCoordinator.Utilities.Content

##### Summary

String resources for test cases

##### See Also

- [TestCoordinator.Utilities.Content.IContentStringResources](#T-TestCoordinator-Utilities-Content-IContentStringResources 'TestCoordinator.Utilities.Content.IContentStringResources')

<a name='P-TestCoordinator-Utilities-Content-TestCasesStringResources-AllItemsPageTitle'></a>
### AllItemsPageTitle `property`

##### Summary

Gets all items page title.

<a name='P-TestCoordinator-Utilities-Content-TestCasesStringResources-ChildItemsRouteFormat'></a>
### ChildItemsRouteFormat `property`

##### Summary

Gets the child items route format.

<a name='P-TestCoordinator-Utilities-Content-TestCasesStringResources-CreateItemPageTitle'></a>
### CreateItemPageTitle `property`

##### Summary

Gets the create item page title.

<a name='P-TestCoordinator-Utilities-Content-TestCasesStringResources-EntitiesNamePlural'></a>
### EntitiesNamePlural `property`

##### Summary

Gets the entities name plural.

<a name='P-TestCoordinator-Utilities-Content-TestCasesStringResources-EntityNameSingular'></a>
### EntityNameSingular `property`

##### Summary

Gets the entity name singular.

<a name='P-TestCoordinator-Utilities-Content-TestCasesStringResources-NoItemsPageTitle'></a>
### NoItemsPageTitle `property`

##### Summary

Gets the no items page title.

<a name='T-TestCoordinator-Utilities-TestEntitiesFactory'></a>
## TestEntitiesFactory `type`

##### Namespace

TestCoordinator.Utilities

##### Summary

Factory for creating entities used in tests.

<a name='M-TestCoordinator-Utilities-TestEntitiesFactory-CreateRandomContentItem``1'></a>
### CreateRandomContentItem\`\`1() `method`

##### Summary

Creates a random entity of specific type.

##### Returns

The created entity.

##### Parameters

This method has no parameters.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the entity to create. |

<a name='M-TestCoordinator-Utilities-TestEntitiesFactory-CreateRandomContentItems``1-System-Int32-'></a>
### CreateRandomContentItems\`\`1(count) `method`

##### Summary

Creates a number of random entities of specific type.

##### Returns

The collection of created entities.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The count. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the entities to create. |

<a name='T-TestCoordinator-Utilities-TestEntitiesHierarchyContainer'></a>
## TestEntitiesHierarchyContainer `type`

##### Namespace

TestCoordinator.Utilities

##### Summary

Container for hierarchies of test entities

<a name='M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [TestEntitiesHierarchyContainer](#T-TestCoordinator-Utilities-TestEntitiesHierarchyContainer 'TestCoordinator.Utilities.TestEntitiesHierarchyContainer') class.

##### Parameters

This constructor has no parameters.

<a name='P-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-AllEntitiesCount'></a>
### AllEntitiesCount `property`

##### Summary

Gets all entities count.

<a name='P-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-Areas'></a>
### Areas `property`

##### Summary

Gets the areas.

<a name='P-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-Features'></a>
### Features `property`

##### Summary

Gets the features.

<a name='P-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-Products'></a>
### Products `property`

##### Summary

Gets the products.

<a name='P-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-TestCases'></a>
### TestCases `property`

##### Summary

Gets the test cases.

<a name='M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-DeleteAllEntities'></a>
### DeleteAllEntities() `method`

##### Summary

Deletes all entities.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-DeleteProductHierarchy-System-Int32-'></a>
### DeleteProductHierarchy(productId) `method`

##### Summary

Deletes a product hierarchy.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| productId | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The product identifier. |

<a name='M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-WithAreas-System-Int32,System-Int32,System-Int32-'></a>
### WithAreas(count,productIndex,featureIndex) `method`

##### Summary

Creates several area(s) in a hierarchy.

##### Returns

The container instance.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The count. |
| productIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Index of the product in the hierarchy. |
| featureIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Index of the feature in the hierarchy. |

<a name='M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-WithFeatures-System-Int32,System-Int32-'></a>
### WithFeatures(count,productIndex) `method`

##### Summary

Creates several feature(s) for a product.

##### Returns

The container instance.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The count. |
| productIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Index of the product in the hierarchy. |

<a name='M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-WithProduct'></a>
### WithProduct() `method`

##### Summary

Creates a product.

##### Returns

The container instance.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Utilities-TestEntitiesHierarchyContainer-WithTestCases-System-Int32,System-Int32,System-Int32,System-Int32-'></a>
### WithTestCases(count,productIndex,featureIndex,areaIndex) `method`

##### Summary

Creates several test case(s) in a hierarchy.

##### Returns

The container instance.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The count. |
| productIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Index of the product in the hierarchy. |
| featureIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Index of the feature in the hierarchy. |
| areaIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Index of the area in the hierarchy. |

<a name='T-TestCoordinator-Utilities-TypeNameResolver'></a>
## TypeNameResolver `type`

##### Namespace

TestCoordinator.Utilities

##### Summary

Resolves labels and names for different types.

<a name='M-TestCoordinator-Utilities-TypeNameResolver-GetChildItemsControllerName-System-Type-'></a>
### GetChildItemsControllerName(type) `method`

##### Summary

Gets the name of the child items controller for specific type.

##### Returns

Controller's name.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| type | [System.Type](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Type 'System.Type') | The type. |

<a name='M-TestCoordinator-Utilities-TypeNameResolver-GetControllerName-System-Type-'></a>
### GetControllerName(type) `method`

##### Summary

Gets the name of the controller.

##### Returns

Controller's name.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| type | [System.Type](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Type 'System.Type') | The type. |

<a name='M-TestCoordinator-Utilities-TypeNameResolver-GetTypeDisplayName-System-Type,System-Boolean,System-Boolean-'></a>
### GetTypeDisplayName(type,pluralForm,lowerCase) `method`

##### Summary

Gets the type display name.

##### Returns

The display name of this type.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| type | [System.Type](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Type 'System.Type') | The system type of the object which name we want to resolve. |
| pluralForm | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | If set to `true`, name will be returned in its plural form. |
| lowerCase | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | If set to `true`, lower case will be used. |

<a name='T-TestCoordinator-Utilities-UrlParameterResolver'></a>
## UrlParameterResolver `type`

##### Namespace

TestCoordinator.Utilities

##### Summary

Resolves different URL parameters.

<a name='M-TestCoordinator-Utilities-UrlParameterResolver-ResolveSortOption-System-String-'></a>
### ResolveSortOption(sortOption) `method`

##### Summary

Resolves the sort option.

##### Returns

The corresponding SortOptions enumeration value.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| sortOption | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The sort option. |
