---
title: ActivityLogger
description: API reference for ActivityLogger in Vendr, the eCommerce solution for Umbraco v8+
---
## ActivityLogger

```csharp
public class ActivityLogger : IActivityLogger
```

**Inheritance**

* interface [IActivityLogger](../iactivitylogger/)

**Namespace**
* [Vendr.Core.Logging](../)

### Constructors

#### ActivityLogger

```csharp
public ActivityLogger(IRepositoryFactory repositoryFactory, IUnitOfWorkProvider uowProvider, 
    ILogger logger)
```


### Methods

#### GetActivityLogs

```csharp
public PagedResult<ActivityLogEntry> GetActivityLogs(Guid storeId, long currentPage, 
    long itemsPerPage)
```


---

#### LogActivity (1 of 4)

```csharp
public void LogActivity(Guid storeId, Guid entityId, string entityType, string entitySummary, 
    string eventType, string eventSummary)
```

---

#### LogActivity (2 of 4)

```csharp
public void LogActivity(Guid storeId, Guid entityId, string entityType, string entitySummary, 
    string eventType, string eventSummary, int userId)
```

---

#### LogActivity (3 of 4)

```csharp
public void LogActivity(Guid storeId, Guid entityId, string entityType, string entitySummary, 
    string eventType, string eventSummary, DateTime eventDateUtc)
```

---

#### LogActivity (4 of 4)

```csharp
public void LogActivity(Guid storeId, Guid entityId, string entityType, string entitySummary, 
    string eventType, string eventSummary, DateTime eventDateUtc, int userId)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->