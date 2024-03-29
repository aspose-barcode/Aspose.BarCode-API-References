---
title: ComplexCodetextReader
second_title: Aspose.BarCode for.NETAPIリファレンス
description: ComplexCodetextReader はコードテキストを指定された複雑なバーコード タイプにデコードします
type: docs
weight: 360
url: /ja/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader は、コードテキストを指定された複雑なバーコード タイプにデコードします。

```csharp
public sealed class ComplexCodetextReader
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | HIBC LIC コードテキストをデコードします。 |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | HIBC PAS コードテキストをデコードします。 |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | メールマーク バーコード C および L コードテキストをデコードします。 |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | Royal Mail Mailmark 2D コードテキストをデコードします。 |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | MaxiCode コードテキストをデコードします。 |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | SwissQR コードテキストをデコードします。 |

### 例

このサンプルでは、SwissQR 画像を認識してデコードする方法を示します。

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### 関連項目

* 名前空間 [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
