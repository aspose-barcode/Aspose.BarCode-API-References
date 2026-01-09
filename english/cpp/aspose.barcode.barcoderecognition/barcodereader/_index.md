---
title: Aspose::BarCode::BarCodeRecognition::BarCodeReader class
linktitle: BarCodeReader
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::BarCodeReader class. BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes in C++.'
type: docs
weight: 500
url: /cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Abort](./abort/)() | Function requests termination of current recognition session from other thread. Abort is unblockable method and returns control just after calling. The method should be used when recognition process is too long. |
| [BarCodeReader](./barcodereader/)() | Initializes a new instance of the [BarCodeReader](./) class with default values. Requires to set image (SetBitmapImage()) before to call [ReadBarCodes()](./readbarcodes/) method. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Initializes a new instance of the [BarCodeReader](./) class from an image. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initializes a new instance of the [BarCodeReader](./) class. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | Initializes a new instance of the [BarCodeReader](./) class. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initializes a new instance of the [BarCodeReader](./) class. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Initializes a new instance of the [BarCodeReader](./) class. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initializes a new instance of the [BarCodeReader](./) class. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Initializes a new instance of the [BarCodeReader](./) class. |
| [BarCodeReader](./barcodereader/)(System::String) | Initializes a new instance of the [BarCodeReader](./) class from file. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initializes a new instance of the [BarCodeReader](./) class. |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | Initializes a new instance of the [BarCodeReader](./) class. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | Initializes a new instance of the [BarCodeReader](./) class. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | Initializes a new instance of the [BarCodeReader](./) class. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initializes a new instance of the [BarCodeReader](./) class. |
| [Dispose](./dispose/)() override | Release resource |
| [ExportToXml](./exporttoxml/)(System::String) | Exports [BarCode](../../aspose.barcode/) properties to the xml-file specified |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exports [BarCode](../../aspose.barcode/) properties to the xml-stream specified |
| [get_BarcodeSettings](./get_barcodesettings/)() | The main [BarCode](../../aspose.barcode/) decoding parameters. Contains parameters which make influence on recognized data. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | Gets recognized [BarCodeResult](../barcoderesult/)s array |
| [get_FoundCount](./get_foundcount/)() | Gets recognized barcodes count |
| static [get_ProcessorSettings](./get_processorsettings/)() | Gets a settings of using processor cores. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](../qualitysettings/) by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of [QualitySettings](../qualitysettings/) is NormalQuality. |
| [get_Timeout](./get_timeout/)() | Gets the timeout of recognition process in milliseconds. |
| static [ImportFromXml](./importfromxml/)(System::String) | Imports [BarCode](../../aspose.barcode/) properties from the xml-file specified and applies them to the current [BarCodeReader](./) instance. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Imports [BarCode](../../aspose.barcode/) properties from the xml-stream specified and applies them to the current [BarCodeReader](./) instance. |
| [ReadBarCodes](./readbarcodes/)() | Reads [BarCodeResult](../barcoderesult/)s from the image. |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](../qualitysettings/) by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of [QualitySettings](../qualitysettings/) is NormalQuality. |
| [set_Timeout](./set_timeout/)(int32_t) | Sets the timeout of recognition process in milliseconds. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Sets bitmap image for recognition. Must be called before [ReadBarCodes()](./readbarcodes/) method. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Sets bitmap image and areas for recognition. Must be called before [ReadBarCodes()](./readbarcodes/) method. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | Sets bitmap image and area for recognition. Must be called before [ReadBarCodes()](./readbarcodes/) method. |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | Sets image file for recognition. Must be called before [ReadBarCodes()](./readbarcodes/) method. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | Sets image stream for recognition. Must be called before [ReadBarCodes()](./readbarcodes/) method. |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Sets [SingleDecodeType](../singledecodetype/) type array for recognition. Must be called before [ReadBarCodes()](./readbarcodes/) method. |
| [SetBarCodeReadType](./setbarcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | Sets decode type for recognition. Must be called before [ReadBarCodes()](./readbarcodes/) method. |
## Remarks


This sample shows how to detect Code39 and Code128 barcodes. 
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

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
