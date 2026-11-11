---
title: "Clase FontUnit"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.FontUnit. Define un formato particular para el texto que incluye el tamaño de la fuente y atributos de estilo donde el tamaño está en la propiedad Unit value."
type: docs
weight: 1320
url: /es/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

Define un formato particular para el texto, incluyendo tipo de fuente, tamaño y atributos de estilo donde el tamaño está en la propiedad Unit value.

```csharp
public sealed class FontUnit
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname/) { get; set; } | Obtiene o establece el nombre de la fuente de este Font. |
| [Size](../../aspose.barcode.generation/fontunit/size/) { get; } | Obtiene o establece el tamaño de este FontUnit en Unit value. |
| [Style](../../aspose.barcode.generation/fontunit/style/) { get; set; } | Obtiene o establece la información de estilo para este FontUnit. |

## Ejemplos

Este ejemplo muestra cómo crear y guardar una imagen BarCode.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


