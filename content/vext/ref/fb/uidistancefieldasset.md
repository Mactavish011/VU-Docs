---
title: UIDistanceFieldAsset
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[UIDistanceFieldAsset](#constructor-0)**() |
| **[UIDistanceFieldAsset](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[UIDistanceFieldAsset](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[UIDistanceFieldAsset](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "distanceFieldTexture" >}} | [TextureAsset](/vext/ref/fb/textureasset) \| nil |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "UIDistanceFieldAsset" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### UIDistanceFieldAsset {#constructor-0}

> **UIDistanceFieldAsset**()

Creates a new [UIDistanceFieldAsset](/vext/ref/fb/uidistancefieldasset) frostbite instance.

### UIDistanceFieldAsset {#constructor-1}

> **UIDistanceFieldAsset**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [UIDistanceFieldAsset](/vext/ref/fb/uidistancefieldasset) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### UIDistanceFieldAsset {#constructor-2}

> **UIDistanceFieldAsset**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [UIDistanceFieldAsset](/vext/ref/fb/uidistancefieldasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [UIDistanceFieldAsset](/vext/ref/fb/uidistancefieldasset). |

### UIDistanceFieldAsset {#constructor-3}

> **UIDistanceFieldAsset**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [UIDistanceFieldAsset](/vext/ref/fb/uidistancefieldasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [UIDistanceFieldAsset](/vext/ref/fb/uidistancefieldasset). |

## Properties

### {{% prop-heading "distanceFieldTexture" %}}

> **[TextureAsset](/vext/ref/fb/textureasset)** \| **nil**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [UIDistanceFieldAsset](/vext/ref/fb/uidistancefieldasset) type.

