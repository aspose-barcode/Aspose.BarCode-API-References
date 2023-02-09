---
title: ECIEncodings
second_title: Aspose.BarCode voor .NET API-referentie
description: Uitgebreide kanaalinterpretatieIDs. Het wordt gebruikt om de streepjescodelezer details te vertellen over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bestaat uit alle bekende tekensetcoderingen. Momenteel wordt het alleen gebruikt voor QR 2Dbarcode.
type: docs
weight: 930
url: /nl/net/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enumeration

Uitgebreide kanaalinterpretatie-ID's. Het wordt gebruikt om de streepjescodelezer details te vertellen over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bestaat uit alle bekende tekensetcoderingen. Momenteel wordt het alleen gebruikt voor QR 2D-barcode.

```csharp
public enum ECIEncodings
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| ISO_8859_1 | `3` | Codering ISO/IEC 8859-1 Latijns alfabet nr. 1. ECI-ID:"\000003" |
| ISO_8859_2 | `4` | Codering ISO/IEC 8859-2 Latijns alfabet nr. 2. ECI-ID:"\000004" |
| ISO_8859_3 | `5` | Codering ISO/IEC 8859-3 Latijns alfabet nr. 3. ECI-ID:"\000005" |
| ISO_8859_4 | `6` | Codering ISO/IEC 8859-4 Latijns alfabet nr. 4. ECI-ID:"\000006" |
| ISO_8859_5 | `7` | ISO/IEC 8859-5 Latijnse/Cyrillische alfabetcodering. ECI-ID:"\000007" |
| ISO_8859_6 | `8` | ISO/IEC 8859-6 Latijnse/Arabische alfabetcodering. ECI-ID:"\000008" |
| ISO_8859_7 | `9` | ISO/IEC 8859-7 Latijnse/Griekse alfabetcodering. ECI-ID:"\000009" |
| ISO_8859_8 | `10` | ISO/IEC 8859-8 Latijnse/Hebreeuwse alfabetcodering. ECI-ID:"\000010" |
| ISO_8859_9 | `11` | Codering ISO/IEC 8859-9 Latijns alfabet nr. 5. ECI-ID:"\000011" |
| ISO_8859_10 | `12` | Codering ISO/IEC 8859-10 Latijns alfabet nr. 6. ECI-ID:"\000012" |
| ISO_8859_11 | `13` | ISO/IEC 8859-11 Latijnse/Thaise alfabetcodering. ECI-ID:"\000013" |
| ISO_8859_13 | `15` | Codering ISO/IEC 8859-13 Latijns alfabet nr. 7 (Baltic Rim). ECI-ID:"\000015" |
| ISO_8859_14 | `16` | Codering ISO/IEC 8859-14 Latijns alfabet nr. 8 (Keltisch). ECI-ID:"\000016" |
| ISO_8859_15 | `17` | Codering ISO/IEC 8859-15 Latijns alfabet nr. 9. ECI-ID:"\000017" |
| ISO_8859_16 | `18` | Codering ISO/IEC 8859-16 Latijns alfabet nr. 10. ECI-ID:"\000018" |
| Shift_JIS | `20` | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) codering. ECI-ID:"\000020" |
| Win1250 | `21` | Windows 1250 Latin 2 (Centraal-Europa) codering. ECI-ID:"\000021" |
| Win1251 | `22` | Windows 1251 Cyrillische codering. ECI-ID:"\000022" |
| Win1252 | `23` | Windows 1252 Latin 1-codering. ECI-ID:"\000023" |
| Win1256 | `24` | Windows 1256 Arabische codering. ECI-ID:"\000024" |
| UTF16BE | `25` | ISO/IEC 10646 UCS-2-codering (High order byte first). ECI-ID:"\000025" |
| UTF8 | `26` | ISO/IEC 10646 UTF-8-codering. ECI-ID:"\000026" |
| US_ASCII | `27` | ISO/IEC 646:1991 Internationale referentieversie van ISO 7-bit gecodeerde tekensetcodering. ECI-ID:"\000027" |
| Big5 | `28` | Codering Big 5 (Taiwan) Chinese tekenset. ECI-ID:"\000028" |
| GB18030 | `29` | GB (PRC) Chinese tekensetcodering. ECI-ID:"\000029" |
| EUC_KR | `30` | Codering van Koreaanse tekenset. ECI-ID:"\000030" |
| NONE | `0` | Geen uitgebreide kanaalinterpretatie |

### Voorbeelden

Dit voorbeeld laat zien hoe u ECI-codering gebruikt en hoe u een streepjescodeafbeelding opslaat.

```csharp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.QrEncodeType = QREncodeType.ForceQR;
    generator.Parameters.Barcode.QR.QrECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
[VB.NET]
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = "12345TEXT"
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ECIEncoding
    generator.Parameters.Barcode.QR.QrEncodeType = QREncodeType.ForceQR
    generator.Parameters.Barcode.QR.QrECIEncoding = ECIEncodings.UTF8
    generator.Save("test.png")
End Using
```

### Zie ook

* naamruimte [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->