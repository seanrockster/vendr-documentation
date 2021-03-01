---
title: ValidateShippingMethodAllowedInShippingCountryRegion
description: API reference for ValidateShippingMethodAllowedInShippingCountryRegion in Vendr, the eCommerce solution for Umbraco v8+
---
## ValidateShippingMethodAllowedInShippingCountryRegion

```csharp
public class ValidateShippingMethodAllowedInShippingCountryRegion : 
    ValidationEventHandlerBase<ValidateOrderShippingMethodChange>
```

**Inheritance**

* class [ValidationEventHandlerBase&lt;TValidationEvent&gt;](../validationeventhandlerbase-1/)

**Namespace**
* [Vendr.Core.Events.Validation.Handlers.Order](../)

### Constructors

#### ValidateShippingMethodAllowedInShippingCountryRegion

```csharp
public ValidateShippingMethodAllowedInShippingCountryRegion(
    IShippingMethodService shippingMethodService)
```


### Methods

#### Validate

```csharp
public override void Validate(ValidateOrderShippingMethodChange evt)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->