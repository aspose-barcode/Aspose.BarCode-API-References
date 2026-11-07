---
title: "enum"
linktitle: "ECIEncodings"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare l'enumerazione in C++."
type: docs
weight: 6600
url: /it/cpp/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enum




```cpp
enum class ECIEncodings
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| ISO_8859_1 | 3 | Codifica alfabeto latino ISO/IEC 8859-1 n. 1. ID ECI:\"\\000003\" |
| ISO_8859_2 | 4 | Codifica alfabeto latino ISO/IEC 8859-2 n. 2. ID ECI:\"\\000004\" |
| ISO_8859_3 | 5 | Codifica alfabeto latino ISO/IEC 8859-3 n. 3. ID ECI:\"\\000005\" |
| ISO_8859_4 | 6 | Codifica alfabeto latino ISO/IEC 8859-4 n. 4. ID ECI:\"\\000006\" |
| ISO_8859_5 | 7 | Codifica alfabeto latino/cirillico ISO/IEC 8859-5. ID ECI:\"\\000007\" |
| ISO_8859_6 | 8 | Codifica alfabeto latino/arabo ISO/IEC 8859-6. ID ECI:\"\\000008\" |
| ISO_8859_7 | 9 | Codifica alfabeto latino/greco ISO/IEC 8859-7. ID ECI:\"\\000009\" |
| ISO_8859_8 | 10 | Codifica alfabeto latino/ebraico ISO/IEC 8859-8. ID ECI:\"\\000010\" |
| ISO_8859_9 | 11 | Codifica alfabeto latino ISO/IEC 8859-9 n. 5. ID ECI:\"\\000011\" |
| ISO_8859_10 | 12 | ISO/IEC 8859-10 codifica dell'alfabeto latino n. 6. ECI Id:"\000012" |
| ISO_8859_11 | 13 | ISO/IEC 8859-11 codifica dell'alfabeto latino/Thai. ECI Id:"\000013" |
| ISO_8859_13 | 15 | ISO/IEC 8859-13 codifica dell'alfabeto latino n. 7 (Baltic Rim). ECI Id:"\000015" |
| ISO_8859_14 | 16 | ISO/IEC 8859-14 codifica dell'alfabeto latino n. 8 (Celtic). ECI Id:"\000016" |
| ISO_8859_15 | 17 | ISO/IEC 8859-15 codifica dell'alfabeto latino n. 9. ECI Id:"\000017" |
| ISO_8859_16 | 18 | ISO/IEC 8859-16 codifica dell'alfabeto latino n. 10. ECI Id:"\000018" |
| Shift_JIS | 20 | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) codifica. ECI Id:"\000020" |
| Win1250 | 21 | [Windows](../../aspose.barcode.windows/) 1250 Latin 2 (Europa centrale) codifica. ECI Id:"\000021" |
| Win1251 | 22 | [Windows](../../aspose.barcode.windows/) 1251 codifica cirillica. ECI Id:"\000022" |
| Win1252 | 23 | [Windows](../../aspose.barcode.windows/) 1252 codifica Latin 1. ECI Id:"\000023" |
| Win1256 | 24 | [Windows](../../aspose.barcode.windows/) 1256 codifica araba. ECI Id:"\000024" |
| UTF16BE | 25 | ISO/IEC 10646 UCS-2 (High order byte first) codifica. ECI Id:"\000025" |
| UTF8 | 26 | ISO/IEC 10646 UTF-8 codifica. ECI Id:"\000026" |
| US_ASCII | 27 | ISO/IEC 646:1991 Versione di riferimento internazionale del set di caratteri a 7 bit codificato. ECI Id:"\000027" |
| Big5 | 28 | Codifica del set di caratteri cinese Big 5 (Taiwan). ECI Id:"\000028" |
| GB2312 | 29 | Codifica del set di caratteri cinese GB2312. ECI Id:"\000029" |
| EUC_KR | 30 | Codifica del set di caratteri coreano. ECI Id:"\000030" |
| GBK | 31 | Codifica GBK (estensione di GB2312 per il cinese semplificato). ECI Id:"\000031" |
| GB18030 | 32 | Codifica del set di caratteri cinese GGB18030. ECI Id:"\000032" |
| UTF16LE | 33 | Codifica ISO/IEC 10646 UTF-16LE. ECI Id:"\000033" |
| UTF32BE | 34 | Codifica ISO/IEC 10646 UTF-32BE. ECI Id:"\000034" |
| UTF32LE | 35 | Codifica ISO/IEC 10646 UTF-32LE. ECI Id:"\000035" |
| INVARIANT | 170 | ISO/IEC 646: set di caratteri codificato a 7 bit ISO - Codifica del set di caratteri invarianti. ECI Id:"\000170" |
| BINARY | 899 | Dati binari a 8 bit. ECI Id:"\000899" |
| NONE | 0 | Nessuna interpretazione estesa del canale |

## Osservazioni


Identificatori di interpretazione estesa del canale. Viene utilizzato per fornire al lettore di codici a barre i dettagli sui riferimenti usati per codificare i dati nel simbolo.

Questo esempio mostra come utilizzare la codifica ECI e salvare un'immagine di [BarCode](../../aspose.barcode/).
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

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
