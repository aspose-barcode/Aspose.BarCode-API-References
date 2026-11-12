---
title: "DataMatrixEncodeMode"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Kodierungsmodus des DataMatrix‑Encoders, standardmäßig Auto. Dieses Beispiel zeigt, wie man Codetext im erweiterten Modus verwendet."
type: docs
weight: 190
url: /de/nodejs/global/datamatrixencodemode/
---

## DataMatrixEncodeMode

Kodierungsmodus des DataMatrix‑Encoders, standardmäßig Auto. Dieses Beispiel zeigt, wie man Codetext im erweiterten Modus verwendet. //Auto‑Modus let codetext = "犬Right狗"; let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext); generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8); generator.save("test.bmp", BarcodeImageFormat.PNG); //Byte‑Modus let encodedArr = [ 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 ]; let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, encodedArr); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.BINARY); generator.save("test.bmp", BarcodeImageFormat.PNG); //Erweiterter Codetext‑Modus //Codetext erstellen let codetextBuilder=new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,DataMatrixEncodeMode.BYTES,"World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF8,"犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C40,"ABCDE"); //Codetext generieren let codetext=codetextBuilder.getExtended(); //generieren let generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.PNG);

## Werte

| Name | Beschreibung |
| --- | --- |
| NONE | Nicht spezifizierter Dekodierungstyp. |
| CODABAR | Gibt an, dass die Daten mit der `CODABAR ` Barcode‑Spezifikation dekodiert werden sollen. |
| CODE_11 | Gibt an, dass die Daten mit der `CODE 11 ` Barcode‑Spezifikation dekodiert werden sollen. |
| CODE_39 | Gibt an, dass die Daten mit der `Code 39 ` Grundzeichensatz‑Barcode‑Spezifikation dekodiert werden sollen: ISO/IEC 16388 |
| CODE_39_FULL_ASCII | Gibt an, dass die Daten mit der `Code 39 ` Voll‑ASCII‑Zeichensatz‑Barcode‑Spezifikation dekodiert werden sollen: ISO/IEC 16388 |
| CODE_93 | Gibt an, dass die Daten mit der `CODE 93 ` Barcode-Spezifikation dekodiert werden sollen |
| CODE_128 | Gibt an, dass die Daten mit der `CODE 128 ` Barcode-Spezifikation dekodiert werden sollen |
| GS_1_CODE_128 | Gibt an, dass die Daten mit der `GS1 CODE 128 ` Barcode-Spezifikation dekodiert werden sollen |
| EAN_8 | Gibt an, dass die Daten mit der `EAN-8 ` Barcode-Spezifikation dekodiert werden sollen |
| EAN_13 | Gibt an, dass die Daten mit der `EAN-13 ` Barcode-Spezifikation dekodiert werden sollen |
| EAN_14 | Gibt an, dass die Daten mit der `EAN14 ` Barcode-Spezifikation dekodiert werden sollen |
| SCC_14 | Gibt an, dass die Daten mit der `SCC14 ` Barcode-Spezifikation dekodiert werden sollen |
| SSCC_18 | Gibt an, dass die Daten mit der `SSCC18 ` Barcode-Spezifikation dekodiert werden sollen |
| UPCA | Gibt an, dass die Daten mit der `UPC-A ` Barcode-Spezifikation dekodiert werden sollen |
| UPCE | Gibt an, dass die Daten mit der `UPC-E ` Barcode-Spezifikation dekodiert werden sollen |
| ISBN | Gibt an, dass die Daten mit der `ISBN ` Barcode-Spezifikation dekodiert werden sollen |
| STANDARD_2_OF_5 | Gibt an, dass die Daten mit der `Standard 2 of 5 ` Barcode-Spezifikation dekodiert werden sollen |
| INTERLEAVED_2_OF_5 | Gibt an, dass die Daten mit der Barcode‑Spezifikation `INTERLEAVED 2 of 5 ` dekodiert werden sollen |
| MATRIX_2_OF_5 | Gibt an, dass die Daten mit der Barcode‑Spezifikation `Matrix 2 of 5 ` dekodiert werden sollen |
| ITALIAN_POST_25 | Gibt an, dass die Daten mit der Barcode‑Spezifikation `Italian Post 25 ` dekodiert werden sollen |
| IATA_2_OF_5 | Gibt an, dass die Daten mit der Barcode‑Spezifikation `IATA 2 of 5 ` dekodiert werden sollen. IATA (International Air Transport Association) verwendet diesen Barcode für die Verwaltung von Luftfracht. |
| ITF_14 | Gibt an, dass die Daten mit der Barcode‑Spezifikation `ITF14 ` dekodiert werden sollen |
| ITF_6 | Gibt an, dass die Daten mit der Barcode‑Spezifikation `ITF6 ` dekodiert werden sollen |
| MSI | Gibt an, dass die Daten mit der Barcode‑Spezifikation `MSI Plessey ` dekodiert werden sollen |
| VIN | Gibt an, dass die Daten mit der Barcode‑Spezifikation `VIN ` (Vehicle Identification Number) dekodiert werden sollen |
| DEUTSCHE_POST_IDENTCODE | Gibt an, dass die Daten mit der Barcode‑Spezifikation `DeutschePost Ident code ` dekodiert werden sollen |
| DEUTSCHE_POST_LEITCODE | Gibt an, dass die Daten mit der Barcode‑Spezifikation `DeutschePost Leit code ` dekodiert werden sollen |
| OPC | Gibt an, dass die Daten mit der Barcode‑Spezifikation `OPC ` dekodiert werden sollen |
| PZN | Gibt an, dass die Daten mit der Barcode‑Spezifikation `PZN ` dekodiert werden sollen. Diese Symbolik ist auch als Pharma Zentral Nummer bekannt |
| PHARMACODE | Gibt an, dass die Daten mit dem Barcode `Pharmacode ` dekodiert werden sollen. Diese Symbolik ist auch als Pharmaceutical BINARY Code bekannt |
| DATA_MATRIX | Gibt an, dass die Daten mit der Barcode‑Symbologie `DataMatrix ` decodiert werden sollen |
| GS_1_DATA_MATRIX | Gibt an, dass die Daten mit der Barcode‑Symbologie `GS1DataMatrix ` decodiert werden sollen |
| QR | Gibt an, dass die Daten mit der Barcode‑Spezifikation `QR Code ` decodiert werden sollen |
| AZTEC | Gibt an, dass die Daten mit der Barcode‑Spezifikation `Aztec ` decodiert werden sollen |
| GS_1_AZTEC | Gibt an, dass die Daten mit der Barcode‑Spezifikation `GS1 Aztec ` decodiert werden sollen |
| PDF_417 | Gibt an, dass die Daten mit der Barcode‑Symbologie `Pdf417 ` decodiert werden sollen |
| MACRO_PDF_417 | Gibt an, dass die Daten mit der Barcode‑Spezifikation `MacroPdf417 ` decodiert werden sollen |
| MICRO_PDF_417 | Gibt an, dass die Daten mit der Barcode‑Spezifikation `MicroPdf417 ` decodiert werden sollen |
| GS_1_MICRO_PDF_417 | Gibt an, dass die Daten mit der Barcode‑Spezifikation MicroPdf417 decodiert werden sollen |
| CODABLOCK_F | Gibt an, dass die Daten mit der Barcode‑Spezifikation `CodablockF ` decodiert werden sollen |
| MAILMARK | Gibt an, dass die Daten mit der Barcode‑Spezifikation Royal Mail Mailmark decodiert werden sollen. |
| AUSTRALIA_POST | Gibt an, dass die Daten mit der Barcode‑Spezifikation `Australia Post ` decodiert werden sollen |
| POSTNET | Gibt an, dass die Daten mit der `Postnet ` Barcode-Spezifikation dekodiert werden sollen |
| PLANET | Gibt an, dass die Daten mit der `Planet ` Barcode-Spezifikation dekodiert werden sollen |
| ONE_CODE | Gibt an, dass die Daten mit der USPS `OneCode ` Barcode-Spezifikation dekodiert werden sollen |
| RM_4_SCC | Gibt an, dass die Daten mit der `RM4SCC ` Barcode-Spezifikation dekodiert werden sollen. RM4SCC (Royal Mail 4-state Customer Code) wird für den automatisierten Postsortierprozess im Vereinigten Königreich verwendet. |
| DATABAR_OMNI_DIRECTIONAL | Gibt an, dass die Daten mit der `GS1 DATABAR omni-directional ` Barcode-Spezifikation dekodiert werden sollen |
| DATABAR_TRUNCATED | Gibt an, dass die Daten mit der `GS1 DATABAR truncated ` Barcode-Spezifikation dekodiert werden sollen |
| DATABAR_LIMITED | Gibt an, dass die Daten mit der `GS1 DATABAR limited ` Barcode-Spezifikation dekodiert werden sollen |
| DATABAR_EXPANDED | Gibt an, dass die Daten mit der `GS1 DATABAR expanded ` Barcode-Spezifikation dekodiert werden sollen |
| DATABAR_STACKED_OMNI_DIRECTIONAL | Gibt an, dass die Daten mit der `GS1 DATABAR stacked omni-directional ` Barcode-Spezifikation dekodiert werden sollen |
| DATABAR_STACKED | Gibt an, dass die Daten mit der `GS1 DATABAR stacked ` Barcode-Spezifikation dekodiert werden sollen |
| DATABAR_EXPANDED_STACKED | Gibt an, dass die Daten mit der `GS1 DATABAR expanded stacked ` Barcode-Spezifikation dekodiert werden sollen |
| PATCH_CODE | Gibt an, dass die Daten mit der `Patch code ` Barcode-Spezifikation dekodiert werden sollen. Die Barcode-Symbologie wird für automatisiertes Scannen verwendet. |
| ISSN | Gibt an, dass die Daten mit der `ISSN ` Barcode-Spezifikation dekodiert werden sollen |
| ISMN | Gibt an, dass die Daten mit `ISMN ` Barcode-Spezifikation dekodiert werden sollen |
| SUPPLEMENT | Gibt an, dass die Daten mit `Supplement(EAN2, EAN5) ` Barcode-Spezifikation dekodiert werden sollen |
| AUSTRALIAN_POSTE_PARCEL | Gibt an, dass die Daten mit `Australian Post Domestic eParcel Barcode ` Barcode-Spezifikation dekodiert werden sollen |
| SWISS_POST_PARCEL | Gibt an, dass die Daten mit `Swiss Post Parcel Barcode ` Barcode-Spezifikation dekodiert werden sollen |
| CODE_16_K | Gibt an, dass die Daten mit `SCode16K ` Barcode-Spezifikation dekodiert werden sollen |
| MICRO_QR | Gibt an, dass die Daten mit `MicroQR Code ` Barcode-Spezifikation dekodiert werden sollen |
| RECT_MICRO_QR | Gibt an, dass die Daten mit RectMicroQR (rMQR) Code Barcode-Spezifikation dekodiert werden sollen |
| COMPACT_PDF_417 | Gibt an, dass die Daten mit `CompactPdf417 ` (Pdf417Truncated) Barcode-Spezifikation dekodiert werden sollen |
| GS_1_QR | Gibt an, dass die Daten mit `GS1 QR ` Barcode-Spezifikation dekodiert werden sollen |
| MAXI_CODE | Gibt an, dass die Daten mit `MaxiCode ` Barcode-Spezifikation dekodiert werden sollen |
| MICR_E_13_B | Gibt an, dass die Daten mit `MICR E-13B ` Leere Spezifikation dekodiert werden sollen |
| CODE_32 | Gibt an, dass die Daten mit `Code32 ` Leere Spezifikation dekodiert werden sollen |
| DATA_LOGIC_2_OF_5 | Gibt an, dass die Daten mit `DataLogic 2 of 5 ` leerer Spezifikation dekodiert werden sollen |
| DOT_CODE | Gibt an, dass die Daten mit `DotCode ` leerer Spezifikation dekodiert werden sollen |
| GS_1_DOT_CODE | Gibt an, dass die Daten mit `GS1 DotCode ` leerer Spezifikation dekodiert werden sollen |
| DUTCH_KIX | Gibt an, dass die Daten mit `DotCode ` leerer Spezifikation dekodiert werden sollen |
| HIBC_CODE_39_LIC | Gibt an, dass die Daten mit `HIBC LIC Code39 ` leerer Spezifikation dekodiert werden sollen |
| HIBC_CODE_128_LIC | Gibt an, dass die Daten mit `HIBC LIC Code128 ` leerer Spezifikation dekodiert werden sollen |
| HIBC_AZTEC_LIC | Gibt an, dass die Daten mit `HIBC LIC Aztec ` leerer Spezifikation dekodiert werden sollen |
| HIBC_DATA_MATRIX_LIC | Gibt an, dass die Daten mit `HIBC LIC DataMatrix ` leerer Spezifikation dekodiert werden sollen |
| HIBBQRLIC | Gibt an, dass die Daten mit `HIBC LIC QR ` leerer Spezifikation dekodiert werden sollen |
| HIBC_CODE_39_PAS | Gibt an, dass die Daten mit `HIBC PAS Code39 ` leerer Spezifikation dekodiert werden sollen |
| HIBC_CODE_128_PAS | Gibt an, dass die Daten mit `HIBC PAS Code128 ` leerer Spezifikation dekodiert werden sollen |
| HIBC_AZTEC_PAS | Gibt an, dass die Daten mit `HIBC PAS Aztec ` leerer Spezifikation dekodiert werden sollen |
| HIBC_DATA_MATRIX_PAS | Gibt an, dass die Daten mit `HIBC PAS DataMatrix ` leerer Spezifikation dekodiert werden sollen |
| HIBCQRPAS | Gibt an, dass die Daten mit `HIBC PAS QR ` leerer Spezifikation dekodiert werden sollen |
| HAN_XIN | Gibt an, dass die Daten mit Han Xin Code leerer Spezifikation dekodiert werden sollen |
| GS_1_HAN_XIN | Gibt an, dass die Daten mit Han Xin Code leerer Spezifikation dekodiert werden sollen |
| GS_1_COMPOSITE_BAR | Gibt an, dass die Daten mit `GS1 Composite Bar ` Barcode-Spezifikation dekodiert werden sollen |
| TYPES_1D | Gibt an, dass Daten mit allen 1D-Barcode-Symbologien geprüft werden |
| POSTAL_TYPES | Gibt an, dass Daten mit allen 1,5D POSTAL-Barcode-Symbologien geprüft werden, wie Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX |
| MOST_COMMON_TYPES | Gibt an, dass Daten mit den am häufigsten verwendeten Symbologien geprüft werden |
| TYPES_2D | Gibt an, dass Daten mit allen 2D-Barcode-Symbologien geprüft werden |
| ALL_SUPPORTED_TYPES | Gibt an, dass Daten mit allen verfügbaren Symbologien geprüft werden |
| is1D | Bestimmt, ob der angegebene BaseDecodeType irgendeine 1D-Barcode-Symbologie enthält |
| isPostal | Bestimmt, ob der angegebene BaseDecodeType irgendeine Postal-Barcode-Symbologie enthält |
| is2D | Bestimmt, ob der angegebene BaseDecodeType irgendeine 2D-Barcode-Symbologie enthält |
| containsAny |  |
