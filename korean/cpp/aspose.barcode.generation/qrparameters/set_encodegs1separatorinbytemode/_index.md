---
title: "메서드"
linktitle: "set_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 Aspose::BarCode::Generation::QrParameters 클래스의 set_EncodeGS1SeparatorInByteMode 메서드를 사용하는 방법."
type: docs
weight: 1800
url: /ko/cpp/aspose.barcode.generation/qrparameters/set_encodegs1separatorinbytemode/
---
## QrParameters::set_EncodeGS1SeparatorInByteMode method




```cpp
void Aspose::BarCode::Generation::QrParameters::set_EncodeGS1SeparatorInByteMode(bool value)
```

## 비고


QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩해야 하는지 여부를 나타내는 값을 설정합니다.

false인 경우, QR 사양에 따라 GS1 구분자는 영숫자 모드에서 ''로 인코딩될 수 있습니다.

true인 경우, GS1 그룹 구분자는 0x1D 문자로 바이트 모드에서 인코딩되며, '' 문자도 데이터로 보존하기 위해 바이트 모드에서 인코딩됩니다.

이 옵션은 바이트 수준 GS1 그룹 구분자를 기대하는 디코더와의 호환성을 향상시킬 수 있으며, '' 데이터 문자가 GS1 구분자로 해석되는 것을 방지합니다.
## 또 보기

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
