---
title: "BarcodeGenerator.SetCodeText"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarcodeGenerator 方法。将 codetext 设置为字节序列"
type: docs
weight: 100
url: /zh/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

将 codetext 设置为字节序列。

```csharp
public void SetCodeText(byte[] codeBytes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| codeBytes | Byte[] | codetext 的字节 |

### 另见

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

使用指定的 **encoding** 将 Unicode **codeText** 编码为字节序列。UTF-8 是最常用的编码。如果该编码支持，函数会自动插入 [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding)。

此功能仅用于 2D 条码（例如，Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR 等）。它允许使用国家或特殊编码手动编码 Unicode 文本；然而，在现代应用中此方法已被视为过时。对于现代使用场景，建议使用 [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) 编码来处理 Unicode 数据。

在 1D 条码、符合 GS1 标准的条码（包括 2D）或 HIBC 条码（包括 2D）中使用此功能不受相应条码标准支持，可能导致不可预测的结果。

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| codeText | 字符串 | CodeText 字符串 |
| 编码 | 编码 | 已应用的编码 |

## 示例

此示例展示了如何使用 `SetCodeText` 为 2D 条码设置使用不同编码的 Unicode 编码文本：

```csharp
[C#]
//使用带 BOM 的 UTF-8 编码 QR Code 文本
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//使用 Shift-JIS（日文编码）编码 DataMatrix 文本
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### 另见

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

使用指定的 **encoding** 将 Unicode **codeText** 编码为字节序列。UTF-8 是最常用的编码。如果该编码支持且 **insertBOM** 被设置为 `true`，函数会包含一个 [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding)。

此功能仅用于 2D 条码（例如，Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR 等）。它允许使用国家或特殊编码手动编码 Unicode 文本；然而，在现代应用中此方法已被视为过时。对于现代使用场景，建议使用 [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) 编码来处理 Unicode 数据。

在 1D 条码、符合 GS1 标准的条码（包括 2D）或 HIBC 条码（包括 2D）中使用此功能不受相应条码标准支持，可能导致不可预测的结果。

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| codeText | 字符串 | CodeText 字符串 |
| 编码 | 编码 | 已应用的编码 |
| insertBOM | Boolean | 指示在指定的编码支持时（例如 UTF-8、UTF-16、UTF-32）是否插入字节顺序标记（BOM）。如果设置为 `true`，则添加 BOM；如果为 `false`，即使该编码通常使用 BOM，也会省略它。 |

## 示例

此示例展示了如何在 2D 条码中使用 `SetCodeText` 带或不带 BOM。

```csharp
[C#]
//使用带 BOM 的 UTF-8 编码 codetext
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//使用不带 BOM 的 UTF-8 编码 codetext
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### 另见

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


