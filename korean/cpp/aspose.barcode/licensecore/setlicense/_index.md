---
title: "메서드"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. 라이선스를 검색하고, 로드하며 구현을 시도합니다. 구현 결과는 C++에서 errorCode에 설정됩니다."
type: docs
weight: 300
url: /ko/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


라이선스를 검색하고 로드한 뒤 구현을 시도합니다. 구현 결과는 errorCode에 설정됩니다.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| licenseName | System::String | 전체 파일 이름이거나 짧은 파일 이름, 혹은 포함된 리소스의 이름일 수 있습니다. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | 검색 경로를 찾기 위한 호출 어셈블리 |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | 라이선스 상태와 가능한 오류 메시지를 위한 추가 정보를 저장하는 오류 코드 |

## 또 보기

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


라이선스를 구현하려고 시도합니다. 구현 결과는 errorCode에 설정됩니다.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | 저장된 라이선스가 있는 스트림 |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | 라이선스 상태와 가능한 오류 메시지를 위한 추가 정보를 저장하는 오류 코드 |

## 또 보기

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
