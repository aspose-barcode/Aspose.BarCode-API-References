---
title: "类 ComplexCodetextReader"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.ComplexCodetextReader 类。ComplexCodetextReader 将码文本解码为指定的复杂条码类型。"
type: docs
weight: 520
url: /zh/net/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader 将代码文本解码为指定的复杂条码类型。

```csharp
public sealed class ComplexCodetextReader
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [TryDecodeGS1Codetext](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1codetext/)(string) | 解码 GS1 码文本。 |
| static [TryDecodeGS1DigitalLink](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodegs1digitallink/)(string) | 解码 GS1 Digital Link。 |
| static [TryDecodeHIBCLIC](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibclic/)(string) | 解码 HIBC LIC 编码文本。 |
| static [TryDecodeHIBCPAS](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodehibcpas/)(string) | 解码 HIBC PAS 编码文本。 |
| static [TryDecodeMailmark](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark/)(string) | 解码 Mailmark 条形码 C 和 L 编码文本。 |
| static [TryDecodeMailmark2D](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemailmark2d/)(string) | 解码 Royal Mail Mailmark 2D 编码文本。 |
| static [TryDecodeMaxiCode](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodemaxicode/)(MaxiCodeMode, string) | 解码 MaxiCode 编码文本。 |
| static [TryDecodeSwissQR](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeswissqr/)(string) | 解码 SwissQR 编码文本。 |
| static [TryDecodeUSADriveId](../../aspose.barcode.complexbarcode/complexcodetextreader/trydecodeusadriveid/)(string) | 解码 USADriveId 编码文本。 |

## 示例

此示例展示了如何识别并解码 SwissQR 图像。

```csharp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

### 另见

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


