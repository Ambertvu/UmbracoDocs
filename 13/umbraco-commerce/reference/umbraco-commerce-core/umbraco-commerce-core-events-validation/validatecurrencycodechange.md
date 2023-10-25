---
title: ValidateCurrencyCodeChange
description: API reference for ValidateCurrencyCodeChange in Umbraco Commerce
---
## ValidateCurrencyCodeChange

```csharp
public class ValidateCurrencyCodeChange : ValidationEventBase
```

**Inheritance**

* Class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateCurrencyCodeChange

```csharp
public ValidateCurrencyCodeChange(CurrencyReadOnly currency, ChangingValue<string> code)
```


### Properties

#### Code

```csharp
public ChangingValue<string> Code { get; }
```


---

#### Currency

```csharp
public CurrencyReadOnly Currency { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->