---
title: "MailmarkCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mailmark à 4 états.

Le type MailmarkCodetext expose les membres suivants:
## Constructeurs
| Name | Description |
| :- | :- |
| MailmarkCodetext() | Initialise une nouvelle instance de la classe MailmarkCodetext |
## Properties
| Name | Description |
| :- | :- |
| format | \"0\" – Nul ou Test<br/>            \"1\" – Lettre<br/>            \"2\" – Grande Lettre |
| version_id | Actuellement \"1\" – Pour le code-barres Mailmark (0 et 2 à 9 et A à Z réservés pour une utilisation future) |
| klass | \"0\" - Nul ou Test<br/>            \"1\" - 1C (Commerce de détail)<br/>            \"2\" - 2C (Commerce de détail)<br/>            \"3\" - 3C (Commerce de détail)<br/>            \"4\" - Premium (Mail de RetailPublishing) (pour une utilisation future éventuelle)<br/>            \"5\" - Différé (Commerce de détail)<br/>            \"6\" - Air (Commerce de détail) (pour une utilisation future éventuelle)<br/>            \"7\" - Surface (Commerce de détail) (pour une utilisation future éventuelle)<br/>            \"8\" - Premium (Accès réseau)<br/>            \"9\" - Standard (Accès réseau) |
| supply_chain_id | Les valeurs maximales sont 99 pour le code-barres C et 999999 pour le code-barres L. |
| item_id | La valeur maximale est 99999999. |
| destination_post_code_and_dps | Le PC et le DP doivent être conformes à un format PAF.<br/>            Chaîne de neuf caractères désignant l'international \"XY11     \" (notez les 5 espaces de fin) ou un motif<br/>            de caractères désignant un code de tri domestique.<br/>            Un code de tri domestique se compose d'un code postal extérieur, d'un code postal intérieur et d'un suffixe de point de livraison. |
## Methods
| Name | Description |
| :- | :- |
| get_constructed_codetext() | Construit le texte de code à partir des données Mailmark. |
| init_from_string(constructed_codetext) | Initialise les données Mailmark à partir du texte de code construit. |
| get_barcode_type() | Obtient le type de code-barres. |

### Voir aussi

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

