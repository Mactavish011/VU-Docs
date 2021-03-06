---
title: AnimatedSkeletonDatabase
---

Inherits from [DataContainer](/vext/ref/shared/type/datacontainer)

## Summary

### Constructors

|  |
| --- |
| **[AnimatedSkeletonDatabase](#constructor-0)**() |
| **[AnimatedSkeletonDatabase](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[AnimatedSkeletonDatabase](#constructor-2)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "ragdolls" >}} | [RagdollAsset](/vext/ref/fb/ragdollasset)[] |
| {{< prop "items" >}} | [AnimatedSkeletonDatabaseItem](/vext/ref/fb/animatedskeletondatabaseitem)[] |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "AnimatedSkeletonDatabase" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### AnimatedSkeletonDatabase {#constructor-0}

> **AnimatedSkeletonDatabase**()

Creates a new [AnimatedSkeletonDatabase](/vext/ref/fb/animatedskeletondatabase) frostbite instance.

### AnimatedSkeletonDatabase {#constructor-1}

> **AnimatedSkeletonDatabase**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [AnimatedSkeletonDatabase](/vext/ref/fb/animatedskeletondatabase) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### AnimatedSkeletonDatabase {#constructor-2}

> **AnimatedSkeletonDatabase**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [AnimatedSkeletonDatabase](/vext/ref/fb/animatedskeletondatabase). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [AnimatedSkeletonDatabase](/vext/ref/fb/animatedskeletondatabase). |

## Properties

### {{% prop-heading "ragdolls" %}}

> **[RagdollAsset](/vext/ref/fb/ragdollasset)**[]

### {{% prop-heading "items" %}}

> **[AnimatedSkeletonDatabaseItem](/vext/ref/fb/animatedskeletondatabaseitem)**[]

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [AnimatedSkeletonDatabase](/vext/ref/fb/animatedskeletondatabase) type.

