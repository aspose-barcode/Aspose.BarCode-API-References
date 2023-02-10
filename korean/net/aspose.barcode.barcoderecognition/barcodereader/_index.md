---
title: BarCodeReader
second_title: .NET API 참조용 Aspose.BarCode
description: BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화한 다음 ReadBarCodes 작업을 수행하여 바코드를 감지할 수 있습니다.
type: docs
weight: 60
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화한 다음 ReadBarCodes 작업을 수행하여 바코드를 감지할 수 있습니다.

```csharp
public class BarCodeReader : Component
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 기본값이 있는 클래스. ReadBarCodes() 메서드를 호출하기 전에 이미지(SetBitmapImage())를 설정해야 합니다. |
| [BarCodeReader](barcodereader/#constructor_1)(Bitmap) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` image. 의 클래스 |
| [BarCodeReader](barcodereader/#constructor_8)(Stream) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |
| [BarCodeReader](barcodereader/#constructor_11)(string) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` file. 의 클래스 |
| [BarCodeReader](barcodereader/#constructor_2)(Bitmap, BaseDecodeType) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |
| [BarCodeReader](barcodereader/#constructor_3)(Bitmap, params BaseDecodeType[]) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |
| [BarCodeReader](barcodereader/#constructor_9)(Stream, BaseDecodeType) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |
| [BarCodeReader](barcodereader/#constructor_10)(Stream, params BaseDecodeType[]) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |
| [BarCodeReader](barcodereader/#constructor_12)(string, BaseDecodeType) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |
| [BarCodeReader](barcodereader/#constructor_13)(string, params BaseDecodeType[]) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |
| [BarCodeReader](barcodereader/#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |
| [BarCodeReader](barcodereader/#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |
| [BarCodeReader](barcodereader/#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |
| [BarCodeReader](barcodereader/#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | 의 새 인스턴스를 초기화합니다.`BarCodeReader` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | 기본 BarCode 디코딩 매개변수입니다. 인식된 데이터에 영향을 미치는 매개변수를 포함합니다. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | 인정받다[`BarCodeResult`](../barcoderesult/)배열 |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | 인식된 바코드 수 가져오기 |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다. 포함된 사전 설정으로 QualitySettings를 빠르게 설정할 수 있습니다: HighPerformance, NormalQuality, HighQuality, MaxBarCodes 또는 개별 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | 인식 프로세스의 제한 시간을 밀리초 단위로 가져오거나 설정합니다. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | 프로세서 코어 사용 설정을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | 지정된 xml-stream에서 BarCode 속성을 가져와 현재 BarCodeReader 인스턴스에 적용합니다. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | 지정된 xml 파일에서 BarCode 속성을 가져와 현재 BarCodeReader 인스턴스에 적용합니다. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | 함수는 다른 스레드에서 현재 인식 세션의 종료를 요청합니다. Abort는 차단할 수 없는 메서드이며 호출 직후 컨트롤을 반환합니다. 인식 과정이 너무 길 때 사용하는 방법입니다. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | 바코드 속성을 xml-stream specified 로 내보냅니다. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | BarCode 속성을 xml 파일로 내보냅니다. |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | 읽기[`BarCodeResult`](../barcoderesult/) 이미지에서 s. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(Bitmap) | 인식용 비트맵 이미지를 설정합니다. ReadBarCodes() 메서드 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Stream) | 인식할 이미지 스트림을 설정합니다. ReadBarCodes() 메서드 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(string) | 인식할 이미지 파일을 설정합니다. ReadBarCodes() 메서드 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(Bitmap, Rectangle) | 인식할 비트맵 이미지와 영역을 설정합니다. ReadBarCodes() 메서드 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(Bitmap, Rectangle[]) | 인식할 비트맵 이미지와 영역을 설정합니다. ReadBarCodes() 메서드 전에 호출해야 합니다. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype)(BaseDecodeType) | 인식을 위한 디코드 유형을 설정합니다. ReadBarCodes() 메서드 전에 호출해야 합니다. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype_1)(params SingleDecodeType[]) | 세트[`SingleDecodeType`](../singledecodetype/) 인식을 위한 유형 배열. ReadBarCodes() 메서드 전에 호출해야 합니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
