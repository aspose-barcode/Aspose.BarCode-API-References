---
title: "QrParameters.EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "QrParameters-Eigenschaft. Gibt einen Wert zurück oder legt ihn fest, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes codiert werden sollen."
type: docs
weight: 30
url: /de/net/aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/
---
## QrParameters.EncodeGS1SeparatorInByteMode property

Liest oder setzt einen Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes codiert werden sollen.

Wenn false, können GS1-Trennzeichen gemäß QR-Spezifikation im Alphanumerischen Modus als '%' kodiert werden.

Wenn true, werden GS1-Gruppentrennzeichen im Byte-Modus als das Zeichen 0x1D kodiert, und '%' Zeichen werden ebenfalls im Byte-Modus kodiert, um sie als Daten zu erhalten.

Diese Option kann die Kompatibilität mit Decodern verbessern, die byteweise GS1-Gruppentrennzeichen erwarten, und verhindert, dass '%' Datenzeichen als GS1-Trennzeichen interpretiert werden.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### Siehe auch

* class [QrParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


