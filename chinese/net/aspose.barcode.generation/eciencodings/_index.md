---
title: "枚举 ECIEncodings"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.ECIEncodings 枚举。扩展信道解释标识符。它用于向条形码读取器提供有关在符号中对数据进行编码所使用的参考的详细信息。"
type: docs
weight: 1270
url: /zh/net/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enumeration

扩展信道解释标识符。它用于向条码读取器提供有关在符号中编码数据所使用的参考的详细信息。

```csharp
public enum ECIEncodings
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| ISO_8859_1 | `3` | ISO/IEC 8859-1 拉丁字母表第 1 号编码。ECI Id:"\000003" |
| ISO_8859_2 | `4` | ISO/IEC 8859-2 拉丁字母表第 2 号编码。ECI Id:"\000004" |
| ISO_8859_3 | `5` | ISO/IEC 8859-3 拉丁字母表第 3 号编码。ECI Id:"\000005" |
| ISO_8859_4 | `6` | ISO/IEC 8859-4 拉丁字母表第 4 号编码。ECI Id:"\000006" |
| ISO_8859_5 | `7` | ISO/IEC 8859-5 拉丁/西里尔字母表编码。ECI Id:"\000007" |
| ISO_8859_6 | `8` | ISO/IEC 8859-6 拉丁/阿拉伯字母表编码。ECI Id:"\000008" |
| ISO_8859_7 | `9` | ISO/IEC 8859-7 拉丁/希腊字母表编码。ECI Id:"\000009" |
| ISO_8859_8 | `10` | ISO/IEC 8859-8 拉丁/希伯来字母表编码。ECI Id:"\000010" |
| ISO_8859_9 | `11` | ISO/IEC 8859-9 拉丁字母表第 5 号编码。ECI Id:"\000011" |
| ISO_8859_10 | `12` | ISO/IEC 8859-10 拉丁字母表第 6 号编码。ECI Id:"\000012" |
| ISO_8859_11 | `13` | ISO/IEC 8859-11 拉丁/泰文字母表编码。ECI Id:"\000013" |
| ISO_8859_13 | `15` | ISO/IEC 8859-13 拉丁字母表第 7 号（波罗的海沿岸）编码。ECI Id:"\000015" |
| ISO_8859_14 | `16` | ISO/IEC 8859-14 拉丁字母表第 8 号（凯尔特）编码。ECI Id:"\000016" |
| ISO_8859_15 | `17` | ISO/IEC 8859-15 拉丁字母第9号编码。 ECI Id:"\000017" |
| ISO_8859_16 | `18` | ISO/IEC 8859-16 拉丁字母第10号编码。 ECI Id:"\000018" |
| Shift_JIS | `20` | Shift JIS（JIS X 0208 附件1 + JIS X 0201）编码。 ECI Id:"\000020" |
| Win1250 | `21` | Windows 1250 拉丁文2（中欧）编码。 ECI Id:"\000021" |
| Win1251 | `22` | Windows 1251 西里尔文编码。 ECI Id:"\000022" |
| Win1252 | `23` | Windows 1252 拉丁文1编码。 ECI Id:"\000023" |
| Win1256 | `24` | Windows 1256 阿拉伯文编码。 ECI Id:"\000024" |
| UTF16BE | `25` | ISO/IEC 10646 UCS-2（高位字节在前）编码。 ECI Id:"\000025" |
| UTF8 | `26` | ISO/IEC 10646 UTF-8 编码。 ECI Id:"\000026" |
| US_ASCII | `27` | ISO/IEC 646:1991 国际参考版 ISO 7 位编码字符集编码。 ECI Id:"\000027" |
| Big5 | `28` | Big 5（台湾）中文字符集编码。 ECI Id:"\000028" |
| GB2312 | `29` | GB2312 中文字符集编码。 ECI Id:"\000029" |
| EUC_KR | `30` | 韩文字符集编码。 ECI Id:"\000030" |
| GBK | `31` | GBK（GB2312 的简体中文扩展）编码。 ECI Id:"\000031" |
| GB18030 | `32` | GGB18030 中文字符集编码。 ECI Id:"\000032" |
| UTF16LE | `33` | ISO/IEC 10646 UTF-16LE 编码。 ECI Id:"\000033" |
| UTF32BE | `34` | ISO/IEC 10646 UTF-32BE 编码。 ECI Id:"\000034" |
| UTF32LE | `35` | ISO/IEC 10646 UTF-32LE 编码。 ECI Id:"\000035" |
| INVARIANT | `170` | ISO/IEC 646：ISO 7 位编码字符集 - 不变字符集编码。 ECI Id:"\000170" |
| BINARY | `899` | 8 位二进制数据。 ECI Id:"\000899" |
| NONE | `0` | 无扩展信道解释 |

## 示例

此示例展示了如何使用 ECI 编码并保存 BarCode 图像。

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

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


