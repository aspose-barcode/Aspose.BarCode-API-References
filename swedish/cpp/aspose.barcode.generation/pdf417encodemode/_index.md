---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: " enum. Pdf417-streckkodskodningsläge i C++."
type: docs
weight: 7900
url: /sv/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Pdf417 streckkod kodningsläge

```cpp
enum class Pdf417EncodeMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | I Auto‑läge kodas CodeText med maximal datakomprimering. Unicode‑tecken omkodas i den angivna ECIEncoding‑kodningen med insättning av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. |
| Binär | 1 | I Binär‑läge kodas CodeText med maximal datakomprimering. Om ett Unicode‑tecken hittas kastas ett undantag. |
| ECI | 2 | I ECI‑läge omkodas hela meddelandet i den angivna ECIEncoding‑kodningen med insättning av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge. |
| Utökad | 3 |  |

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
