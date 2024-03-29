---
title: License
second_title: Aspose.BarCode för .NET API-referens
description: Tillhandahåller metoder för att licensiera komponenten.
type: docs
weight: 1010
url: /sv/net/aspose.barcode/license/
---
## License class

Tillhandahåller metoder för att licensiera komponenten.

```csharp
public class License
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [License](license)() | Default_Constructor |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense#setlicense)(Stream) | Licensierar komponenten. |
| [SetLicense](../../aspose.barcode/license/setlicense#setlicense_1)(string) | Licensierar komponenten. |

### Exempel

I det här exemplet kommer ett försök att göras att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten , i mappen som innehåller den anropande sammansättningen, i mappen för postsammansättningen och sedan i embedded resurser för den anropande församlingen.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Se även

* namnutrymme [Aspose.BarCode](../../aspose.barcode)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
