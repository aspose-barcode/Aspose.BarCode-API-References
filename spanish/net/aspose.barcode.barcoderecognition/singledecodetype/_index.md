---
title: "Clase SingleDecodeType"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.SingleDecodeType. Tipo de decodificación único. Consulte el tipo de decodificación para obtener una instancia."
type: docs
weight: 390
url: /es/net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

Tipo de decodificación único. Consulte el tipo de decodificación para obtener una instancia.

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | Obtiene un índice del tipo de decodificación. |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | Obtiene un nombre del tipo de decodificación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | Convierte la representación en cadena del nombre de un SingleDecodeType a su instancia. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | Devuelve un valor que indica si esta instancia está incluida en la lista especificada. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [`BaseDecodeType`](../basedecodetype/). |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_1)(MultiDecodeType) | Devuelve un valor que indica si la colección especificada de [`MultiDecodeType`](../multidecodetype/) contiene solo este tipo de decodificación. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `SingleDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `SingleDecodeType`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | Devuelve el código hash de esta instancia. |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | Convierte la instancia de SingleDecodeType a su representación en cadena equivalente. El formato de cadena es: "Index:-1; Name:None". |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | Devuelve el nombre del SingleDecodeType dado como una cadena. |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | Convierte la instancia de SingleDecodeType a su representación en cadena equivalente. El formato de cadena es: "Index:-1; Name:None". |

## Ejemplos

Este ejemplo muestra cómo obtener una instancia del tipo de decodificación único.

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### Ver también

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


