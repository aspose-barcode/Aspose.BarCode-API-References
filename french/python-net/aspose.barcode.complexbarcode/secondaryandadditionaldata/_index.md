---
title: "SecondaryAndAdditionalData"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Classe pour le stockage des données secondaires et supplémentaires HIBC LIC.

Le type SecondaryAndAdditionalData expose les membres suivants :
## Constructeurs
| Name | Description |
| :- | :- |
| SecondaryAndAdditionalData() | Initialise une nouvelle instance de la classe SecondaryAndAdditionalData |
## Properties
| Name | Description |
| :- | :- |
| expiry_date_format | Identifie le format de date d'expiration. |
| expiry_date | Identifie la date d'expiration. Sera utilisé si ExpiryDateFormat n'est pas défini sur None. |
| lot_number | Identifie le numéro de lot ou de lotissement. Le numéro de lot/lotissement doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles. . |
| serial_number | Identifie le numéro de série. Le numéro de série doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles. |
| date_of_manufacture | Identifie la date de fabrication.<br/>            La date de fabrication peut être définie sur DateTime.MinValue afin de ne pas utiliser ce champ.<br/>            Valeur par défaut : DateTime.MinValue |
| quantity | Identifie la quantité, doit être une valeur entière de 0 à 500. <br/>            La quantité peut être définie sur -1 afin de ne pas utiliser ce champ.<br/>            Valeur par défaut : -1 |
## Methods
| Name | Description |
| :- | :- |
| parse_from_string(secondary_data_codetext) | Instancie les données secondaires et supplémentaires complémentaires à partir du format chaîne selon la spécification HIBC LIC. |

### Voir aussi

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

