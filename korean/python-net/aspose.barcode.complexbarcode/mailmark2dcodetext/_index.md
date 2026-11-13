---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Royal Mail 2D Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.

Mailmark2DCodetext 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| Mailmark2DCodetext() | Mailmark2DCodetext 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| upu_country_id | UPU 국가 ID를 식별합니다. 최대 길이: 4자. |
| information_type_id | 각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다. |
| version_id | 각 Information Type ID와 관련된 바코드 버전을 식별합니다. |
| klass | 항목의 클래스를 식별합니다. |
| supply_chain_id | 메일링에 참여하는 고유 고객 그룹을 식별합니다.<br/>            최대값: 9999999. |
| item_id | Supply Chain ID 내에서 고유 항목을 식별합니다.<br/>            모든 Mailmark 바코드에는 ID가 포함되어야 하며<br/>            최소 90일 동안 고유하게 식별될 수 있습니다.<br/>            최대값: 99999999. |
| destination_post_code_and_dps | 배송 주소의 우편번호와 DPS를 포함합니다.<br/>            내륙인 경우 우편번호/DP는 다음과 같은 문자 수를 가집니다.<br/>            지역 (1~2자) 구역(1~2자)<br/>            섹터(1자) 유닛(2자) DPS(2자).<br/>            우편번호와 DPS는 유효한 PAF® 형식을 따라야 합니다. |
| rts_flag | 요청된 반송 서비스 수준을 나타내는 플래그입니다. |
| return_to_sender_post_code | 반송 우편 코드를 포함하지만 DPS는 포함하지 않습니다.<br/>            DPS가 없는 PC는 PAF® 형식을 따라야 합니다. |
| customer_content | 고객이 사용할 수 있는 선택적 공간입니다. |
| customer_content_encode_mode | Datamatrix 바코드의 인코드 모드입니다.<br/>            기본값: EncodeMode.C40. |
| data_matrix_type | 2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| get_constructed_codetext() | Mailmark 데이터에서 코드 텍스트를 구성합니다. |
| init_from_string(constructed_codetext) | 구성된 코드 텍스트에서 Mailmark 데이터를 초기화합니다. |
| get_barcode_type() | 바코드 유형을 가져옵니다. |

### 또 보기

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

