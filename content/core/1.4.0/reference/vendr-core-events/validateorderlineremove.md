---
title: ValidateOrderLineRemove
description: API reference for ValidateOrderLineRemove in Vendr, the eCommerce solution for Umbraco v8+
---
## ValidateOrderLineRemove

```csharp
public class ValidateOrderLineRemove : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidateOrderLineRemove

```csharp
public ValidateOrderLineRemove(OrderReadOnly order, OrderLineReadOnly orderLine)
```


### Properties

#### Order

```csharp
public OrderReadOnly Order { get; }
```


---

#### OrderLine

```csharp
public OrderLineReadOnly OrderLine { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->