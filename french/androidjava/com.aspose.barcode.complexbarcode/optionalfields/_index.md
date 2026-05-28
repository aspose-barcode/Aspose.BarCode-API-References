---
title: USADriveIdCodetext.OptionalFields
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Champs des éléments optionnels de la carte
type: docs
weight: 11
url: /fr/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

Éléments optionnels (champs) de la carte
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, Deuxième ligne de la partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, Autre nom de famille sous lequel le titulaire de la carte est connu, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, Autre prénom sous lequel le titulaire de la carte est connu, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, Autre suffixe sous lequel le titulaire de la carte est connu, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, Une chaîne de lettres et/ou de chiffres qui identifie quand, où et par qui un permis de conduire/carte d'identité a été fabriqué. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, Champ requis par le DHS qui indique la date de la modification ou du changement de version le plus récent du format visible du DL/ID. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, Champ requis par le DHS qui indique la conformité : \u201cF\u201d = conforme ; et, \u201cN\u201d = non conforme, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, Texte qui explique le(s) code(s) spécifique(s) à la juridiction indiquant les privilèges de conduite supplémentaires accordés au titulaire de la carte au-delà de la classe de véhicule, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, Date à laquelle l'endorsement de matières dangereuses accordé par le document n'est plus valide. |
| [getHairColor()](#getHairColor--) | DAZ, Chauve, noir, blond, brun, gris, rouge/roux, sable, blanc, inconnu. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, Une chaîne de lettres et/ou de chiffres qui est apposée aux matières premières (papier cartonné, laminé, etc.) utilisées pour produire les permis de conduire et les cartes d'identité. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, Champ requis par le DHS qui indique que le titulaire de la carte a un statut légal temporaire = \u201c1\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, Suffixe de nom (Si la juridiction participe à des systèmes nécessitant un suffixe de nom (PDPS, CDLIS, etc.), le suffixe doit être collecté et affiché sur le DL/ID et dans le MRT). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, Champ qui indique que le titulaire de la carte est un donneur d'organes = \u201c1\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, Pays et municipalité et/ou état/province, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, Codes de race ou d'ethnicité du titulaire de la carte, tels que définis dans AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, Texte décrivant le(s) code(s) de restriction spécifique(s) à la juridiction qui limitent les privilèges de conduite, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, Code(s) d'endorsement standard pour le titulaire de la carte. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, Code(s) de restriction standard pour le titulaire de la carte. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, Code(s) de classification de véhicule standard pour le titulaire de la carte. |
| [getUnder18Until()](#getUnder18Until--) | DDH, Date à laquelle le titulaire de la carte atteint 18 ans. |
| [getUnder19Until()](#getUnder19Until--) | DDI, Date à laquelle le titulaire de la carte atteint 19 ans. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, Date à laquelle le titulaire de la carte atteint 21 ans. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, Texte qui explique le(s) code(s) spécifique(s) à la juridiction pour les classifications de véhicules que le titulaire est autorisé à conduire, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, Champ qui indique que le titulaire est un vétéran = \\u201c1\\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, Poids du titulaire en kilogrammes, Ex. |
| [getWeightPounds()](#getWeightPounds--) | DAW, Poids du titulaire en livres, Ex. |
| [getWeightRange()](#getWeightRange--) | DCE, Indique la fourchette de poids approximative du titulaire : 0 = jusqu'à 31 kg (jusqu'à 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, Deuxième ligne de la partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, Autre nom de famille sous lequel le titulaire de la carte est connu, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, Autre prénom sous lequel le titulaire de la carte est connu, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, Autre suffixe sous lequel le titulaire de la carte est connu, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, Une chaîne de lettres et/ou de chiffres qui identifie quand, où et par qui un permis de conduire/carte d'identité a été fabriqué. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, Champ requis par le DHS qui indique la date de la modification ou du changement de version le plus récent du format visible du DL/ID. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, Champ requis par le DHS qui indique la conformité : \u201cF\u201d = conforme ; et, \u201cN\u201d = non conforme, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, Texte qui explique le(s) code(s) spécifique(s) à la juridiction indiquant les privilèges de conduite supplémentaires accordés au titulaire de la carte au-delà de la classe de véhicule, DL, V50ANS |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, Chauve, noir, blond, brun, gris, rouge/roux, sable, blanc, inconnu. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, Une chaîne de lettres et/ou de chiffres qui est apposée aux matières premières (papier cartonné, laminé, etc.) utilisées pour produire les permis de conduire et les cartes d'identité. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, Champ requis par le DHS qui indique que le titulaire de la carte a un statut légal temporaire = \u201c1\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, Suffixe de nom (Si la juridiction participe à des systèmes nécessitant un suffixe de nom (PDPS, CDLIS, etc.), le suffixe doit être collecté et affiché sur le DL/ID et dans le MRT). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, Champ qui indique que le titulaire de la carte est un donneur d'organes = \u201c1\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, Pays et municipalité et/ou état/province, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, Codes de race ou d'ethnicité du titulaire de la carte, tels que définis dans AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, Texte décrivant le(s) code(s) de restriction spécifique(s) à la juridiction qui limitent les privilèges de conduite, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, Code(s) d'endorsement standard pour le titulaire de la carte. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, Code(s) de restriction standard pour le titulaire de la carte. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, Code(s) de classification de véhicule standard pour le titulaire de la carte. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, Date à laquelle le titulaire de la carte atteint 18 ans. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, Date à laquelle le titulaire de la carte atteint 19 ans. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, Date à laquelle le titulaire de la carte atteint 21 ans. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, Texte qui explique le(s) code(s) spécifique(s) à la juridiction pour les classifications de véhicules que le titulaire est autorisé à conduire, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, Champ qui indique que le titulaire est un vétéran = \\u201c1\\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, Poids du titulaire en kilogrammes, Ex. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, Poids du titulaire en livres, Ex. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, Indique la fourchette de poids approximative du titulaire : 0 = jusqu'à 31 kg (jusqu'à 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptionalFields() {#OptionalFields--}
```
public OptionalFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH, Deuxième ligne de la partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN, Autre nom de famille sous lequel le titulaire de la carte est connu, DL/ID, V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG, Autre prénom sous lequel le titulaire de la carte est connu, DL/ID, V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS, Autre suffixe sous lequel le titulaire de la carte est connu, DL/ID, V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, Chaîne de lettres et/ou de chiffres qui identifie quand, où et par qui un permis de conduire/carte d'identité a été fabriqué. Si les informations d'audit ne sont pas utilisées sur la carte ou le MRT, elles doivent être incluses dans le dossier du conducteur, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, Champ requis par le DHS qui indique la date du changement ou de la modification de version la plus récente du format visible du DL/ID. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplianceType() {#getComplianceType--}
```
public final String getComplianceType()
```


DDA, Champ requis par le DHS qui indique la conformité : \u201cF\u201d = conforme ; et, \u201cN\u201d = non conforme, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, Texte qui explique le(s) code(s) spécifique(s) à la juridiction indiquant les privilèges de conduite supplémentaires accordés au titulaire de la carte au-delà de la classe de véhicule, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, Date à laquelle l'endorsement de matières dangereuses accordé par le document n'est plus valide. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, Chauve, noir, blond, brun, gris, rouge/roux, sable, blanc, inconnu. Si la juridiction émettrice souhaite abréger les couleurs, les codes à trois caractères fournis dans AAMVA D20 doivent être utilisés, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, Chaîne de lettres et/ou de chiffres apposée aux matières premières (papier, lamination, etc.) utilisées pour la production des permis de conduire et des cartes d'identité. (Champ recommandé par le DHS), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, Champ requis par le DHS qui indique que le titulaire de la carte a un statut légal temporaire = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, Suffixe de nom (Si la juridiction participe à des systèmes nécessitant un suffixe de nom (PDPS, CDLIS, etc.), le suffixe doit être recueilli et affiché sur le DL/ID et dans le MRT). JR (Junior), SR (Senior), 1ST ou I (Premier), jusqu'à 9TH ou IX (Neuvième), DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, Champ qui indique que le titulaire de la carte est un donneur d'organes = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, Pays et municipalité et/ou état/province, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, Codes de race ou d'ethnicité du titulaire de la carte, tels que définis dans AAMVA D20, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, Texte décrivant le(s) code(s) de restriction spécifique(s) à la juridiction qui limitent les privilèges de conduite, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN, Code(s) d'endorsement standard pour le titulaire. Voir les codes dans D20. Cet élément de données est un espace réservé aux futurs efforts de normalisation des codes d'endorsement, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, Code(s) de restriction standard pour le titulaire. Voir les codes dans D20. Cet élément de données est un espace réservé aux futurs efforts de normalisation des codes de restriction, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, Code(s) de classification de véhicule standard pour le titulaire. Cet élément de données est un espace réservé aux futurs efforts de normalisation des classifications de véhicules, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, Date à laquelle le titulaire de la carte atteint 18 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, Date à laquelle le titulaire de la carte atteint 19 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, Date à laquelle le titulaire de la carte atteint 21 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, Texte qui explique le(s) code(s) spécifique(s) à la juridiction pour les classifications de véhicules que le titulaire est autorisé à conduire, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, Champ qui indique que le titulaire est un vétéran = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, Poids du titulaire en kilogrammes, Ex. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, Poids du titulaire en livres, Ex. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, Indique la fourchette de poids approximative du titulaire : 0 = jusqu'à 31 kg (jusqu'à 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressStreet2(String value) {#setAddressStreet2-java.lang.String-}
```
public final void setAddressStreet2(String value)
```


DAH, Deuxième ligne de la partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, Autre nom de famille sous lequel le titulaire de la carte est connu, DL/ID, V10ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, Autre prénom sous lequel le titulaire de la carte est connu, DL/ID, V15ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, Autre suffixe sous lequel le titulaire de la carte est connu, DL/ID, V5ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, Chaîne de lettres et/ou de chiffres qui identifie quand, où et par qui un permis de conduire/carte d'identité a été fabriqué. Si les informations d'audit ne sont pas utilisées sur la carte ou le MRT, elles doivent être incluses dans le dossier du conducteur, DL/ID, V25ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, Champ requis par le DHS qui indique la date du changement ou de la modification de version la plus récente du format visible du DL/ID. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, Champ requis par le DHS qui indique la conformité : \u201cF\u201d = conforme ; et, \u201cN\u201d = non conforme, DL/ID, F1A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, Texte qui explique le(s) code(s) spécifique(s) à la juridiction indiquant les privilèges de conduite supplémentaires accordés au titulaire de la carte au-delà de la classe de véhicule, DL, V50ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, Chauve, noir, blond, brun, gris, rouge/roux, sable, blanc, inconnu. Si la juridiction émettrice souhaite abréger les couleurs, les codes à trois caractères fournis dans AAMVA D20 doivent être utilisés, DL/ID, V12A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, Chaîne de lettres et/ou de chiffres apposée aux matières premières (papier, lamination, etc.) utilisées pour la production des permis de conduire et des cartes d'identité. (Champ recommandé par le DHS), DL/ID, V25ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, Champ requis par le DHS qui indique que le titulaire de la carte a un statut légal temporaire = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, Suffixe de nom (Si la juridiction participe à des systèmes nécessitant un suffixe de nom (PDPS, CDLIS, etc.), le suffixe doit être recueilli et affiché sur le DL/ID et dans le MRT). JR (Junior), SR (Senior), 1ST ou I (Premier), jusqu'à 9TH ou IX (Neuvième), DL/ID, V5ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, Champ qui indique que le titulaire de la carte est un donneur d'organes = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, Pays et municipalité et/ou état/province, DL/ID, V33A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, Codes de race ou d'ethnicité du titulaire de la carte, tels que définis dans AAMVA D20, DL/ID, V3A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, Texte décrivant le(s) code(s) de restriction spécifique(s) à la juridiction qui limitent les privilèges de conduite, DL, V50ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, Code(s) d'endorsement standard pour le titulaire. Voir les codes dans D20. Cet élément de données est un espace réservé aux futurs efforts de normalisation des codes d'endorsement, DL, F5AN

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, Code(s) de restriction standard pour le titulaire. Voir les codes dans D20. Cet élément de données est un espace réservé aux futurs efforts de normalisation des codes de restriction, DL, F12AN

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, Code(s) de classification de véhicule standard pour le titulaire. Cet élément de données est un espace réservé aux futurs efforts de normalisation des classifications de véhicules, DL, F4AN

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, Date à laquelle le titulaire de la carte atteint 18 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, Date à laquelle le titulaire de la carte atteint 19 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, Date à laquelle le titulaire de la carte atteint 21 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, Texte qui explique le(s) code(s) spécifique(s) à la juridiction pour les classifications de véhicules que le titulaire est autorisé à conduire, DL, V50ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, Champ qui indique que le titulaire est un vétéran = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, Poids du titulaire en kilogrammes, Ex. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, Poids du titulaire en livres, Ex. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, Indique la fourchette de poids approximative du titulaire : 0 = jusqu'à 31 kg (jusqu'à 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

