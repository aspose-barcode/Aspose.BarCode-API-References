---
title: "클래스 DotCodeExtendedParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.DotCodeExtendedParameters 클래스. DotCode 인식 바코드의 특수 데이터를 저장합니다."
type: docs
weight: 250
url: /ko/net/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class

DotCode 인식 바코드의 특수 데이터를 저장합니다.

```csharp
public sealed class DotCodeExtendedParameters : BaseExtendedParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/isreaderinitialization/) { get; } | 코드가 바코드 리더기의 초기화 또는 재프로그래밍을 위한 지시로 해석하도록 리더기에 지시하는 데 사용되는지 여부를 나타냅니다. 기본값은 false입니다. |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodeid/) { get; } | DotCode 구조화 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodescount/) { get; } | DotCode 구조화 추가 모드 바코드 수를 가져옵니다. 기본값은 -1이며, 카운트는 1에서 35 사이의 값이어야 합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/equals/)(object) | `DotCodeExtendedParameters` 지정 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/tostring/)() | 이 `DotCodeExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [operator ==](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_equality/) | 첫 번째 `DotCodeExtendedParameters` 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다. |
| [operator !=](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_inequality/) | 첫 번째 `DotCodeExtendedParameters` 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |

## 예제

이 샘플은 DotCode 원시 값을 가져오는 방법을 보여줍니다.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

### 또 보기

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


