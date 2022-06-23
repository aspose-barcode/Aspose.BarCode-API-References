---
title: SetBarCodeImage
second_title: Aspose.BarCode for .NET API 参考
description: 设置用于识别的位图图像 必须在 ReadBarCodes 方法之前调用
type: docs
weight: 110
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage}

设置用于识别的位图图像。 必须在 ReadBarCodes() 方法之前调用。

```csharp
public void SetBarCodeImage(Bitmap value)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | Bitmap | 用于识别的位图图像。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(bmp);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        reader.SetBarCodeImage(bmp)
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

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_2}

设置位图图像和识别区域。 必须在 ReadBarCodes() 方法之前调用。

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | Bitmap | 用于识别的位图图像。 |
| areas | Rectangle[] | 识别区域列表 |

### 例子

此示例说明如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) });
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        reader.SetBarCodeImage(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)})
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

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_1}

设置位图图像和识别区域。 必须在 ReadBarCodes() 方法之前调用。

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | Bitmap | 用于识别的位图图像。 |
| area | Rectangle | 识别区域 |

### 例子

此示例显示如何检测Code39 和 Code128 条码。

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height));
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        reader.SetBarCodeImage(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height))
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

## SetBarCodeImage(string) {#setbarcodeimage_4}

设置要识别的图像文件。 必须在 ReadBarCodes() 方法之前调用。

```csharp
public void SetBarCodeImage(string filename)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 用于识别的图像文件。 |

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

## SetBarCodeImage(Stream) {#setbarcodeimage_3}

设置用于识别的图像流。 必须在 ReadBarCodes() 方法之前调用。

```csharp
public void SetBarCodeImage(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于识别的图像流。 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(fstr);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        reader.SetBarCodeImage(fstr)
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
