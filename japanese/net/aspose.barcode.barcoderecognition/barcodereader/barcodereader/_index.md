---
title: BarCodeReader
second_title: Aspose.BarCode for.NETAPIリファレンス
description: の新しいインスタンスを初期化しますBarCodeReaderaspose.barcode.barcoderecognition/barcodereader/デフォルト値を持つクラス. ReadBarCodes メソッドを呼び出す前に画像を設定する必要があります SetBitmapImage.
type: docs
weight: 10
url: /ja/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

の新しいインスタンスを初期化します[`BarCodeReader`](../)デフォルト値を持つクラス. ReadBarCodes() メソッドを呼び出す前に画像を設定する必要があります (SetBitmapImage()).

```csharp
public BarCodeReader()
```

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

の新しいインスタンスを初期化します[`BarCodeReader`](../)画像からのクラス.

```csharp
public BarCodeReader(Bitmap image)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | Bitmap | 画像を含む Bitmap インスタンス |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | Bitmap | 画像。 |
| decodeTypes | BaseDecodeType[] | タイプをデコードします。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | Bitmap | 画像。 |
| type | BaseDecodeType | デコードタイプ1.シングルでもマルチでもかまいません |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | Bitmap | 画像。 |
| area | Rectangle | 認識のための領域。 |
| decodeTypes | BaseDecodeType[] | タイプをデコードします。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | Bitmap | 画像。 |
| area | Rectangle | 認識のための領域。 |
| type | BaseDecodeType | デコード タイプ。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | Bitmap | 読みたいイメージ |
| areas | Rectangle[] | 認識領域の配列 |
| decodeTypes | BaseDecodeType[] | 指定されたすべての領域に適用可能なデコード タイプ。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | Bitmap | 読みたいイメージ |
| areas | Rectangle[] | 認識領域の配列 |
| type | BaseDecodeType | 指定されたすべての領域に適用可能なデコード タイプ。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

の新しいインスタンスを初期化します[`BarCodeReader`](../) file. からのクラス

```csharp
public BarCodeReader(string filename)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filename | String | ファイル名。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filename | String | ファイル名。 |
| decodeTypes | BaseDecodeType[] | タイプをデコードします。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filename | String | ファイル名。 |
| type | BaseDecodeType | デコード タイプ。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ストリーム。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ストリーム。 |
| type | BaseDecodeType | デコード タイプ。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

の新しいインスタンスを初期化します[`BarCodeReader`](../)class.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ストリーム。 |
| decodeTypes | BaseDecodeType[] | タイプをデコードします。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
