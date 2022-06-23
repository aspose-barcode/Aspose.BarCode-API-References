---
title: BarCodeReader
second_title: Aspose.BarCode for .NET API 参考
description: 使用默认值初始化BarCodeReaderaspose.barcode.barcoderecognition/barcodereader类的新实例 在调用 ReadBarCodes 方法之前需要设置图像 SetBitmapImage
type: docs
weight: 10
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

使用默认值初始化[`BarCodeReader`](../../barcodereader)类的新实例。 在调用 ReadBarCodes() 方法之前需要设置图像 (SetBitmapImage())。

```csharp
public BarCodeReader()
```

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 也可以看看

* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

从图像初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(Bitmap image)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Bitmap | 包含图像的位图实例 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp))
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp)
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Bitmap | 图像。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Bitmap | 图像。 |
| type | BaseDecodeType | 解码类型1。它可以是单个或多个 |

### 例子

此示例显示如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Bitmap | 图像。 |
| area | Rectangle | 识别区域。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39Standard, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Bitmap | 图像。 |
| area | Rectangle | 识别区域。 |
| type | BaseDecodeType | 解码类型。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Bitmap | 要读取的图像 |
| areas | Rectangle[] | 的数组识别区域 |
| decodeTypes | BaseDecodeType[] | 适用于所有指定区域的解码类型。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, DecodeType.Code39Standard, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Bitmap | 要读取的图像 |
| areas | Rectangle[] | 的数组识别区域 |
| type | BaseDecodeType | 适用于所有指定区域的解码类型。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

从文件中初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(string filename)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 文件名。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 也可以看看

* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 文件名。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 也可以看看

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 文件名。 |
| type | BaseDecodeType | 解码类型。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 也可以看看

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr))
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr)
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |
| type | BaseDecodeType | 解码类型。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

初始化[`BarCodeReader`](../../barcodereader)类的新实例。

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |
| decodeTypes | BaseDecodeType[] | 解码类型。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
