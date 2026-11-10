---
title: "Classe USADriveIdCodetext.MandatoryFields"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields classe. Champs obligatoires de la carte"
type: docs
weight: 820
url: /fr/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Éléments obligatoires (champs) de la carte

```csharp
public class MandatoryFields
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, Partie ville de l'adresse du titulaire de la carte, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, Partie code postal de l'adresse du titulaire de la carte aux États‑Unis et au Canada. Si la partie finale du code postal aux États‑Unis n'est pas connue, des zéros seront utilisés pour remplir la série finale de chiffres jusqu'à 9 chiffres, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, Partie État de l'adresse du titulaire de la carte, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, Partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, Pays dans lequel le DL/ID est délivré. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, Le numéro attribué ou calculé par l'autorité émettrice, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Date à laquelle le document a été délivré, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, Le numéro doit identifier de manière unique un document particulier délivré à ce client parmi d'autres qui pourraient avoir été délivrés dans le passé. Ce numéro peut servir à plusieurs fins : discrimination de documents, numéro d'information d'audit et/ou contrôle d'inventaire, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Codes d'endossement spécifiques à la juridiction, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Date d'expiration du document, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Couleur des yeux du titulaire de la carte. (ANSI D-20 codes). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Nom de famille du titulaire de la carte, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si le statut de troncature est inconnu (U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, Prénom du titulaire de la carte, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si le statut de troncature est inconnu (U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Taille du titulaire de la carte. Pouces (in) : nombre de pouces suivi de " in" ex. 6'1'' = "073 in" Centimètres(cm) : nombre de centimètres suivi de " cm" ex. 181 centimètres="181 cm" , DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Date à laquelle le document a été délivré, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Deuxième(s) prénom(s) du titulaire de la carte. Dans le cas de plusieurs prénoms, ils doivent être séparés par une virgule ","., DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si le statut de troncature est inconnu (U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, Codes de restrictions spécifiques à la juridiction, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Sexe du titulaire de la carte. 1 = homme, 2 = femme, 9 = non spécifié, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, Code de classe/groupe de véhicule spécifique à la juridiction, DL, V6ANS |

### Voir aussi

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


