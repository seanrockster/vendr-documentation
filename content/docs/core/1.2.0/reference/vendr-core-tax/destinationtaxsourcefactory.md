---
title: DestinationTaxSourceFactory
description: API reference for DestinationTaxSourceFactory in Vendr, the eCommerce solution for Umbraco v8+
---
## DestinationTaxSourceFactory

```csharp
public class DestinationTaxSourceFactory : TaxSourceFactoryBase
```

**Inheritance**

* class [TaxSourceFactoryBase](../taxsourcefactorybase/)

**Namespace**
* [Vendr.Core.Tax](../)

### Constructors

#### DestinationTaxSourceFactory

The default constructor.

```csharp
public DestinationTaxSourceFactory()
```


### Methods

#### Create

```csharp
public override TaxSource Create(Guid? paymentCountryId, Guid? paymentRegionId = default(Guid?), 
    Guid? shippingCountryId = default(Guid?), Guid? shippingRegionId = default(Guid?))
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->