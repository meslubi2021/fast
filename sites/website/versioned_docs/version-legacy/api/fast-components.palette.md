---
id: fast-components.palette
title: Palette interface
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-components](./fast-components.md) &gt; [Palette](./fast-components.palette.md)

## Palette interface

A collection of [Swatch](./fast-components.swatch.md) instances

<b>Signature:</b>

```typescript
export interface Palette<T extends Swatch = Swatch> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [source](./fast-components.palette.source.md) | T |  |
|  [swatches](./fast-components.palette.swatches.md) | ReadonlyArray&lt;T&gt; |  |

## Methods

|  Method | Description |
|  --- | --- |
|  [closestIndexOf(reference)](./fast-components.palette.closestindexof.md) | Returns the index of the palette that most closely matches the relativeLuminance of the provided swatch |
|  [colorContrast(reference, contrast, initialIndex, direction)](./fast-components.palette.colorcontrast.md) | Returns a swatch from the palette that most closely matches the contrast ratio provided to a provided reference. |
|  [get(index)](./fast-components.palette.get.md) | Gets a swatch by index. Index is clamped to the limits of the palette so a Swatch will always be returned. |