---
title: "メソッド"
linktitle: "SetBarCodeImage"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。認識用のビットマップ画像を設定します。C++ で ReadBarCodes() メソッドを呼び出す前に実行する必要があります。"
type: docs
weight: 1500
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>) method


認識用のビットマップ画像を設定します。[ReadBarCodes()](../readbarcodes/) メソッドを呼び出す前に実行する必要があります。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | System::SharedPtr\<System::Drawing::Bitmap\> | 認識用のビットマップ画像です。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        reader.SetBarCodeImage(bmp)
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
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) method


認識用のビットマップ画像と領域を設定します。[ReadBarCodes()](../readbarcodes/) メソッドを呼び出す前に実行する必要があります。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value, System::ArrayPtr<System::Drawing::Rectangle> areas)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | System::SharedPtr\<System::Drawing::Bitmap\> | 認識用のビットマップ画像です。 |
| 領域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 認識用領域リスト |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        reader.SetBarCodeImage(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)})
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
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) method


認識用にビットマップ画像と領域を設定します。 [ReadBarCodes()](../readbarcodes/) メソッドを呼び出す前に実行する必要があります。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value, System::Drawing::Rectangle area)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | System::SharedPtr\<System::Drawing::Bitmap\> | 認識用のビットマップ画像です。 |
| 領域 | System::Drawing::Rectangle | 認識用領域 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        reader.SetBarCodeImage(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height))
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
## BarCodeReader::SetBarCodeImage(System::String) method


認識用に画像ファイルを設定します。 [ReadBarCodes()](../readbarcodes/) メソッドを呼び出す前に実行する必要があります。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::String filename)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | System::String | 認識用の画像ファイルです。 |
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
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::IO::Stream\>) method


認識用に画像ストリームを設定します。 [ReadBarCodes()](../readbarcodes/) メソッドを呼び出す前に実行する必要があります。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::IO::Stream> stream)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | 認識用の画像ストリームです。 |
## 備考



このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        reader.SetBarCodeImage(fstr)
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
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) method


認識用に輝度フレームと領域を設定します。 [ReadBarCodes](../readbarcodes/) メソッドを呼び出す前に実行する必要があります。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フレーム | System::SharedPtr\<LuminanceFrame\> | 認識用の輝度フレームです。 |
| 領域 | System::Drawing::Rectangle | 認識用の領域です。 |
## 備考



このサンプルは、輝度フレームの指定領域で Code39 と Code128 バーコードを検出する方法を示しています。
```cpp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(frame, new Rectangle(0, 0, width, height));
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
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) method


認識用に輝度フレームと領域を設定します。 [ReadBarCodes](../readbarcodes/) メソッドを呼び出す前に実行する必要があります。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フレーム | System::SharedPtr\<LuminanceFrame\> | 認識用の輝度フレームです。 |
| 領域 | System::ArrayPtr\<System::Drawing::Rectangle\> | 認識領域の配列です。 |
## 備考



このサンプルは、輝度フレームの指定領域で Code39 と Code128 のバーコードを検出する方法を示します。
```cpp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle[] areas = { new Rectangle(0, 0, width, height / 2), new Rectangle(0, height / 2, width, height / 2) };

using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(frame, areas);
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
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>) method


認識用に輝度フレームを設定します。 [ReadBarCodes](../readbarcodes/) メソッドを呼び出す前に実行する必要があります。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フレーム | System::SharedPtr\<LuminanceFrame\> | 認識用の輝度フレームです。 |
## 備考



このサンプルは、輝度フレーム内で Code39 と Code128 バーコードを検出する方法を示しています。
```cpp
int width = 1920;
int height = 1080;
int rowStride = 2048;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height, rowStride, 90);

using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(frame);
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
