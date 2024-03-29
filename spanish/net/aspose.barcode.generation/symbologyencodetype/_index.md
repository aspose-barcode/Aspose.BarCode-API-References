---
title: SymbologyEncodeType
second_title: Referencia de API de Aspose.BarCode para .NET
description: Tipo de codificación de simbología. Ver EncodeTypes para obtener instancia.
type: docs
weight: 960
url: /es/net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

Tipo de codificación de simbología. Ver EncodeTypes para obtener instancia.

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification) { get; } | Obtiene una clasificación de esta simbología. |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex) { get; } | Obtiene un índice de tipo de codificación |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename) { get; } | Obtiene un nombre de tipo de codificación |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals)(BaseEncodeType) | Devuelve un valor que indica si esta instancia es igual a una especificada[`BaseEncodeType`](../baseencodetype) valor. |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals)(object) | Devuelve un valor que indica si esta instancia es igual a una especificada[`BaseEncodeType`](../baseencodetype) valor. |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode)() | Devuelve el código hash de esta instancia. |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring)() | Convierte la instancia de BaseEncodeType a su representación de cadena equivalente. El formato de cadena es: "Índice:0; Nombre:Codabar". |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring)() | Devuelve el nombre del BaseEncodeType dado como una cadena. |

### Ejemplos

Este ejemplo muestra cómo obtener una instancia de la clase SymbologyEncodeType.

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### Ver también

* class [BaseEncodeType](../baseencodetype)
* espacio de nombres [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
