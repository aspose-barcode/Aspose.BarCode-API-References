---
title: "클래스 MaxiCodeCodetext"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeCodetext 클래스. MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스"
type: docs
weight: 680
url: /ko/net/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class

MaxiCode 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 기본 클래스입니다.

```csharp
public abstract class MaxiCodeCodetext : IComplexCodetext
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | ECI 인코딩을 가져오거나 설정합니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | MaxiCode 인코드 모드를 가져오거나 설정합니다. 기본값: Auto. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | 바코드 유형을 가져옵니다. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodecodetext/getconstructedcodetext/)() | 코드텍스트를 구성합니다. |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | MaxiCode 모드를 가져옵니다. |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/maxicodecodetext/initfromstring/)(string) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |

## 예제

이 샘플은 원시 MaxiCode 코드텍스트를 MaxiCodeCodetext 인스턴스로 디코딩하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### 또 보기

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


