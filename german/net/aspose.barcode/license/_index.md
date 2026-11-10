---
title: "Klasse Lizenz"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.License-Klasse. Stellt Methoden zum Lizenzieren der Komponente bereit"
type: docs
weight: 1760
url: /de/net/aspose.barcode/license/
---
## License class

Stellt Methoden zur Lizenzierung der Komponente bereit.

```csharp
public class License
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [License](license/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense)(Stream) | Lizenziert die Bibliothek. |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense_1)(string) | Lizenziert die Bibliothek. |

## Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Siehe auch

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


