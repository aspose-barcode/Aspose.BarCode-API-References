---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeReader 클래스"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeReader 클래스. BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화하며, C++에서 바코드를 감지하기 위해 ReadBarCodes 작업을 수행할 수 있습니다."
type: docs
weight: 500
url: /ko/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Abort](./abort/)() | 함수는 다른 스레드에서 현재 인식 세션의 종료를 요청합니다. Abort은 차단할 수 없는 메서드이며 호출 직후 제어를 반환합니다. 인식 프로세스가 너무 오래 걸릴 때 이 메서드를 사용해야 합니다. |
| [BarCodeReader](./barcodereader/)() | 기본값으로 [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. [ReadBarCodes()](./readbarcodes/) 메서드를 호출하기 전에 이미지(SetBitmapImage())를 설정해야 합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | 이미지에서 [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::String) | 파일에서 [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | 휘도 프레임에서 [BarCodeReader](./) 클래스의 새 인스턴스를 초기화합니다. |
| [Dispose](./dispose/)() override | 리소스 해제 |
| [ExportToXml](./exporttoxml/)(System::String) | [BarCode](../../aspose.barcode/) 속성을 지정된 xml 파일로 내보냅니다 |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | [BarCode](../../aspose.barcode/) 속성을 지정된 xml 스트림으로 내보냅니다 |
| [get_BarCodeReadType](./get_barcodereadtype/)() | 인식에 사용되는 바코드 디코드 유형을 가져옵니다. [ReadBarCodes](./readbarcodes/)를 호출하기 전에 설정해야 합니다. |
| [get_BarcodeSettings](./get_barcodesettings/)() | 주요 [BarCode](../../aspose.barcode/) 디코딩 매개변수. 인식된 데이터에 영향을 주는 매개변수를 포함합니다. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | 인식된 [BarCodeResult](../barcoderesult/) 배열을 가져옵니다 |
| [get_FoundCount](./get_foundcount/)() | 인식된 바코드 수를 가져옵니다 |
| static [get_ProcessorSettings](./get_processorsettings/)() | 프로세서 코어 사용에 대한 설정을 가져옵니다. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/)는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. 내장 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxBarCodes를 사용하여 빠르게 설정할 수 있으며, 별도의 옵션을 수동으로 구성할 수도 있습니다. [QualitySettings](../qualitysettings/)의 기본값은 NormalQuality입니다. |
| [get_Timeout](./get_timeout/)() | 인식 프로세스의 제한 시간을 밀리초 단위로 가져옵니다. |
| static [ImportFromXml](./importfromxml/)(System::String) | 지정된 xml 파일에서 [BarCode](../../aspose.barcode/) 속성을 가져와 현재 [BarCodeReader](./) 인스턴스에 적용합니다. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | 지정된 xml 스트림에서 [BarCode](../../aspose.barcode/) 속성을 가져와 현재 [BarCodeReader](./) 인스턴스에 적용합니다. |
| [ReadBarCodes](./readbarcodes/)() | 이미지에서 [BarCodeResult](../barcoderesult/)를 읽어옵니다. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | 인식에 사용되는 바코드 디코드 유형을 설정합니다. [ReadBarCodes](./readbarcodes/)를 호출하기 전에 설정해야 합니다. |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/)는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. 내장 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxBarCodes를 사용하여 빠르게 설정할 수 있으며, 별도의 옵션을 수동으로 구성할 수도 있습니다. [QualitySettings](../qualitysettings/)의 기본값은 NormalQuality입니다. |
| [set_Timeout](./set_timeout/)(int32_t) | 인식 프로세스의 제한 시간을 밀리초 단위로 설정합니다. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | 인식을 위해 비트맵 이미지를 설정합니다. [ReadBarCodes()](./readbarcodes/) 메서드 호출 전에 호출해야 합니다. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | 인식을 위해 비트맵 이미지와 영역들을 설정합니다. [ReadBarCodes()](./readbarcodes/) 메서드 호출 전에 호출해야 합니다. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | 인식을 위해 비트맵 이미지와 영역을 설정합니다. [ReadBarCodes()](./readbarcodes/) 메서드 호출 전에 호출해야 합니다. |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | 인식을 위해 이미지 파일을 설정합니다. [ReadBarCodes()](./readbarcodes/) 메서드 호출 전에 호출해야 합니다. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | 인식을 위해 이미지 스트림을 설정합니다. [ReadBarCodes()](./readbarcodes/) 메서드 호출 전에 호출해야 합니다. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | 인식을 위해 광도 프레임과 영역을 설정합니다. [ReadBarCodes](./readbarcodes/) 메서드 호출 전에 호출해야 합니다. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | 인식을 위해 광도 프레임과 여러 영역을 설정합니다. [ReadBarCodes](./readbarcodes/) 메서드 호출 전에 호출해야 합니다. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | 인식을 위해 광도 프레임을 설정합니다. [ReadBarCodes](./readbarcodes/) 메서드 호출 전에 호출해야 합니다. |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | [SingleDecodeType](../singledecodetype/) 유형 배열을 인식에 설정합니다. [ReadBarCodes()](./readbarcodes/) 메서드 호출 전에 호출해야 합니다. |
## 비고


이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.
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

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
