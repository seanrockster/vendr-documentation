---
title: PaymentMethodService
description: API reference for PaymentMethodService in Vendr, the eCommerce solution for Umbraco v8+
---
## PaymentMethodService

```csharp
public class PaymentMethodService : EntityServiceBase, IPaymentMethodService
```

**Inheritance**

* class [EntityServiceBase](../entityservicebase/)
* interface [IPaymentMethodService](../ipaymentmethodservice/)

**Namespace**
* [Vendr.Core.Services](../)

### Constructors

#### PaymentMethodService

```csharp
public PaymentMethodService(ILicensingService licensingService, 
    IRepositoryFactory repositoryFactory, IUnitOfWorkProvider uowProvider, ILogger logger, 
    ICache cache, IEntityStateCacheAccessor entityStateCacheAccessor)
```


### Methods

#### DeletePaymentMethod (1 of 2)

```csharp
public void DeletePaymentMethod(Guid id)
```

---

#### DeletePaymentMethod (2 of 2)

```csharp
public void DeletePaymentMethod(PaymentMethod entity)
```


---

#### GetPaymentMethod (1 of 2)

```csharp
public PaymentMethodReadOnly GetPaymentMethod(Guid id)
```

---

#### GetPaymentMethod (2 of 2)

```csharp
public PaymentMethodReadOnly GetPaymentMethod(Guid storeId, string alias)
```


---

#### GetPaymentMethods

```csharp
public IEnumerable<PaymentMethodReadOnly> GetPaymentMethods(Guid storeId)
```


---

#### GetPaymentMethodsAllowedIn

```csharp
public IEnumerable<PaymentMethodReadOnly> GetPaymentMethodsAllowedIn(Guid countryId, Guid? regionId)
```


---

#### PaymentMethodExists

```csharp
public bool PaymentMethodExists(Guid storeId, string alias)
```


---

#### SavePaymentMethod

```csharp
public void SavePaymentMethod(PaymentMethod entity)
```


---

#### SortPaymentMethods

```csharp
public void SortPaymentMethods(Guid[] sortedIds)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->