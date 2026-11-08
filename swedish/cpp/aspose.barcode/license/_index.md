---
title: "Aspose::BarCode::License klass"
linktitle: "License"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::License klass. Tillhandahåller metoder för att licensiera komponenten i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.barcode/license/
---
## License class


Tillhandahåller metoder för att licensiera komponenten.

```cpp
class License : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [License](./license/)() | Initierar en ny instans av denna klass. |
| [SetLicense](./setlicense/)(System::String) | Licensierar biblioteket. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | Licensierar biblioteket. |
## Anmärkningar


I det här exemplet kommer ett försök att göras att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande assemblyn, i mappen för entry assemblyn och sedan i de inbäddade resurserna för den anropande assemblyn.
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

## Se även

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
