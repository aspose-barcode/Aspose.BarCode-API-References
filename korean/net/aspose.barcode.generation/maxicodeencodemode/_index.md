---
title: MaxiCodeEncodeMode
second_title: .NET API 참조용 Aspose.BarCode
description: MaxiCode 바코드용 인코딩 모드.
type: docs
weight: 1030
url: /ko/net/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enumeration

MaxiCode 바코드용 인코딩 모드.

```csharp
public enum MaxiCodeEncodeMode
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | ECIEncoding 속성에 설정된 값으로 코드 텍스트를 인코딩합니다. |
| Bytes | `1` | 일반 바이트로 코드 텍스트를 인코딩합니다. 유니코드 문자를 감지하면 문자가 2바이트로 인코딩되며 낮은 바이트부터 시작됩니다. |
| ExtendedCodetext | `2` | 다중 ECI 모드를 지원하는 확장 모드. |

### 예

```csharp
[C#]
//자동 모드
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//바이트 모드
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };

//배열을 문자열로 인코딩
StringBuilder strBld = new StringBuilder();
foreach (byte bval in encodedArr)
    strBld.Append((char) bval);
var codetext = strBld.ToString();

using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Bytes;
    generator.Save("test.bmp");
}

//확장 코드텍스트 모드
//코드텍스트 생성
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//코드 텍스트 생성
string codetext = textBuilder.GetExtendedCodetext();    

//생성하다
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### 또한보십시오

* 네임스페이스 [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->