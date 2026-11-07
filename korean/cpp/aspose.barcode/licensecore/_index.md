---
title: "Aspose::BarCode::LicenseCore 클래스"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::LicenseCore 클래스. C++에서 라이선스를 읽고 구현하는 클래스."
type: docs
weight: 400
url: /ko/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


라이선스를 읽고 구현하는 클래스.

```cpp
class LicenseCore : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | 데이터를 서명으로 인코딩합니다. |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | assebly 폴더에서 파일 이름을 찾으려고 시도합니다. |
| [LicenseCore](./licensecore/)() | 새로운 [LicenseCore](./) 클래스 인스턴스를 초기화합니다. |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | 메서드는 내부 사용 및 테스트를 위해 라이선스 상태를 재설정합니다. |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | 라이선스를 검색하고 로드한 뒤 구현을 시도합니다. 구현 결과는 errorCode에 설정됩니다. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | 라이선스를 구현하려고 시도합니다. 구현 결과는 errorCode에 설정됩니다. |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## 또 보기

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
