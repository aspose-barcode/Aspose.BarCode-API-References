---
title: "BarcodeGenerator.SetCodeText"
second_title: "Aspose.BarCode för .NET API-referens"
description: "BarcodeGenerator-metod. Ställ in kodtext som en sekvens av byte"
type: docs
weight: 100
url: /sv/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

Ställ in kodtext som en sekvens av byte.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codeBytes | Byte[] | Byte av kodtext |

### Se även

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Kodar Unicode-**codeText** till en byte‑sekvens med den angivna **encoding**. UTF-8 är den mest använda kodningen. Om kodningen stödjer det, infogar funktionen automatiskt ett [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Denna funktion är avsedd att endast användas med 2D-streckkoder (t.ex. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Den möjliggör manuell kodning av Unicode-text med nationella eller speciella kodningar; dock anses denna metod vara föråldrad i moderna applikationer. För moderna användningsfall rekommenderas [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation)-kodning för Unicode-data.

Att använda denna funktion med 1D-streckkoder, GS1-kompatibla streckkoder (inklusive 2D) eller HIBC-streckkoder (inklusive 2D) stöds inte av motsvarande streckkodstandarder och kan leda till oförutsägbara resultat.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codeText | String | CodeText-sträng |
| kodning | Kodning | Tillämad kodning |

## Exempel

Detta exempel visar hur man använder `SetCodeText` för att ange Unicode‑kodad text för 2D-streckkoder med olika kodningar:

```csharp
[C#]
//Kodera QR‑kodtext med UTF-8 och BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Koda DataMatrix-text med Shift-JIS (japansk kodning)
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### Se även

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Kodar Unicode **codeText** till en bytesekvens med den angivna **encoding**. UTF-8 är den mest använda kodningen. Om kodningen stödjer det och **insertBOM** är satt till `true`, inkluderar funktionen en [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Denna funktion är avsedd att endast användas med 2D-streckkoder (t.ex. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Den möjliggör manuell kodning av Unicode-text med nationella eller speciella kodningar; dock anses denna metod vara föråldrad i moderna applikationer. För moderna användningsfall rekommenderas [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation)-kodning för Unicode-data.

Att använda denna funktion med 1D-streckkoder, GS1-kompatibla streckkoder (inklusive 2D) eller HIBC-streckkoder (inklusive 2D) stöds inte av motsvarande streckkodstandarder och kan leda till oförutsägbara resultat.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codeText | String | CodeText-sträng |
| kodning | Kodning | Tillämad kodning |
| insertBOM | Boolean | Anger om en byte order mark (BOM) ska infogas när den angivna kodningen stödjer det (t.ex. UTF-8, UTF-16, UTF-32). Om satt till `true` läggs BOM till; om `false` utelämnas BOM även om kodningen normalt använder en. |

## Exempel

Detta exempel visar hur man använder `SetCodeText` med eller utan en BOM för 2D-streckkoder.

```csharp
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

### Se även

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


