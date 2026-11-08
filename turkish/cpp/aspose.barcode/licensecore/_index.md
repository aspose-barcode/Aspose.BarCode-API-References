---
title: "Aspose::BarCode::LicenseCore sınıfı"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::LicenseCore sınıfı. C++'ta lisansı okuyan ve uygulayan sınıf."
type: docs
weight: 400
url: /tr/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


Lisansı okuyan ve uygulayan sınıf

```cpp
class LicenseCore : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | Verileri imzaya kodlar |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | Derleme klasöründe dosya adını bulmaya çalışır |
| [LicenseCore](./licensecore/)() | Yeni bir [LicenseCore](./) sınıf örneği başlatır. |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | Yöntem, lisans durumunu dahili kullanım ve testler için sıfırlar |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Lisansı arar, yükler ve uygulamaya çalışır. Uygulamanın sonucu errorCode değişkenine ayarlanır. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Lisansı uygulamaya çalışır. Uygulamanın sonucu errorCode değişkenine ayarlanır. |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
