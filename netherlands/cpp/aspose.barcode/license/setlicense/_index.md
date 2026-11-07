---
title: "methode"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Licentieert de bibliotheek in C++."
type: docs
weight: 200
url: /nl/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


Licentieert de bibliotheek.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseName | System::String | Kan een volledige of korte bestandsnaam of de naam van een ingesloten resource zijn. |
## Opmerkingen


Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.

2. De map die de **Aspose** componentassembly bevat.

3. De map die de aanroepende assembly van de client bevat.

4. De map die de entry (startup) assembly bevat.

5. Een ingebedde bron in de aanroepende assembly van de client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliciet pad.

2. Een ingebedde bron in de aanroepende assembly van de client.

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die het component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde resources van de aanroepende assembly.
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


## Zie ook

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Licentieert de bibliotheek.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Een stream die de licentie bevat. |
## Opmerkingen



Gebruik deze methode om een licentie uit een stream te laden.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## Zie ook

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
