---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix 매개변수.

DataMatrixParameters 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| ecc_type | Datamatrix ECC 유형을 가져오거나 설정합니다.<br/>            기본값: DataMatrixEccType.Ecc200. |
| version | Datamatrix 심볼 크기를 가져오거나 설정합니다.<br/>            기본값: Version.Auto. |
| encode_mode | Datamatrix 바코드의 인코드 모드.<br/>            기본값: EncodeMode.Auto. |
| structured_append_barcode_id | Datamatrix 바코드의 Structured Append 모드에 대한 바코드 ID.<br/>            기본값: 0 |
| structured_append_barcodes_count | Datamatrix 바코드의 Structured Append 모드에 대한 바코드 수.<br/>            기본값: 0 |
| structured_append_file_id | Datamatrix 바코드의 Structured Append 모드에 대한 파일 ID.<br/>            기본값: 0 |
| is_reader_programming | 리더가 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.<br/>            기본값: false |
| macro_characters | 매크로 문자 05 및 06 값은 특수 모드에서 보다 압축된 인코딩을 얻는 데 사용됩니다.<br/>            DataMatrixEccType.Ecc200 또는 DataMatrixEccType.EccAuto와 함께만 사용할 수 있습니다.<br/>            EncodeTypes.GS1DataMatrix와 함께 사용할 수 없습니다.<br/>            기본값: MacroCharacters.None. |
| aspect_ratio | 2D 바코드 모듈의 높이/너비 비율. |
| eci_encoding | ECI 인코딩을 가져오거나 설정합니다. EncodeMode가 Auto일 때 사용됩니다.<br/>            기본값: ISO-8859-1 |

### 또 보기

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

