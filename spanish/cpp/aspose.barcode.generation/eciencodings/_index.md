---
title: "enum"
linktitle: "Codificaciones ECI"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar el enum en C++."
type: docs
weight: 6600
url: /es/cpp/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enum




```cpp
enum class ECIEncodings
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ISO_8859_1 | 3 | Codificación del alfabeto latino No. 1 ISO/IEC 8859-1. Id ECI:"\000003" |
| ISO_8859_2 | 4 | Codificación del alfabeto latino No. 2 ISO/IEC 8859-2. Id ECI:"\000004" |
| ISO_8859_3 | 5 | Codificación del alfabeto latino No. 3 ISO/IEC 8859-3. Id ECI:"\000005" |
| ISO_8859_4 | 6 | Codificación del alfabeto latino No. 4 ISO/IEC 8859-4. Id ECI:"\000006" |
| ISO_8859_5 | 7 | Codificación del alfabeto latino/cirílico ISO/IEC 8859-5. Id ECI:"\000007" |
| ISO_8859_6 | 8 | Codificación del alfabeto latino/árabe ISO/IEC 8859-6. Id ECI:"\000008" |
| ISO_8859_7 | 9 | Codificación del alfabeto latino/griego ISO/IEC 8859-7. Id ECI:"\000009" |
| ISO_8859_8 | 10 | Codificación del alfabeto latino/hebreo ISO/IEC 8859-8. Id ECI:"\000010" |
| ISO_8859_9 | 11 | Codificación del alfabeto latino No. 5 ISO/IEC 8859-9. Id ECI:"\000011" |
| ISO_8859_10 | 12 | ISO/IEC 8859-10 codificación del alfabeto latino n.º 6. ECI Id:"\000012" |
| ISO_8859_11 | 13 | ISO/IEC 8859-11 codificación del alfabeto latino/tailandés. ECI Id:"\000013" |
| ISO_8859_13 | 15 | ISO/IEC 8859-13 codificación del alfabeto latino n.º 7 (Borde Báltico). ECI Id:"\000015" |
| ISO_8859_14 | 16 | ISO/IEC 8859-14 codificación del alfabeto latino n.º 8 (Céltico). ECI Id:"\000016" |
| ISO_8859_15 | 17 | ISO/IEC 8859-15 codificación del alfabeto latino n.º 9. ECI Id:"\000017" |
| ISO_8859_16 | 18 | ISO/IEC 8859-16 codificación del alfabeto latino n.º 10. ECI Id:"\000018" |
| Shift_JIS | 20 | Shift JIS (JIS X 0208 Anexo 1 + JIS X 0201) codificación. ECI Id:"\000020" |
| Win1250 | 21 | [Windows](../../aspose.barcode.windows/) 1250 Latin 2 (Europa Central) codificación. ECI Id:"\000021" |
| Win1251 | 22 | [Windows](../../aspose.barcode.windows/) 1251 codificación cirílica. ECI Id:"\000022" |
| Win1252 | 23 | [Windows](../../aspose.barcode.windows/) 1252 Latin 1 codificación. ECI Id:"\000023" |
| Win1256 | 24 | [Windows](../../aspose.barcode.windows/) 1256 codificación árabe. ECI Id:"\000024" |
| UTF16BE | 25 | ISO/IEC 10646 UCS-2 (byte de orden alto primero) codificación. ECI Id:"\000025" |
| UTF8 | 26 | ISO/IEC 10646 UTF-8 codificación. ECI Id:"\000026" |
| US_ASCII | 27 | ISO/IEC 646:1991 versión de referencia internacional del conjunto de caracteres codificado ISO de 7 bits. ECI Id:"\000027" |
| Big5 | 28 | Codificación del conjunto de caracteres chino Big 5 (Taiwan). ECI Id:"\000028" |
| GB2312 | 29 | Codificación del conjunto de caracteres chino GB2312. ECI Id:"\000029" |
| EUC_KR | 30 | Codificación del conjunto de caracteres coreano. ECI Id:"\000030" |
| GBK | 31 | Codificación GBK (extensión de GB2312 para chino simplificado). ECI Id:"\000031" |
| GB18030 | 32 | Codificación del conjunto de caracteres chino GGB18030. ECI Id:"\000032" |
| UTF16LE | 33 | Codificación ISO/IEC 10646 UTF-16LE. ECI Id:"\000033" |
| UTF32BE | 34 | Codificación ISO/IEC 10646 UTF-32BE. ECI Id:"\000034" |
| UTF32LE | 35 | Codificación ISO/IEC 10646 UTF-32LE. ECI Id:"\000035" |
| INVARIANT | 170 | ISO/IEC 646: conjunto de caracteres codificado ISO de 7 bits - codificación del conjunto de caracteres invariantes. ECI Id:"\000170" |
| BINARY | 899 | Datos binarios de 8 bits. ECI Id:"\000899" |
| NONE | 0 | Sin interpretación de canal extendido |

## Observaciones


Identificadores de interpretación de canal extendido. Se utiliza para indicar al lector de códigos de barras los detalles sobre las referencias usadas para codificar los datos en el símbolo.

Este ejemplo muestra cómo usar la codificación ECI y guardar una imagen de [BarCode](../../aspose.barcode/).
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

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
