<a name='assembly'></a>
# TestCoordinator.Db

## Contents

- [DbContextBase](#T-TestCoordinator-Db-DbContextBase 'TestCoordinator.Db.DbContextBase')
  - [#ctor(databaseNameOrConnectionString)](#M-TestCoordinator-Db-DbContextBase-#ctor-System-String- 'TestCoordinator.Db.DbContextBase.#ctor(System.String)')
  - [Areas](#P-TestCoordinator-Db-DbContextBase-Areas 'TestCoordinator.Db.DbContextBase.Areas')
  - [Attachments](#P-TestCoordinator-Db-DbContextBase-Attachments 'TestCoordinator.Db.DbContextBase.Attachments')
  - [Features](#P-TestCoordinator-Db-DbContextBase-Features 'TestCoordinator.Db.DbContextBase.Features')
  - [Products](#P-TestCoordinator-Db-DbContextBase-Products 'TestCoordinator.Db.DbContextBase.Products')
  - [TestCases](#P-TestCoordinator-Db-DbContextBase-TestCases 'TestCoordinator.Db.DbContextBase.TestCases')
  - [OnModelCreating(modelBuilder)](#M-TestCoordinator-Db-DbContextBase-OnModelCreating-System-Data-Entity-DbModelBuilder- 'TestCoordinator.Db.DbContextBase.OnModelCreating(System.Data.Entity.DbModelBuilder)')
- [IDbContext](#T-TestCoordinator-Db-IDbContext 'TestCoordinator.Db.IDbContext')
  - [Dispose()](#M-TestCoordinator-Db-IDbContext-Dispose 'TestCoordinator.Db.IDbContext.Dispose')
  - [Entry\`\`1(entity)](#M-TestCoordinator-Db-IDbContext-Entry``1-``0- 'TestCoordinator.Db.IDbContext.Entry``1(``0)')
  - [SaveChanges()](#M-TestCoordinator-Db-IDbContext-SaveChanges 'TestCoordinator.Db.IDbContext.SaveChanges')
  - [Set\`\`1()](#M-TestCoordinator-Db-IDbContext-Set``1 'TestCoordinator.Db.IDbContext.Set``1')
- [ProductionDbContext](#T-TestCoordinator-Db-ProductionDbContext 'TestCoordinator.Db.ProductionDbContext')
  - [#ctor()](#M-TestCoordinator-Db-ProductionDbContext-#ctor 'TestCoordinator.Db.ProductionDbContext.#ctor')
- [ProductionMigrationConfig](#T-TestCoordinator-Db-ProductionMigrationConfig 'TestCoordinator.Db.ProductionMigrationConfig')
  - [#ctor()](#M-TestCoordinator-Db-ProductionMigrationConfig-#ctor 'TestCoordinator.Db.ProductionMigrationConfig.#ctor')
- [TestDbContext](#T-TestCoordinator-Db-TestDbContext 'TestCoordinator.Db.TestDbContext')
  - [#ctor()](#M-TestCoordinator-Db-TestDbContext-#ctor 'TestCoordinator.Db.TestDbContext.#ctor')
- [TestMigrationConfig](#T-TestCoordinator-Db-TestMigrationConfig 'TestCoordinator.Db.TestMigrationConfig')
  - [#ctor()](#M-TestCoordinator-Db-TestMigrationConfig-#ctor 'TestCoordinator.Db.TestMigrationConfig.#ctor')

<a name='T-TestCoordinator-Db-DbContextBase'></a>
## DbContextBase `type`

##### Namespace

TestCoordinator.Db

##### Summary

Base database context.

##### See Also

- [System.Data.Entity.DbContext](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Data.Entity.DbContext 'System.Data.Entity.DbContext')
- [TestCoordinator.Db.IDbContext](#T-TestCoordinator-Db-IDbContext 'TestCoordinator.Db.IDbContext')

<a name='M-TestCoordinator-Db-DbContextBase-#ctor-System-String-'></a>
### #ctor(databaseNameOrConnectionString) `constructor`

##### Summary

Initializes a new instance of the [DbContextBase](#T-TestCoordinator-Db-DbContextBase 'TestCoordinator.Db.DbContextBase') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| databaseNameOrConnectionString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The database name or connection string. |

<a name='P-TestCoordinator-Db-DbContextBase-Areas'></a>
### Areas `property`

##### Summary

Gets or sets the areas.

<a name='P-TestCoordinator-Db-DbContextBase-Attachments'></a>
### Attachments `property`

##### Summary

Gets or sets the attachments.

<a name='P-TestCoordinator-Db-DbContextBase-Features'></a>
### Features `property`

##### Summary

Gets or sets the features.

<a name='P-TestCoordinator-Db-DbContextBase-Products'></a>
### Products `property`

##### Summary

Gets or sets the products.

<a name='P-TestCoordinator-Db-DbContextBase-TestCases'></a>
### TestCases `property`

##### Summary

Gets or sets the test cases.

<a name='M-TestCoordinator-Db-DbContextBase-OnModelCreating-System-Data-Entity-DbModelBuilder-'></a>
### OnModelCreating(modelBuilder) `method`

##### Summary

This method is called when the model for a derived context has been initialized, but
before the model has been locked down and used to initialize the context.  The default
implementation of this method does nothing, but it can be overridden in a derived class
such that the model can be further configured before it is locked down.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| modelBuilder | [System.Data.Entity.DbModelBuilder](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Data.Entity.DbModelBuilder 'System.Data.Entity.DbModelBuilder') | The builder that defines the model for the context being created. |

##### Remarks

Typically, this method is called only once when the first instance of a derived context
is created.  The model for that context is then cached and is for all further instances of
the context in the app domain.  This caching can be disabled by setting the ModelCaching
property on the given ModelBuilder, but note that this can seriously degrade performance.
More control over caching is provided through use of the DbModelBuilder and DbContextFactory
classes directly.

<a name='T-TestCoordinator-Db-IDbContext'></a>
## IDbContext `type`

##### Namespace

TestCoordinator.Db

##### Summary

Interface for database context.

<a name='M-TestCoordinator-Db-IDbContext-Dispose'></a>
### Dispose() `method`

##### Summary

Releases unmanaged and - optionally - managed resources.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Db-IDbContext-Entry``1-``0-'></a>
### Entry\`\`1(entity) `method`

##### Summary

The entry of specified entity type.

##### Returns

The entity entry.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| entity | [\`\`0](#T-``0 '``0') | The entity. |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of the entity. |

<a name='M-TestCoordinator-Db-IDbContext-SaveChanges'></a>
### SaveChanges() `method`

##### Summary

Saves the changes.

##### Returns

The number of objects in an Added, Modified, or Deleted state when SaveChanges was called.

##### Parameters

This method has no parameters.

<a name='M-TestCoordinator-Db-IDbContext-Set``1'></a>
### Set\`\`1() `method`

##### Summary

The set of entities of specified type.

##### Returns

The set of entities.

##### Parameters

This method has no parameters.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | The type of entities. |

<a name='T-TestCoordinator-Db-ProductionDbContext'></a>
## ProductionDbContext `type`

##### Namespace

TestCoordinator.Db

##### Summary

The production database context.

<a name='M-TestCoordinator-Db-ProductionDbContext-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [ProductionDbContext](#T-TestCoordinator-Db-ProductionDbContext 'TestCoordinator.Db.ProductionDbContext') class.

##### Parameters

This constructor has no parameters.

<a name='T-TestCoordinator-Db-ProductionMigrationConfig'></a>
## ProductionMigrationConfig `type`

##### Namespace

TestCoordinator.Db

##### Summary

Migration strategy configuration.

<a name='M-TestCoordinator-Db-ProductionMigrationConfig-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [ProductionMigrationConfig](#T-TestCoordinator-Db-ProductionMigrationConfig 'TestCoordinator.Db.ProductionMigrationConfig') class.

##### Parameters

This constructor has no parameters.

<a name='T-TestCoordinator-Db-TestDbContext'></a>
## TestDbContext `type`

##### Namespace

TestCoordinator.Db

##### Summary

The test database context.

##### See Also

- [TestCoordinator.Db.DbContextBase](#T-TestCoordinator-Db-DbContextBase 'TestCoordinator.Db.DbContextBase')

<a name='M-TestCoordinator-Db-TestDbContext-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [TestDbContext](#T-TestCoordinator-Db-TestDbContext 'TestCoordinator.Db.TestDbContext') class.

##### Parameters

This constructor has no parameters.

<a name='T-TestCoordinator-Db-TestMigrationConfig'></a>
## TestMigrationConfig `type`

##### Namespace

TestCoordinator.Db

##### Summary

Migration strategy configuration.

<a name='M-TestCoordinator-Db-TestMigrationConfig-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the [TestMigrationConfig](#T-TestCoordinator-Db-TestMigrationConfig 'TestCoordinator.Db.TestMigrationConfig') class.

##### Parameters

This constructor has no parameters.
