---
title: "메서드"
linktitle: "SetMeteredKey"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. 계량형 public 및 private 키를 설정합니다. 계량형 라이선스를 구매한 경우 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. 그러나 사용량 데이터를 업로드하는 데 계속 실패하고 24시간을 초과하면 라이선스가 평가 상태로 전환됩니다. 이러한 상황을 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 C++에서 이 API를 다시 호출해야 합니다."
type: docs
weight: 200
url: /ko/cpp/aspose.barcode/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


계량 라이선스를 구매한 경우, 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. 그러나 소비 데이터를 업로드하는 데 계속 실패하고 24시간을 초과하면 라이선스가 평가 상태로 설정됩니다. 이러한 경우를 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 다시 이 API를 호출해야 합니다.

```cpp
void Aspose::BarCode::Metered::SetMeteredKey(System::String publicKey, System::String privateKey)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| publicKey | System::String | public 키 |
| privateKey | System::String | private 키 |

## 또 보기

* Class [Metered](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
