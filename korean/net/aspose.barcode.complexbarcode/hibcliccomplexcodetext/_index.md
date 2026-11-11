---
title: "클래스 HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICComplexCodetext 클래스. HIBC LIC 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 기본 클래스"
type: docs
weight: 560
url: /ko/net/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class

HIBC LIC 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 기본 클래스입니다.

```csharp
public abstract class HIBCLICComplexCodetext : IComplexCodetext
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | 바코드 유형을 가져오거나 설정합니다. HIBC LIC 코드텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | 바코드 유형을 가져옵니다. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getconstructedcodetext/)() | 코드텍스트를 구성합니다. |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/initfromstring/)(string) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |

## 예제

이 샘플은 원시 HIBC LIC 코드텍스트를 HIBCLICComplexCodetext 인스턴스로 디코딩하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### 또 보기

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


