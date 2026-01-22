---
title:  enum
linktitle: Pdf417EncodeMode
second_title: Aspose.BarCode for C++ API Reference
description: ' enum. Pdf417 barcode encode mode in C++.'
type: docs
weight: 7400
url: /cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Pdf417 barcode encode mode

```cpp
enum class Pdf417EncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| Binary | 1 | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| ECI | 2 | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |
| Extended | 3 |  |

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
