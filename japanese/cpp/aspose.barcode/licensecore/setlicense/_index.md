---
title: "メソッド"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。ライセンスを検索し、ロードして実装しようとします。実装結果は C++ で errorCode に設定されます。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


ライセンスを検索し、ロードして実装しようとします。実装の結果は errorCode に設定されます

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| licenseName | System::String | 完全なファイル名または短いファイル名、あるいは埋め込みリソースの名前にすることができます。 |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | 検索パスを見つけるための呼び出し元アセンブリ |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | ライセンス状態と、可能なエラーメッセージのための追加情報を格納するエラーコード |

## 関連項目

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


ライセンスの実装を試みます。実装の結果は errorCode に設定されます

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | 保存されたライセンスを含むストリーム |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | ライセンス状態と、可能なエラーメッセージのための追加情報を格納するエラーコード |

## 関連項目

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
