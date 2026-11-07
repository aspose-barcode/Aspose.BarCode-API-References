---
title: "Aspose::BarCode::LicenseCore класс"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::LicenseCore класс. Класс, который читает и реализует лицензию в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


Класс, который читает и реализует лицензию

```cpp
class LicenseCore : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | Кодирует данные в подпись |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | Пытается найти имя файла в папке сборки |
| [LicenseCore](./licensecore/)() | Инициализирует новый экземпляр класса [LicenseCore](./). |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | Метод сбрасывает состояние лицензии для внутреннего использования и тестов |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Ищет лицензию, загружает её и пытается реализовать. Результат реализации устанавливается в errorCode |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Пытается реализовать лицензию. Результат реализации устанавливается в errorCode |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## См. также

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
