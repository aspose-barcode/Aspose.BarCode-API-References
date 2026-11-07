---
title: "method"
linktitle: "SetLicense"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Лицензирует библиотеку в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


Лицензирует библиотеку.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| licenseName | System::String | Может быть полным или коротким именем файла или именем встроенного ресурса. |
## Примечания


Пытается найти лицензию в следующих местах:

1. Явный путь.

2. Папка, содержащая сборку компонента **Aspose**.

3. Папка, содержащая вызывающую сборку клиента.

4. Папка, содержащая входную (запускную) сборку.

5. Встроенный ресурс в вызывающей сборке клиента.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Явный путь.

2. Встроенный ресурс в вызывающей сборке клиента.

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
@endverbatim
```


## См. также

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Лицензирует библиотеку.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Поток, содержащий лицензию. |
## Примечания



Используйте этот метод для загрузки лицензии из потока.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## См. также

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
