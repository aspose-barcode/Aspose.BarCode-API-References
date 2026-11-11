---
title: "클래스 GS1DigitalLink"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink 클래스. 애플리케이션 식별자 요소들의 순서가 지정된 시퀀스로 인코딩 및 디코딩하기 위한 GS1 Digital Link 코드텍스트를 나타냅니다. 원본 순서와 반복되는 애플리케이션 식별자는 보존됩니다. 구성된 코드텍스트는 압축되지 않은 GS1 Digital Link URI입니다. 파싱 시 NonGS1 쿼리 매개변수와 URI 조각은 무시됩니다."
type: docs
weight: 540
url: /ko/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

GS1 Digital Link 코드텍스트를 인코딩 및 디코딩하기 위해 Application Identifier 요소들의 순서가 지정된 시퀀스로 나타냅니다. 원본 순서와 반복되는 Application Identifier가 보존됩니다. 구성된 코드텍스트는 압축되지 않은 GS1 Digital Link URI입니다. 파싱 시 비-GS1 쿼리 매개변수와 URI 조각은 무시됩니다.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | 지정된 URI 스템으로 빈 GS1 Digital Link를 초기화합니다. 기본 키 후보가 정확히 하나만 존재할 경우 기본 키가 자동으로 선택됩니다. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | 지정된 URI 스템과 기본 키로 빈 GS1 Digital Link를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | 이 GS1 디지털 링크를 인코딩하는 데 사용되는 바코드 유형을 가져오거나 설정합니다. 지원되는 유형은 QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF 및 Code128입니다. 기본값은 QR입니다. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Application Identifier 요소의 개수를 가져옵니다. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | 원본 순서대로 모든 요소의 복사본을 가져옵니다. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | 정렬된 시퀀스에서 위치에 따라 요소를 가져옵니다. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Digital Link 기본 키로 사용되는 Application Identifier를 가져옵니다. null은 URI가 구성될 때 기본 키가 자동으로 선택됨을 의미합니다. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | GS1 기본 키 경로 세그먼트 이전의 절대 URI 접두사를 가져옵니다. 이 스템에는 쿼리 문자열이나 프래그먼트가 포함되지 않습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | GS1 코덱스트에서 모든 요소를 복사하고 유일한 사용 가능한 기본 키를 선택하여 GS1 디지털 링크를 생성합니다. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | GS1 코덱스트에서 모든 요소를 복사하고 지정된 기본 키를 사용하여 GS1 디지털 링크를 생성합니다. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | 압축되지 않은 GS1 디지털 링크 URI를 구문 분석합니다. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | 검증된 Application Identifier 요소를 추가합니다. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | 원본 순서대로 Application Identifier의 모든 값을 가져옵니다. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | 이 GS1 디지털 링크를 인코딩하는 데 사용되는 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | 압축되지 않은 GS1 디지털 링크 URI를 구성합니다. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Application Identifier의 첫 번째 값을 가져옵니다. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | 압축되지 않은 GS1 디지털 링크 URI에서 이 인스턴스를 초기화합니다. 제공된 URI가 성공적으로 구문 분석된 후에만 기존 상태가 교체됩니다. 선택된 바코드 유형은 유지됩니다. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | 현재 GS1 요소를 포함하는 독립적인 GS1 코덱스트를 생성합니다. URI 전용 정보는 포함되지 않습니다. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | 압축되지 않은 GS1 디지털 링크 URI를 반환합니다. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | 현재 객체 상태를 압축되지 않은 GS1 디지털 링크 URI로 포맷합니다. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | 압축되지 않은 GS1 디지털 링크 URI를 구문 분석하려 시도하고 구조화된 검증 오류를 반환합니다. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | 객체를 생성하지 않고 압축되지 않은 GS1 디지털 링크 URI를 검증합니다. |

### 또 보기

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


