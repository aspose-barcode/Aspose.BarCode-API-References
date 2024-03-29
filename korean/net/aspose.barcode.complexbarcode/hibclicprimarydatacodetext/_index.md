---
title: HIBCLICPrimaryDataCodetext
second_title: .NET API 참조용 Aspose.BarCode
description: 기본 데이터를 저장하는 HIBC LIC 코드에 포함된 텍스트를 인코딩 및 디코딩하는 클래스.
type: docs
weight: 400
url: /ko/net/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class

기본 데이터를 저장하는 HIBC LIC 코드에 포함된 텍스트를 인코딩 및 디코딩하는 클래스.

```csharp
public class HIBCLICPrimaryDataCodetext : HIBCLICComplexCodetext
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HIBCLICPrimaryDataCodetext](hibclicprimarydatacodetext/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | 바코드 유형을 가져오거나 설정합니다. HIBC LIC 코드 텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코딩 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/data/) { get; set; } | 기본 데이터를 식별합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/equals/)(object) | 이 인스턴스가 지정된 것과 같은지 여부를 나타내는 값을 반환합니다.`HIBCLICPrimaryDataCodetext` 값. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | 바코드 유형을 가져옵니다. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/getconstructedcodetext/)() | codetext 구성 |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/initfromstring/)(string) | 구성된 코드 텍스트에서 인스턴스를 초기화합니다. |

### 예

이 샘플은 HIBCLICPrimaryCodetext. 를 사용하여 HIBC LIC를 인코딩 및 디코딩하는 방법을 보여줍니다.

```csharp
[C#]
HIBCLICPrimaryCodetext complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryCodetext result = (HIBCLICPrimaryCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

### 또한보십시오

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* 네임스페이스 [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
