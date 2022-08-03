---
title: ECIEncodings
second_title: Referencia de API de Aspose.BarCode para .NET
description: Identificadores de interpretación de canal extendido. Se usa para informar al lector de código de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual consiste en todas las codificaciones de juego de caracteres conocidas. Actualmente se usa solo para código de barras QR 2D.
type: docs
weight: 700
url: /es/net/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enumeration

Identificadores de interpretación de canal extendido. Se usa para informar al lector de código de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual consiste en todas las codificaciones de juego de caracteres conocidas. Actualmente, se usa solo para código de barras QR 2D.

```csharp
public enum ECIEncodings
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ISO_8859_1 | `3` | ISO/IEC 8859-1 Codificación del alfabeto latino n.º 1. Identificación de ECI: "\ 000003" |
| ISO_8859_2 | `4` | ISO/IEC 8859-2 Codificación del alfabeto latino n.° 2. Identificación de ECI: "\ 000004" |
| ISO_8859_3 | `5` | ISO/IEC 8859-3 Codificación del alfabeto latino n.° 3. Identificación de ECI: "\ 000005" |
| ISO_8859_4 | `6` | ISO/IEC 8859-4 Codificación del alfabeto latino n.° 4. Identificación de ECI: "\ 000006" |
| ISO_8859_5 | `7` | ISO/IEC 8859-5 Codificación del alfabeto latino/cirílico. Identificación de ECI: "\ 000007" |
| ISO_8859_6 | `8` | ISO/IEC 8859-6 Codificación alfabética latina/árabe. Identificación de ECI: "\ 000008" |
| ISO_8859_7 | `9` | Codificación del alfabeto latino/griego ISO/IEC 8859-7. Identificación de ECI: "\ 000009" |
| ISO_8859_8 | `10` | Codificación del alfabeto latino/hebreo ISO/IEC 8859-8. Identificación de ECI: "\ 000010" |
| ISO_8859_9 | `11` | ISO/IEC 8859-9 Codificación del alfabeto latino n.º 5. Identificación de ECI: "\ 000011" |
| ISO_8859_10 | `12` | ISO/IEC 8859-10 Codificación del alfabeto latino n.º 6. Identificación de ECI: "\ 000012" |
| ISO_8859_11 | `13` | ISO/IEC 8859-11 Codificación alfabética latina/tailandesa. Identificación de ECI: "\ 000013" |
| ISO_8859_13 | `15` | ISO/IEC 8859-13 Codificación del alfabeto latino n.º 7 (Baltic Rim). Identificación de ECI: "\ 000015" |
| ISO_8859_14 | `16` | ISO/IEC 8859-14 Codificación del alfabeto latino n.º 8 (celta). Identificación de ECI: "\ 000016" |
| ISO_8859_15 | `17` | ISO/IEC 8859-15 Codificación del alfabeto latino n.° 9. Identificación de ECI: "\ 000017" |
| ISO_8859_16 | `18` | ISO/IEC 8859-16 Codificación del alfabeto latino No. 10. Identificación de ECI: "\ 000018" |
| Shift_JIS | `20` | Codificación Shift JIS (JIS X 0208 Anexo 1 + JIS X 0201). Identificación de ECI: "\ 000020" |
| Win1250 | `21` | Codificación Windows 1250 Latin 2 (Europa Central). Identificación de ECI: "\ 000021" |
| Win1251 | `22` | Codificación cirílica de Windows 1251. Identificación de ECI: "\ 000022" |
| Win1252 | `23` | Codificación Windows 1252 Latin 1. Identificación de ECI: "\ 000023" |
| Win1256 | `24` | Codificación árabe de Windows 1256. Identificación de ECI: "\ 000024" |
| UTF16BE | `25` | Codificación ISO/IEC 10646 UCS-2 (primer byte de orden superior). Identificación de ECI: "\ 000025" |
| UTF8 | `26` | Codificación ISO/IEC 10646 UTF-8. Identificación de ECI: "\ 000026" |
| US_ASCII | `27` | ISO/IEC 646:1991 Versión de referencia internacional de codificación de juego de caracteres codificados ISO de 7 bits. Identificación de ECI: "\ 000027" |
| Big5 | `28` | Codificación del juego de caracteres chinos Big 5 (Taiwán). Identificación de ECI: "\ 000028" |
| GB18030 | `29` | GB (PRC) Codificación del conjunto de caracteres chinos. Identificación de ECI: "\ 000029" |
| EUC_KR | `30` | Codificación del conjunto de caracteres coreanos. Identificación de ECI: "\ 000030" |
| NONE | `0` | Sin interpretación de canal extendida |

### Ejemplos

Este ejemplo muestra cómo usar la codificación ECI y guardar una imagen de código de barras.

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

### Ver también

* espacio de nombres [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
