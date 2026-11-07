---
title: "Aspose::BarCode::License класс"
linktitle: "Лицензия"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::License класс. Предоставляет методы лицензирования компонента в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.barcode/license/
---
## License class


Предоставляет методы для лицензирования компонента.

```cpp
class License : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [License](./license/)() | Инициализирует новый экземпляр этого класса. |
| [SetLicense](./setlicense/)(System::String) | Лицензирует библиотеку. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | Лицензирует библиотеку. |
## Примечания


В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.
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

## См. также

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
