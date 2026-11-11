---
title: "Enum Pdf417EncodeMode"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.Generation.Pdf417EncodeMode enum. Pdf417 streckkod kodningsläge"
type: docs
weight: 1540
url: /sv/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Pdf417 streckkod kodningsläge

```csharp
public enum Pdf417EncodeMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | `0` | I Auto-läge kodas CodeText med maximal datakomprimering. Unicode-tecken kodas om i den angivna ECIEncoding‑kodningen med införandet av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. |
| Binary | `1` | I Binärt läge kodas CodeText med maximal datakomprimering. Om ett Unicode‑tecken hittas kastas ett undantag. |
| ECI | `2` | I ECI‑läge kodas hela meddelandet om i den angivna ECIEncoding‑kodningen med införandet av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge. |
| Extended | `3` | Utökat läge som stödjer flera ECI‑lägen. |

### Se även

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


