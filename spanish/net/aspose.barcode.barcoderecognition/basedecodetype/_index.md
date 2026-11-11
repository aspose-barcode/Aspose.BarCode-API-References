---
title: "Clase BaseDecodeType"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.BaseDecodeType. Clase base para MultiDecodeType y SingleDecodeType"
type: docs
weight: 130
url: /es/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

Clase base para MultiDecodeType y SingleDecodeType.

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany/)(params BaseDecodeType[]) | Determina si alguno de los tipos de decodificación proporcionados está incluido en |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals)(BaseDecodeType) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `BaseDecodeType`. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_1)(MultiDecodeType) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [`MultiDecodeType`](../multidecodetype/). |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_3)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `BaseDecodeType`. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_2)(SingleDecodeType) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [`SingleDecodeType`](../singledecodetype/). |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode/)() | Devuelve el código hash de esta instancia. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse)(string, out BaseDecodeType) | Convierte la representación en cadena de un BaseDecodeType a su instancia, habiendo determinado el tipo concreto. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_1)(string, out MultiDecodeType) | Convierte la representación en cadena de un MultiDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_2)(string, out SingleDecodeType) | Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |

## Ejemplos

Este ejemplo muestra cómo usar BaseDecodeType con SingleDecodeType y MultiDecodeType.

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


