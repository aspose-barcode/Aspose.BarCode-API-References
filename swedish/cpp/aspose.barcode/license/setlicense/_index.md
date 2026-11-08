---
title: "metod"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API-referens"
description: " method. Licensierar biblioteket i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


Licensierar biblioteket.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | System::String | Kan vara ett fullständigt eller kort filnamn eller namn på en inbäddad resurs. |
## Anmärkningar


Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen som innehåller **Aspose**-komponentens assembly.

3. Mappen som innehåller klientens anropande assembly.

4. Mappen som innehåller entry (startup)-assemblyn.

5. En inbäddad resurs i klientens anropande assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit sökväg.

2. En inbäddad resurs i klientens anropande assembly.

I det här exemplet kommer ett försök att göras att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande assemblyn, i mappen för entry assemblyn och sedan i de inbäddade resurserna för den anropande assemblyn.
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


## Se även

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Licensierar biblioteket.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | System::SharedPtr\<System::IO::Stream\> | En ström som innehåller licensen. |
## Anmärkningar



Använd den här metoden för att läsa in en licens från en ström.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## Se även

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
