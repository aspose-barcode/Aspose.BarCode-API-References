---
title: "enum"
linktitle: "ECI エンコーディング"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++でenumを使用する方法。"
type: docs
weight: 6600
url: /ja/cpp/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enum




```cpp
enum class ECIEncodings
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| ISO_8859_1 | 3 | ISO/IEC 8859-1 ラテン文字アルファベット No. 1 エンコーディング。ECI Id:"\000003" |
| ISO_8859_2 | 4 | ISO/IEC 8859-2 ラテン文字アルファベット No. 2 エンコーディング。ECI Id:"\000004" |
| ISO_8859_3 | 5 | ISO/IEC 8859-3 ラテン文字アルファベット No. 3 エンコーディング。ECI Id:"\000005" |
| ISO_8859_4 | 6 | ISO/IEC 8859-4 ラテン文字アルファベット No. 4 エンコーディング。ECI Id:"\000006" |
| ISO_8859_5 | 7 | ISO/IEC 8859-5 ラテン/キリル文字アルファベット エンコーディング。ECI Id:"\000007" |
| ISO_8859_6 | 8 | ISO/IEC 8859-6 ラテン/アラビア文字アルファベット エンコーディング。ECI Id:"\000008" |
| ISO_8859_7 | 9 | ISO/IEC 8859-7 ラテン/ギリシャ文字アルファベット エンコーディング。ECI Id:"\000009" |
| ISO_8859_8 | 10 | ISO/IEC 8859-8 ラテン/ヘブライ文字アルファベット エンコーディング。ECI Id:"\000010" |
| ISO_8859_9 | 11 | ISO/IEC 8859-9 ラテン文字アルファベット No. 5 エンコーディング。ECI Id:"\000011" |
| ISO_8859_10 | 12 | ISO/IEC 8859-10 ラテン文字アルファベット No. 6 エンコーディング。 ECI Id:"\000012" |
| ISO_8859_11 | 13 | ISO/IEC 8859-11 ラテン/タイ文字アルファベット エンコーディング。 ECI Id:"\000013" |
| ISO_8859_13 | 15 | ISO/IEC 8859-13 ラテン文字アルファベット No. 7（バルトリム）エンコーディング。 ECI Id:"\000015" |
| ISO_8859_14 | 16 | ISO/IEC 8859-14 ラテン文字アルファベット No. 8（ケルト）エンコーディング。 ECI Id:"\000016" |
| ISO_8859_15 | 17 | ISO/IEC 8859-15 ラテン文字アルファベット No. 9 エンコーディング。 ECI Id:"\000017" |
| ISO_8859_16 | 18 | ISO/IEC 8859-16 ラテン文字アルファベット No. 10 エンコーディング。 ECI Id:"\000018" |
| Shift_JIS | 20 | Shift JIS（JIS X 0208 Annex 1 + JIS X 0201）エンコーディング。 ECI Id:"\000020" |
| Win1250 | 21 | [Windows](../../aspose.barcode.windows/) 1250 ラテン 2（中欧）エンコーディング。 ECI Id:"\000021" |
| Win1251 | 22 | [Windows](../../aspose.barcode.windows/) 1251 キリル文字 エンコーディング。 ECI Id:"\000022" |
| Win1252 | 23 | [Windows](../../aspose.barcode.windows/) 1252 ラテン 1 エンコーディング。 ECI Id:"\000023" |
| Win1256 | 24 | [Windows](../../aspose.barcode.windows/) 1256 アラビア文字 エンコーディング。 ECI Id:"\000024" |
| UTF16BE | 25 | ISO/IEC 10646 UCS-2（上位バイトが先）エンコーディング。 ECI Id:"\000025" |
| UTF8 | 26 | ISO/IEC 10646 UTF-8 エンコーディング。 ECI Id:"\000026" |
| US_ASCII | 27 | ISO/IEC 646:1991 国際リファレンスバージョンの ISO 7ビット符号化文字セット エンコーディング。 ECI Id:"\000027" |
| Big5 | 28 | Big 5（台湾）中国文字セットのエンコーディング。ECI Id:"\000028" |
| GB2312 | 29 | GB2312 中国文字セットのエンコーディング。ECI Id:"\000029" |
| EUC_KR | 30 | 韓国文字セットのエンコーディング。ECI Id:"\000030" |
| GBK | 31 | GBK（簡体字中国語用の GB2312 の拡張）エンコーディング。ECI Id:"\000031" |
| GB18030 | 32 | GGB18030 中国文字セットのエンコーディング。ECI Id:"\000032" |
| UTF16LE | 33 | ISO/IEC 10646 UTF-16LE エンコーディング。ECI Id:"\000033" |
| UTF32BE | 34 | ISO/IEC 10646 UTF-32BE エンコーディング。ECI Id:"\000034" |
| UTF32LE | 35 | ISO/IEC 10646 UTF-32LE エンコーディング。ECI Id:"\000035" |
| INVARIANT | 170 | ISO/IEC 646: ISO 7ビット符号化文字セット - 不変文字セットのエンコーディング。ECI Id:"\000170" |
| BINARY | 899 | 8ビットバイナリデータ。ECI Id:"\000899" |
| NONE | 0 | 拡張チャネル解釈なし |

## 備考


拡張チャネル解釈識別子。シンボル内のデータをエンコードする際に使用された参照について、バーコードリーダーに詳細を伝えるために使用されます。

このサンプルは、ECI エンコーディングの使用方法と、[BarCode](../../aspose.barcode/) 画像の保存方法を示しています。
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

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
