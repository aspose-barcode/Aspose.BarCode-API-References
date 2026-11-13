---
title: "GS1ValidationErrorCode"
second_title: "Référence de l'API .NET Aspose.Sildes pour Python"
description: 
type: docs
url: /fr/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Identifie une erreur de validation d'une chaîne d'élément GS1, d'une URI Digital Link ou d'une valeur.

## Members
| Nom du membre | Description |
| :- | :- |
| EMPTY_ELEMENT_STRING | La chaîne d'élément GS1 fournie est vide. |
| MISSING_OPENING_PARENTHESIS | Une parenthèse ouvrante qui devrait commencer un Application Identifier est manquante. |
| MISSING_CLOSING_PARENTHESIS | Un Application Identifier n'a pas de parenthèse fermante. |
| INVALID_APPLICATION_IDENTIFIER | Un Application Identifier ne contient pas deux à quatre chiffres ASCII. |
| UNKNOWN_APPLICATION_IDENTIFIER | L'Application Identifier fourni n'est pas défini par le dictionnaire de syntaxe GS1 pris en charge. |
| MISSING_VALUE | Un Application Identifier est présent sans valeur. |
| INVALID_ESCAPE_SEQUENCE | Une valeur contient une séquence d'échappement non prise en charge. Seul \\( est pris en charge. |
| VALUE_TOO_SHORT | Une valeur est plus courte que la longueur minimale définie pour son Application Identifier. |
| VALUE_TOO_LONG | Une valeur est plus longue que la longueur maximale définie pour son Application Identifier. |
| INVALID_CHARACTER | Une valeur contient un caractère en dehors du jeu de caractères autorisé pour son composant. |
| INVALID_CHECKSUM | Une somme de contrôle numérique ou alphabétique est invalide. |
| INVALID_DATE | Un composant de date n'est pas une date significative selon les règles définies pour son Application Identifier. |
| INVALID_TIME | Un composant temporel est hors de sa plage autorisée ou possède une structure invalide. |
| INVALID_CODE_LIST_VALUE | Une valeur de composant n'est pas présente dans sa liste de codes fermée autorisée. |
| INVALID_COMPONENT_LENGTH | Un composant ne satisfait pas sa structure de longueur spécifique au composant. |
| TRUNCATED_COMPONENT | Un composant à longueur fixe se termine avant que tous les caractères requis ne soient présents. |
| UNEXPECTED_DATA | Des données restent après que tous les composants définis pour l'Identifiant d'Application ont été consommés. |
| INVALID_VALUE | Un composant viole une règle de contenu qui n'a pas de code d'erreur de validation plus spécifique. |
| GCP_PREFIX_TOO_SHORT | Un composant est trop court pour contenir le préfixe d'entreprise GS1 structurel minimum de quatre chiffres. |
| INVALID_GCP_PREFIX | Le préfixe d'entreprise GS1 structurel contient un caractère autre qu'un chiffre ASCII. |
| INVALID_DIGITAL_LINK_URI | La valeur fournie n'est pas une URI GS1 Digital Link absolue bien formée. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | Une URI GS1 Digital Link utilise un schéma autre que HTTP ou HTTPS. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | Le chemin d'une URI GS1 Digital Link ne contient pas de clé primaire prise en charge. |
| INVALID_DIGITAL_LINK_PATH | Le chemin d'une URI GS1 Digital Link ne se compose pas de paires AI et valeur valides. |
| INVALID_DIGITAL_LINK_QUALIFIER | Un identifiant d'application de chemin n'est pas un qualificateur autorisé à cette position. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | Un paramètre de requête GS1 Digital Link est malformé. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | Un identifiant d'application n'est pas autorisé en tant qu'attribut de données GS1 Digital Link. |
| INVALID_PERCENT_ENCODING | Un composant d'URI GS1 Digital Link contient un encodage de pourcentage malformé. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | Plus d'un élément pourrait être sélectionné comme clé primaire du GS1 Digital Link. |
| UNSUPPORTED_ELEMENT_COMBINATION | La combinaison fournie d'éléments GS1 n'est pas prise en charge par la symbologie ou le mode d'encodage sélectionné. |

### Voir aussi

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

