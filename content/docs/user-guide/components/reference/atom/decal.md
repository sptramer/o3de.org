---
title: Decal component
linktitle: Decal
description: ' Open 3D Engine (O3DE) Decal component reference. '
weight: 100
---

{{< preview-migrated >}}

The **Decal** component enables an entity to project a material onto a mesh. The decal is projected along the positive Z axis of the entity in local space (denoted by a red X). The decal can be projected onto any mesh from any entity that penetrates the bounding box of the entity that contains the Decal component. The decal can be resized by adjusting the Scale property of the Transform of the entity that contains the Decal component.

## Provider ##

[Atom Gem](/docs/user-guide/gems/reference/atom)

## Base properties ##

![Decal component base properties](/images/user-guide/components/reference/atom/decal-component-ui-01.png)

| Property | Description | Values | Default |
|-|-|-|-|
| **Attenuation Angle** | The effect on the opacity of the decal material, in relation to the angle between the decal and the projection surface . With the default value of 1.0, the decal becomes more transparent as the angle between the decal and the projection surface increases. A value of 0.0 makes the decal opacity uniform regardless of the angle between the decal and the projection surface. | 0.0 - 1.0 | `1.0` |
| **Opacity** | The opacity of the decal. A value of 0.0 is transparent. A value of 1.0 is opaque. | 0.0 - 1.0 | `1.0` |
| **Sort Key** | The sorting order for the decal. Decals with larger Sort Key values appear on top of decals with smaller Sort Key values. | 0 - Infinity | `16` |
| **Material** | The material to project as a decal. | .material file |  |
