---
title: "DotCodeEncodeMode"
second_title: "Référence de l'API .NET Aspose.Sildes pour Python"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/dotcodeencodemode/
---

## DotCodeEncodeMode enumeration

Mode d'encodage pour les codes-barres DotCode.

## Members
| Nom du membre | Description |
| :- | :- |
| AUTO | En mode Auto, le CodeText est encodé avec la compacité maximale des données. <br/>            Les caractères Unicode sont ré-encodés dans le codage spécifié par ECIEncoding avec l’insertion d’un identifiant ECI.<br/>            Si un caractère est trouvé qui n’est pas pris en charge par le codage ECI sélectionné, une exception est levée. |
| BINARY | En mode Binaire, le CodeText est encodé avec la compacité maximale des données. <br/>            Si un caractère Unicode est trouvé, une exception est levée. |
| ECI | En mode ECI, le message complet est ré-encodé dans le codage spécifié par ECIEncoding avec l’insertion d’un identifiant ECI.<br/>            Si un caractère est trouvé qui n’est pas pris en charge par le codage ECI sélectionné, une exception est levée.<br/>            Veuillez noter que certains anciens scanners (pré 2006) peuvent ne pas prendre en charge ce mode. |
| EXTENDED |  |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

