---
title: "enum"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 열거형. Han Xin 코드 인코딩 모드입니다. C++에서는 ASCII/중국어 문자에 Auto를 사용하거나 유니코드 문자에 Unicode를 사용하는 것이 권장됩니다."
type: docs
weight: 6900
url: /ko/cpp/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enum


Han Xin Code 인코딩 모드. ASCII/중국어 문자와 함께 Auto를 사용하거나 유니코드 문자는 Unicode를 사용하는 것이 권장됩니다.

```cpp
enum class HanXinEncodeMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 자동 | 0 | Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자는 HanXin 바코드 사양에 따라 GB18030 인코딩을 사용해 인코딩됩니다. |
| 이진 | 1 | Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다. |
| ECI | 2 | ECI 모드에서는 전체 메시지가 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. 일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있다는 점에 유의하십시오. |
| Unicode | 3 | Unicode 모드는 Han Xin 코드에서 UTF8 인코딩/문자 집합을 참조하여 모든 텍스트 데이터를 표현하는 방법을 설계합니다. |
| URI | 4 | URI 모드는 Han Xin 코드에서 표현되는 데이터가 RFC 3986에 정의된 통합 자원 식별자(URI)임을 나타냅니다. |
| Extended | 5 | Extended 모드는 내부 모드들의 조합을 허용합니다: Auto, Binary, Text, Numeric, URI, Unicode, ECI, [Common](../../aspose.barcode.common/) Chinese Region One, [Common](../../aspose.barcode.common/) Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. 코드텍스트는 접두사와 이중 백슬래시를 사용해 수동으로 만들 수 있으며, 예: ":abc\000009:ΑΒΓΔΕ:ab\c" 또는 [HanXinExtCodetextBuilder](../hanxinextcodetextbuilder/)를 사용할 수 있습니다. 코드텍스트에 ECI 조각이 포함된 경우, 해당 ECI 조각 이후에는 다음 모드만 사용할 수 있습니다: Auto, Binary, Text, Numeric, URI, ECI. |

## 비고



```cpp
[C#]
// 자동 모드
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
//코드텍스트 생성
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

//코드텍스트 생성
var str = codeTextBuilder.GetExtendedCodetext();

//생성
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
