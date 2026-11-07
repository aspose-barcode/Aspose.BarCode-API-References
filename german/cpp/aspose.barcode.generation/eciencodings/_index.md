---
title: "enum"
linktitle: "ECI‑Kodierungen"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man das enum in C++ verwendet."
type: docs
weight: 6600
url: /de/cpp/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enum




```cpp
enum class ECIEncodings
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| ISO_8859_1 | 3 | ISO/IEC 8859-1 Lateinisches Alphabet Nr. 1 Kodierung. ECI‑Id:"\000003" |
| ISO_8859_2 | 4 | ISO/IEC 8859-2 Lateinisches Alphabet Nr. 2 Kodierung. ECI‑Id:"\000004" |
| ISO_8859_3 | 5 | ISO/IEC 8859-3 Lateinisches Alphabet Nr. 3 Kodierung. ECI‑Id:"\000005" |
| ISO_8859_4 | 6 | ISO/IEC 8859-4 Lateinisches Alphabet Nr. 4 Kodierung. ECI‑Id:"\000006" |
| ISO_8859_5 | 7 | ISO/IEC 8859-5 Lateinisch/Kyrillisches Alphabet Kodierung. ECI‑Id:"\000007" |
| ISO_8859_6 | 8 | ISO/IEC 8859-6 Lateinisch/Arabisches Alphabet Kodierung. ECI‑Id:"\000008" |
| ISO_8859_7 | 9 | ISO/IEC 8859-7 Lateinisch/Griechisches Alphabet Kodierung. ECI‑Id:"\000009" |
| ISO_8859_8 | 10 | ISO/IEC 8859-8 Lateinisch/Hebräisches Alphabet Kodierung. ECI‑Id:"\000010" |
| ISO_8859_9 | 11 | ISO/IEC 8859-9 Lateinisches Alphabet Nr. 5 Kodierung. ECI Id:"\000011" |
| ISO_8859_10 | 12 | ISO/IEC 8859-10 Lateinisches Alphabet Nr. 6 Kodierung. ECI Id:"\000012" |
| ISO_8859_11 | 13 | ISO/IEC 8859-11 Lateinisch/Thailändisches Alphabet Kodierung. ECI Id:"\000013" |
| ISO_8859_13 | 15 | ISO/IEC 8859-13 Lateinisches Alphabet Nr. 7 (Baltische Halbinsel) Kodierung. ECI Id:"\000015" |
| ISO_8859_14 | 16 | ISO/IEC 8859-14 Lateinisches Alphabet Nr. 8 (Keltisch) Kodierung. ECI Id:"\000016" |
| ISO_8859_15 | 17 | ISO/IEC 8859-15 Lateinisches Alphabet Nr. 9 Kodierung. ECI Id:"\000017" |
| ISO_8859_16 | 18 | ISO/IEC 8859-16 Lateinisches Alphabet Nr. 10 Kodierung. ECI Id:"\000018" |
| Shift_JIS | 20 | Shift JIS (JIS X 0208 Anhang 1 + JIS X 0201) Kodierung. ECI Id:"\000020" |
| Win1250 | 21 | [Windows](../../aspose.barcode.windows/) 1250 Latin 2 (Zentraleuropa) Kodierung. ECI Id:"\000021" |
| Win1251 | 22 | [Windows](../../aspose.barcode.windows/) 1251 Kyrillisch Kodierung. ECI Id:"\000022" |
| Win1252 | 23 | [Windows](../../aspose.barcode.windows/) 1252 Latin 1 Kodierung. ECI Id:"\000023" |
| Win1256 | 24 | [Windows](../../aspose.barcode.windows/) 1256 Arabisch Kodierung. ECI Id:"\000024" |
| UTF16BE | 25 | ISO/IEC 10646 UCS-2 (höherwertiges Byte zuerst) Kodierung. ECI Id:"\000025" |
| UTF8 | 26 | ISO/IEC 10646 UTF-8 Kodierung. ECI Id:"\000026" |
| US_ASCII | 27 | ISO/IEC 646:1991 Internationale Referenzversion des ISO 7‑Bit‑kodierten Zeichensatzes Kodierung. ECI Id:"\000027" |
| Big5 | 28 | Big 5 (Taiwan) Chinesisches Zeichensatz-Encoding. ECI Id:"\000028" |
| GB2312 | 29 | GB2312 Chinesisches Zeichensatz-Encoding. ECI Id:"\000029" |
| EUC_KR | 30 | Koreanisches Zeichensatz-Encoding. ECI Id:"\000030" |
| GBK | 31 | GBK (Erweiterung von GB2312 für vereinfachtes Chinesisch) Encoding. ECI Id:"\000031" |
| GB18030 | 32 | GGB18030 Chinesisches Zeichensatz-Encoding. ECI Id:"\000032" |
| UTF16LE | 33 | ISO/IEC 10646 UTF-16LE Encoding. ECI Id:"\000033" |
| UTF32BE | 34 | ISO/IEC 10646 UTF-32BE Encoding. ECI Id:"\000034" |
| UTF32LE | 35 | ISO/IEC 10646 UTF-32LE Encoding. ECI Id:"\000035" |
| INVARIANT | 170 | ISO/IEC 646: ISO 7-bit codierter Zeichensatz - Invariant Characters set Encoding. ECI Id:"\000170" |
| BINARY | 899 | 8-bit Binärdaten. ECI Id:"\000899" |
| NONE | 0 | Keine erweiterte Kanalinterpretation |

## Hinweise


Extended Channel Interpretation Identifiers. Es wird verwendet, um dem Barcode-Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen.

Dieses Beispiel zeigt, wie man ECI‑Kodierung verwendet und ein [BarCode](../../aspose.barcode/)‑Bild speichert.
```cpp
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

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
