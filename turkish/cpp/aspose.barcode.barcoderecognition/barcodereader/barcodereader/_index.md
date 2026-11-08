---
title: "yapıcı"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yapıcı. BarCodeReader sınıfının yeni bir örneğini varsayılan değerlerle başlatır. C++ içinde ReadBarCodes() yöntemini çağırmadan önce görüntüyü (SetBitmapImage()) ayarlamayı gerektirir."
type: docs
weight: 1400
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader::BarCodeReader() constructor


Varsayılan değerlerle [BarCodeReader](../) sınıfının yeni bir örneğini başlatır. [ReadBarCodes()](../readbarcodes/) yöntemini çağırmadan önce görüntüyü (SetBitmapImage()) ayarlamayı gerektirir.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader()
```

## Açıklamalar


Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>) constructor


Bir görüntüden [BarCodeReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | System::SharedPtr\<System::Drawing::Bitmap\> | Görüntüyü içeren bir Bitmap örneği |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | System::SharedPtr\<System::Drawing::Bitmap\> | Görüntü. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | Kod çözümleme türleri. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::SharedPtr<BaseDecodeType> type)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | System::SharedPtr\<System::Drawing::Bitmap\> | Görüntü. |
| tür | System::SharedPtr\<BaseDecodeType\> | Bu decode type1. Tek veya çok olabilir |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::Drawing::Rectangle area, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | System::SharedPtr\<System::Drawing::Bitmap\> | Görüntü. |
| alan | System::Drawing::Rectangle | Tanıma için alan. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | Kod çözümleme türleri. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::Drawing::Rectangle area, System::SharedPtr<BaseDecodeType> type)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | System::SharedPtr\<System::Drawing::Bitmap\> | Görüntü. |
| alan | System::Drawing::Rectangle | Tanıma için alan. |
| tür | System::SharedPtr\<BaseDecodeType\> | Kod çözümleme türü. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::ArrayPtr<System::Drawing::Rectangle> areas, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | System::SharedPtr\<System::Drawing::Bitmap\> | Okunacak görüntü |
| alanlar | System::ArrayPtr\<System::Drawing::Rectangle\> | Tanıma alanlarının dizisi |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | Belirtilen tüm alanlar için geçerli kod çözümleme türleri. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::Drawing::Bitmap> image, System::ArrayPtr<System::Drawing::Rectangle> areas, System::SharedPtr<BaseDecodeType> type)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | System::SharedPtr\<System::Drawing::Bitmap\> | Okunacak görüntü |
| alanlar | System::ArrayPtr\<System::Drawing::Rectangle\> | Tanıma alanlarının dizisi |
| tür | System::SharedPtr\<BaseDecodeType\> | Belirtilen tüm alanlar için geçerli kod çözümleme türü. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String) constructor


Dosyadan [BarCodeReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | System::String | Dosya adı. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | System::String | Dosya adı. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | Kod çözümleme türleri. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::String, System::SharedPtr\<BaseDecodeType\>) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::String filename, System::SharedPtr<BaseDecodeType> type)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | System::String | Dosya adı. |
| tür | System::SharedPtr\<BaseDecodeType\> | Kod çözümleme türü. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Akış. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<BaseDecodeType> type)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Akış. |
| tür | System::SharedPtr\<BaseDecodeType\> | Kod çözümleme türü. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<System::IO::Stream> stream, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Akış. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | Kod çözümleme türleri. |
## Açıklamalar



Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas, System::SharedPtr<BaseDecodeType> type)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | System::SharedPtr\<LuminanceFrame\> | Okunacak aydınlık çerçeve. |
| alanlar | System::ArrayPtr\<System::Drawing::Rectangle\> | Tanıma alanlarının dizisi. |
| tür | System::SharedPtr\<BaseDecodeType\> | Kod çözümleme türü. |
## Açıklamalar



Bu örnek, bir aydınlık çerçevenin belirtilen alanlarında Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.
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

## Ayrıca Bakınız

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | System::SharedPtr\<LuminanceFrame\> | Okunacak aydınlık çerçeve. |
| alanlar | System::ArrayPtr\<System::Drawing::Rectangle\> | Tanıma alanlarının dizisi. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | Kod çözümleme türleri. |
## Açıklamalar



Bu örnek, bir aydınlık çerçevenin belirtilen alanlarında Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.
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

## Ayrıca Bakınız

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area, System::SharedPtr<BaseDecodeType> type)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | System::SharedPtr\<LuminanceFrame\> | Okunacak aydınlık çerçeve. |
| alan | System::Drawing::Rectangle | Tanıma için alan. |
| tür | System::SharedPtr\<BaseDecodeType\> | Kod çözümleme türü. |
## Açıklamalar



Bu örnek, bir parlaklık çerçevesinin belirli bir alanında Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.
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

## Ayrıca Bakınız

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | System::SharedPtr\<LuminanceFrame\> | Okunacak aydınlık çerçeve. |
| alan | System::Drawing::Rectangle | Tanıma için alan. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | Kod çözümleme türleri. |
## Açıklamalar



Bu örnek, bir parlaklık çerçevesinin belirli bir alanında Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.
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

## Ayrıca Bakınız

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, System::SharedPtr<BaseDecodeType> type)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | System::SharedPtr\<LuminanceFrame\> | Okunacak aydınlık çerçeve. |
| tür | System::SharedPtr\<BaseDecodeType\> | Kod çözümleme türü. |
## Açıklamalar



Bu örnek, bir parlaklık çerçevesinde Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.
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

## Ayrıca Bakınız

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) constructor


Yeni bir [BarCodeReader](../) sınıf örneği başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame, const System::ArrayPtr<System::SharedPtr<BaseDecodeType>> &decodeTypes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | System::SharedPtr\<LuminanceFrame\> | Okunacak aydınlık çerçeve. |
| decodeTypes | const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\& | Kod çözümleme türleri. |
## Açıklamalar



Bu örnek, bir parlaklık çerçevesinde Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.
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

## Ayrıca Bakınız

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::BarCodeReader(System::SharedPtr\<LuminanceFrame\>) constructor


Parlaklık çerçevesinden [BarCodeReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::BarCodeReader::BarCodeReader(System::SharedPtr<LuminanceFrame> frame)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çerçeve | System::SharedPtr\<LuminanceFrame\> | Okunacak aydınlık çerçeve. |
## Açıklamalar



Bu örnek, bir parlaklık çerçevesinde Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.
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

## Ayrıca Bakınız

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
