---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

4-state Royal Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.

MailmarkCodetext 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| MailmarkCodetext() | MailmarkCodetext 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| format | "0" – Null 또는 테스트<br/>            "1" – Letter<br/>            "2" – Large Letter |
| version_id | 현재 "1" – Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 예약됨) |
| klass | "0" - Null 또는 테스트<br/>            "1" - 1C (소매)<br/>            "2" - 2C (소매)<br/>            "3" - 3C (소매)<br/>            "4" - Premium (RetailPublishing Mail) (잠재적 향후 사용을 위해)<br/>            "5" - Deferred (소매)<br/>            "6" - Air (소매) (잠재적 향후 사용을 위해)<br/>            "7" - Surface (소매) (잠재적 향후 사용을 위해)<br/>            "8" - Premium (네트워크 액세스)<br/>            "9" - Standard (네트워크 액세스) |
| supply_chain_id | Barcode C는 최대 99, Barcode L은 최대 999999입니다. |
| item_id | 최대 값은 99999999입니다. |
| destination_post_code_and_dps | PC와 DP는 PAF 형식을 준수해야 합니다.<br/>            국제 "XY11     "을 나타내는 9자 문자열(뒤에 5개의 공백에 유의) 또는 패턴<br/>            국내 정렬 코드를 나타내는 문자들.<br/>            국내 정렬 코드는 외부 우편번호, 내부 우편번호 및 Delivery Point Suffix로 구성됩니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| get_constructed_codetext() | Mailmark 데이터에서 코드 텍스트를 구성합니다. |
| init_from_string(constructed_codetext) | 구성된 코드 텍스트에서 Mailmark 데이터를 초기화합니다. |
| get_barcode_type() | 바코드 유형을 가져옵니다. |

### 또 보기

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

