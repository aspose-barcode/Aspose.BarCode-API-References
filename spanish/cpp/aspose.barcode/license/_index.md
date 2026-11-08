---
title: "Clase Aspose::BarCode::License"
linktitle: "Licencia"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::License. Proporciona métodos para licenciar el componente en C++."
type: docs
weight: 300
url: /es/cpp/aspose.barcode/license/
---
## License class


Proporciona métodos para licenciar el componente.

```cpp
class License : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [License](./license/)() | Inicializa una nueva instancia de esta clase. |
| [SetLicense](./setlicense/)(System::String) | Licencia la biblioteca. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | Licencia la biblioteca. |
## Observaciones


En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama.
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

## Ver también

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
