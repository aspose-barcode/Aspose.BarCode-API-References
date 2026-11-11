---
title: "클래스 MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeStructuredCodetext 클래스. 모드 2 및 3용 MaxiCode 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스"
type: docs
weight: 740
url: /ko/net/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class

모드 2 및 3용 MaxiCode 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 기본 클래스입니다.

```csharp
public abstract class MaxiCodeStructuredCodetext : MaxiCodeCodetext
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CountryCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/countrycode/) { get; set; } | 3자리 국가 코드를 식별합니다. |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | ECI 인코딩을 가져오거나 설정합니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | MaxiCode 인코드 모드를 가져오거나 설정합니다. 기본값: Auto. |
| [PostalCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/postalcode/) { get; set; } | 우편 번호를 식별합니다. 모드 2에서는 9자리 숫자여야 하며, 모드 3에서는 6개의 영숫자 기호여야 합니다. |
| [SecondMessage](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/secondmessage/) { get; set; } | 바코드의 두 번째 메시지를 식별합니다. |
| [ServiceCategory](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/servicecategory/) { get; set; } | 3자리 서비스 카테고리를 식별합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/equals/)(object) | 이 인스턴스가 지정된 `MaxiCodeStructuredCodetext` 값과 동일한지 여부를 나타내는 값을 반환합니다. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | 바코드 유형을 가져옵니다. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/getconstructedcodetext/)() | 코드텍스트를 구성합니다. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | MaxiCode 모드를 가져옵니다. |
| override [InitFromString](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/initfromstring/)(string) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |

## 예제

이 샘플은 원시 MaxiCode 코드텍스트를 MaxiCodeStructuredCodetext 인스턴스로 디코딩하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

### 또 보기

* class [MaxiCodeCodetext](../maxicodecodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


