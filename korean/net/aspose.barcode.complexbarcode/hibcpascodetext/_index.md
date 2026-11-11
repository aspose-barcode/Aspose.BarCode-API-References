---
title: "클래스 HIBCPASCodetext"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.HIBCPASCodetext 클래스. HIBC PAS 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스"
type: docs
weight: 600
url: /ko/net/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class

HIBC PAS 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스입니다.

```csharp
public class HIBCPASCodetext : IComplexCodetext
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HIBCPASCodetext](hibcpascodetext/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/barcodetype/) { get; set; } | 바코드 유형을 가져오거나 설정합니다. HIBC PAS 코덱텍스트는 HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS 및 HIBCQRPAS 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39PAS. |
| [DataLocation](../../aspose.barcode.complexbarcode/hibcpascodetext/datalocation/) { get; set; } | 데이터 위치를 식별합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord_1)(HIBCPASRecord) | 새 레코드를 추가합니다 |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord)(HIBCPASDataType, string) | 새 레코드를 추가합니다 |
| [Clear](../../aspose.barcode.complexbarcode/hibcpascodetext/clear/)() | 레코드 목록을 비웁니다 |
| override [Equals](../../aspose.barcode.complexbarcode/hibcpascodetext/equals/)(object) | 이 인스턴스가 지정된 `HIBCPASCodetext` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/getbarcodetype/)() | 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcpascodetext/getconstructedcodetext/)() | 코드텍스트를 구성합니다. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcpascodetext/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| [GetRecords](../../aspose.barcode.complexbarcode/hibcpascodetext/getrecords/)() | 레코드 목록을 가져옵니다 |
| [InitFromString](../../aspose.barcode.complexbarcode/hibcpascodetext/initfromstring/)(string) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |

## 예제

이 샘플은 HIBCPASCodetext를 사용하여 HIBC PAS를 인코딩하고 디코딩하는 방법을 보여줍니다.

```csharp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText; 
		HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
		Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

### 또 보기

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


