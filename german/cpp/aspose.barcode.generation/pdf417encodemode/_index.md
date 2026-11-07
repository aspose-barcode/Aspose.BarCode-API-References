---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Enum. Pdf417-Barcode-Kodierungsmodus in C++."
type: docs
weight: 7900
url: /de/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Pdf417-Barcode-Kodierungsmodus

```cpp
enum class Pdf417EncodeMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Im Auto-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode-Zeichen werden in der angegebenen ECIEncoding neu kodiert, wobei ein ECI-Identifikator eingefügt wird. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Codierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. |
| Binär | 1 | Im Binärmodus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode-Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | 2 | Im ECI-Modus wird die gesamte Nachricht in der angegebenen ECIEncoding neu kodiert, wobei ein ECI-Identifikator eingefügt wird. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Codierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige ältere (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. |
| Erweitert | 3 |  |

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
