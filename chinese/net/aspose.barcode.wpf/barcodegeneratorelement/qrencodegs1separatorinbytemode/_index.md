---
title: "BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarcodeGeneratorElement 属性。获取或设置一个值，指示是否应在 QR 和 RectMicroQR 条码的字节模式下对 GS1 特殊字符进行编码"
type: docs
weight: 1290
url: /zh/net/aspose.barcode.wpf/barcodegeneratorelement/qrencodegs1separatorinbytemode/
---
## BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode property

获取或设置一个值，指示是否应在 QR 和 RectMicroQR 条码的字节模式下对 GS1 特殊字符进行编码。

如果为 false，则根据 QR 规范，GS1 分隔符可能在字母数字模式下被编码为 '%'

如果为 true，GS1 组分隔符将在字节模式下编码为 0x1D 字符，且 '%' 字符也将在字节模式下编码以保留为数据

此选项可能提升与期望字节级 GS1 组分隔符的解码器的兼容性，并防止将 '%' 数据字符解释为 GS1 分隔符

```csharp
public bool QREncodeGS1SeparatorInByteMode { get; set; }
```

### 另见

* class [BarcodeGeneratorElement](../)
* namespace [Aspose.BarCode.WPF](../../../aspose.barcode.wpf/)
* assembly [Aspose.BarCode](../../../)


