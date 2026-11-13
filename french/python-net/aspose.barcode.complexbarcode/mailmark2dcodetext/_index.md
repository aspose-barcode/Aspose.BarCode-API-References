---
title: "Mailmark2DCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mail 2D Mailmark.

Le type Mailmark2DCodetext expose les membres suivants:
## Constructeurs
| Name | Description |
| :- | :- |
| Mailmark2DCodetext() | Initialise une nouvelle instance de la classe Mailmark2DCodetext |
## Properties
| Name | Description |
| :- | :- |
| upu_country_id | Identifie l'ID pays UPU. Longueur maximale : 4 caractères. |
| information_type_id | Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit. |
| version_id | Identifie la version du code-barres pertinente pour chaque ID de type d'information. |
| klass | Identifie la classe de l'élément. |
| supply_chain_id | Identifie le groupe unique de clients impliqués dans l'envoi.<br/>            Valeur maximale : 9999999. |
| item_id | Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement.<br/>            Chaque code-barres Mailmark doit contenir un ID<br/>            afin qu'il puisse être identifié de manière unique pendant au moins 90 jours.<br/>            Valeur maximale : 99999999. |
| destination_post_code_and_dps | Contient le code postal de l'adresse de livraison avec DPS<br/>            Si intérieur, le code postal/DP contient le nombre de caractères suivant.<br/>            Zone (1 ou 2 caractères) District (1 ou 2 caractères)<br/>            Secteur (1 caractère) Unité (2 caractères) DPS (2 caractères).<br/>            Le code postal et le DPS doivent être conformes à un format PAF® valide. |
| rts_flag | Indicateur qui indique le niveau de service Retour à l'expéditeur demandé. |
| return_to_sender_post_code | Contient le code postal de Retour à l'expéditeur mais pas de DPS.<br/>            Le PC (sans DPS) doit être conforme à un format PAF®. |
| customer_content | Espace optionnel à l'usage du client. |
| customer_content_encode_mode | Mode d'encodage du code-barres Datamatrix.<br/>            Valeur par défaut : EncodeMode.C40. |
| data_matrix_type | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
## Methods
| Name | Description |
| :- | :- |
| get_constructed_codetext() | Construit le texte de code à partir des données Mailmark. |
| init_from_string(constructed_codetext) | Initialise les données Mailmark à partir du texte de code construit. |
| get_barcode_type() | Obtient le type de code-barres. |

### Voir aussi

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

