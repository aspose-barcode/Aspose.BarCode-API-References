---
title: "Aspose::BarCode::Generation::HanXinParameters Klasse"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::HanXinParameters Klasse. Han Xin Parameter in C++."
type: docs
weight: 2900
url: /de/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Han‑Xin-Parameter.

```cpp
class HanXinParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers. Es wird verwendet, um dem Barcode-Leser Details über die verwendeten Referenzen zur Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. |
| [get_EncodeMode](./get_encodemode/)() const | HanXin-Codierungsmodus. Standardwert: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | Level der Reed-Solomon-Fehlerkorrektur für den Han Xin Barcode. Von niedrig nach hoch: L1, L2, L3, L4. siehe ErrorLevel. |
| [get_Version](./get_version/)() const | Version des HanXin-Codes. Von Version01 bis Version84 für Han Xin Code. Standardwert ist [Version.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. Es wird verwendet, um dem Barcode-Leser Details über die verwendeten Referenzen zur Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | HanXin-Codierungsmodus. Standardwert: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Level der Reed-Solomon-Fehlerkorrektur für den Han Xin Barcode. Von niedrig nach hoch: L1, L2, L3, L4. siehe ErrorLevel. |
| [set_Version](./set_version/)(HanXinVersion) | Version des HanXin-Codes. Von Version01 bis Version84 für Han Xin Code. Standardwert ist [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [HanXinParameters](./) zurück. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
