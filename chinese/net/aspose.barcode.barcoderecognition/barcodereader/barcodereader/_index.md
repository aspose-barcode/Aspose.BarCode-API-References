---
title: "BarCodeReader.BarCodeReader"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarCodeReader 构造函数。使用默认值初始化 BarCodeReader 类的新实例。调用 ReadBarCodes 方法前需要先设置图像（SetBitmapImage）。"
type: docs
weight: 10
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

使用默认值初始化 [`BarCodeReader`](../) 类的新实例。调用 ReadBarCodes() 方法前需要先设置图像（SetBitmapImage()）。

```csharp
public BarCodeReader()
```

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 另见

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_8}

从图像初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(Bitmap image)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | 位图 | 包含图像的位图实例 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp)
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 另见

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_10}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | 位图 | 图像。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_9}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | 位图 | 图像。 |
| 类型 | BaseDecodeType | 解码 type1。它可以是单个或多个。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_12}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | 位图 | 图像。 |
| 区域 | Rectangle | 用于识别的区域。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_11}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | 位图 | 图像。 |
| 区域 | Rectangle | 用于识别的区域。 |
| 类型 | BaseDecodeType | 解码类型。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), new MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_14}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | 位图 | 要读取的图像 |
| areas | Rectangle[] | 识别区域的数组 |
| decodeTypes | BaseDecodeType[] | 适用于所有指定区域的解码类型。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, DecodeType.Code39, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_13}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | 位图 | 要读取的图像 |
| areas | Rectangle[] | 识别区域的数组 |
| 类型 | BaseDecodeType | 适用于所有指定区域的解码类型。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_18}

从文件初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(string filename)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | 字符串 | 文件名。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 另见

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_20}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | 字符串 | 文件名。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_19}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | 字符串 | 文件名。 |
| 类型 | BaseDecodeType | 解码类型。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_15}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 流。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr)
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 另见

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_16}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 流。 |
| 类型 | BaseDecodeType | 解码类型。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_17}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 流。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], BaseDecodeType) {#constructor_6}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, BaseDecodeType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | LuminanceFrame | 要读取的亮度帧。 |
| areas | Rectangle[] | 识别区域的数组。 |
| 类型 | BaseDecodeType | 解码类型。 |

## 示例

此示例展示了如何在亮度帧的指定区域中检测 Code39 和 Code128 条形码。

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle[] areas = { new Rectangle(0, 0, width, height / 2), new Rectangle(0, height / 2, width, height / 2) };

using (BarCodeReader reader = new BarCodeReader(frame, areas, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### 另见

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], params BaseDecodeType[]) {#constructor_7}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | LuminanceFrame | 要读取的亮度帧。 |
| areas | Rectangle[] | 识别区域的数组。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

## 示例

此示例展示了如何在亮度帧的指定区域中检测 Code39 和 Code128 条形码。

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle[] areas = { new Rectangle(0, 0, width, height / 2), new Rectangle(0, height / 2, width, height / 2) };

using (BarCodeReader reader = new BarCodeReader(frame, areas, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### 另见

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, BaseDecodeType) {#constructor_4}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, BaseDecodeType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | LuminanceFrame | 要读取的亮度帧。 |
| 区域 | Rectangle | 用于识别的区域。 |
| 类型 | BaseDecodeType | 解码类型。 |

## 示例

此示例展示了如何在亮度帧的指定区域中检测 Code39 和 Code128 条形码。

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle area = new Rectangle(0, 0, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, area, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### 另见

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, params BaseDecodeType[]) {#constructor_5}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | LuminanceFrame | 要读取的亮度帧。 |
| 区域 | Rectangle | 用于识别的区域。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

## 示例

此示例展示了如何在亮度帧的指定区域中检测 Code39 和 Code128 条形码。

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle area = new Rectangle(0, 0, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, area, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### 另见

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, BaseDecodeType) {#constructor_2}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(LuminanceFrame frame, BaseDecodeType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | LuminanceFrame | 要读取的亮度帧。 |
| 类型 | BaseDecodeType | 解码类型。 |

## 示例

此示例展示了如何在亮度帧中检测 Code39 和 Code128 条形码。

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### 另见

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, params BaseDecodeType[]) {#constructor_3}

初始化一个新的 [`BarCodeReader`](../) 类实例。

```csharp
public BarCodeReader(LuminanceFrame frame, params BaseDecodeType[] decodeTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | LuminanceFrame | 要读取的亮度帧。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

## 示例

此示例展示了如何在亮度帧中检测 Code39 和 Code128 条形码。

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### 另见

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame) {#constructor_1}

从亮度帧初始化 [`BarCodeReader`](../) 类的新实例。

```csharp
public BarCodeReader(LuminanceFrame frame)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | LuminanceFrame | 要读取的亮度帧。 |

## 示例

此示例展示了如何在亮度帧中检测 Code39 和 Code128 条形码。

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader(frame))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### 另见

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


