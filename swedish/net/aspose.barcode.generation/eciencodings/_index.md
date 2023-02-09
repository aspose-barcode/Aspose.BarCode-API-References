---
title: ECIEncodings
second_title: Aspose.BarCode för .NET API-referens
description: Identifierare för utökad kanaltolkning. Den används för att berätta streckkodsläsarens detaljer om de referenser som används för att koda data i symbolen. Den nuvarande implementeringen består av alla välkända teckenuppsättningskoder. För närvarande används den endast för QR 2D-streckkoder.
type: docs
weight: 700
url: /sv/net/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enumeration

Identifierare för utökad kanaltolkning. Den används för att berätta streckkodsläsarens detaljer om de referenser som används för att koda data i symbolen. Den nuvarande implementeringen består av alla välkända teckenuppsättningskoder. För närvarande används den endast för QR 2D-streckkoder.

```csharp
public enum ECIEncodings
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| ISO_8859_1 | `3` | ISO/IEC 8859-1 kodning med latinskt alfabet nr 1. ECI-id:"\000003" |
| ISO_8859_2 | `4` | ISO/IEC 8859-2 kodning med latinskt alfabet nr 2. ECI-id:"\000004" |
| ISO_8859_3 | `5` | ISO/IEC 8859-3 latinska alfabet nr 3 kodning. ECI-id:"\000005" |
| ISO_8859_4 | `6` | ISO/IEC 8859-4 kodning med latinskt alfabet nr 4. ECI-id:"\000006" |
| ISO_8859_5 | `7` | ISO/IEC 8859-5 kodning med latinskt/kyrilliskt alfabet. ECI-id:"\000007" |
| ISO_8859_6 | `8` | ISO/IEC 8859-6 kodning med latinsk/arabiskt alfabet. ECI-id:"\000008" |
| ISO_8859_7 | `9` | ISO/IEC 8859-7 kodning med latinskt/grekiskt alfabet. ECI-id:"\000009" |
| ISO_8859_8 | `10` | ISO/IEC 8859-8 latinsk/hebreiska alfabetkodning. ECI-id:"\000010" |
| ISO_8859_9 | `11` | ISO/IEC 8859-9 kodning med latinskt alfabet nr 5. ECI-id:"\000011" |
| ISO_8859_10 | `12` | ISO/IEC 8859-10 latinska alfabet nr 6 kodning. ECI-id:"\000012" |
| ISO_8859_11 | `13` | ISO/IEC 8859-11 latinsk/thailändsk alfabetkodning. ECI-id:"\000013" |
| ISO_8859_13 | `15` | ISO/IEC 8859-13 latinska alfabet nr 7 (Baltic Rim) kodning. ECI-id:"\000015" |
| ISO_8859_14 | `16` | ISO/IEC 8859-14 latinska alfabet nr 8 (keltisk) kodning. ECI-id:"\000016" |
| ISO_8859_15 | `17` | ISO/IEC 8859-15 kodning med latinskt alfabet nr 9. ECI-id:"\000017" |
| ISO_8859_16 | `18` | ISO/IEC 8859-16 kodning med latinskt alfabet nr 10. ECI-id:"\000018" |
| Shift_JIS | `20` | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201)-kodning. ECI-id:"\000020" |
| Win1250 | `21` | Windows 1250 Latin 2 (Centraleuropa) kodning. ECI-id:"\000021" |
| Win1251 | `22` | Windows 1251 kyrillisk kodning. ECI-id:"\000022" |
| Win1252 | `23` | Windows 1252 Latin 1-kodning. ECI-id:"\000023" |
| Win1256 | `24` | Windows 1256 arabisk kodning. ECI-id:"\000024" |
| UTF16BE | `25` | ISO/IEC 10646 UCS-2 (Hög ordning byte först) kodning. ECI-id:"\000025" |
| UTF8 | `26` | ISO/IEC 10646 UTF-8-kodning. ECI-id:"\000026" |
| US_ASCII | `27` | ISO/IEC 646:1991 Internationell referensversion av ISO 7-bitars kodad teckenuppsättningskodning. ECI-id:"\000027" |
| Big5 | `28` | Big 5 (Taiwan) kinesisk teckenuppsättning kodning. ECI-id:"\000028" |
| GB18030 | `29` | GB (PRC) Kinesisk teckenuppsättningskodning. ECI-id:"\000029" |
| EUC_KR | `30` | Koreansk teckenuppsättningskodning. ECI-id:"\000030" |
| NONE | `0` | Ingen utökad kanaltolkning |

### Exempel

Detta exempel visar hur man använder ECI-kodning och sparar en streckkodsbild.

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

### Se även

* namnutrymme [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->