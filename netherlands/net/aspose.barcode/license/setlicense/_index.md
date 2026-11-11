---
title: "License.SetLicense"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "License methode. Licentieert de bibliotheek"
type: docs
weight: 20
url: /nl/net/aspose.barcode/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licentieert de bibliotheek.

```csharp
public void SetLicense(string licenseName)
```

## Opmerkingen

Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.

2. De map die de Aspose-componentassembly bevat.

3. De map die de aanroepende assembly van de client bevat.

4. De map die de entry (startup) assembly bevat.

5. Een ingebedde bron in de aanroepende assembly van de client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliciet pad.

2. Een ingebedde bron in de aanroepende assembly van de client.

## Voorbeelden

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die het component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingesloten resources van de aanroepende assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Kan een volledige of korte bestandsnaam of de naam van een ingebedde bron zijn.

### Zie ook

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)

---

## SetLicense(Stream) {#setlicense}

Licentieert de bibliotheek.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Een stream die de licentie bevat. |

## Opmerkingen

Gebruik deze methode om een licentie uit een stream te laden.

## Voorbeelden

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Zie ook

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)


