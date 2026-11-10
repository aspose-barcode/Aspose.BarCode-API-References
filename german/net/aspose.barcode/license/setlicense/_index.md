---
title: "License.SetLicense"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "License Methode. Lizenziert die Bibliothek"
type: docs
weight: 20
url: /de/net/aspose.barcode/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Lizenziert die Bibliothek.

```csharp
public void SetLicense(string licenseName)
```

## Bemerkungen

Versucht, die Lizenz an den folgenden Orten zu finden:

1. Expliziter Pfad.

2. Der Ordner, der die Aspose component assembly enthält.

3. Der Ordner, der die client's calling assembly enthält.

4. Der Ordner, der die entry (startup) assembly enthält.

5. Eine eingebettete Ressource in der client's calling assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliziter Pfad.

2. Eine eingebettete Ressource in der client's calling assembly.

## Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Kann ein voller oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein.

### Siehe auch

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)

---

## SetLicense(Stream) {#setlicense}

Lizenziert die Bibliothek.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Strom | Ein Stream, der die Lizenz enthält. |

## Bemerkungen

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.

## Beispiele

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Siehe auch

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)


