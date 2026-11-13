---
title: "HanXinEncodeMode"
second_title: "Aspose.Sildes för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Han Xin Code-kodningsläge. Det rekommenderas att använda Auto med ASCII / kinesiska tecken eller Unicode för Unicode-tecken.

## Members
| Medlemsnamn | Beskrivning |
| :- | :- |
| AUTO | I Auto‑läge kodas CodeText med maximal datakomprimering. <br/>            Unicode‑tecken kodas med GB18030‑kodning enligt HanXin‑streckkodsspecifikationen. |
| BINARY | I Binary‑läge kodas CodeText med maximal datakomprimering. <br/>            Om ett Unicode‑tecken hittas, kastas ett undantag. |
| ECI | I ECI‑läge omkodas hela meddelandet i den angivna ECIEncoding‑kodningen med införande av en ECI‑identifierare.<br/>            Om ett tecken hittas som inte stöds av den valda ECI‑kodningen, kastas ett undantag.<br/>            Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge. |
| UNICODE | Unicode‑läge utformar ett sätt att representera all textdata med referens till UTF8‑kodning/teckenuppsättning i Han Xin‑kod. |
| URI | URI‑läge indikerar att data som representeras i Han Xin‑kod är en Uniform Resource Identifier (URI)<br/>            referens till RFC 3986. |
| EXTENDED | Extended‑läge tillåter kombinationer av interna lägen: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            Kodtext kan byggas manuellt med prefix och dubbla bakstreck, t.ex.: @\"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c\" eller med HanXinExtCodetextBuilder.<br/>            Om kodtexten innehåller ett ECI‑fragment, får endast följande lägen finnas i kodtexten efter ECI‑fragmentet:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

