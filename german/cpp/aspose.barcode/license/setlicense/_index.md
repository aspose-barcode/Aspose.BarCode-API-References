---
title: "Methode"
linktitle: "SetLicense"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Lizenziert die Bibliothek in C++."
type: docs
weight: 200
url: /de/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


Lizenziert die Bibliothek.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | System::String | Kann ein voller oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. |
## Hinweise


Versucht, die Lizenz an den folgenden Speicherorten zu finden:

1. Expliziter Pfad.

2. Der Ordner, der die **Aspose**-Komponentenassembly enthält.

3. Der Ordner, der die Aufrufassembly des Clients enthält.

4. Der Ordner, der die Einstieg (Startup)Assembly enthält.

5. Eine eingebettete Ressource in der Aufrufassembly des Clients.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliziter Pfad.

2. Eine eingebettete Ressource in der Aufrufassembly des Clients.

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Entry-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.
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


## Siehe auch

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Lizenziert die Bibliothek.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Ein Stream, der die Lizenz enthält. |
## Hinweise



Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## Siehe auch

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
