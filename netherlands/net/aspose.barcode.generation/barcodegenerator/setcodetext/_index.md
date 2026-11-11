---
title: "BarcodeGenerator.SetCodeText"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarcodeGenerator methode. Stelt codetext in als een reeks bytes"
type: docs
weight: 100
url: /nl/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

Stel codetext in als een reeks bytes.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codeBytes | Byte[] | Bytes van codetext |

### Zie ook

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Encodeert de Unicode **codeText** naar een byte‑reeks met behulp van de opgegeven **encoding**. UTF-8 is de meest gebruikte codering. Als de codering dit ondersteunt, voegt de functie automatisch een [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) toe.

Deze functie is uitsluitend bedoeld voor gebruik met 2D-barcodes (bijv. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, enz.). Het maakt handmatige codering van Unicode-tekst mogelijk met nationale of speciale coderingen; echter wordt deze methode als verouderd beschouwd in moderne toepassingen. Voor moderne gebruikssituaties wordt [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) codering aanbevolen voor Unicode-gegevens.

Het gebruik van deze functie met 1D-barcodes, GS1-conforme barcodes (inclusief 2D), of HIBC-barcodes (inclusief 2D) wordt niet ondersteund door de bijbehorende barcode-standaarden en kan leiden tot onvoorspelbare resultaten.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codeText | String | CodeText string |
| codering | Codering | Toegepaste codering |

## Voorbeelden

Dit voorbeeld toont hoe `SetCodeText` te gebruiken om Unicode-gecodeerde tekst voor 2D-barcodes met verschillende coderingen in te stellen:

```csharp
[C#]
//QR-code-tekst coderen met UTF-8 met BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//DataMatrix-tekst coderen met Shift-JIS (Japanse codering)
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### Zie ook

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Encodeert de Unicode **codeText** naar een byte‑reeks met behulp van de opgegeven **encoding**. UTF-8 is de meest gebruikte codering. Als de codering dit ondersteunt en **insertBOM** is ingesteld op `true`, voegt de functie een [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) toe.

Deze functie is uitsluitend bedoeld voor gebruik met 2D-barcodes (bijv. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, enz.). Het maakt handmatige codering van Unicode-tekst mogelijk met nationale of speciale coderingen; echter wordt deze methode als verouderd beschouwd in moderne toepassingen. Voor moderne gebruikssituaties wordt [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) codering aanbevolen voor Unicode-gegevens.

Het gebruik van deze functie met 1D-barcodes, GS1-conforme barcodes (inclusief 2D), of HIBC-barcodes (inclusief 2D) wordt niet ondersteund door de bijbehorende barcode-standaarden en kan leiden tot onvoorspelbare resultaten.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codeText | String | CodeText string |
| codering | Codering | Toegepaste codering |
| insertBOM | Boolean | Geeft aan of een byte order mark (BOM) moet worden ingevoegd wanneer de opgegeven codering dit ondersteunt (bijv. UTF-8, UTF-16, UTF-32). Als ingesteld op `true`, wordt de BOM toegevoegd; als `false`, wordt de BOM weggelaten, zelfs als de codering normaal gesproken een BOM gebruikt. |

## Voorbeelden

Dit voorbeeld toont hoe `SetCodeText` te gebruiken met of zonder een BOM voor 2D-barcodes.

```csharp
[C#]
//Codetekst coderen met UTF-8 met BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Codetekst coderen met UTF-8 zonder BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### Zie ook

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


