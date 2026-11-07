---
title: "method"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Concede la licenza alla libreria in C++."
type: docs
weight: 200
url: /it/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


Licenzia la libreria.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| licenseName | System::String | Può essere un nome file completo o breve o il nome di una risorsa incorporata. |
## Osservazioni


Cerca di trovare la licenza nelle seguenti posizioni:

1. Percorso esplicito.

2. La cartella che contiene l'assembly del componente **Aspose**.

3. La cartella che contiene l'assembly chiamante del client.

4. La cartella che contiene l'assembly di ingresso (avvio).

5. Una risorsa incorporata nell'assembly chiamante del client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Percorso esplicito.

2. Una risorsa incorporata nell'assembly chiamante del client.

In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante.
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


## Vedi anche

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Licenzia la libreria.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Un flusso che contiene la licenza. |
## Osservazioni



Utilizza questo metodo per caricare una licenza da un flusso.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## Vedi anche

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
