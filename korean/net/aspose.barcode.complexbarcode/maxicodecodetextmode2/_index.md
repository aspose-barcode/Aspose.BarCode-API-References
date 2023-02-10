---
title: MaxiCodeCodetextMode2
second_title: .NET API 참조용 Aspose.BarCode
description: 모드 2. 에 대한 MaxiCode 코드에 포함된 텍스트 인코딩 및 디코딩을 위한 클래스
type: docs
weight: 510
url: /ko/net/aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
## MaxiCodeCodetextMode2 class

모드 2. 에 대한 MaxiCode 코드에 포함된 텍스트 인코딩 및 디코딩을 위한 클래스

```csharp
public class MaxiCodeCodetextMode2 : MaxiCodeStructuredCodetext
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MaxiCodeCodetextMode2](maxicodecodetextmode2/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CountryCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/countrycode/) { get; set; } | 3자리 국가 코드를 식별합니다. |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | ECI 인코딩을 가져오거나 설정합니다. MaxiCodeEncodeMode가 Auto일 때 사용. 기본값: ISO-8859-1 |
| [MaxiCodeEncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/maxicodeencodemode/) { get; set; } | MaxiCode 인코딩 모드를 가져오거나 설정합니다. 기본값: Auto. |
| [PostalCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/postalcode/) { get; set; } | 우편 번호를 식별합니다. 모드 2에서 9자리 숫자 또는 모드 3에서 6개의 영숫자 기호여야 합니다. |
| [SecondMessage](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/secondmessage/) { get; set; } | 바코드의 두 번째 메시지를 식별합니다. |
| [ServiceCategory](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/servicecategory/) { get; set; } | 3자리 서비스 범주를 식별합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/equals/)(object) | 이 인스턴스가 지정된 것과 같은지 여부를 나타내는 값을 반환합니다.[`MaxiCodeStructuredCodetext`](../maxicodestructuredcodetext/) 값. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | 바코드 유형을 가져옵니다. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/getconstructedcodetext/)() | codetext 구성 |
| override [GetHashCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetextmode2/getmode/)() | MaxiCode 모드를 가져옵니다. |
| override [InitFromString](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/initfromstring/)(string) | 구성된 코드 텍스트에서 인스턴스를 초기화합니다. |

### 예

이 샘플은 모드 2. 에 대한 MaxiCode 코드 텍스트를 인코딩 및 디코딩하는 방법을 보여줍니다.

```csharp
[C#]
// 표준 두 번째 메시지가 있는 모드 2
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandartSecondMessage maxiCodeStandartSecondMessage = new MaxiCodeStandartSecondMessage();
maxiCodeStandartSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandartSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//구조화된 두 번째 메시지가 있는 모드 2
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//표준 두 번째 메시지로 원시 코드 텍스트 디코딩
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStandartSecondMessage){
                MaxiCodeStandartSecondMessage secondMessage = (MaxiCodeStandartSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message: " + secondMessage.Message);
            }
        }
    }
}
// 구조화된 두 번째 메시지로 원시 코드 텍스트 디코딩
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStructuredSecondMessage){
                MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message:");
                foreach (var identifier in secondMessage.Identifiers){
                    Console.WriteLine(identifier);
                }
            }
        }
    }
}
```

### 또한보십시오

* class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* 네임스페이스 [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
