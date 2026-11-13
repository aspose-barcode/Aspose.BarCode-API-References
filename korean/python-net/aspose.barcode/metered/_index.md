---
title: "Metered"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode/metered/
---

## Metered class

계량 키를 설정하는 메서드를 제공합니다.

Metered 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| Metered() | Metered 클래스의 새 인스턴스를 초기화합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| set_metered_key(public_key, private_key) | Metered 공개 및 개인 키를 설정합니다.<br/>            메터링 라이선스를 구매한 경우, 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. <br/>            그러나 소비 데이터 업로드에 계속 실패하고 24시간을 초과하면 라이선스가 평가 상태로 전환됩니다, <br/>            이러한 경우를 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 이 API를 다시 호출해야 합니다. |
| get_consumption_quantity() | 소비 파일 크기를 가져옵니다 |
| get_consumption_credit() | 소비 크레딧을 가져옵니다 |
| get_product_name() | 라이선스된 제품의 이름을 가져옵니다 |
| is_metered_licensed() | Metered가 라이선스되었는지 확인합니다 |

### 또 보기

* namespace [aspose.barcode](/barcode/python-net/aspose.barcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

