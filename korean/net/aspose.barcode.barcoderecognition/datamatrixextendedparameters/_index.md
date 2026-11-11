---
title: "클래스 DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters 클래스. 인식된 DataMatrix 바코드의 특수 데이터를 저장합니다."
type: docs
weight: 220
url: /ko/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

DataMatrix 인식 바코드의 특수 데이터를 저장합니다.

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | 코드가 바코드 리더기의 초기화 또는 재프로그래밍을 위한 지시로 해석하도록 리더기에 지시하는 데 사용되는지 여부를 나타냅니다. 기본값은 false입니다. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | DataMatrix 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | DataMatrix 구조 추가 모드 바코드 수를 가져옵니다. 기본값은 -1이며, 카운트는 1에서 35 사이의 값이어야 합니다. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | DataMatrix 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | 이 인스턴스가 지정된 `DataMatrixExtendedParameters` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | 이 `DataMatrixExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | 첫 번째 `DataMatrixExtendedParameters` 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | 첫 번째 `DataMatrixExtendedParameters` 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |

## 예제

이 샘플은 DataMatrix 원시 값을 가져오는 방법을 보여줍니다.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### 또 보기

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


