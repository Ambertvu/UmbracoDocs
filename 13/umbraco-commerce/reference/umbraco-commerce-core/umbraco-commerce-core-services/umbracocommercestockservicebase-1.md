---
title: UmbracoCommerceStockServiceBase<TSelf>
description: API reference for UmbracoCommerceStockServiceBase<TSelf> in Umbraco Commerce
---
## UmbracoCommerceStockServiceBase&lt;TSelf&gt;

```csharp
public abstract class UmbracoCommerceStockServiceBase<TSelf> : ServiceBase<TSelf>, IStockService
    where TSelf : UmbracoCommerceStockServiceBase<TSelf>
```

**Inheritance**

* Class [ServiceBase&lt;TSelf&gt;](servicebase-1.md)
* interface [IStockService](istockservice.md)

**Namespace**
* [Umbraco.Commerce.Core.Services](README.md)

### Constructors

#### UmbracoCommerceStockServiceBase&lt;TSelf&gt;

```csharp
public UmbracoCommerceStockServiceBase(IRepositoryFactory repositoryFactory, 
    IUnitOfWorkProvider uowProvider, ILogger<TSelf> logger, ICacheAccessor cacheAccessor)
```


### Methods

#### GetStock (1 of 2)

```csharp
public virtual decimal? GetStock(Guid storeId, string productReference)
```

---

#### GetStock (2 of 2)

```csharp
public virtual decimal? GetStock(Guid storeId, string productReference, 
    string productVariantReference)
```


---

#### IncreaseStock (1 of 2)

```csharp
public virtual void IncreaseStock(Guid storeId, string productReference, decimal increaseBy)
```

---

#### IncreaseStock (2 of 2)

```csharp
public virtual void IncreaseStock(Guid storeId, string productReference, 
    string productVariantReference, decimal increaseBy)
```


---

#### InvalidateStockCache

```csharp
public void InvalidateStockCache()
```


---

#### InvalidateStockCache

```csharp
public void InvalidateStockCache(Guid storeId, string productReference, 
    string productVariantReference)
```


---

#### ReduceStock (1 of 2)

```csharp
public virtual void ReduceStock(Guid storeId, string productReference, decimal reduceBy)
```

---

#### ReduceStock (2 of 2)

```csharp
public virtual void ReduceStock(Guid storeId, string productReference, 
    string productVariantReference, decimal reduceBy)
```


---

#### SetStock (1 of 2)

```csharp
public virtual void SetStock(Guid storeId, string productReference, decimal value)
```

---

#### SetStock (2 of 2)

```csharp
public virtual void SetStock(Guid storeId, string productReference, string productVariantReference, 
    decimal value)
```


---

#### TryGetStock (1 of 2)

```csharp
public virtual bool TryGetStock(Guid storeId, string productReference, out decimal? stock)
```

---

#### TryGetStock (2 of 2)

```csharp
public virtual bool TryGetStock(Guid storeId, string productReference, 
    string productVariantReference, out decimal? stock)
```


---

#### TryIncreaseStock (1 of 2)

```csharp
public virtual bool TryIncreaseStock(Guid storeId, string productReference, decimal increaseBy)
```

---

#### TryIncreaseStock (2 of 2)

```csharp
public virtual bool TryIncreaseStock(Guid storeId, string productReference, 
    string productVariantReference, decimal increaseBy)
```


---

#### TryReduceStock (1 of 2)

```csharp
public virtual bool TryReduceStock(Guid storeId, string productReference, decimal reduceBy)
```

---

#### TryReduceStock (2 of 2)

```csharp
public virtual bool TryReduceStock(Guid storeId, string productReference, 
    string productVariantReference, decimal reduceBy)
```


---

#### TrySetStock (1 of 2)

```csharp
public virtual bool TrySetStock(Guid storeId, string productReference, decimal value)
```

---

#### TrySetStock (2 of 2)

```csharp
public virtual bool TrySetStock(Guid storeId, string productReference, 
    string productVariantReference, decimal value)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->