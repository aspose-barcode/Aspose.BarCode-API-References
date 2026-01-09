---
title:  enum
linktitle: AutoSizeMode
second_title: Aspose.BarCode for C++ API Reference
description: ' enum. Specifies the different types of automatic sizing modes in C++.'
type: docs
weight: 4700
url: /cpp/aspose.barcode.generation/autosizemode/
---
## AutoSizeMode enum


Specifies the different types of automatic sizing modes.

```cpp
enum class AutoSizeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Automatic resizing is disabled. |
| Nearest | 1 | Resizes barcode to nearest lowest possible size specified by ImageWidth and ImageHeight properties. Preserves default aspect ratio. |
| Interpolation | 2 | Resizes barcode to specified size. Size can be specified by ImageWidth and ImageHeight properties. Generated barcode may be invalid (not readable) after scaling. |

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
