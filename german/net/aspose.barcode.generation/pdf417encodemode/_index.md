---
title: "Enum Pdf417EncodeMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.Pdf417EncodeMode Aufzählung. Pdf417 Barcode-Kodierungsmodus"
type: docs
weight: 1540
url: /de/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Pdf417-Barcode-Kodierungsmodus

```csharp
public enum Pdf417EncodeMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Im Auto-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode-Zeichen werden in der angegebenen ECIEncoding-Kodierung mit dem Einfügen eines ECI-Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. |
| Binary | `1` | Im Binär-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode-Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | `2` | Im ECI-Modus wird die gesamte Nachricht in der angegebenen ECIEncoding-Kodierung mit dem Einfügen eines ECI-Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige ältere (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. |
| Extended | `3` | Erweiterter Modus, der mehrere ECI‑Modi unterstützt. |

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


