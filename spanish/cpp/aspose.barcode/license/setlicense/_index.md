---
title: "método"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Licencia la biblioteca en C++."
type: docs
weight: 200
url: /es/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


Licencia la biblioteca.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseName | System::String | Puede ser un nombre de archivo completo o corto, o el nombre de un recurso incrustado. |
## Observaciones


Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

2. La carpeta que contiene el ensamblado del componente **Aspose**.

3. La carpeta que contiene el ensamblado de llamada del cliente.

4. La carpeta que contiene el ensamblado de entrada (inicio).

5. Un recurso incrustado en el ensamblado de llamada del cliente.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ruta explícita.

2. Un recurso incrustado en el ensamblado de llamada del cliente.

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama.
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


## Ver también

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Licencia la biblioteca.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Un flujo que contiene la licencia. |
## Observaciones



Utilice este método para cargar una licencia desde un flujo.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## Ver también

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
