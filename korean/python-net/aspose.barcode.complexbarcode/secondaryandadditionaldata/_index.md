---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

HIBC LIC 보조 및 추가 데이터를 저장하기 위한 클래스.

SecondaryAndAdditionalData 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| SecondaryAndAdditionalData() | SecondaryAndAdditionalData 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| expiry_date_format | 만료 날짜 형식을 식별합니다. |
| expiry_date | 만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우에 사용됩니다. |
| lot_number | LOT 또는 배치 번호를 식별합니다. LOT/배치 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| serial_number | 시리얼 번호를 식별합니다. 시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| date_of_manufacture | 제조 날짜를 식별합니다.<br/>            이 필드를 사용하지 않으려면 제조 날짜를 DateTime.MinValue 로 설정할 수 있습니다.<br/>            기본값: DateTime.MinValue |
| quantity | 수량을 식별합니다. 0에서 500 사이의 정수값이어야 합니다. <br/>            이 필드를 사용하지 않으려면 수량을 -1 로 설정할 수 있습니다.<br/>            기본값: -1 |
## 메서드
| 이름 | 설명 |
| :- | :- |
| parse_from_string(secondary_data_codetext) | HIBC LIC 사양에 따라 문자열 형식에서 2차 및 추가 보조 데이터를 인스턴스화합니다. |

### 또 보기

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

