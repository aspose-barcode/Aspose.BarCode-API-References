---
title: "열거형 AztecEncodeMode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.AztecEncodeMode 열거형. Aztec 바코드의 인코딩 모드"
type: docs
weight: 940
url: /ko/net/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enumeration

Aztec 바코드의 인코딩 모드.

```csharp
public enum AztecEncodeMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자는 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. |
| Extended | `3` | 다중 ECI 모드를 지원하는 확장 모드. |
| Binary | `4` | Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다. |
| ECI | `5` | ECI 모드에서는 전체 메시지가 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. 일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있습니다. |

## 예제

```csharp
[C#]
//Auto 모드
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extended 모드
//코덱텍스트 생성
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//코덱텍스트 생성
string codetext = textBuilder.GetExtendedCodetext();    

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


