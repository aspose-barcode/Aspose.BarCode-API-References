---
title: ECIEncodings Enum
linktitle: ECIEncodings
articleTitle: ECIEncodings
second_title: Aspose.BarCode for Node.js via Java
description: Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Currently, it is used only for QR 2D barcode.
type: docs
weight: 1080
url: /nodejs/eciencodings/
---
## ECIEncodings enumeration

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Currently, it is used only for QR 2D barcode.

```javascript
public enum ECIEncodings
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| ISO_8859_1 | `3` | ISO/IEC 8859-1 Latin alphabet No. 1 encoding. ECI Id:"\000003" |
| ISO_8859_2 | `4` | ISO/IEC 8859-2 Latin alphabet No. 2 encoding. ECI Id:"\000004" |
| ISO_8859_3 | `5` | ISO/IEC 8859-3 Latin alphabet No. 3 encoding. ECI Id:"\000005" |
| ISO_8859_4 | `6` | ISO/IEC 8859-4 Latin alphabet No. 4 encoding. ECI Id:"\000006" |
| ISO_8859_5 | `7` | ISO/IEC 8859-5 Latin/Cyrillic alphabet encoding. ECI Id:"\000007" |
| ISO_8859_6 | `8` | ISO/IEC 8859-6 Latin/Arabic alphabet encoding. ECI Id:"\000008" |
| ISO_8859_7 | `9` | ISO/IEC 8859-7 Latin/Greek alphabet encoding. ECI Id:"\000009" |
| ISO_8859_8 | `10` | ISO/IEC 8859-8 Latin/Hebrew alphabet encoding. ECI Id:"\000010" |
| ISO_8859_9 | `11` | ISO/IEC 8859-9 Latin alphabet No. 5 encoding. ECI Id:"\000011" |
| ISO_8859_10 | `12` | ISO/IEC 8859-10 Latin alphabet No. 6 encoding. ECI Id:"\000012" |
| ISO_8859_11 | `13` | ISO/IEC 8859-11 Latin/Thai alphabet encoding. ECI Id:"\000013" |
| ISO_8859_13 | `15` | ISO/IEC 8859-13 Latin alphabet No. 7 (Baltic Rim) encoding. ECI Id:"\000015" |
| ISO_8859_14 | `16` | ISO/IEC 8859-14 Latin alphabet No. 8 (Celtic) encoding. ECI Id:"\000016" |
| ISO_8859_15 | `17` | ISO/IEC 8859-15 Latin alphabet No. 9 encoding. ECI Id:"\000017" |
| ISO_8859_16 | `18` | ISO/IEC 8859-16 Latin alphabet No. 10 encoding. ECI Id:"\000018" |
| UTF16BE | `25` | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) encoding. ECI Id:"\000020" / Shift_JIS: 20, // /** Windows 1250 Latin 2 (Central Europe) encoding. ECI Id:"\000021" / Win1250: 21, /** Windows 1251 Cyrillic encoding. ECI Id:"\000022" / Win1251: 22, /** Windows 1252 Latin 1 encoding. ECI Id:"\000023" / Win1252: 23, /** Windows 1256 Arabic encoding. ECI Id:"\000024" / Win1256: 24, // /** ISO/IEC 10646 UCS-2 (High order byte first) encoding. ECI Id:"\000025" |
| UTF8 | `26` | ISO/IEC 10646 UTF-8 encoding. ECI Id:"\000026" |
| US_ASCII | `27` | ISO/IEC 646:1991 International Reference Version of ISO 7-bit coded character set encoding. ECI Id:"\000027" |
| GB2312 | `29` | Big 5 (Taiwan) Chinese Character Set encoding. ECI Id:"\000028" / Big5: 28, /** GB (PRC) Chinese Character Set encoding. ECI Id:"\000029" |
| EUC_KR | `30` | Korean Character Set encoding. ECI Id:"\000030" |
| GBK | `31` | GBK (extension of GB2312 for Simplified Chinese)  encoding. ECI Id:"\000031" |
| GB18030 | `32` | GGB18030 Chinese Character Set encoding. ECI Id:"\000032" |
| UTF16LE | `33` | ISO/IEC 10646 UTF-16LE encoding. ECI Id:"\000033" |
| UTF32BE | `34` | ISO/IEC 10646 UTF-32BE encoding. ECI Id:"\000034" |
| UTF32LE | `35` | ISO/IEC 10646 UTF-32LE encoding. ECI Id:"\000035" |
| INVARIANT | `170` | ISO/IEC 646: ISO 7-bit coded character set - Invariant Characters set encoding. ECI Id:"\000170" |
| BINARY | `899` | 8-bit binary data. ECI Id:"\000899" |
| NONE | `0` | No Extended Channel Interpretation |

## Examples

```javascript
let generator = new BarcodeGenerator(EncodeTypes.QR);
generator.setCodeText("12345TEXT");
generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING);
generator.getParameters().getBarcode().getQR().setQrEncodeType(QREncodeType.FORCE_QR);
generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF_8);
generator.save("test.png", BarCodeImageFormat.PNG);
```

### See Also

* assembly [Aspose.BarCode](../)

