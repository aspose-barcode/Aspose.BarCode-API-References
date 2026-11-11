---
title: "Clase SymbologyEncodeType"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.SymbologyEncodeType. Tipo de codificación de simbología. Consulte EncodeTypes para obtener una instancia."
type: docs
weight: 1710
url: /es/net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

Tipo de codificación de simbología. Consulte EncodeTypes para obtener una instancia.

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification/) { get; } | Obtiene una clasificación de esta simbología. |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex/) { get; } | Obtiene un índice del tipo de codificación |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename/) { get; } | Obtiene un nombre del tipo de codificación |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(BaseEncodeType) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [`BaseEncodeType`](../baseencodetype/). |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [`BaseEncodeType`](../baseencodetype/). |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode/)() | Devuelve el código hash de esta instancia. |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring/)() | Convierte la instancia de BaseEncodeType a su representación de cadena equivalente. El formato de la cadena es: "Index:0; Name:Codabar". |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring/)() | Devuelve el nombre del BaseEncodeType dado como una cadena. |

## Ejemplos

Este ejemplo muestra cómo obtener una instancia de la clase SymbologyEncodeType.

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### Ver también

* class [BaseEncodeType](../baseencodetype/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


