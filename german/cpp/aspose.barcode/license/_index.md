---
title: "Aspose::BarCode::License Klasse"
linktitle: "Lizenz"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::License Klasse. Stellt Methoden bereit, um die Komponente in C++ zu lizenzieren."
type: docs
weight: 300
url: /de/cpp/aspose.barcode/license/
---
## License class


Stellt Methoden zur Lizenzierung der Komponente bereit.

```cpp
class License : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [License](./license/)() | Initialisiert eine neue Instanz dieser Klasse. |
| [SetLicense](./setlicense/)(System::String) | Lizenziert die Bibliothek. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | Lizenziert die Bibliothek. |
## Hinweise


In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Entry-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.
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

## Siehe auch

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
