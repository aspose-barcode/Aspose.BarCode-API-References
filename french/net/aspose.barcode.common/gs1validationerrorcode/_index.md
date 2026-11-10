---
title: "Enum GS1ValidationErrorCode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode enum. Identifie une erreur de validation d’une chaîne d’élément GS1, d’une URI Digital Link ou d’une valeur"
type: docs
weight: 430
url: /fr/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

Identifie une chaîne d'élément GS1, une URI Digital Link ou une erreur de validation de valeur.

```csharp
public enum GS1ValidationErrorCode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| EmptyElementString | `0` | La chaîne d'élément GS1 fournie est vide. |
| MissingOpeningParenthesis | `1` | Une parenthèse ouvrante qui devrait commencer un identifiant d'application est manquante. |
| MissingClosingParenthesis | `2` | Un identifiant d'application n'a pas de parenthèse fermante. |
| InvalidApplicationIdentifier | `3` | Un identifiant d'application ne contient pas entre deux et quatre chiffres ASCII. |
| UnknownApplicationIdentifier | `4` | L'identifiant d'application fourni n'est pas défini dans le dictionnaire de syntaxe GS1 pris en charge. |
| MissingValue | `5` | Un identifiant d'application est présent sans valeur. |
| InvalidEscapeSequence | `6` | Une valeur contient une séquence d'échappement non prise en charge. Seul \( est pris en charge. |
| ValueTooShort | `7` | Une valeur est plus courte que la longueur minimale définie pour son identifiant d'application. |
| ValueTooLong | `8` | Une valeur est plus longue que la longueur maximale définie pour son identifiant d'application. |
| InvalidCharacter | `9` | Une valeur contient un caractère en dehors du jeu de caractères autorisé pour son composant. |
| InvalidChecksum | `10` | Une somme de contrôle numérique ou alphabétique est invalide. |
| InvalidDate | `11` | Un composant de date n'est pas une date significative selon les règles définies pour son identifiant d'application. |
| InvalidTime | `12` | Un composant d'heure est en dehors de sa plage autorisée ou possède une structure invalide. |
| InvalidCodeListValue | `13` | Une valeur de composant n'est pas présente dans sa liste de codes fermés autorisée. |
| InvalidComponentLength | `14` | Un composant ne satisfait pas sa structure de longueur spécifique au composant. |
| TruncatedComponent | `15` | Un composant à longueur fixe se termine avant que tous les caractères requis soient présents. |
| UnexpectedData | `16` | Des données restent après que tous les composants définis pour l'identifiant d'application ont été consommés. |
| InvalidValue | `17` | Un composant viole une règle de contenu qui n'a pas de code d'erreur de validation plus spécifique. |
| GcpPrefixTooShort | `18` | Un composant est trop court pour contenir le préfixe d'entreprise GS1 structurel minimum à quatre chiffres. |
| InvalidGcpPrefix | `19` | Le préfixe d'entreprise GS1 structurel contient un caractère autre qu'un chiffre ASCII. |
| InvalidDigitalLinkUri | `20` | La valeur fournie n'est pas une URI GS1 Digital Link absolue bien formée. |
| UnsupportedDigitalLinkScheme | `21` | Une URI GS1 Digital Link utilise un schéma autre que HTTP ou HTTPS. |
| MissingDigitalLinkPrimaryKey | `22` | Le chemin d'une URI GS1 Digital Link ne contient pas de clé primaire prise en charge. |
| InvalidDigitalLinkPath | `23` | Le chemin d'une URI GS1 Digital Link ne se compose pas de paires AI et valeur valides. |
| InvalidDigitalLinkQualifier | `24` | Un identifiant d'application de chemin n'est pas un qualificateur autorisé à cette position. |
| InvalidDigitalLinkQueryParameter | `25` | Un paramètre de requête GS1 Digital Link est mal formé. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | Un identifiant d'application n'est pas autorisé en tant qu'attribut de données GS1 Digital Link. |
| InvalidPercentEncoding | `27` | Un composant d'URI GS1 Digital Link contient un encodage de pourcentage mal formé. |
| MultipleDigitalLinkPrimaryKeys | `28` | Plus d'un élément pourrait être sélectionné comme clé primaire du GS1 Digital Link. |
| UnsupportedElementCombination | `29` | La combinaison fournie d'éléments GS1 n'est pas prise en charge par la symbologie ou le mode d'encodage sélectionnés. |

### Voir aussi

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


