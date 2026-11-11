---
title: "Enum ECIEncodings"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.ECIEncodings enum. Uitgebreide kanaalinterpretatie‑identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool"
type: docs
weight: 1270
url: /nl/net/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enumeration

Extended Channel Interpretation-identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool.

```csharp
public enum ECIEncodings
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| ISO_8859_1 | `3` | ISO/IEC 8859-1 Latijns alfabet Nr. 1 codering. ECI Id:"\000003" |
| ISO_8859_2 | `4` | ISO/IEC 8859-2 Latijns alfabet Nr. 2 codering. ECI Id:"\000004" |
| ISO_8859_3 | `5` | ISO/IEC 8859-3 Latijns alfabet Nr. 3 codering. ECI Id:"\000005" |
| ISO_8859_4 | `6` | ISO/IEC 8859-4 Latijns alfabet Nr. 4 codering. ECI Id:"\000006" |
| ISO_8859_5 | `7` | ISO/IEC 8859-5 Latijns/Cyrillisch alfabet codering. ECI Id:"\000007" |
| ISO_8859_6 | `8` | ISO/IEC 8859-6 Latijns/Arabisch alfabet codering. ECI Id:"\000008" |
| ISO_8859_7 | `9` | ISO/IEC 8859-7 Latijns/Grieks alfabet codering. ECI Id:"\000009" |
| ISO_8859_8 | `10` | ISO/IEC 8859-8 Latijns/Hebreeuw alfabet codering. ECI Id:"\000010" |
| ISO_8859_9 | `11` | ISO/IEC 8859-9 Latijns alfabet Nr. 5 codering. ECI Id:"\000011" |
| ISO_8859_10 | `12` | ISO/IEC 8859-10 Latijns alfabet Nr. 6 codering. ECI Id:"\000012" |
| ISO_8859_11 | `13` | ISO/IEC 8859-11 Latijns/Thais alfabet codering. ECI Id:"\000013" |
| ISO_8859_13 | `15` | ISO/IEC 8859-13 Latijns alfabet Nr. 7 (Baltische rand) codering. ECI Id:"\000015" |
| ISO_8859_14 | `16` | ISO/IEC 8859-14 Latijns alfabet Nr. 8 (Keltisch) codering. ECI Id:"\000016" |
| ISO_8859_15 | `17` | ISO/IEC 8859-15 Latijns alfabet Nr. 9 codering. ECI Id:"\000017" |
| ISO_8859_16 | `18` | ISO/IEC 8859-16 Latijns alfabet Nr. 10 codering. ECI Id:"\000018" |
| Shift_JIS | `20` | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) codering. ECI Id:"\000020" |
| Win1250 | `21` | Windows 1250 Latijns 2 (Centraal‑Europa) codering. ECI Id:"\000021" |
| Win1251 | `22` | Windows 1251 Cyrillische codering. ECI Id:"\000022" |
| Win1252 | `23` | Windows 1252 Latijns 1 codering. ECI Id:"\000023" |
| Win1256 | `24` | Windows 1256 Arabische codering. ECI Id:"\000024" |
| UTF16BE | `25` | ISO/IEC 10646 UCS-2 (hoogste byte eerst) codering. ECI Id:"\000025" |
| UTF8 | `26` | ISO/IEC 10646 UTF-8 codering. ECI Id:"\000026" |
| US_ASCII | `27` | ISO/IEC 646:1991 Internationale referentie‑versie van ISO 7‑bit gecodeerde tekenset codering. ECI Id:"\000027" |
| Big5 | `28` | Big 5 (Taiwan) Chinese tekenset codering. ECI Id:"\000028" |
| GB2312 | `29` | GB2312 Chinese tekenset codering. ECI Id:"\000029" |
| EUC_KR | `30` | Koreaanse tekenset codering. ECI Id:"\000030" |
| GBK | `31` | GBK (extensie van GB2312 voor Vereenvoudigd Chinees) codering. ECI Id:"\000031" |
| GB18030 | `32` | GGB18030 Chinese tekenset codering. ECI Id:"\000032" |
| UTF16LE | `33` | ISO/IEC 10646 UTF-16LE codering. ECI Id:"\000033" |
| UTF32BE | `34` | ISO/IEC 10646 UTF-32BE codering. ECI Id:"\000034" |
| UTF32LE | `35` | ISO/IEC 10646 UTF-32LE codering. ECI Id:"\000035" |
| INVARIANT | `170` | ISO/IEC 646: ISO 7‑bit gecodeerde tekenset - Invariante tekenset codering. ECI Id:"\000170" |
| BINARY | `899` | 8‑bit binaire gegevens. ECI Id:"\000899" |
| NONE | `0` | Geen uitgebreide kanaalinterpretatie |

## Voorbeelden

Deze voorbeeld toont hoe ECI‑codering te gebruiken en een BarCode‑afbeelding op te slaan.

```csharp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
[VB.NET]
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = "12345TEXT"
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding
    generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8
    generator.Save("test.png")
End Using
```

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


