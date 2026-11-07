---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "enum. DataMatrix 인코더의 인코딩 모드이며, C++에서 기본값은 Auto입니다."
type: docs
weight: 6300
url: /ko/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


DataMatrix 인코더의 인코딩 모드, 기본값은 Auto

```cpp
enum class DataMatrixEncodeMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 자동 | 0 | Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자는 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. |
| ASCII | 1 | 바이트당 하나의 영숫자 또는 두 개의 숫자 문자를 인코딩합니다. |
| C40 | 8 | C40 인코딩을 사용합니다. 대문자 영숫자, 소문자 및 특수 문자를 인코딩합니다. |
| 텍스트 | 9 | Text 인코딩을 사용합니다. 소문자 영숫자, 대문자 및 특수 문자를 인코딩합니다. |
| EDIFACT | 10 | EDIFACT 인코딩을 사용합니다. 문자당 6비트를 사용하며, 숫자, 대문자 및 다양한 구두점을 인코딩하지만 소문자는 지원하지 않습니다. |
| ANSIX12 | 11 | ANSI X12 인코딩을 사용합니다. |
| 확장 | 13 |  |
| Base256 | 14 | 8비트 값을 인코딩합니다. |
| 이진 | 15 | Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다. |
| ECI | 16 | ECI 모드에서는 전체 메시지가 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. 일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있다는 점에 유의하십시오. |

## 비고


이 샘플은 확장 모드에서 코드텍스트를 사용하는 방법을 보여줍니다.
```cpp
[C#]
//자동 모드
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//바이트 모드
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//확장 코드텍스트 모드
//코드텍스트 생성
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//코드텍스트 생성
string codetext = textBuilder.GetExtendedCodetext();

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
