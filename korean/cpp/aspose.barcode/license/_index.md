---
title: "Aspose::BarCode::License 클래스"
linktitle: "라이선스"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::License 클래스. C++에서 구성 요소에 라이선스를 적용하는 메서드를 제공합니다."
type: docs
weight: 300
url: /ko/cpp/aspose.barcode/license/
---
## License class


구성 요소에 라이선스를 적용하는 메서드를 제공합니다.

```cpp
class License : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [License](./license/)() | 이 클래스의 새 인스턴스를 초기화합니다. |
| [SetLicense](./setlicense/)(System::String) | 라이브러리에 라이선스를 적용합니다. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | 라이브러리에 라이선스를 적용합니다. |
## 비고


이 예제에서는 구성 요소가 포함된 폴더, 호출 어셈블리가 포함된 폴더, 진입 어셈블리 폴더, 그리고 호출 어셈블리의 임베디드 리소스에서 MyLicense.lic 라는 라이선스 파일을 찾으려고 시도합니다.
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
@endverbatim
```

## 또 보기

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
