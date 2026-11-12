---
title: "DeconvolutionMode"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Deconvolution (Bildrestaurierung) Modus, der das Niveau der Bilddegradation definiert."
type: docs
weight: 220
url: /de/nodejs/global/deconvolutionmode/
---

## DeconvolutionMode

Deconvolution (Bildrestaurierung) Modus, der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine natürliche Funktion wie Unschärfe (blur) degradiertes (konvolutiertes) Bild wiederherstellen kann, wenn das Bild mit einer Kamera aufgenommen wird. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen. Dieses Beispiel zeigt, wie man den Deconvolution‑Modus verwendet let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setDeconvolution(DeconvolutionMode.SLOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Werte

| Name | Beschreibung |
| --- | --- |
| ISO_8859_1 | ISO/IEC 8859-1 Latin‑Alphabet‑Kodierung Nr. 1. ECI‑Id:"\000003" |
| ISO_8859_2 | ISO/IEC 8859-2 Latin‑Alphabet‑Kodierung Nr. 2. ECI‑Id:"\000004" |
| ISO_8859_3 | ISO/IEC 8859-3 Latin‑Alphabet‑Kodierung Nr. 3. ECI‑Id:"\000005" |
| ISO_8859_4 | ISO/IEC 8859-4 Latin‑Alphabet‑Kodierung Nr. 4. ECI‑Id:"\000006" |
| ISO_8859_5 | ISO/IEC 8859-5 Latin/Kyrillische Alphabetkodierung. ECI Id:"\000007" |
| ISO_8859_6 | ISO/IEC 8859-6 Latin/Arabische Alphabetkodierung. ECI Id:"\000008" |
| ISO_8859_7 | ISO/IEC 8859-7 Latin/Griechische Alphabetkodierung. ECI Id:"\000009" |
| ISO_8859_8 | ISO/IEC 8859-8 Latin/Hebräische Alphabetkodierung. ECI Id:"\000010" |
| ISO_8859_9 | ISO/IEC 8859-9 Lateinisches Alphabet Nr. 5 Kodierung. ECI Id:"\000011" |
| ISO_8859_10 | ISO/IEC 8859-10 Lateinisches Alphabet Nr. 6 Kodierung. ECI Id:"\000012" |
| ISO_8859_11 | ISO/IEC 8859-11 Latin/Thailändische Alphabetkodierung. ECI Id:"\000013" |
| ISO_8859_13 | ISO/IEC 8859-13 Lateinisches Alphabet Nr. 7 (Baltische Halbinsel) Kodierung. ECI Id:"\000015" |
| ISO_8859_14 | ISO/IEC 8859-14 Lateinisches Alphabet Nr. 8 (Keltisch) Kodierung. ECI Id:"\000016" |
| ISO_8859_15 | ISO/IEC 8859-15 Lateinisches Alphabet Nr. 9 Kodierung. ECI Id:"\000017" |
| ISO_8859_16 | ISO/IEC 8859-16 Lateinisches Alphabet Nr. 10 Kodierung. ECI Id:"\000018" |
| Shift_JIS | Shift JIS (JIS X 0208 Anhang 1 + JIS X 0201) Kodierung. ECI Id:"\000020" |
| Win1250 | Windows 1250 Latin 2 (Zentraleuropa) Kodierung. ECI Id:"\000021" |
| Win1251 | Windows 1251 Kyrillische Kodierung. ECI Id:"\000022" |
| Win1252 | Windows 1252 Latin-1-Kodierung. ECI Id:"\000023" |
| Win1256 | Windows 1256 Arabische Kodierung. ECI Id:"\000024" |
| UTF16BE | ISO/IEC 10646 UCS-2 (höheres Byte zuerst) Kodierung. ECI Id:"\000025" |
| UTF8 | ISO/IEC 10646 UTF-8 Kodierung. ECI Id:"\000026" |
| US_ASCII | ISO/IEC 646:1991 Internationale Referenzversion des ISO 7‑Bit‑kodierten Zeichensatzes. ECI Id:"\000027" |
| Big5 | Big 5 (Taiwan) Chinesischer Zeichensatzkodierung. ECI Id:"\000028" |
| GB2312 | GB (VR China) Chinesischer Zeichensatzkodierung. ECI Id:"\000029" |
| EUC_KR | Koreanischer Zeichensatzkodierung. ECI Id:"\000030" |
| GBK | GBK (Erweiterung von GB2312 für vereinfachtes Chinesisch) Kodierung. ECI Id:"\000031" |
| GB18030 | GGB18030 Chinesischer Zeichensatzkodierung. ECI Id:"\000032" |
| UTF16LE | ISO/IEC 10646 UTF-16LE Kodierung. ECI Id:"\000033" |
| UTF32BE | ISO/IEC 10646 UTF-32BE Kodierung. ECI Id:"\000034" |
| UTF32LE | ISO/IEC 10646 UTF-32LE Kodierung. ECI Id:"\000035" |
| INVARIANT | ISO/IEC 646: ISO 7-Bit kodierter Zeichensatz - Invariant Characters-Set Kodierung. ECI Id:"\000170" |
| BINARY | 8-Bit Binärdaten. ECI Id:"\000899" |
| NONE | Keine erweiterte Kanalinterpretation |
