---
title: "DataMatrixEncodeMode"
second_title: "Référence de l'API .NET Aspose.Sildes pour Python"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

Mode d'encodage de l'encodeur DataMatrix, par défaut Auto

## Members
| Nom du membre | Description |
| :- | :- |
| AUTO | En mode Auto, le CodeText est encodé avec la compacité maximale des données. <br/>            Les caractères Unicode sont ré-encodés dans le codage spécifié par ECIEncoding avec l’insertion d’un identifiant ECI.<br/>            Si un caractère est trouvé qui n’est pas pris en charge par le codage ECI sélectionné, une exception est levée. |
| ASCII | Encode un caractère alphanumérique ou deux caractères numériques par octet |
| C40 | Utilise l’encodage C40. Encode les caractères alphanumériques majuscules, les minuscules et les caractères spéciaux |
| TEXT | Utilise l’encodage Text. Encode les caractères alphanumériques minuscules, les majuscules et les caractères spéciaux |
| EDIFACT | Utilise l’encodage EDIFACT. Utilise six bits par caractère, encode les chiffres, les lettres majuscules et de nombreuses ponctuations, mais ne prend pas en charge les lettres minuscules. |
| ANSIX12 | Utilise l’encodage ANSI X12. |
| EXTENDED |  |
| BASE256 | Encode des valeurs sur 8 bits |
| BINARY | En mode Binaire, le CodeText est encodé avec la compacité maximale des données. <br/>            Si un caractère Unicode est trouvé, une exception est levée. |
| ECI | En mode ECI, le message complet est ré-encodé dans le codage spécifié par ECIEncoding avec l’insertion d’un identifiant ECI.<br/>            Si un caractère est trouvé qui n’est pas pris en charge par le codage ECI sélectionné, une exception est levée.<br/>            Veuillez noter que certains anciens scanners (pré 2006) peuvent ne pas prendre en charge ce mode. |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

