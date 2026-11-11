---
title: "BarCodeReader 클래스"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeReader 클래스. BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화하며, 이후 ReadBarCodes 작업을 수행하여 바코드를 감지할 수 있습니다."
type: docs
weight: 70
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화하며, 바코드를 감지하기 위해 ReadBarCodes 작업을 수행할 수 있습니다.

```csharp
public class BarCodeReader : Component
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | 기본값으로 `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. ReadBarCodes() 메서드를 호출하기 전에 이미지(SetBitmapImage())를 설정해야 합니다. |
| [BarCodeReader](barcodereader/#constructor_8)(Bitmap) | 이미지에서 `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_1)(LuminanceFrame) | 휘도 프레임에서 `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_15)(Stream) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_18)(string) | 파일에서 `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_9)(Bitmap, BaseDecodeType) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_10)(Bitmap, params BaseDecodeType[]) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_2)(LuminanceFrame, BaseDecodeType) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_3)(LuminanceFrame, params BaseDecodeType[]) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_16)(Stream, BaseDecodeType) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_17)(Stream, params BaseDecodeType[]) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_19)(string, BaseDecodeType) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_20)(string, params BaseDecodeType[]) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_11)(Bitmap, Rectangle, BaseDecodeType) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_12)(Bitmap, Rectangle, params BaseDecodeType[]) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_13)(Bitmap, Rectangle[], BaseDecodeType) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_14)(Bitmap, Rectangle[], params BaseDecodeType[]) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_4)(LuminanceFrame, Rectangle, BaseDecodeType) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_5)(LuminanceFrame, Rectangle, params BaseDecodeType[]) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_6)(LuminanceFrame, Rectangle[], BaseDecodeType) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |
| [BarCodeReader](barcodereader/#constructor_7)(LuminanceFrame, Rectangle[], params BaseDecodeType[]) | `BarCodeReader` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/) { get; set; } | 인식에 사용되는 바코드 디코드 유형을 가져오거나 설정합니다. [`ReadBarCodes`](./readbarcodes/)를 호출하기 전에 설정해야 합니다. |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | 주요 BarCode 디코딩 매개변수. 인식된 데이터에 영향을 주는 매개변수를 포함합니다. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | 인식된 [`BarCodeResult`](../barcoderesult/) 배열을 가져옵니다 |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | 인식된 바코드 수를 가져옵니다 |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. 내장 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxBarCodes를 사용하여 빠르게 QualitySettings를 설정하거나 별도의 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | 인식 프로세스의 타임아웃을 밀리초 단위로 가져오거나 설정합니다. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | 프로세서 코어 사용 설정을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | 지정된 xml 스트림에서 BarCode 속성을 가져와 현재 BarCodeReader 인스턴스에 적용합니다. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | 지정된 xml 파일에서 BarCode 속성을 가져와 현재 BarCodeReader 인스턴스에 적용합니다. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | 이 함수는 다른 스레드에서 현재 인식 세션의 종료를 요청합니다. Abort은 차단할 수 없는 메서드이며 호출 직후 제어를 반환합니다. 인식 프로세스가 너무 오래 걸릴 때 이 메서드를 사용해야 합니다. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | 지정된 xml 스트림으로 BarCode 속성을 내보냅니다 |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | 지정된 xml 파일로 BarCode 속성을 내보냅니다 |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | 이미지에서 [`BarCodeResult`](../barcoderesult/)를 읽어옵니다 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Bitmap) | 인식을 위한 비트맵 이미지를 설정합니다. ReadBarCodes() 메서드 호출 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(LuminanceFrame) | 인식에 사용할 밝기 프레임을 설정합니다. [`ReadBarCodes`](./readbarcodes/) 메서드를 호출하기 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_6)(Stream) | 인식을 위한 이미지 스트림을 설정합니다. ReadBarCodes() 메서드를 호출하기 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_7)(string) | 인식을 위한 이미지 파일을 설정합니다. ReadBarCodes() 메서드를 호출하기 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(Bitmap, Rectangle) | 인식을 위한 비트맵 이미지와 영역을 설정합니다. ReadBarCodes() 메서드를 호출하기 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_5)(Bitmap, Rectangle[]) | 인식을 위한 비트맵 이미지와 여러 영역을 설정합니다. ReadBarCodes() 메서드를 호출하기 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(LuminanceFrame, Rectangle) | 인식을 위한 밝기 프레임과 영역을 설정합니다. [`ReadBarCodes`](./readbarcodes/) 메서드를 호출하기 전에 호출해야 합니다. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(LuminanceFrame, Rectangle[]) | 인식을 위한 밝기 프레임과 여러 영역을 설정합니다. [`ReadBarCodes`](./readbarcodes/) 메서드를 호출하기 전에 호출해야 합니다. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/)(params SingleDecodeType[]) | 인식을 위한 [`SingleDecodeType`](../singledecodetype/) 타입 배열을 설정합니다. ReadBarCodes() 메서드를 호출하기 전에 호출해야 합니다. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

```csharp
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

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


