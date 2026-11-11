---
title: "DecodeType.TryParse"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Método DecodeType. Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló."
type: docs
weight: 980
url: /es/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | Cadena | Una cadena que contiene un SingleDecodeType en el formato "EAN8" o "EAN13" o "CodaBar"... para convertir. |
| resultado | SingleDecodeType& | Un SingleDecodeType real se devuelve cuando la conversión se ha completado con éxito; de lo contrario, devuelve el tipo indefinido: DecodeType.None. |

### Valor de retorno

**true** if parsingType was converted successfully; otherwise, **false**.

### Ver también

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse}

Convierte la representación en cadena de un MultiDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | Cadena | Una cadena con el formato "AllSupportedTypes" o "EAN8,EAN13,CodaBar" para convertir. |
| resultado | MultiDecodeType& | Se devuelve un MultiDecodeType real cuando la conversión se completa con éxito; de lo contrario, devuelve el tipo indefinido: new MultiDecodeType(DecodeType.None) |

### Valor de retorno

**true** if parsingType was converted successfully; otherwise, **false**.

### Ver también

* class [MultiDecodeType](../../multidecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


