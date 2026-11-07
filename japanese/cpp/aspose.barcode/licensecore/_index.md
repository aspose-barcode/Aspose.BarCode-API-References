---
title: "Aspose::BarCode::LicenseCore クラス"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::LicenseCore クラス。C++ でライセンスを読み取り、実装するクラスです。"
type: docs
weight: 400
url: /ja/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


ライセンスを読み取り実装するクラス。

```cpp
class LicenseCore : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | データを署名にエンコードします |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | アセンブリ フォルダー内のファイル名を探します |
| [LicenseCore](./licensecore/)() | 新しい [LicenseCore](./) クラスのインスタンスを初期化します。 |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | メソッドは内部使用とテストのためにライセンス状態をリセットします |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | ライセンスを検索し、ロードして実装しようとします。実装の結果は errorCode に設定されます |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | ライセンスの実装を試みます。実装の結果は errorCode に設定されます |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## 関連項目

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
