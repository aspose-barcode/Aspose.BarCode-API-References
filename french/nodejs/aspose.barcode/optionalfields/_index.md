---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Éléments optionnels (champs) de la carte"
type: docs
weight: 730
url: /fr/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

Éléments optionnels (champs) de la carte

```js
new OptionalFields()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, autre nom de famille sous lequel le titulaire de la carte est connu, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, autre prénom sous lequel le titulaire de la carte est connu, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, autre suffixe sous lequel le titulaire de la carte est connu, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, une chaîne de lettres et/ou de chiffres qui identifie quand, où et par qui un permis de conduire/carte d'identité a été fabriqué. Si un |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, champ obligatoire DHS qui indique la date du changement de version le plus récent ou de la modification du format visible de t |
| [getComplianceType()](#getcompliancetype) | DDA, champ obligatoire DHS qui indique la conformité : « F » = conforme ; et, « N » = non conforme, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, texte qui explique le(s) code(s) spécifique(s) à la juridiction qui indique(nt) des privilèges de conduite supplémentaires accordés au ca |
| [getHairColor()](#gethaircolor) | DAZ, Chauve, noir, blond, brun, gris, rouge/auburn, sable, blanc, inconnu. Si la juridiction émettrice souhaite abréger |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, date à laquelle l'agrément de matière dangereuse accordé par le document n'est plus valide. (MMDDCCYY pour les États‑Unis, CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, une chaîne de lettres et/ou de chiffres qui est apposée aux matières premières (papier cartonné, stratifié, etc.) utilisées dans la produci |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, champ obligatoire DHS qui indique que le titulaire de la carte a un statut légal temporaire = « 1 », DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, suffixe de nom (Si la juridiction participe à des systèmes nécessitant un suffixe de nom (PDPS, CDLIS, etc.), le suffixe doit être |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, champ qui indique que le titulaire de la carte est donneur d'organes = « 1 », DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, pays et municipalité et/ou État/province, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, codes de race ou d'ethnicité du titulaire de la carte, tels que définis dans AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, texte décrivant le(s) code(s) de restriction spécifique(s) à la juridiction qui restreint(issent) les privilèges de conduite, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, code(s) d'agrément standard pour le titulaire de la carte. Voir les codes dans D20. Cet élément de données est un espace réservé pour de futurs travaux |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, code(s) de restriction standard pour le titulaire de la carte. Voir les codes dans D20. Cet élément de données est un espace réservé pour de futurs travaux |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, code(s) de classification de véhicule standard pour le titulaire de la carte. Cet élément de données est un espace réservé pour de futurs travaux à st |
| [getUnder18Until()](#getunder18until) | DDH, date à laquelle le titulaire de la carte atteint 18 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, date à laquelle le titulaire de la carte atteint 21 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, texte qui explique le(s) code(s) spécifique(s) à la juridiction pour les classifications de véhicules que le titulaire de la carte est autorisé à dr |
| [getVeteranIndicator()](#getveteranindicator) | DDL, champ qui indique que le titulaire de la carte est un vétéran = « 1 », DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, poids du titulaire de la carte en kilogrammes, ex. 84 kg = « 084 », DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, poids du titulaire de la carte en livres, ex. 185 lb = « 185 », DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, indique la fourchette de poids approximative du titulaire de la carte : 0 = jusqu'à 31 kg (jusqu'à 70 lb), 1 = 32 – 45 kg (71 – 100 lb |
| [setAddressStreet2()](#setaddressstreet2) | DAH, deuxième ligne de la partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, autre nom de famille sous lequel le titulaire de la carte est connu, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, autre prénom sous lequel le titulaire de la carte est connu, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, autre suffixe sous lequel le titulaire de la carte est connu, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, une chaîne de lettres et/ou de chiffres qui identifie quand, où et par qui un permis de conduire/carte d'identité a été fabriqué. Si un |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, champ obligatoire DHS qui indique la date du changement de version le plus récent ou de la modification du format visible de t |
| [setComplianceType()](#setcompliancetype) | DDA, champ obligatoire DHS qui indique la conformité : « F » = conforme ; et, « N » = non conforme, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, texte qui explique le(s) code(s) spécifique(s) à la juridiction qui indique(nt) des privilèges de conduite supplémentaires accordés au ca |
| [setHairColor()](#sethaircolor) | DAZ, Chauve, noir, blond, brun, gris, rouge/auburn, sable, blanc, inconnu. Si la juridiction émettrice souhaite abréger |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, une chaîne de lettres et/ou de chiffres qui est apposée aux matières premières (papier cartonné, stratifié, etc.) utilisées dans la produci |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, champ obligatoire DHS qui indique que le titulaire de la carte a un statut légal temporaire = « 1 », DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, suffixe de nom (Si la juridiction participe à des systèmes nécessitant un suffixe de nom (PDPS, CDLIS, etc.), le suffixe doit être |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, champ qui indique que le titulaire de la carte est donneur d'organes = « 1 », DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, pays et municipalité et/ou État/province, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, codes de race ou d'ethnicité du titulaire de la carte, tels que définis dans AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, texte décrivant le(s) code(s) de restriction spécifique(s) à la juridiction qui restreint(issent) les privilèges de conduite, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, code(s) d'agrément standard pour le titulaire de la carte. Voir les codes dans D20. Cet élément de données est un espace réservé pour de futurs travaux |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, code(s) de restriction standard pour le titulaire de la carte. Voir les codes dans D20. Cet élément de données est un espace réservé pour de futurs travaux |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, code(s) de classification de véhicule standard pour le titulaire de la carte. Cet élément de données est un espace réservé pour de futurs travaux à st |
| [setUnder18Until()](#setunder18until) | DDI, date à laquelle le titulaire de la carte atteint 19 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, date à laquelle le titulaire de la carte atteint 19 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, date à laquelle le titulaire de la carte atteint 21 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, texte qui explique le(s) code(s) spécifique(s) à la juridiction pour les classifications de véhicules que le titulaire de la carte est autorisé à dr |
| [setVeteranIndicator()](#setveteranindicator) | DDL, champ qui indique que le titulaire de la carte est un vétéran = « 1 », DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, poids du titulaire de la carte en kilogrammes, ex. 84 kg = « 084 », DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, poids du titulaire de la carte en livres, ex. 185 lb = « 185 », DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, indique la fourchette de poids approximative du titulaire de la carte : 0 = jusqu'à 31 kg (jusqu'à 70 lb), 1 = 32 – 45 kg (71 – 100 lb |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, autre nom de famille sous lequel le titulaire de la carte est connu, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, autre prénom sous lequel le titulaire de la carte est connu, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, autre suffixe sous lequel le titulaire de la carte est connu, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, une chaîne de lettres et/ou de chiffres qui identifie quand, où et par qui un permis de conduire/carte d'identité a été fabriqué. Si les informations d'audit ne sont pas utilisées sur la carte ou le MRT, elles doivent être incluses dans le dossier du conducteur, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, champ requis par le DHS qui indique la date du changement de version le plus récent ou de la modification du format visible du DL/ID. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, champ obligatoire DHS qui indique la conformité : « F » = conforme ; et, « N » = non conforme, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, texte qui explique le(s) code(s) spécifique(s) à la juridiction indiquant les privilèges de conduite supplémentaires accordés au titulaire au‑delà de la classe de véhicule, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, Chauve, noir, blond, brun, gris, rouge/roux, sable, blanc, inconnu. Si la juridiction émettrice souhaite abréger les couleurs, les codes à trois caractères fournis dans AAMVA D20 doivent être utilisés, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, date à laquelle l’endossement de matières dangereuses accordé par le document n’est plus valable. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, chaîne de lettres et/ou de chiffres apposée aux matières premières (papier, laminage, etc.) utilisées pour la production des permis de conduire et des cartes d’identité. (champ recommandé par le DHS), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, champ obligatoire DHS qui indique que le titulaire de la carte a un statut légal temporaire = « 1 », DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, suffixe de nom (Si la juridiction participe à des systèmes nécessitant un suffixe de nom (PDPS, CDLIS, etc.), le suffixe doit être recueilli et affiché sur le DL/ID et dans le MRT). JR (Junior), SR (Senior), 1ST ou I (Premier), jusqu’à 9TH ou IX (Neuvième), DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, champ qui indique que le titulaire de la carte est donneur d'organes = « 1 », DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, pays et municipalité et/ou État/province, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, codes de race ou d'ethnicité du titulaire de la carte, tels que définis dans AAMVA D20, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, texte décrivant le(s) code(s) de restriction spécifique(s) à la juridiction qui restreint(issent) les privilèges de conduite, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, code(s) d’endossement standard pour le titulaire. Voir les codes dans D20. Cet élément de données est un espace réservé aux futurs efforts de normalisation des codes d’endossement, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, code(s) de restriction standard pour le titulaire. Voir les codes dans D20. Cet élément de données est un espace réservé aux futurs efforts de normalisation des codes de restriction, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, code(s) de classification de véhicule standard pour le titulaire. Cet élément de données est un espace réservé aux futurs efforts de normalisation des classifications de véhicules, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, date à laquelle le titulaire de la carte atteint 18 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, date à laquelle le titulaire de la carte atteint 21 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, texte qui explique le(s) code(s) spécifique(s) à la juridiction pour les classifications de véhicules que le titulaire est autorisé à conduire, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, champ qui indique que le titulaire de la carte est un vétéran = « 1 », DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, poids du titulaire de la carte en kilogrammes, ex. 84 kg = « 084 », DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, poids du titulaire de la carte en livres, ex. 185 lb = « 185 », DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, indique la fourchette de poids approximative du titulaire : 0 = jusqu’à 31 kg (jusqu’à 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 – 59 kg (101 – 130 lb), 3 = 60 – 70 kg (131 – 160 lb), 4 = 71 – 86 kg (161 – 190 lb), 5 = 87 – 100 kg (191 – 220 lb), 6 = 101 – 113 kg (221 – 250 lb), 7 = 114 – 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146 + kg (321 + lb), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, deuxième ligne de la partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, autre nom de famille sous lequel le titulaire de la carte est connu, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, autre prénom sous lequel le titulaire de la carte est connu, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, autre suffixe sous lequel le titulaire de la carte est connu, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, une chaîne de lettres et/ou de chiffres qui identifie quand, où et par qui un permis de conduire/carte d'identité a été fabriqué. Si les informations d'audit ne sont pas utilisées sur la carte ou le MRT, elles doivent être incluses dans le dossier du conducteur, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, champ requis par le DHS qui indique la date du changement de version le plus récent ou de la modification du format visible du DL/ID. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, champ obligatoire DHS qui indique la conformité : « F » = conforme ; et, « N » = non conforme, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, texte qui explique le(s) code(s) spécifique(s) à la juridiction indiquant les privilèges de conduite supplémentaires accordés au titulaire au‑delà de la classe de véhicule, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, Chauve, noir, blond, brun, gris, rouge/roux, sable, blanc, inconnu. Si la juridiction émettrice souhaite abréger les couleurs, les codes à trois caractères fournis dans AAMVA D20 doivent être utilisés, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, chaîne de lettres et/ou de chiffres apposée aux matières premières (papier, laminage, etc.) utilisées pour la production des permis de conduire et des cartes d’identité. (champ recommandé par le DHS), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, champ obligatoire DHS qui indique que le titulaire de la carte a un statut légal temporaire = « 1 », DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, suffixe de nom (Si la juridiction participe à des systèmes nécessitant un suffixe de nom (PDPS, CDLIS, etc.), le suffixe doit être recueilli et affiché sur le DL/ID et dans le MRT). JR (Junior), SR (Senior), 1ST ou I (Premier), jusqu’à 9TH ou IX (Neuvième), DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, champ qui indique que le titulaire de la carte est donneur d'organes = « 1 », DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, pays et municipalité et/ou État/province, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, codes de race ou d'ethnicité du titulaire de la carte, tels que définis dans AAMVA D20, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, texte décrivant le(s) code(s) de restriction spécifique(s) à la juridiction qui restreint(issent) les privilèges de conduite, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, code(s) d’endossement standard pour le titulaire. Voir les codes dans D20. Cet élément de données est un espace réservé aux futurs efforts de normalisation des codes d’endossement, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, code(s) de restriction standard pour le titulaire. Voir les codes dans D20. Cet élément de données est un espace réservé aux futurs efforts de normalisation des codes de restriction, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, code(s) de classification de véhicule standard pour le titulaire. Cet élément de données est un espace réservé aux futurs efforts de normalisation des classifications de véhicules, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, date à laquelle le titulaire de la carte atteint 19 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, date à laquelle le titulaire de la carte atteint 19 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, date à laquelle le titulaire de la carte atteint 21 ans. (MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, texte qui explique le(s) code(s) spécifique(s) à la juridiction pour les classifications de véhicules que le titulaire est autorisé à conduire, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, champ qui indique que le titulaire de la carte est un vétéran = « 1 », DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, poids du titulaire de la carte en kilogrammes, ex. 84 kg = « 084 », DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, poids du titulaire de la carte en livres, ex. 185 lb = « 185 », DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, indique la fourchette de poids approximative du titulaire : 0 = jusqu’à 31 kg (jusqu’à 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 – 59 kg (101 – 130 lb), 3 = 60 – 70 kg (131 – 160 lb), 4 = 71 – 86 kg (161 – 190 lb), 5 = 87 – 100 kg (191 – 220 lb), 6 = 101 – 113 kg (221 – 250 lb), 7 = 114 – 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146 + kg (321 + lb), DL/ID, F1N
