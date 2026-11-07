---
title: "Methode"
linktitle: "set_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man die Methode set_EncodeGS1SeparatorInByteMode der Klasse Aspose::BarCode::Generation::QrParameters in C++ verwendet."
type: docs
weight: 1800
url: /de/cpp/aspose.barcode.generation/qrparameters/set_encodegs1separatorinbytemode/
---
## QrParameters::set_EncodeGS1SeparatorInByteMode method




```cpp
void Aspose::BarCode::Generation::QrParameters::set_EncodeGS1SeparatorInByteMode(bool value)
```

## Hinweise


Legt einen Wert fest, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes codiert werden sollen.

Wenn false, können GS1-Trennzeichen gemäß QR-Spezifikation im alphanumerischen Modus als '' codiert werden.

Wenn true, werden GS1-Gruppentrennzeichen im Byte-Modus als das Zeichen 0x1D codiert, und ''-Zeichen werden ebenfalls im Byte-Modus codiert, um sie als Daten zu erhalten.

Diese Option kann die Kompatibilität mit Decodern verbessern, die byteweise GS1-Gruppentrennzeichen erwarten, und verhindert, dass ''-Datenzeichen als GS1-Trennzeichen interpretiert werden.
## Siehe auch

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
