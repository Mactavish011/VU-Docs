---
title: TreeBase
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[TreeBase](#constructor-0)**() |
| **[TreeBase](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[TreeBase](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[TreeBase](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "TreeBase" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### TreeBase {#constructor-0}

> **TreeBase**()

Creates a new [TreeBase](/vext/ref/fb/treebase) frostbite instance.

### TreeBase {#constructor-1}

> **TreeBase**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [TreeBase](/vext/ref/fb/treebase) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### TreeBase {#constructor-2}

> **TreeBase**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [TreeBase](/vext/ref/fb/treebase). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [TreeBase](/vext/ref/fb/treebase). |

### TreeBase {#constructor-3}

> **TreeBase**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [TreeBase](/vext/ref/fb/treebase). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [TreeBase](/vext/ref/fb/treebase). |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [TreeBase](/vext/ref/fb/treebase) type.

