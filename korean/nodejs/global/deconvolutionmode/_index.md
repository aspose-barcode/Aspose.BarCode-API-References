---
title: "DeconvolutionMode"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "Deconvolution(이미지 복원) 모드는 이미지 손상 정도를 정의합니다."
type: docs
weight: 220
url: /ko/nodejs/global/deconvolutionmode/
---

## DeconvolutionMode

Deconvolution(이미지 복원) 모드는 이미지 손상 정도를 정의합니다. 원래 Deconvolution은 흐림과 같은 자연 함수에 의해 손상된(컨볼루션된) 이미지를 복원할 수 있는 함수입니다. 카메라로 이미지를 얻는 동안 발생합니다. 이미지 손상을 일으키는 함수를 알 수 없기 때문에, 우리는 일반적으로 알려진 함수인 샤프 또는 수학적 형태학을 확인해야 합니다. 이 샘플은 Deconvolution 모드를 사용하는 방법을 보여줍니다 let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setDeconvolution(DeconvolutionMode.SLOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## 값

| 이름 | 설명 |
| --- | --- |
| ISO_8859_1 | ISO/IEC 8859-1 라틴 알파벳 1번 인코딩. ECI Id:"\000003" |
| ISO_8859_2 | ISO/IEC 8859-2 라틴 알파벳 2번 인코딩. ECI Id:"\000004" |
| ISO_8859_3 | ISO/IEC 8859-3 라틴 알파벳 3번 인코딩. ECI Id:"\000005" |
| ISO_8859_4 | ISO/IEC 8859-4 라틴 알파벳 4번 인코딩. ECI Id:"\000006" |
| ISO_8859_5 | ISO/IEC 8859-5 라틴/키릴 알파벳 인코딩. ECI Id:"\000007" |
| ISO_8859_6 | ISO/IEC 8859-6 라틴/아라비아 알파벳 인코딩. ECI Id:"\000008" |
| ISO_8859_7 | ISO/IEC 8859-7 라틴/그리스 알파벳 인코딩. ECI Id:"\000009" |
| ISO_8859_8 | ISO/IEC 8859-8 라틴/히브리 알파벳 인코딩. ECI Id:"\000010" |
| ISO_8859_9 | ISO/IEC 8859-9 라틴 알파벳 5번 인코딩. ECI Id:"\000011" |
| ISO_8859_10 | ISO/IEC 8859-10 라틴 알파벳 6번 인코딩. ECI Id:"\000012" |
| ISO_8859_11 | ISO/IEC 8859-11 라틴/태국 알파벳 인코딩. ECI Id:"\000013" |
| ISO_8859_13 | ISO/IEC 8859-13 라틴 알파벳 7번 (발트 해안) 인코딩. ECI Id:"\000015" |
| ISO_8859_14 | ISO/IEC 8859-14 라틴 알파벳 No. 8 (Celtic) 인코딩. ECI Id:"\000016" |
| ISO_8859_15 | ISO/IEC 8859-15 라틴 알파벳 No. 9 인코딩. ECI Id:"\000017" |
| ISO_8859_16 | ISO/IEC 8859-16 라틴 알파벳 No. 10 인코딩. ECI Id:"\000018" |
| Shift_JIS | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) 인코딩. ECI Id:"\000020" |
| Win1250 | Windows 1250 라틴 2 (중부 유럽) 인코딩. ECI Id:"\000021" |
| Win1251 | Windows 1251 키릴 문자 인코딩. ECI Id:"\000022" |
| Win1252 | Windows 1252 라틴 1 인코딩. ECI Id:"\000023" |
| Win1256 | Windows 1256 아라비아어 인코딩. ECI Id:"\000024" |
| UTF16BE | ISO/IEC 10646 UCS-2 (고위 바이트 우선) 인코딩. ECI Id:"\000025" |
| UTF8 | ISO/IEC 10646 UTF-8 인코딩. ECI Id:"\000026" |
| US_ASCII | ISO/IEC 646:1991 ISO 7비트 부호 문자 집합 인코딩의 국제 참조 버전. ECI Id:"\000027" |
| Big5 | Big 5 (Taiwan) 중국 문자 집합 인코딩. ECI Id:"\000028" |
| GB2312 | GB (PRC) 중국 문자 집합 인코딩. ECI Id:"\000029" |
| EUC_KR | 한국어 문자 집합 인코딩. ECI Id:"\000030" |
| GBK | GBK (GB2312의 간체 중국어 확장) 인코딩. ECI Id:"\000031" |
| GB18030 | GGB18030 중국 문자 집합 인코딩. ECI Id:"\000032" |
| UTF16LE | ISO/IEC 10646 UTF-16LE 인코딩. ECI Id:"\000033" |
| UTF32BE | ISO/IEC 10646 UTF-32BE 인코딩. ECI Id:"\000034" |
| UTF32LE | ISO/IEC 10646 UTF-32LE 인코딩. ECI Id:"\000035" |
| INVARIANT | ISO/IEC 646: ISO 7비트 부호 문자 집합 - 불변 문자 집합 인코딩. ECI Id:"\000170" |
| 바이너리 | 8비트 바이너리 데이터. ECI Id:"\000899" |
| NONE | 확장 채널 해석 없음 |
