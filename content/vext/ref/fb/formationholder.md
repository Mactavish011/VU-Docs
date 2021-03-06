---
title: FormationHolder
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[FormationHolder](#constructor-0)**() |
| **[FormationHolder](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[FormationHolder](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[FormationHolder](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "formations" >}} | [FormationData](/vext/ref/fb/formationdata)[] |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "FormationHolder" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### FormationHolder {#constructor-0}

> **FormationHolder**()

Creates a new [FormationHolder](/vext/ref/fb/formationholder) frostbite instance.

### FormationHolder {#constructor-1}

> **FormationHolder**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [FormationHolder](/vext/ref/fb/formationholder) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### FormationHolder {#constructor-2}

> **FormationHolder**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [FormationHolder](/vext/ref/fb/formationholder). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [FormationHolder](/vext/ref/fb/formationholder). |

### FormationHolder {#constructor-3}

> **FormationHolder**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [FormationHolder](/vext/ref/fb/formationholder). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [FormationHolder](/vext/ref/fb/formationholder). |

## Properties

### {{% prop-heading "formations" %}}

> **[FormationData](/vext/ref/fb/formationdata)**[]

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [FormationHolder](/vext/ref/fb/formationholder) type.

