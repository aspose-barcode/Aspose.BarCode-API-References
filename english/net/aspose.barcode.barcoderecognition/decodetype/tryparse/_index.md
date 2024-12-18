---
title: DecodeType.TryParse
second_title: Aspose.BarCode for .NET API Reference
description: DecodeType method. Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed
type: docs
weight: 970
url: /net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../decodetype/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultyDecodeType) {#tryparse}

Converts the string representation of a MultyDecodeType to its instance. A return value indicates whether the conversion succeeded or failed.

```csharp
public static bool TryParse(string parsingType, out MultyDecodeType result)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | String | A string in the format as either "AllSupportedTypes" or "EAN8,EAN13,CodaBar" to convert. |
| result | MultyDecodeType& | An actual MultyDecodeType is returned, when conversion has completed successfully; otherwise it returns indefinite type: new MultyDecodeType(DecodeType.None) |

### Return Value

**true** if parsingType was converted successfully; otherwise, **false**.

### See Also

* class [MultyDecodeType](../../multydecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../decodetype/)
* assembly [Aspose.BarCode](../../../)


