---
title: "Methode"
linktitle: "get_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man die Methode get_EncodeGS1SeparatorInByteMode der Klasse Aspose::BarCode::Generation::QrParameters in C++ verwendet."
type: docs
weight: 1700
url: /de/cpp/aspose.barcode.generation/qrparameters/get_encodegs1separatorinbytemode/
---
## QrParameters::get_EncodeGS1SeparatorInByteMode method




```cpp
bool Aspose::BarCode::Generation::QrParameters::get_EncodeGS1SeparatorInByteMode() const
```

## Hinweise


Gibt einen Wert zurück, der angibt, ob GS1-Sonderzeichen für QR- und RectMicroQR-Barcodes im Byte-Modus codiert werden sollen.

Wenn false, können GS1-Trennzeichen gemäß QR-Spezifikation im alphanumerischen Modus als '' codiert werden.

Wenn true, werden GS1-Gruppentrennzeichen im Byte-Modus als das Zeichen 0x1D codiert, und ''-Zeichen werden ebenfalls im Byte-Modus codiert, um sie als Daten zu erhalten.

Diese Option kann die Kompatibilität mit Decodern verbessern, die byteweise GS1-Gruppentrennzeichen erwarten, und verhindert, dass ''-Datenzeichen als GS1-Trennzeichen interpretiert werden.
## Siehe auch

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
