---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.service: minecraft-bedrock-edition
title: minecraft/server.EntityTameMountComponent Class
description: Contents of the @minecraft/server.EntityTameMountComponent class.
monikerRange: "=minecraft-bedrock-experimental"
---
# EntityTameMountComponent Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Extends
- [*EntityComponent*](EntityComponent.md)

Contains options for taming a rideable entity based on the entity that mounts it.

## Methods
- [tame](#tame)

### **tame**
`
tame(showParticles: boolean): void
`

Sets this rideable entity as tamed.

#### **Parameters**
- **showParticles**: *boolean*
  
  Whether to show effect particles when this entity is tamed.

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.

## Constants

### **componentId**
`static read-only componentId = "minecraft:tamemount";`

Type: *string*
