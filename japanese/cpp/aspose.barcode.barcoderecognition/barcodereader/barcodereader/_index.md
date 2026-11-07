---
title: "constructor"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " constructor. BarCodeReader クラスの新しいインスタンスをデフォルト値で初期化します。C++ で ReadBarCodes() メソッドを呼び出す前に画像（SetBitmapImage()）を設定する必要があります。"
type: docs
weight: 1400
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader::BarCodeReader() constructor


デフォルト値で [BarCodeReader](../) クラスの新しいインスタンスを初期化します。呼び出す前に画像（SetBitmapImage()）を設定し、[ReadBarCodes()](../readbarcodes/) メソッドを使用してください。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader()
```

## 備考


このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>) constructor


画像から [BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | System::SharedPtr\<System::Drawing::Bitmap\> | 画像を含む Bitmap インスタンス |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | System::SharedPtr\<System::Drawing::Bitmap\> | 画像。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | デコードタイプ。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::SharedPtr<BaseDecodeType> type)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | System::SharedPtr\<System::Drawing::Bitmap\> | 画像。 |
| タイプ | System::SharedPtr\<BaseDecodeType\> | デコード type1です。単一または複数に設定できます。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::Drawing::Rectangle area, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | System::SharedPtr\<System::Drawing::Bitmap\> | 画像。 |
| 領域 | System::Drawing::Rectangle | 認識用の領域です。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | デコードタイプ。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::Drawing::Rectangle area, System::SharedPtr<BaseDecodeType> type)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | System::SharedPtr\<System::Drawing::Bitmap\> | 画像。 |
| 領域 | System::Drawing::Rectangle | 認識用の領域です。 |
| タイプ | System::SharedPtr\<BaseDecodeType\> | デコードタイプです。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::ArrayPtr<System::Drawing::Rectangle> areas, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | System::SharedPtr\<System::Drawing::Bitmap\> | 読み取る画像 |
| 領域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 認識領域の配列 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | 指定されたすべての領域に適用できるデコードタイプです。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::ArrayPtr<System::Drawing::Rectangle> areas, System::SharedPtr<BaseDecodeType> type)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 画像 | System::SharedPtr\<System::Drawing::Bitmap\> | 読み取る画像 |
| 領域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 認識領域の配列 |
| タイプ | System::SharedPtr\<BaseDecodeType\> | 指定されたすべての領域に適用できるデコードタイプです。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String) constructor


ファイルから [BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | System::String | ファイル名です。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | System::String | ファイル名です。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | デコードタイプ。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename, System::SharedPtr<BaseDecodeType> type)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | System::String | ファイル名です。 |
| タイプ | System::SharedPtr\<BaseDecodeType\> | デコードタイプです。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | ストリームです。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<BaseDecodeType> type)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | ストリームです。 |
| タイプ | System::SharedPtr\<BaseDecodeType\> | デコードタイプです。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | ストリームです。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | デコードタイプ。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
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

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas, System::SharedPtr<BaseDecodeType> type)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フレーム | System::SharedPtr\<LuminanceFrame\> | 読み取る輝度フレームです。 |
| 領域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 認識領域の配列です。 |
| タイプ | System::SharedPtr\<BaseDecodeType\> | デコードタイプです。 |
## 備考



このサンプルは、輝度フレームの指定領域で Code39 と Code128 のバーコードを検出する方法を示します。
```cpp
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

## 関連項目

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フレーム | System::SharedPtr\<LuminanceFrame\> | 読み取る輝度フレームです。 |
| 領域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 認識領域の配列です。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | デコードタイプです。 |
## 備考



このサンプルは、輝度フレームの指定領域で Code39 と Code128 のバーコードを検出する方法を示します。
```cpp
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

## 関連項目

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area, System::SharedPtr<BaseDecodeType> type)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フレーム | System::SharedPtr\<LuminanceFrame\> | 読み取る輝度フレームです。 |
| 領域 | System::Drawing::Rectangle | 認識用の領域です。 |
| タイプ | System::SharedPtr\<BaseDecodeType\> | デコードタイプです。 |
## 備考



このサンプルは、輝度フレームの指定領域で Code39 と Code128 バーコードを検出する方法を示しています。
```cpp
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

## 関連項目

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フレーム | System::SharedPtr\<LuminanceFrame\> | 読み取る輝度フレームです。 |
| 領域 | System::Drawing::Rectangle | 認識用の領域です。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | デコードタイプです。 |
## 備考



このサンプルは、輝度フレームの指定領域で Code39 と Code128 バーコードを検出する方法を示しています。
```cpp
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

## 関連項目

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::SharedPtr<BaseDecodeType> type)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フレーム | System::SharedPtr\<LuminanceFrame\> | 読み取る輝度フレームです。 |
| タイプ | System::SharedPtr\<BaseDecodeType\> | デコードタイプです。 |
## 備考



このサンプルは、輝度フレーム内で Code39 と Code128 バーコードを検出する方法を示しています。
```cpp
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

## 関連項目

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


[BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フレーム | System::SharedPtr\<LuminanceFrame\> | 読み取る輝度フレームです。 |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | デコードタイプです。 |
## 備考



このサンプルは、輝度フレーム内で Code39 と Code128 バーコードを検出する方法を示しています。
```cpp
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

## 関連項目

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>) constructor


輝度フレームから [BarCodeReader](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フレーム | System::SharedPtr\<LuminanceFrame\> | 読み取る輝度フレームです。 |
## 備考



このサンプルは、輝度フレーム内で Code39 と Code128 バーコードを検出する方法を示しています。
```cpp
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

## 関連項目

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
