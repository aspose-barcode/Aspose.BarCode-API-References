---
title: "Enumeración EnableChecksum"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.Generation.EnableChecksum enum. Habilita la suma de verificación durante la generación para códigos de barras 1D"
type: docs
weight: 1280
url: /es/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

Habilitar suma de verificación durante la generación de códigos de barras 1D.

El valor predeterminado se trata como Sí para las simbologías que deben contener suma de verificación, y como No donde la suma de verificación solo es posible.

Suma de verificación nunca usada: Codabar

La suma de verificación es posible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Suma de verificación siempre utilizada: resto de simbologías

```csharp
public enum EnableChecksum
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Default | `0` | Si la suma de verificación es requerida por la especificación, se adjuntará. |
| Yes | `1` | Utilice siempre la suma de verificación si es posible. |
| No | `2` | No utilice la suma de verificación. |

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


