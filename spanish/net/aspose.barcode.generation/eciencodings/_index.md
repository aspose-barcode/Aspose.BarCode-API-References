---
title: "Enumeración ECIEncodings"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Enumeración Aspose.BarCode.Generation.ECIEncodings. Identificadores de Interpretación de Canal Extendido. Se utiliza para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo"
type: docs
weight: 1270
url: /es/net/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enumeration

Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo.

```csharp
public enum ECIEncodings
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ISO_8859_1 | `3` | Codificación ISO/IEC 8859-1 alfabeto latino n.º 1. Id ECI:"\000003" |
| ISO_8859_2 | `4` | Codificación ISO/IEC 8859-2 alfabeto latino n.º 2. Id ECI:"\000004" |
| ISO_8859_3 | `5` | Codificación ISO/IEC 8859-3 alfabeto latino n.º 3. Id ECI:"\000005" |
| ISO_8859_4 | `6` | Codificación ISO/IEC 8859-4 alfabeto latino n.º 4. Id ECI:"\000006" |
| ISO_8859_5 | `7` | Codificación ISO/IEC 8859-5 alfabeto latino/cirílico. Id ECI:"\000007" |
| ISO_8859_6 | `8` | Codificación ISO/IEC 8859-6 alfabeto latino/árabe. Id ECI:"\000008" |
| ISO_8859_7 | `9` | Codificación ISO/IEC 8859-7 alfabeto latino/griego. Id ECI:"\000009" |
| ISO_8859_8 | `10` | Codificación ISO/IEC 8859-8 alfabeto latino/hebreo. Id ECI:"\000010" |
| ISO_8859_9 | `11` | Codificación ISO/IEC 8859-9 alfabeto latino n.º 5. Id ECI:"\000011" |
| ISO_8859_10 | `12` | Codificación ISO/IEC 8859-10 alfabeto latino n.º 6. Id ECI:"\000012" |
| ISO_8859_11 | `13` | Codificación ISO/IEC 8859-11 alfabeto latino/tailandés. Id ECI:"\000013" |
| ISO_8859_13 | `15` | Codificación ISO/IEC 8859-13 alfabeto latino n.º 7 (Báltico) . Id ECI:"\000015" |
| ISO_8859_14 | `16` | Codificación ISO/IEC 8859-14 alfabeto latino n.º 8 (Céltico) . Id ECI:"\000016" |
| ISO_8859_15 | `17` | Codificación ISO/IEC 8859-15 del alfabeto latino n.º 9. ECI Id:"\000017" |
| ISO_8859_16 | `18` | Codificación ISO/IEC 8859-16 del alfabeto latino n.º 10. ECI Id:"\000018" |
| Shift_JIS | `20` | Codificación Shift JIS (JIS X 0208 Anexo 1 + JIS X 0201). ECI Id:"\000020" |
| Win1250 | `21` | Codificación Windows 1250 Latin 2 (Europa Central). ECI Id:"\000021" |
| Win1251 | `22` | Codificación Windows 1251 cirílico. ECI Id:"\000022" |
| Win1252 | `23` | Codificación Windows 1252 Latin 1. ECI Id:"\000023" |
| Win1256 | `24` | Codificación Windows 1256 árabe. ECI Id:"\000024" |
| UTF16BE | `25` | Codificación ISO/IEC 10646 UCS-2 (byte de orden alto primero). ECI Id:"\000025" |
| UTF8 | `26` | Codificación ISO/IEC 10646 UTF-8. ECI Id:"\000026" |
| US_ASCII | `27` | Codificación ISO/IEC 646:1991 Versión de referencia internacional del conjunto de caracteres codificado ISO de 7 bits. ECI Id:"\000027" |
| Big5 | `28` | Codificación Big 5 (Taiwán) conjunto de caracteres chino. ECI Id:"\000028" |
| GB2312 | `29` | Codificación GB2312 conjunto de caracteres chino. ECI Id:"\000029" |
| EUC_KR | `30` | Codificación conjunto de caracteres coreano. ECI Id:"\000030" |
| GBK | `31` | Codificación GBK (extensión de GB2312 para chino simplificado). ECI Id:"\000031" |
| GB18030 | `32` | Codificación GGB18030 conjunto de caracteres chino. ECI Id:"\000032" |
| UTF16LE | `33` | Codificación ISO/IEC 10646 UTF-16LE. ECI Id:"\000033" |
| UTF32BE | `34` | Codificación ISO/IEC 10646 UTF-32BE. ECI Id:"\000034" |
| UTF32LE | `35` | Codificación ISO/IEC 10646 UTF-32LE. ECI Id:"\000035" |
| INVARIANT | `170` | Codificación ISO/IEC 646: conjunto de caracteres codificado de 7 bits - conjunto de caracteres invariantes. ECI Id:"\000170" |
| BINARY | `899` | Datos binarios de 8 bits. ECI Id:"\000899" |
| NONE | `0` | Sin interpretación de canal extendida |

## Ejemplos

Este ejemplo muestra cómo usar la codificación ECI y guardar una imagen de BarCode.

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

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


