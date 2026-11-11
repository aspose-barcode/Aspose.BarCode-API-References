---
title: "Klasse License"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.License klasse. Biedt methoden om het component te licentiëren"
type: docs
weight: 1760
url: /nl/net/aspose.barcode/license/
---
## License class

Biedt methoden om het component te licentiëren.

```csharp
public class License
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [License](license/)() | De standaardconstructor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense)(Stream) | Licentieert de bibliotheek. |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense_1)(string) | Licentieert de bibliotheek. |

## Voorbeelden

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die het component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingesloten resources van de aanroepende assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Zie ook

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


