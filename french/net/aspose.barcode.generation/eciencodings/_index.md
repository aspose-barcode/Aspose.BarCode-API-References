---
title: "Énumération ECIEncodings"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Énumération Aspose.BarCode.Generation.ECIEncodings. Identifiants d'Interprétation de Canal Étendu. Elle est utilisée pour informer le lecteur de code-barres des détails concernant les références utilisées pour l'encodage des données dans le symbole."
type: docs
weight: 1270
url: /fr/net/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enumeration

Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour informer le lecteur de code-barres des détails concernant les références utilisées pour encoder les données dans le symbole.

```csharp
public enum ECIEncodings
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| ISO_8859_1 | `3` | Encodage ISO/IEC 8859-1 alphabet latin n° 1. Id ECI :"\000003" |
| ISO_8859_2 | `4` | Encodage ISO/IEC 8859-2 alphabet latin n° 2. Id ECI :"\000004" |
| ISO_8859_3 | `5` | Encodage ISO/IEC 8859-3 alphabet latin n° 3. Id ECI :"\000005" |
| ISO_8859_4 | `6` | Encodage ISO/IEC 8859-4 alphabet latin n° 4. Id ECI :"\000006" |
| ISO_8859_5 | `7` | Encodage ISO/IEC 8859-5 alphabet latin/cyrillique. Id ECI :"\000007" |
| ISO_8859_6 | `8` | Encodage ISO/IEC 8859-6 alphabet latin/arabe. Id ECI :"\000008" |
| ISO_8859_7 | `9` | Encodage ISO/IEC 8859-7 alphabet latin/grec. Id ECI :"\000009" |
| ISO_8859_8 | `10` | Encodage ISO/IEC 8859-8 alphabet latin/hebreu. Id ECI :"\000010" |
| ISO_8859_9 | `11` | Encodage ISO/IEC 8859-9 alphabet latin n° 5. Id ECI :"\000011" |
| ISO_8859_10 | `12` | Encodage ISO/IEC 8859-10 alphabet latin n° 6. Id ECI :"\000012" |
| ISO_8859_11 | `13` | Encodage ISO/IEC 8859-11 alphabet latin/thai. Id ECI :"\000013" |
| ISO_8859_13 | `15` | Encodage ISO/IEC 8859-13 alphabet latin n° 7 (Baltic Rim). Id ECI :"\000015" |
| ISO_8859_14 | `16` | Encodage ISO/IEC 8859-14 alphabet latin n° 8 (Celtique). Id ECI :"\000016" |
| ISO_8859_15 | `17` | ISO/IEC 8859-15 alphabet latin n° 9 encodage. ECI Id:"\000017" |
| ISO_8859_16 | `18` | ISO/IEC 8859-16 alphabet latin n° 10 encodage. ECI Id:"\000018" |
| Shift_JIS | `20` | Shift JIS (JIS X 0208 Annexe 1 + JIS X 0201) encodage. ECI Id:"\000020" |
| Win1250 | `21` | Windows 1250 Latin 2 (Europe centrale) encodage. ECI Id:"\000021" |
| Win1251 | `22` | Windows 1251 cyrillique encodage. ECI Id:"\000022" |
| Win1252 | `23` | Windows 1252 Latin 1 encodage. ECI Id:"\000023" |
| Win1256 | `24` | Windows 1256 arabe encodage. ECI Id:"\000024" |
| UTF16BE | `25` | ISO/IEC 10646 UCS-2 (octet de poids fort en premier) encodage. ECI Id:"\000025" |
| UTF8 | `26` | ISO/IEC 10646 UTF-8 encodage. ECI Id:"\000026" |
| US_ASCII | `27` | ISO/IEC 646:1991 version de référence internationale du jeu de caractères codé ISO 7 bits encodage. ECI Id:"\000027" |
| Big5 | `28` | Big 5 (Taïwan) jeu de caractères chinois encodage. ECI Id:"\000028" |
| GB2312 | `29` | GB2312 jeu de caractères chinois encodage. ECI Id:"\000029" |
| EUC_KR | `30` | Jeu de caractères coréen encodage. ECI Id:"\000030" |
| GBK | `31` | GBK (extension de GB2312 pour le chinois simplifié) encodage. ECI Id:"\000031" |
| GB18030 | `32` | GGB18030 jeu de caractères chinois encodage. ECI Id:"\000032" |
| UTF16LE | `33` | ISO/IEC 10646 UTF-16LE encodage. ECI Id:"\000033" |
| UTF32BE | `34` | ISO/IEC 10646 UTF-32BE encodage. ECI Id:"\000034" |
| UTF32LE | `35` | ISO/IEC 10646 UTF-32LE encodage. ECI Id:"\000035" |
| INVARIANT | `170` | ISO/IEC 646 : jeu de caractères codé ISO 7 bits - jeu de caractères invariants encodage. ECI Id:"\000170" |
| BINARY | `899` | Données binaires 8 bits. ECI Id:"\000899" |
| NONE | `0` | Pas d'interprétation de canal étendu |

## Exemples

Cet exemple montre comment utiliser l'encodage ECI et enregistrer une image de BarCode.

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

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


