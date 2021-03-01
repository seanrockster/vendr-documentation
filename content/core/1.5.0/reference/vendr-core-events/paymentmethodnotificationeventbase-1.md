---
title: PaymentMethodNotificationEventBase<TEntity>
description: API reference for PaymentMethodNotificationEventBase<TEntity> in Vendr, the eCommerce solution for Umbraco v8+
---
## PaymentMethodNotificationEventBase&lt;TEntity&gt;

```csharp
public abstract class PaymentMethodNotificationEventBase<TEntity> : NotificationEventBase
    where TEntity : PaymentMethodReadOnly
```

**Inheritance**

* class [NotificationEventBase](../notificationeventbase/)

**Namespace**
* [Vendr.Core.Events.Notification](../)

### Constructors

#### PaymentMethodNotificationEventBase&lt;TEntity&gt;

```csharp
public PaymentMethodNotificationEventBase(TEntity paymentMethod)
```


### Properties

#### PaymentMethod

```csharp
public TEntity PaymentMethod { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->