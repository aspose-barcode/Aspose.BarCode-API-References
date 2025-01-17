---
title: DecodeType.Parse
second_title: Aspose.BarCode for .NET API Reference
description: DecodeType method. Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed
type: docs
weight: 950
url: /net/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType.Parse method

Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed.

```csharp
public static bool Parse(string parsingType, out SingleDecodeType result)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | String | A string containing a SingleDecodeType in the format as "EAN8" or "EAN13" or "CodaBar"... to convert. |
| result | SingleDecodeType& | An actual SingleDecodeType returns, when conversion has completed successfully; otherwise it returns indefinite type: DecodeType.None. |

### Return Value

**true** if parsingType was converted successfully; otherwise, **false**.

### See Also

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


