---
title: "Clase MultiDecodeType"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.MultiDecodeType. Tipo de decodificación compuesta"
type: docs
weight: 320
url: /es/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Tipo de decodificación compuesto.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | Inicializa una nueva instancia de la clase `MultiDecodeType`. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | Inicializa una nueva instancia de la clase `MultiDecodeType`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Devuelve un número de tipos simples. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | Agrega uno más [`SingleDecodeType`](../singledecodetype/) al MultiDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Comprueba si esto contiene todos los tipos de códigos de barras. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Contiene alguno de los tipos. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [`BaseDecodeType`](../basedecodetype/). |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `MultiDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `MultiDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Devuelve un valor que indica si esta colección de tipos de decodificación contiene solo el valor especificado [`SingleDecodeType`](../singledecodetype/). |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Excluye [`SingleDecodeType`](../singledecodetype/) del MultiDecodeType y devuelve una nueva instancia de MultiDecodeType. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Devuelve el código hash de esta instancia. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Representa una lista de tipos simples. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Método sobrescrito que representa MultiDecodeType como una cadena. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | Convierte la representación en cadena de un MultiDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |

## Ejemplos

Este ejemplo muestra cómo crear tipos compuestos de MultiDecode que combinan SingleDecodeType y tipos MultiDecode.

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### Ver también

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


