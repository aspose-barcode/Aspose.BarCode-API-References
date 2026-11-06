---
title: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader 类"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::ComplexCodetextReader 类。ComplexCodetextReader 将编码文本解码为 C++ 中指定的复合条码类型。"
type: docs
weight: 400
url: /zh/cpp/aspose.barcode.complexbarcode/complexcodetextreader/
---
## ComplexCodetextReader class


[ComplexCodetextReader](./) decodes codetext to specified complex barcode type.

```cpp
class ComplexCodetextReader : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [TryDecodeGS1Codetext](./trydecodegs1codetext/)(System::String) | 解码 GS1 编码文本。 |
| static [TryDecodeGS1DigitalLink](./trydecodegs1digitallink/)(System::String) | 解码 GS1 Digital Link。 |
| static [TryDecodeHIBCLIC](./trydecodehibclic/)(System::String) | 解码 HIBC LIC 编码文本。 |
| static [TryDecodeHIBCPAS](./trydecodehibcpas/)(System::String) | 解码 HIBC PAS 编码文本。 |
| static [TryDecodeMailmark](./trydecodemailmark/)(System::String) | 解码 Mailmark 条码 C 和 L 的编码文本。 |
| static [TryDecodeMailmark2D](./trydecodemailmark2d/)(System::String) | 解码 Royal Mail Mailmark 2D 编码文本。 |
| static [TryDecodeMaxiCode](./trydecodemaxicode/)(Generation::MaxiCodeMode, System::String) | 解码 MaxiCode 编码文本。 |
| static [TryDecodeSwissQR](./trydecodeswissqr/)(System::String) | 解码 SwissQR 编码文本。 |
| static [TryDecodeUSADriveId](./trydecodeusadriveid/)(System::String) | 解码 USADriveId 编码文本。 |
## 备注


此示例展示了如何识别并解码 SwissQR 图像。
```cpp
[C#]
  using (var cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR))
  {
    cr.Read();
    SwissQRCodetext result = ComplexCodetextReader.TryDecodeSwissQR(cr.GetCodeText());
  }
```

## 另见

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
