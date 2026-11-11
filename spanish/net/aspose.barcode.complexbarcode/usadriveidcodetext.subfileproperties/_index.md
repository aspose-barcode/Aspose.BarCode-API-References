---
title: "Clase USADriveIdCodetext.SubfileProperties"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties clase. Las propiedades de subarchivo USA DL, desplazamiento y longitud, se establecen automáticamente"
type: docs
weight: 840
url: /es/net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

Las propiedades de subarchivo USA DL, desplazamiento y longitud, se establecen automáticamente.

```csharp
public class SubfileProperties
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | 4 Estos bytes contienen un valor numérico de 4 dígitos que especifica la longitud del Subfile en bytes. El terminador de segmento debe incluirse al calcular la longitud del subfile. Un terminador de segmento = 1. Cada subfile debe comenzar con el Tipo de Subfile de dos caracteres y estos dos caracteres también deben incluirse en la longitud. |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | Valor numérico de 4 dígitos que especifica el número de bytes desde el inicio del archivo hasta donde se encuentran los datos relacionados con el subarchivo particular. El primer byte del archivo se encuentra en el desplazamiento 0. |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | Tipo de subarchivo de 2 bytes, como "DL" |

### Ver también

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


