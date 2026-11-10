---
title: "Classe License"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.License. Fournit des méthodes pour licencier le composant"
type: docs
weight: 1760
url: /fr/net/aspose.barcode/license/
---
## License class

Fournit des méthodes pour licencier le composant.

```csharp
public class License
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [License](license/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense)(Stream) | Licence la bibliothèque. |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense_1)(string) | Licence la bibliothèque. |

## Exemples

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Voir aussi

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


