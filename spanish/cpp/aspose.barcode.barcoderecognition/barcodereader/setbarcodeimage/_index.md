---
title: "método"
linktitle: "SetBarCodeImage"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Establece la imagen bitmap para el reconocimiento. Debe llamarse antes del método ReadBarCodes() en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>) method


Establece la imagen bitmap para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | System::SharedPtr\<System::Drawing::Bitmap\> | La imagen bitmap para el reconocimiento. |
## Observaciones



Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.
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

## Ver también

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) method


Establece la imagen bitmap y áreas para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value, System::ArrayPtr<System::Drawing::Rectangle> areas)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | System::SharedPtr\<System::Drawing::Bitmap\> | La imagen bitmap para el reconocimiento. |
| areas | System::ArrayPtr\<System::Drawing::Rectangle\> | lista de áreas para el reconocimiento |
## Observaciones



Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.
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

## Ver también

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) method


Establece la imagen bitmap y el área para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::Drawing::Bitmap> value, System::Drawing::Rectangle area)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | System::SharedPtr\<System::Drawing::Bitmap\> | La imagen bitmap para el reconocimiento. |
| area | System::Drawing::Rectangle | área para el reconocimiento |
## Observaciones



Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.
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

## Ver también

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::String) method


Establece el archivo de imagen para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::String filename)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre de archivo | System::String | El archivo de imagen para el reconocimiento. |
## Observaciones



Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.
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

## Ver también

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<System::IO::Stream\>) method


Establece el flujo de imagen para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<System::IO::Stream> stream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | El flujo de imagen para el reconocimiento. |
## Observaciones



Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.
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

## Ver también

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) method


Establece el marco de luminancia y el área para el reconocimiento. Debe llamarse antes del método [ReadBarCodes](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame, System::Drawing::Rectangle area)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frame | System::SharedPtr\<LuminanceFrame\> | El marco de luminancia para el reconocimiento. |
| area | System::Drawing::Rectangle | El área para el reconocimiento. |
## Observaciones



Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128 en un área especificada de un cuadro de luminancia.
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

## Ver también

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) method


Establece el marco de luminancia y las áreas para el reconocimiento. Debe llamarse antes del método [ReadBarCodes](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame, System::ArrayPtr<System::Drawing::Rectangle> areas)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frame | System::SharedPtr\<LuminanceFrame\> | El marco de luminancia para el reconocimiento. |
| areas | System::ArrayPtr\<System::Drawing::Rectangle\> | La matriz de áreas de reconocimiento. |
## Observaciones



Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128 en áreas especificadas de un luminance frame.
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

## Ver también

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarCodeReader::SetBarCodeImage(System::SharedPtr\<LuminanceFrame\>) method


Establece el marco de luminancia para el reconocimiento. Debe llamarse antes del método [ReadBarCodes](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeImage(System::SharedPtr<LuminanceFrame> frame)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frame | System::SharedPtr\<LuminanceFrame\> | El marco de luminancia para el reconocimiento. |
## Observaciones



Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128 en un cuadro de luminancia.
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

## Ver también

* Class [LuminanceFrame](../../luminanceframe/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
