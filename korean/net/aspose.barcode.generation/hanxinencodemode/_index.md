---
title: "열거형 HanXinEncodeMode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.HanXinEncodeMode 열거형. 한신 코드 인코딩 모드입니다. ASCII/중국어 문자에는 Auto를, 유니코드 문자에는 Unicode를 사용하는 것이 권장됩니다."
type: docs
weight: 1360
url: /ko/net/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enumeration

Han Xin Code 인코딩 모드. ASCII/중국어 문자 또는 유니코드 문자의 경우 Auto를 사용하는 것이 권장됩니다.

```csharp
public enum HanXinEncodeMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자는 HanXin 바코드 사양에 따라 GB18030 인코딩을 사용해 인코딩됩니다. |
| Binary | `1` | Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다. |
| ECI | `2` | ECI 모드에서는 전체 메시지가 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. 일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있습니다. |
| Unicode | `3` | Unicode 모드는 Han Xin 코드에서 UTF8 인코딩/문자 집합을 참조하여 모든 텍스트 데이터를 표현하는 방법을 설계합니다. |
| URI | `4` | URI 모드는 Han Xin 코드에 표시되는 데이터가 RFC 3986에 정의된 통합 자원 식별자(URI)임을 나타냅니다. |
| Extended | `5` | Extended 모드는 내부 모드들의 조합을 허용합니다: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. 코드텍스트는 접두사와 이중 백슬래시를 사용해 수동으로 구축할 수 있습니다, 예: @\"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c\" 또는 HanXinExtCodetextBuilder를 사용합니다. 코드텍스트에 ECI 조각이 포함된 경우, 그 이후에는 다음 모드만 사용할 수 있습니다: Auto, Binary, Text, Numeric, URI, ECI. |

## 예제

```csharp
[C#]
// Auto 모드
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Binary 모드
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// ECI 모드
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Unicode 모드
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// URI 모드
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Extended 모드
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Extended 모드에 HanXinExtCodetextBuilder 사용 (이전 예와 동일한 코드텍스트)
//코덱텍스트 생성
var codeTextBuilder = new HanXinExtCodetextBuilder();
codeTextBuilder.AddGB18030TwoByte("漄");
codeTextBuilder.AddGB18030FourByte("㐁");
codeTextBuilder.AddCommonChineseRegionOne("全");
codeTextBuilder.AddCommonChineseRegionTwo("螅");
codeTextBuilder.AddNumeric("123");
codeTextBuilder.AddText("qwe");
codeTextBuilder.AddUnicode("ıntəˈnæʃənəl");
codeTextBuilder.AddECI("ΑΒΓΔΕ", 9);
codeTextBuilder.AddAuto("abc");
codeTextBuilder.AddBinary("abc");
codeTextBuilder.AddURI(@"backslashes_should_be_doubled\000555:test");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

//코덱텍스트 생성
var str = codeTextBuilder.GetExtendedCodetext();

//생성
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


