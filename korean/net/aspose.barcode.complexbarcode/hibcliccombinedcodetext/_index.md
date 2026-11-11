---
title: "클래스 HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICCombinedCodetext 클래스. 기본 및 보조 데이터를 저장하는 HIBC LIC 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스"
type: docs
weight: 550
url: /ko/net/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class

HIBC LIC 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 클래스이며, 기본 및 보조 데이터를 저장합니다.

```csharp
public class HIBCLICCombinedCodetext : HIBCLICComplexCodetext
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HIBCLICCombinedCodetext](hibcliccombinedcodetext/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | 바코드 유형을 가져오거나 설정합니다. HIBC LIC 코드텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC. |
| [PrimaryData](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/primarydata/) { get; set; } | 기본 데이터를 식별합니다. |
| [SecondaryAndAdditionalData](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/secondaryandadditionaldata/) { get; set; } | 보조 및 추가 보충 데이터를 식별합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/equals/)(object) | 이 인스턴스가 지정된 `HIBCLICCombinedCodetext` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | 바코드 유형을 가져옵니다. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/getconstructedcodetext/)() | 코드텍스트를 구성합니다. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/initfromstring/)(string) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |

## 예제

이 샘플은 HIBCLICCombinedCodetext를 사용하여 HIBC LIC를 인코딩하고 디코딩하는 방법을 보여줍니다.

```csharp
[C#]
HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
combinedCodetext.PrimaryData = new PrimaryData();
combinedCodetext.PrimaryData.ProductOrCatalogNumber = "12345";
combinedCodetext.PrimaryData.LabelerIdentificationCode = "A999";
combinedCodetext.PrimaryData.UnitOfMeasureID = 1;
combinedCodetext.SecondaryAndAdditionalData = new SecondaryAndAdditionalData();
combinedCodetext.SecondaryAndAdditionalData.ExpiryDate = DateTime.Now;
combinedCodetext.SecondaryAndAdditionalData.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
combinedCodetext.SecondaryAndAdditionalData.Quantity = 30;
combinedCodetext.SecondaryAndAdditionalData.LotNumber = "LOT123";
combinedCodetext.SecondaryAndAdditionalData.SerialNumber = "SERIAL123";
combinedCodetext.SecondaryAndAdditionalData.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.PrimaryData.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.PrimaryData.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.PrimaryData.UnitOfMeasureID);
        Console.WriteLine("Expiry date: " + result.SecondaryAndAdditionalData.ExpiryDate);
        Console.WriteLine("Quantity: " + result.SecondaryAndAdditionalData.Quantity);
        Console.WriteLine("Lot number: " + result.SecondaryAndAdditionalData.LotNumber);
        Console.WriteLine("Serial number: " + result.SecondaryAndAdditionalData.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.SecondaryAndAdditionalData.DateOfManufacture);
    }
}
```

### 또 보기

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


