---
title: "metod"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Ställ in kodtext som en byte‑sekvens i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


Ange kodtext som en sekvens av byte.

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | Byte av kodtext |

## Se även

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codeText | System::String | CodeText‑sträng |
| kodning | System::SharedPtr\<System::Text::Encoding\> | Tillämpad kodning |
## Anmärkningar


Kodar Unicode **codeText** till en byte‑sekvens med den angivna **encoding**. UTF-8 är den mest använda kodningen. Om kodningen stödjer det, infogar funktionen automatiskt ett [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Denna funktion är avsedd att endast användas med 2D‑streckkoder (t.ex. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR osv.). Den möjliggör manuell kodning av Unicode‑text med nationella eller speciella kodningar; dock anses denna metod vara föråldrad i moderna applikationer. För moderna användningsfall rekommenderas [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation)-kodning för Unicode‑data.

Att använda denna funktion med 1D‑streckkoder, GS1‑kompatibla streckkoder (inklusive 2D) eller HIBC‑streckkoder (inklusive 2D) stöds inte av de motsvarande streckkodstandarderna och kan leda till oförutsägbara resultat.


Detta exempel visar hur man använder **SetCodeText** för att ange Unicode‑kodad text för 2D‑streckkoder med olika kodningar:


```cpp
[C#]
//Koda QR‑kodtext med UTF-8 och BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Koda DataMatrix‑text med Shift-JIS (japansk kodning)
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## Se även

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codeText | System::String | CodeText‑sträng |
| kodning | System::SharedPtr\<System::Text::Encoding\> | Tillämpad kodning |
| insertBOM | bool | Anger om en byteordningsmarkör (BOM) ska infogas när den angivna kodningen stöder det (t.ex. UTF-8, UTF-16, UTF-32). Om den är satt till **true** läggs BOM till; om den är **false** utelämnas BOM även om kodningen normalt använder en. |
## Anmärkningar


Kodar Unicode **codeText** till en byte-sekvens med den angivna **encoding**. UTF-8 är den mest använda kodningen. Om kodningen stöder det och **insertBOM** är satt till **true** inkluderar funktionen en [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Denna funktion är avsedd att endast användas med 2D‑streckkoder (t.ex. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR osv.). Den möjliggör manuell kodning av Unicode‑text med nationella eller speciella kodningar; dock anses denna metod vara föråldrad i moderna applikationer. För moderna användningsfall rekommenderas [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation)-kodning för Unicode‑data.

Att använda denna funktion med 1D‑streckkoder, GS1‑kompatibla streckkoder (inklusive 2D) eller HIBC‑streckkoder (inklusive 2D) stöds inte av de motsvarande streckkodstandarderna och kan leda till oförutsägbara resultat.


Detta exempel visar hur man använder **SetCodeText** med eller utan en BOM för 2D-streckkoder.


```cpp
[C#]
    //Koda kodtext med UTF-8 med BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Koda kodtext med UTF-8 utan BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## Se även

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
