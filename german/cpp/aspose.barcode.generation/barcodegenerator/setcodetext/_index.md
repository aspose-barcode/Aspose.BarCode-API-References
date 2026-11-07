---
title: "Methode"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Setzt den Codetext als Byte‑Sequenz in C++."
type: docs
weight: 700
url: /de/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


Setze den Codetext als Bytefolge.

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | Bytes des Codetexts |

## Siehe auch

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codeText | System::String | CodeText‑Zeichenkette |
| Kodierung | System::SharedPtr\<System::Text::Encoding\> | Angewandte Kodierung |
## Hinweise


Kodiert den Unicode **codeText** in eine Byte‑Sequenz unter Verwendung der angegebenen **encoding**. UTF-8 ist die am häufigsten verwendete Kodierung. Unterstützt die Kodierung dies, fügt die Funktion automatisch ein [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) ein.

Diese Funktion ist ausschließlich für die Verwendung mit 2D‑Barcodes vorgesehen (z. B. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR usw.). Sie ermöglicht die manuelle Kodierung von Unicode‑Text mit nationalen oder speziellen Kodierungen; diese Methode gilt jedoch in modernen Anwendungen als veraltet. Für aktuelle Anwendungsfälle wird die [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation)-Kodierung für Unicode‑Daten empfohlen.

Die Verwendung dieser Funktion mit 1D‑Barcodes, GS1‑konformen Barcodes (einschließlich 2D) oder HIBC‑Barcodes (einschließlich 2D) wird von den jeweiligen Barcode‑Standards nicht unterstützt und kann zu unvorhersehbaren Ergebnissen führen.


Dieses Beispiel zeigt, wie man **SetCodeText** verwendet, um Unicode‑kodierten Text für 2D‑Barcodes mit verschiedenen Kodierungen festzulegen:


```cpp
[C#]
//QR‑Code‑Text mit UTF-8 und BOM kodieren
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //DataMatrix-Text mit Shift-JIS (japanische Kodierung) kodieren
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## Siehe auch

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codeText | System::String | CodeText‑Zeichenkette |
| Kodierung | System::SharedPtr\<System::Text::Encoding\> | Angewandte Kodierung |
| insertBOM | bool | Gibt an, ob ein Byte Order Mark (BOM) eingefügt werden soll, wenn die angegebene Kodierung dies unterstützt (z. B. UTF-8, UTF-16, UTF-32). Ist sie auf **true** gesetzt, wird das BOM hinzugefügt; ist sie auf **false** gesetzt, wird das BOM weggelassen, selbst wenn die Kodierung normalerweise eines verwendet. |
## Hinweise


Kodiert den Unicode-**codeText** in eine Byte‑Sequenz unter Verwendung der angegebenen **encoding**. UTF-8 ist die am häufigsten verwendete Kodierung. Unterstützt die Kodierung dies und ist **insertBOM** auf **true** gesetzt, fügt die Funktion ein [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) hinzu.

Diese Funktion ist ausschließlich für die Verwendung mit 2D‑Barcodes vorgesehen (z. B. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR usw.). Sie ermöglicht die manuelle Kodierung von Unicode‑Text mit nationalen oder speziellen Kodierungen; diese Methode gilt jedoch in modernen Anwendungen als veraltet. Für aktuelle Anwendungsfälle wird die [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation)-Kodierung für Unicode‑Daten empfohlen.

Die Verwendung dieser Funktion mit 1D‑Barcodes, GS1‑konformen Barcodes (einschließlich 2D) oder HIBC‑Barcodes (einschließlich 2D) wird von den jeweiligen Barcode‑Standards nicht unterstützt und kann zu unvorhersehbaren Ergebnissen führen.


Dieses Beispiel zeigt, wie **SetCodeText** mit oder ohne ein BOM für 2D‑Barcodes verwendet wird.


```cpp
[C#]
    //Codetext mit UTF-8 und BOM kodieren
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Codetext mit UTF-8 ohne BOM kodieren
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## Siehe auch

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
