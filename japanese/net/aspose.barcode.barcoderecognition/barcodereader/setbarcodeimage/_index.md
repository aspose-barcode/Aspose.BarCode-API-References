---
title: SetBarCodeImage
second_title: Aspose.BarCode for.NETAPIリファレンス
description: 認識用のビットマップ イメージを設定します ReadBarCodes メソッドの前に呼び出す必要があります
type: docs
weight: 110
url: /ja/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage}

認識用のビットマップ イメージを設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。

```csharp
public void SetBarCodeImage(Bitmap value)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | Bitmap | 認識用のビットマップ イメージ。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_2}

認識用のビットマップ イメージと領域を設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | Bitmap | 認識用のビットマップ イメージ。 |
| areas | Rectangle[] | 認識のための領域リスト |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_1}

ビットマップ画像と認識領域を設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| value | Bitmap | 認識用のビットマップ イメージ。 |
| area | Rectangle | 認識領域 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_4}

認識用の画像ファイルを設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。

```csharp
public void SetBarCodeImage(string filename)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filename | String | 認識用の画像ファイル。 |

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

## SetBarCodeImage(Stream) {#setbarcodeimage_3}

認識用の画像ストリームを設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。

```csharp
public void SetBarCodeImage(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | 認識用の画像ストリーム。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

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

### 関連項目

* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
