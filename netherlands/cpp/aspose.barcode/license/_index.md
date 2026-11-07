---
title: "Aspose::BarCode::License klasse"
linktitle: "Licentie"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::License klasse. Biedt methoden om het component te licentiëren in C++."
type: docs
weight: 300
url: /nl/cpp/aspose.barcode/license/
---
## License class


Biedt methoden om het component te licentiëren.

```cpp
class License : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [License](./license/)() | Initialiseert een nieuw exemplaar van deze klasse. |
| [SetLicense](./setlicense/)(System::String) | Licentieert de bibliotheek. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | Licentieert de bibliotheek. |
## Opmerkingen


In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die het component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde resources van de aanroepende assembly.
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

## Zie ook

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
