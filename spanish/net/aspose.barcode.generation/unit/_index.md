---
title: "Clase Unit"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.Unit. Especifica el valor de tamaño en diferentes unidades Pixel Pulgadas, etc"
type: docs
weight: 1740
url: /es/net/aspose.barcode.generation/unit/
---
## Unit class

Especifica el valor de tamaño en diferentes unidades (píxel, pulgadas, etc.).

```csharp
public sealed class Unit
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | Obtiene o establece el valor de tamaño en unidades del documento. |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | Obtiene o establece el valor de tamaño en pulgadas. |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | Obtiene o establece el valor de tamaño en milímetros. |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | Obtiene o establece el valor de tamaño en píxeles. |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | Obtiene o establece el valor de tamaño en puntos. |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | Resolución |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | Determina si esta instancia y un objeto especificado, que también debe ser un objeto `Unit`, tienen el mismo valor. |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | Devuelve el código hash de este objeto. |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | Devuelve una representación de cadena legible para humanos de este `Unit`. |

## Ejemplos

Este ejemplo muestra cómo crear y guardar una imagen BarCode.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


