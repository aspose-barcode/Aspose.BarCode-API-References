---
title: "Aspose::BarCode::License classe"
linktitle: "Licenza"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::License classe. Fornisce metodi per licenziare il componente in C++."
type: docs
weight: 300
url: /it/cpp/aspose.barcode/license/
---
## License class


Fornisce metodi per licenziare il componente.

```cpp
class License : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [License](./license/)() | Inizializza una nuova istanza di questa classe. |
| [SetLicense](./setlicense/)(System::String) | Licenzia la libreria. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | Licenzia la libreria. |
## Osservazioni


In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante.
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

## Vedi anche

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
