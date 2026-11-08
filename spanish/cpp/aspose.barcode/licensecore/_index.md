---
title: "Aspose::BarCode::LicenseCore clase"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::LicenseCore clase. Clase que lee e implementa la licencia en C++."
type: docs
weight: 400
url: /es/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


Clase que lee e implementa la licencia.

```cpp
class LicenseCore : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | Codifica datos a firma |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | Intenta encontrar el nombre de archivo en la carpeta assebly |
| [LicenseCore](./licensecore/)() | Inicializa una nueva instancia de la clase [LicenseCore](./). |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | El método restablece el estado de la licencia para uso interno y pruebas. |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Busca la licencia, la carga e intenta implementarla. El resultado de la implementación se asigna a errorCode. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Intenta implementar la licencia. El resultado de la implementación se asigna a errorCode. |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## Ver también

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
