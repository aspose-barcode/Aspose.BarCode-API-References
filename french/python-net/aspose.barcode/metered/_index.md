---
title: "Metered"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode/metered/
---

## Metered class

Fournit des méthodes pour définir la clé mesurée.

Le type Metered expose les membres suivants :
## Constructeurs
| Name | Description |
| :- | :- |
| Metered() | Initialise une nouvelle instance de la classe Metered |
## Methods
| Name | Description |
| :- | :- |
| set_metered_key(public_key, private_key) | Définit les clés publiques et privées mesurées.<br/>            Si vous achetez une licence mesurée, au démarrage de l'application, cette API doit être appelée, normalement, cela suffit. <br/>            Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation, <br/>            pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence ; s'il est en statut d'évaluation, appelez à nouveau cette API. |
| get_consumption_quantity() | Obtient la taille du fichier de consommation |
| get_consumption_credit() | Obtient le crédit de consommation |
| get_product_name() | Obtient le nom du produit sous licence |
| is_metered_licensed() | Vérifie si la licence mesurée est active |

### Voir aussi

* namespace [aspose.barcode](/barcode/python-net/aspose.barcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

