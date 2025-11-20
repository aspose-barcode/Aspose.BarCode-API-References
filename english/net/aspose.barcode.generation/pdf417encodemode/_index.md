---
title: Enum Pdf417EncodeMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.Pdf417EncodeMode enum. Pdf417 barcode encode mode
type: docs
weight: 1430
url: /net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Pdf417 barcode encode mode

```csharp
public enum Pdf417EncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| Binary | `1` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| ECI | `2` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |
| Extended | `3` | Extended mode which supports multi ECI modes. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


