---
title: "Classe USADriveIdCodetext.OptionalFields"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields. Champs des éléments optionnels de la carte"
type: docs
weight: 830
url: /fr/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Éléments (champs) optionnels de la carte

```csharp
public class OptionalFields
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Deuxième ligne de la partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Autre nom de famille sous lequel le titulaire de la carte est connu, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Autre prénom sous lequel le titulaire de la carte est connu, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Autre suffixe sous lequel le titulaire de la carte est connu, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, Une chaîne de lettres et/ou de chiffres qui identifie quand, où et par qui un permis de conduire/carte d'identité a été fabriqué. Si les informations d'audit ne sont pas utilisées sur la carte ou le MRT, elles doivent être incluses dans l'enregistrement du conducteur, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, Champ requis par le DHS indiquant la date du changement de version le plus récent ou de la modification du format visible du DL/ID. (MMJJCCAA pour les États‑Unis, AACCJJMM pour le Canada), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, Champ requis par le DHS indiquant la conformité : « F » = conforme ; et « N » = non conforme, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Texte expliquant le(s) code(s) spécifique(s) à la juridiction qui indique(nt) des privilèges de conduite supplémentaires accordés au titulaire de la carte au-delà de la classe de véhicule, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Chauve, noir, blond, brun, gris, rouge/roux, sable, blanc, inconnu. Si la juridiction émettrice souhaite abréger les couleurs, les codes à trois caractères fournis dans AAMVA D20 doivent être utilisés, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Date à laquelle l'endorsement de matières dangereuses accordé par le document n'est plus valide. (MMJJCCAA pour les États‑Unis, AACCJJMM pour le Canada), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, Une chaîne de lettres et/ou de chiffres apposée aux matières premières (papier, laminage, etc.) utilisées pour fabriquer les permis de conduire et les cartes d'identité. (Champ recommandé par le DHS), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, Champ requis par le DHS indiquant que le titulaire de la carte a un statut légal temporaire = « 1 », DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, Suffixe de nom (Si la juridiction participe à des systèmes nécessitant un suffixe de nom (PDPS, CDLIS, etc.), le suffixe doit être collecté et affiché sur le DL/ID et dans le MRT). JR (Junior), SR (Senior), 1ST ou I (Premier), jusqu'à 9TH ou IX (Neuvième), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Champ indiquant que le titulaire de la carte est donneur d'organes = « 1 », DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, Pays et municipalité et/ou État/province, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Codes de race ou d'ethnicité du titulaire de la carte, tels que définis dans AAMVA D20, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Texte décrivant le(s) code(s) de restriction spécifique(s) à la juridiction qui limitent les privilèges de conduite, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Code(s) d'endorsement standard pour le titulaire de la carte. Voir les codes dans D20. Cet élément de données est un espace réservé aux futurs efforts de normalisation des codes d'endorsement, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, Code(s) de restriction standard pour le titulaire de la carte. Voir les codes dans D20. Cet élément de données est un espace réservé aux futurs efforts de normalisation des codes de restriction, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, Code(s) de classification de véhicule standard pour le titulaire de la carte. Cet élément de données est un espace réservé aux futurs efforts de normalisation des classifications de véhicules, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, Date à laquelle le titulaire de la carte atteint 18 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, Date à laquelle le titulaire de la carte atteint 19 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, Date à laquelle le titulaire de la carte atteint 21 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, Texte qui explique le(s) code(s) spécifiques à la juridiction pour les classifications de véhicules que le titulaire de la carte est autorisé à conduire, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, Champ qui indique que le titulaire de la carte est un vétéran = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, Poids du titulaire de la carte en kilogrammes, Ex. 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, Poids du titulaire de la carte en livres, Ex. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, Indique la fourchette de poids approximative du titulaire de la carte : 0 = jusqu’à 31 kg (jusqu’à 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 - 59 kg (101 – 130 lb), 3 = 60 - 70 kg (131 – 160 lb), 4 = 71 - 86 kg (161 – 190 lb), 5 = 87 - 100 kg (191 – 220 lb), 6 = 101 - 113 kg (221 – 250 lb), 7 = 114 - 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |

### Voir aussi

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


