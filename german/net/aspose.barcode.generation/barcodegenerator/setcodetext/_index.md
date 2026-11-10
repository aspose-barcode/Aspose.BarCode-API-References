---
title: "BarcodeGenerator.SetCodeText"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarcodeGenerator-Methode. Codetext als Byte‑Sequenz festlegen"
type: docs
weight: 100
url: /de/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

Setzt den Codetext als Byte‑Sequenz.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codeBytes | Byte[] | Bytes des Codetexts |

### Siehe auch

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Kodiert den Unicode **codeText** in eine Byte‑Sequenz unter Verwendung der angegebenen **encoding**. UTF-8 ist das am häufigsten verwendete Encoding. Unterstützt das Encoding dies, fügt die Funktion automatisch ein [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) ein.

Diese Funktion ist ausschließlich für die Verwendung mit 2D‑Barcodes vorgesehen (z. B. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR usw.). Sie ermöglicht die manuelle Kodierung von Unicode‑Text mit nationalen oder speziellen Kodierungen; diese Methode gilt jedoch in modernen Anwendungen als veraltet. Für aktuelle Anwendungsfälle wird die [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation)-Kodierung für Unicode‑Daten empfohlen.

Die Verwendung dieser Funktion mit 1D‑Barcodes, GS1‑konformen Barcodes (einschließlich 2D) oder HIBC‑Barcodes (einschließlich 2D) wird von den jeweiligen Barcode‑Standards nicht unterstützt und kann zu unvorhersehbaren Ergebnissen führen.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codeText | String | CodeText‑Zeichenkette |
| Kodierung | Kodierung | Angewandte Kodierung |

## Beispiele

Dieses Beispiel zeigt, wie `SetCodeText` verwendet wird, um Unicode‑kodierten Text für 2D‑Barcodes mit verschiedenen Kodierungen festzulegen:

```csharp
[C#]
//QR‑Code‑Text mit UTF‑8 und BOM kodieren
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//DataMatrix‑Text mit Shift‑JIS (japanische Kodierung) kodieren
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### Siehe auch

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Kodiert den Unicode **codeText** in eine Byte‑Sequenz unter Verwendung der angegebenen **encoding**. UTF-8 ist das am häufigsten verwendete Encoding. Unterstützt das Encoding dies und ist **insertBOM** auf `true` gesetzt, fügt die Funktion ein [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) hinzu.

Diese Funktion ist ausschließlich für die Verwendung mit 2D‑Barcodes vorgesehen (z. B. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR usw.). Sie ermöglicht die manuelle Kodierung von Unicode‑Text mit nationalen oder speziellen Kodierungen; diese Methode gilt jedoch in modernen Anwendungen als veraltet. Für aktuelle Anwendungsfälle wird die [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation)-Kodierung für Unicode‑Daten empfohlen.

Die Verwendung dieser Funktion mit 1D‑Barcodes, GS1‑konformen Barcodes (einschließlich 2D) oder HIBC‑Barcodes (einschließlich 2D) wird von den jeweiligen Barcode‑Standards nicht unterstützt und kann zu unvorhersehbaren Ergebnissen führen.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codeText | String | CodeText‑Zeichenkette |
| Kodierung | Kodierung | Angewandte Kodierung |
| insertBOM | Boolesch | Gibt an, ob ein Byte‑Order‑Mark (BOM) eingefügt werden soll, wenn die angegebene Kodierung dies unterstützt (z. B. UTF‑8, UTF‑16, UTF‑32). Ist sie auf `true` gesetzt, wird das BOM hinzugefügt; bei `false` wird das BOM weggelassen, selbst wenn die Kodierung normalerweise eines verwendet. |

## Beispiele

Dieses Beispiel zeigt, wie `SetCodeText` für 2D‑Barcodes mit oder ohne BOM verwendet wird.

```csharp
[C#]
//Codetext mit UTF‑8 und BOM kodieren
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Codetext mit UTF‑8 ohne BOM kodieren
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### Siehe auch

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


