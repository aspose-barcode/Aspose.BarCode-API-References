---
title: "열거형 ECIEncodings"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.ECIEncodings 열거형. 확장 채널 해석 식별자. 심볼의 데이터 인코딩에 사용된 참조에 대한 세부 정보를 바코드 리더에게 전달하는 데 사용됩니다."
type: docs
weight: 1270
url: /ko/net/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enumeration

Extended Channel Interpretation 식별자. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더에게 전달하는 데 사용됩니다.

```csharp
public enum ECIEncodings
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| ISO_8859_1 | `3` | ISO/IEC 8859-1 라틴 알파벳 No. 1 인코딩. ECI Id:"\\000003" |
| ISO_8859_2 | `4` | ISO/IEC 8859-2 라틴 알파벳 No. 2 인코딩. ECI Id:"\\000004" |
| ISO_8859_3 | `5` | ISO/IEC 8859-3 라틴 알파벳 No. 3 인코딩. ECI Id:"\\000005" |
| ISO_8859_4 | `6` | ISO/IEC 8859-4 라틴 알파벳 No. 4 인코딩. ECI Id:"\\000006" |
| ISO_8859_5 | `7` | ISO/IEC 8859-5 라틴/키릴 알파벳 인코딩. ECI Id:"\\000007" |
| ISO_8859_6 | `8` | ISO/IEC 8859-6 라틴/아라비아 알파벳 인코딩. ECI Id:"\\000008" |
| ISO_8859_7 | `9` | ISO/IEC 8859-7 라틴/그리스 알파벳 인코딩. ECI Id:"\\000009" |
| ISO_8859_8 | `10` | ISO/IEC 8859-8 라틴/히브리 알파벳 인코딩. ECI Id:"\\000010" |
| ISO_8859_9 | `11` | ISO/IEC 8859-9 라틴 알파벳 No. 5 인코딩. ECI Id:"\\000011" |
| ISO_8859_10 | `12` | ISO/IEC 8859-10 라틴 알파벳 No. 6 인코딩. ECI Id:"\\000012" |
| ISO_8859_11 | `13` | ISO/IEC 8859-11 라틴/태국 알파벳 인코딩. ECI Id:"\\000013" |
| ISO_8859_13 | `15` | ISO/IEC 8859-13 라틴 알파벳 No. 7 (Baltic Rim) 인코딩. ECI Id:"\\000015" |
| ISO_8859_14 | `16` | ISO/IEC 8859-14 라틴 알파벳 No. 8 (Celtic) 인코딩. ECI Id:"\\000016" |
| ISO_8859_15 | `17` | ISO/IEC 8859-15 라틴 알파벳 No. 9 인코딩. ECI Id:"\000017" |
| ISO_8859_16 | `18` | ISO/IEC 8859-16 라틴 알파벳 No. 10 인코딩. ECI Id:"\000018" |
| Shift_JIS | `20` | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) 인코딩. ECI Id:"\000020" |
| Win1250 | `21` | Windows 1250 라틴 2 (중부 유럽) 인코딩. ECI Id:"\000021" |
| Win1251 | `22` | Windows 1251 키릴 문자 인코딩. ECI Id:"\000022" |
| Win1252 | `23` | Windows 1252 라틴 1 인코딩. ECI Id:"\000023" |
| Win1256 | `24` | Windows 1256 아라비아어 인코딩. ECI Id:"\000024" |
| UTF16BE | `25` | ISO/IEC 10646 UCS-2 (고위 바이트 우선) 인코딩. ECI Id:"\000025" |
| UTF8 | `26` | ISO/IEC 10646 UTF-8 인코딩. ECI Id:"\000026" |
| US_ASCII | `27` | ISO/IEC 646:1991 국제 기준 버전 ISO 7비트 부호 문자 집합 인코딩. ECI Id:"\000027" |
| Big5 | `28` | Big 5 (대만) 중국어 문자 집합 인코딩. ECI Id:"\000028" |
| GB2312 | `29` | GB2312 중국어 문자 집합 인코딩. ECI Id:"\000029" |
| EUC_KR | `30` | 한국어 문자 집합 인코딩. ECI Id:"\000030" |
| GBK | `31` | GBK (간체 중국어용 GB2312 확장) 인코딩. ECI Id:"\000031" |
| GB18030 | `32` | GGB18030 중국어 문자 집합 인코딩. ECI Id:"\000032" |
| UTF16LE | `33` | ISO/IEC 10646 UTF-16LE 인코딩. ECI Id:"\000033" |
| UTF32BE | `34` | ISO/IEC 10646 UTF-32BE 인코딩. ECI Id:"\000034" |
| UTF32LE | `35` | ISO/IEC 10646 UTF-32LE 인코딩. ECI Id:"\000035" |
| INVARIANT | `170` | ISO/IEC 646: ISO 7비트 부호 문자 집합 - 불변 문자 집합 인코딩. ECI Id:"\000170" |
| BINARY | `899` | 8비트 바이너리 데이터. ECI Id:"\000899" |
| NONE | `0` | 확장 채널 해석 없음 |

## 예제

이 샘플은 ECI 인코딩을 사용하는 방법과 BarCode 이미지를 저장하는 방법을 보여줍니다.

```csharp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
[VB.NET]
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = "12345TEXT"
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding
    generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8
    generator.Save("test.png")
End Using
```

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


