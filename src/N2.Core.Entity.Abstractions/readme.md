# N2.Core.Entity.Abstractions

This package contains the interfaces and classes that simplify the use of a database context in a .NET Core application.

## Usage

	- IDbBaseModel : This interface is used to define the base properties of a model class that is used in the database context.
	- IDbContext : This interface is used to define the base properties of a database context class.
	- IBasicListModel : This interface is used to define the base properties of a model class that is used in the database context as a list of items.
	- IChangeLog : This interface is used to define the base properties of a model class that is used in the database context as a change log.
	- IConnectionStringService : Helper service to find a connection string based on the environment or user context.
	- IModifiable : This interface is used to define the base properties of a model class that is used in the database context as a modifiable item.
	- IDesignComponent : This interface is used to define the base functionality for a component that is used to manage a specific data model.
	- ICoreDataContext : This interface is used to define the base properties of a database context class that is used to manage the core data models.

### 1. Create a new class that implements the `IDbBaseModel` interface

```csharp

```

### 2. Create a new class that implements the `IDbContext` interface

```csharp

```
