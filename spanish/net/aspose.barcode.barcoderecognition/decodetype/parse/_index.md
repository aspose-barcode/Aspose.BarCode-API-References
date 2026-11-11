---
title: "DecodeType.Parse"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Método DecodeType. Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló."
type: docs
weight: 960
url: /es/net/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType.Parse method

Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

```csharp
public static bool Parse(string parsingType, out SingleDecodeType result)
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


