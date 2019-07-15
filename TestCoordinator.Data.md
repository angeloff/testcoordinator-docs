<a name='assembly'></a>
# TestCoordinator.Data

## Contents

- [AttachmentsRepository](#T-TestCoordinator-Data-AttachmentsRepository 'TestCoordinator.Data.AttachmentsRepository')
  - [#ctor(databaseContext)](#M-TestCoordinator-Data-AttachmentsRepository-#ctor-TestCoordinator-Db-IDbContext- 'TestCoordinator.Data.AttachmentsRepository.#ctor(TestCoordinator.Db.IDbContext)')
- [ContentRepository\`1](#T-TestCoordinator-Data-ContentRepository`1 'TestCoordinator.Data.ContentRepository`1')
  - [#ctor(databaseContext)](#M-TestCoordinator-Data-ContentRepository`1-#ctor-TestCoordinator-Db-IDbContext- 'TestCoordinator.Data.ContentRepository`1.#ctor(TestCoordinator.Db.IDbContext)')
  - [GetAll(parentId)](#M-TestCoordinator-Data-ContentRepository`1-GetAll-System-Nullable{System-Int32}- 'TestCoordinator.Data.ContentRepository`1.GetAll(System.Nullable{System.Int32})')
  - [Insert(entity)](#M-TestCoordinator-Data-ContentRepository`1-Insert-`0- 'TestCoordinator.Data.ContentRepository`1.Insert(`0)')
  - [LockItem(item,clientId)](#M-TestCoordinator-Data-ContentRepository`1-LockItem-`0,System-String- 'TestCoordinator.Data.ContentRepository`1.LockItem(`0,System.String)')
  - [UnlockItem(item)](#M-TestCoordinator-Data-ContentRepository`1-UnlockItem-`0- 'TestCoordinator.Data.ContentRepository`1.UnlockItem(`0)')
  - [Update(entityToUpdate)](#M-TestCoordinator-Data-ContentRepository`1-Update-`0- 'TestCoordinator.Data.ContentRepository`1.Update(`0)')
- [GenericRepository\`1](#T-TestCoordinator-Data-GenericRepository`1 'TestCoordinator.Data.GenericRepository`1')
  - [#ctor(context)](#M-TestCoordinator-Data-GenericRepository`1-#ctor-TestCoordinator-Db-IDbContext- 'TestCoordinator.Data.GenericRepository`1.#ctor(TestCoordinator.Db.IDbContext)')
  - [#ctor()](#M-TestCoordinator-Data-GenericRepository`1-#ctor 'TestCoordinator.Data.GenericRepository`1.#ctor')
  - [Context](#P-TestCoordinator-Data-GenericRepository`1-Context 'TestCoordinator.Data.GenericRepository`1.Context')
  - [DbSet](#P-TestCoordinator-Data-GenericRepository`1-DbSet 'TestCoordinator.Data.GenericRepository`1.DbSet')
  - [Delete(id)](#M-TestCoordinator-Data-GenericRepository`1-Delete-System-Object- 'TestCoordinator.Data.GenericRepository`1.Delete(System.Object)')
  - [Delete(entityToDelete)](#M-TestCoordinator-Data-GenericRepository`1-Delete-`0- 'TestCoordinator.Data.GenericRepository`1.Delete(`0)')
  - [GetAll()](#M-TestCoordinator-Data-GenericRepository`1-GetAll 'TestCoordinator.Data.GenericRepository`1.GetAll')
  - [GetAll(filterExpression)](#M-TestCoordinator-Data-GenericRepository`1-GetAll-System-Func{`0,System-Boolean}- 'TestCoordinator.Data.GenericRepository`1.GetAll(System.Func{`0,System.Boolean})')
  - [GetById(id)](#M-TestCoordinator-Data-GenericRepository`1-GetById-System-Object- 'TestCoordinator.Data.GenericRepository`1.GetById(System.Object)')
  - [Insert(entity)](#M-TestCoordinator-Data-GenericRepository`1-Insert-`0- 'TestCoordinator.Data.GenericRepository`1.Insert(`0)')
  - [Update(entityToUpdate)](#M-TestCoordinator-Data-GenericRepository`1-Update-`0- 'TestCoordinator.Data.GenericRepository`1.Update(`0)')
- [IContentRepository\`1](#T-TestCoordinator-Data-IContentRepository`1 'TestCoordinator.Data.IContentRepository`1')
  - [GetAll(parentId)](#M-TestCoordinator-Data-IContentRepository`1-GetAll-System-Nullable{System-Int32}- 'TestCoordinator.Data.IContentRepository`1.GetAll(System.Nullable{System.Int32})')
  - [LockItem(item,clientId)](#M-TestCoordinator-Data-IContentRepository`1-LockItem-`0,System-String- 'TestCoordinator.Data.IContentRepository`1.LockItem(`0,System.String)')
  - [UnlockItem(item)](#M-TestCoordinator-Data-IContentRepository`1-UnlockItem-`0- 'TestCoordinator.Data.IContentRepository`1.UnlockItem(`0)')
- [IRepository\`1](#T-TestCoordinator-Data-IRepository`1 'TestCoordinator.Data.IRepository`1')
  - [Context](#P-TestCoordinator-Data-IRepository`1-Context 'TestCoordinator.Data.IRepository`1.Context')
  - [DbSet](#P-TestCoordinator-Data-IRepository`1-DbSet 'TestCoordinator.Data.IRepository`1.DbSet')
  - [Delete(id)](#M-TestCoordinator-Data-IRepository`1-Delete-System-Object- 'TestCoordinator.Data.IRepository`1.Delete(System.Object)')
  - [Delete(entityToDelete)](#M-TestCoordinator-Data-IRepository`1-Delete-`0- 'TestCoordinator.Data.IRepository`1.Delete(`0)')
  - [GetAll()](#M-TestCoordinator-Data-IRepository`1-GetAll 'TestCoordinator.Data.IRepository`1.GetAll')
  - [GetAll(filterExpression)](#M-TestCoordinator-Data-IRepository`1-GetAll-System-Func{`0,System-Boolean}- 'TestCoordinator.Data.IRepository`1.GetAll(System.Func{`0,System.Boolean})')
  - [GetById(id)](#M-TestCoordinator-Data-IRepository`1-GetById-System-Object- 'TestCoordinator.Data.IRepository`1.GetById(System.Object)')
  - [Insert(entity)](#M-TestCoordinator-Data-IRepository`1-Insert-`0- 'TestCoordinator.Data.IRepository`1.Insert(`0)')
  - [Update(entityToUpdate)](#M-TestCoordinator-Data-IRepository`1-Update-`0- 'TestCoordinator.Data.IRepository`1.Update(`0)')
- [IUnitOfWork](#T-TestCoordinator-Data-IUnitOfWork 'TestCoordinator.Data.IUnitOfWork')
  - [AreasRepository](#P-TestCoordinator-Data-IUnitOfWork-AreasRepository 'TestCoordinator.Data.IUnitOfWork.AreasRepository')
  - [AttachmentsRepository](#P-TestCoordinator-Data-IUnitOfWork-AttachmentsRepository 'TestCoordinator.Data.IUnitOfWork.AttachmentsRepository')
  - [FeaturesRepository](#P-TestCoordinator-Data-IUnitOfWork-FeaturesRepository 'TestCoordinator.Data.IUnitOfWork.FeaturesRepository')
  - [ProductsRepository](#P-TestCoordinator-Data-IUnitOfWork-ProductsRepository 'TestCoordinator.Data.IUnitOfWork.ProductsRepository')
  - [TestCasesRepository](#P-TestCoordinator-Data-IUnitOfWork-TestCasesRepository 'TestCoordinator.Data.IUnitOfWork.TestCasesRepository')
  - [Dispose()](#M-TestCoordinator-Data-IUnitOfWork-Dispose 'TestCoordinator.Data.IUnitOfWork.Dispose')
  - [GetContentRepository\`\`1()](#M-TestCoordinator-Data-IUnitOfWork-GetContentRepository``1 'TestCoordinator.Data.IUnitOfWork.GetContentRepository``1')
  - [Save()](#M-TestCoordinator-Data-IUnitOfWork-Save 'TestCoordinator.Data.IUnitOfWork.Save')
- [UnitOfWork](#T-TestCoordinator-Data-UnitOfWork 'TestCoordinator.Data.UnitOfWork')
  - [#ctor()](#M-TestCoordinator-Data-UnitOfWork-#ctor 'TestCoordinator.Data.UnitOfWork.#ctor')
  - [AreasRepository](#P-TestCoordinator-Data-UnitOfWork-AreasRepository 'TestCoordinator.Data.UnitOfWork.AreasRepository')
  - [AttachmentsRepository](#P-TestCoordinator-Data-UnitOfWork-AttachmentsRepository 'TestCoordinator.Data.UnitOfWork.AttachmentsRepository')
  - [FeaturesRepository](#P-TestCoordinator-Data-UnitOfWork-FeaturesRepository 'TestCoordinator.Data.UnitOfWork.FeaturesRepository')
  - [ProductsRepository](#P-TestCoordinator-Data-UnitOfWork-ProductsRepository 'TestCoordinator.Data.UnitOfWork.ProductsRepository')
  - [TestCasesRepository](#P-TestCoordinator-Data-UnitOfWork-TestCasesRepository 'TestCoordinator.Data.UnitOfWork.TestCasesRepository')
  - [Dispose()](#M-TestCoordinator-Data-UnitOfWork-Dispose 'TestCoordinator.Data.UnitOfWork.Dispose')
  - [Dispose(disposing)](#M-TestCoordinator-Data-UnitOfWork-Dispose-System-Boolean- 'TestCoordinator.Data.UnitOfWork.Dispose(System.Boolean)')
  - [GetContentRepository\`\`1()](#M-TestCoordinator-Data-UnitOfWork-GetContentRepository``1 'TestCoordinator.Data.UnitOfWork.GetContentRepository``1')
  - [Save()](#M-TestCoordinator-Data-UnitOfWork-Save 'TestCoordinator.Data.UnitOfWork.Save')

<a name='T-TestCoordinator-Data-AttachmentsRepository'></a>
## AttachmentsRepository `type`

##### Namespace

TestCoordinator.Data

##### Summary

Repository for attachments

##### See Also

- [TestCoordinator.Data.Repository.IRepository<TestCoordinator.Model.Attachment>](#!-TestCoordinator-Data-Repository-IRepository<TestCoordinator-Model-Attachment> 'TestCoordinator.Data.Repository.IRepository<TestCoordinator.Model.Attachment>')

<a name='M-TestCoordinator-Data-AttachmentsRepository-#ctor-TestCoordinator-Db-IDbContext-'></a>
### #ctor(databaseContext) `constructor`

##### Summary

Initializes a new instance of the [AttachmentsRepository](#T-TestCoordinator-Data-AttachmentsRepository 'TestCoordinator.Data.AttachmentsRepository') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| databaseContext | [TestCoordinator.Db.IDbContext](#T-TestCoordinator-Db-IDbContext 'TestCoordinator.Db.IDbContext') | The database context. |

<a name='T-TestCoordinator-Data-ContentRepository`1'></a>
## ContentRepository\`1 `type`

##### Namespace

TestCoordinator.Data

##### Summary

Base repository for content items.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the content item |

##### See Also

- [TestCoordinator.Data.GenericRepository\`1](#T-TestCoordinator-Data-GenericRepository`1 'TestCoordinator.Data.GenericRepository`1')

<a name='M-TestCoordinator-Data-ContentRepository`1-#ctor-TestCoordinator-Db-IDbContext-'></a>
### #ctor(databaseContext) `constructor`

##### Summary

Initializes a new instance of the [ContentRepository\`1](#T-TestCoordinator-Data-ContentRepository`1 'TestCoordinator.Data.ContentRepository`1') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| databaseContext | [TestCoordinator.Db.IDbContext](#T-TestCoordinator-Db-IDbContext 'TestCoordinator.Db.IDbContext') | The database context. |

<a name='M-TestCoordinator-Data-ContentRepository`1-GetAll-System-Nullable{System-Int32}-'></a>
### GetAll(parentId) `method`

##### Summary

Gets all entities.

##### Returns

All entities.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent identifier. |

<a name='M-TestCoordinator-Data-ContentRepository`1-Insert-`0-'></a>
### Insert(entity) `method`

##### Summary

Inserts the specified entity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| entity | [\`0](#T-`0 '`0') | The entity. |

<a name='M-TestCoordinator-Data-ContentRepository`1-LockItem-`0,System-String-'></a>
### LockItem(item,clientId) `method`

##### Summary

Locks the item.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [\`0](#T-`0 '`0') | The item. |
| clientId | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The client identifier. |

<a name='M-TestCoordinator-Data-ContentRepository`1-UnlockItem-`0-'></a>
### UnlockItem(item) `method`

##### Summary

Unlocks the item.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [\`0](#T-`0 '`0') | The item. |

<a name='M-TestCoordinator-Data-ContentRepository`1-Update-`0-'></a>
### Update(entityToUpdate) `method`

##### Summary

Updates the specified entity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| entityToUpdate | [\`0](#T-`0 '`0') | The entity to update. |

<a name='T-TestCoordinator-Data-GenericRepository`1'></a>
## GenericRepository\`1 `type`

##### Namespace

TestCoordinator.Data

##### Summary

Generic repository implementation

##### Generic Types

| Name | Description |
| ---- | ----------- |
| TEntity | The type of the entity. |

<a name='M-TestCoordinator-Data-GenericRepository`1-#ctor-TestCoordinator-Db-IDbContext-'></a>
### #ctor(context) `constructor`

##### Summary

Initializes a new instance of the [GenericRepository\`1](#T-TestCoordinator-Data-GenericRepository`1 'TestCoordinator.Data.GenericRepository`1') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| context | [TestCoordinator.Db.IDbContext](#T-TestCoordinator-Db-IDbContext 'TestCoordinator.Db.IDbContext') | The context. |

<a name='M-TestCoordinator-Data-GenericRepository`1-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [GenericRepository\`1](#T-TestCoordinator-Data-GenericRepository`1 'TestCoordinator.Data.GenericRepository`1') class.

##### Parameters

This constructor has no parameters.

<a name='P-TestCoordinator-Data-GenericRepository`1-Context'></a>
### Context `property`

##### Summary

Gets or sets the context.

<a name='P-TestCoordinator-Data-GenericRepository`1-DbSet'></a>
### DbSet `property`

##### Summary

Gets or sets the database set.

<a name='M-TestCoordinator-Data-GenericRepository`1-Delete-System-Object-'></a>
### Delete(id) `method`

##### Summary

Deletes the object with the specified identifier.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| id | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The identifier. |

<a name='M-TestCoordinator-Data-GenericRepository`1-Delete-`0-'></a>
### Delete(entityToDelete) `method`

##### Summary

Deletes the specified entity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| entityToDelete | [\`0](#T-`0 '`0') | The entity to delete. |

<a name='M-TestCoordinator-Data-GenericRepository`1-GetAll'></a>
### GetAll() `method`

##### Summary

Gets all entities.

##### Returns

All entities.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Data-GenericRepository`1-GetAll-System-Func{`0,System-Boolean}-'></a>
### GetAll(filterExpression) `method`

##### Summary

Gets all entities with specified filter expression.

##### Returns

All filtered entities.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| filterExpression | [System.Func{\`0,System.Boolean}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Func 'System.Func{`0,System.Boolean}') | The filter expression. |

<a name='M-TestCoordinator-Data-GenericRepository`1-GetById-System-Object-'></a>
### GetById(id) `method`

##### Summary

Gets the entity by identifier.

##### Returns

The entity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| id | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The identifier. |

<a name='M-TestCoordinator-Data-GenericRepository`1-Insert-`0-'></a>
### Insert(entity) `method`

##### Summary

Inserts the specified entity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| entity | [\`0](#T-`0 '`0') | The entity. |

<a name='M-TestCoordinator-Data-GenericRepository`1-Update-`0-'></a>
### Update(entityToUpdate) `method`

##### Summary

Updates the specified entity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| entityToUpdate | [\`0](#T-`0 '`0') | The entity to update. |

<a name='T-TestCoordinator-Data-IContentRepository`1'></a>
## IContentRepository\`1 `type`

##### Namespace

TestCoordinator.Data

##### Summary

Denotes a repository for managing content items

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the content entity for which the repository is used |

##### See Also

- [TestCoordinator.Data.IRepository\`1](#T-TestCoordinator-Data-IRepository`1 'TestCoordinator.Data.IRepository`1')

<a name='M-TestCoordinator-Data-IContentRepository`1-GetAll-System-Nullable{System-Int32}-'></a>
### GetAll(parentId) `method`

##### Summary

Gets all.

##### Returns

The entities collection.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parentId | [System.Nullable{System.Int32}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Nullable 'System.Nullable{System.Int32}') | The parent identifier. |

<a name='M-TestCoordinator-Data-IContentRepository`1-LockItem-`0,System-String-'></a>
### LockItem(item,clientId) `method`

##### Summary

Locks the item.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [\`0](#T-`0 '`0') | The item. |
| clientId | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The client identifier. |

<a name='M-TestCoordinator-Data-IContentRepository`1-UnlockItem-`0-'></a>
### UnlockItem(item) `method`

##### Summary

Unlocks the item.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [\`0](#T-`0 '`0') | The item. |

<a name='T-TestCoordinator-Data-IRepository`1'></a>
## IRepository\`1 `type`

##### Namespace

TestCoordinator.Data

##### Summary

Denotes a generic repository

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the entity |

<a name='P-TestCoordinator-Data-IRepository`1-Context'></a>
### Context `property`

##### Summary

Gets or sets the context.

<a name='P-TestCoordinator-Data-IRepository`1-DbSet'></a>
### DbSet `property`

##### Summary

Gets or sets the database set.

<a name='M-TestCoordinator-Data-IRepository`1-Delete-System-Object-'></a>
### Delete(id) `method`

##### Summary

Deletes an entity by its identifier.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| id | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The identifier. |

<a name='M-TestCoordinator-Data-IRepository`1-Delete-`0-'></a>
### Delete(entityToDelete) `method`

##### Summary

Deletes the specified entity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| entityToDelete | [\`0](#T-`0 '`0') | The entity to delete. |

<a name='M-TestCoordinator-Data-IRepository`1-GetAll'></a>
### GetAll() `method`

##### Summary

Gets all.

##### Returns

The entities collection.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Data-IRepository`1-GetAll-System-Func{`0,System-Boolean}-'></a>
### GetAll(filterExpression) `method`

##### Summary

Gets all.

##### Returns

The filtered entities collection.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| filterExpression | [System.Func{\`0,System.Boolean}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Func 'System.Func{`0,System.Boolean}') | The filter expression. |

<a name='M-TestCoordinator-Data-IRepository`1-GetById-System-Object-'></a>
### GetById(id) `method`

##### Summary

Gets an entity by identifier.

##### Returns

The entity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| id | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | The identifier. |

<a name='M-TestCoordinator-Data-IRepository`1-Insert-`0-'></a>
### Insert(entity) `method`

##### Summary

Inserts the specified entity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| entity | [\`0](#T-`0 '`0') | The entity. |

<a name='M-TestCoordinator-Data-IRepository`1-Update-`0-'></a>
### Update(entityToUpdate) `method`

##### Summary

Updates the specified entity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| entityToUpdate | [\`0](#T-`0 '`0') | The entity to update. |

<a name='T-TestCoordinator-Data-IUnitOfWork'></a>
## IUnitOfWork `type`

##### Namespace

TestCoordinator.Data

##### Summary

Represents the Unit of Work pattern for the project

##### See Also

- [System.IDisposable](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.IDisposable 'System.IDisposable')

<a name='P-TestCoordinator-Data-IUnitOfWork-AreasRepository'></a>
### AreasRepository `property`

##### Summary

Gets the areas repository.

<a name='P-TestCoordinator-Data-IUnitOfWork-AttachmentsRepository'></a>
### AttachmentsRepository `property`

##### Summary

Gets the attachments repository.

<a name='P-TestCoordinator-Data-IUnitOfWork-FeaturesRepository'></a>
### FeaturesRepository `property`

##### Summary

Gets the features repository.

<a name='P-TestCoordinator-Data-IUnitOfWork-ProductsRepository'></a>
### ProductsRepository `property`

##### Summary

Gets the products repository.

<a name='P-TestCoordinator-Data-IUnitOfWork-TestCasesRepository'></a>
### TestCasesRepository `property`

##### Summary

Gets the test cases repository.

<a name='M-TestCoordinator-Data-IUnitOfWork-Dispose'></a>
### Dispose() `method`

##### Summary

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Data-IUnitOfWork-GetContentRepository``1'></a>
### GetContentRepository\`\`1() `method`

##### Summary

Gets a content repository of specific type.

##### Returns

The content repository of the specified type.

##### Parameters

This method has no parameters.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the entity. |

<a name='M-TestCoordinator-Data-IUnitOfWork-Save'></a>
### Save() `method`

##### Summary

Saves this instance.

##### Parameters

This method has no parameters.

<a name='T-TestCoordinator-Data-UnitOfWork'></a>
## UnitOfWork `type`

##### Namespace

TestCoordinator.Data

##### Summary

Provides access to the repositories and manages the database context.

##### See Also

- [System.IDisposable](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.IDisposable 'System.IDisposable')

<a name='M-TestCoordinator-Data-UnitOfWork-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [UnitOfWork](#T-TestCoordinator-Data-UnitOfWork 'TestCoordinator.Data.UnitOfWork') class.

##### Parameters

This constructor has no parameters.

<a name='P-TestCoordinator-Data-UnitOfWork-AreasRepository'></a>
### AreasRepository `property`

##### Summary

Gets the areas repository.

<a name='P-TestCoordinator-Data-UnitOfWork-AttachmentsRepository'></a>
### AttachmentsRepository `property`

##### Summary

Gets the attachments repository.

<a name='P-TestCoordinator-Data-UnitOfWork-FeaturesRepository'></a>
### FeaturesRepository `property`

##### Summary

Gets the features repository.

<a name='P-TestCoordinator-Data-UnitOfWork-ProductsRepository'></a>
### ProductsRepository `property`

##### Summary

Gets the products repository.

<a name='P-TestCoordinator-Data-UnitOfWork-TestCasesRepository'></a>
### TestCasesRepository `property`

##### Summary

Gets the test cases repository.

<a name='M-TestCoordinator-Data-UnitOfWork-Dispose'></a>
### Dispose() `method`

##### Summary

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Data-UnitOfWork-Dispose-System-Boolean-'></a>
### Dispose(disposing) `method`

##### Summary

Releases unmanaged and - optionally - managed resources.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| disposing | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | `true` to release both managed and unmanaged resources; `false` to release only unmanaged resources. |

<a name='M-TestCoordinator-Data-UnitOfWork-GetContentRepository``1'></a>
### GetContentRepository\`\`1() `method`

##### Summary

Gets a ContentRepository specified by type.

##### Returns

The content repository.

##### Parameters

This method has no parameters.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the content repository. |

<a name='M-TestCoordinator-Data-UnitOfWork-Save'></a>
### Save() `method`

##### Summary

Saves all changes in the database context.

##### Parameters

This method has no parameters.
