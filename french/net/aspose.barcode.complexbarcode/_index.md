---
title: "Aspose.BarCode.ComplexBarcode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Le Aspose.BarCode.ComplexBarcode contenant des classes générales pour l'implémentation des fonctions de génération de codes-barres complexes."
type: docs
weight: 40
url: /fr/net/aspose.barcode.complexbarcode/
---
Le **Aspose.BarCode.ComplexBarcode** contenant des classes générales pour la mise en œuvre de fonctions de génération de codes-barres complexes.

## Classes

| Classe | Description |
| --- | --- |
| [Address](./address/) | Adresse du créancier ou du débiteur. |
| [AlternativeScheme](./alternativescheme/) | Instructions du schéma de paiement alternatif |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator pour la génération d'images de codes-barres complexes côté serveur (p. ex. SwissQR). |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader décode le texte de code vers le type de code-barres complexe spécifié. |
| [GS1Codetext](./gs1codetext/) | Représente le texte de code GS1 pour l'encodage et le décodage sous forme d'une séquence ordonnée d'éléments d'Identifiant d'Application. L'ordre d'origine et les Identifiants d'Application répétés sont conservés. La représentation entre parenthèses a la forme (AI)valeur(AI)valeur. Une parenthèse ouvrante littérale '(' à l'intérieur d'une valeur doit être écrite comme \\(; c'est la seule séquence d'échappement prise en charge. Une parenthèse fermante ')' à l'intérieur d'une valeur ne nécessite pas d'échappement. |
| [GS1DigitalLink](./gs1digitallink/) | Représente le texte de code GS1 Digital Link pour l'encodage et le décodage sous forme d'une séquence ordonnée d'éléments d'Identifiant d'Application. L'ordre d'origine et les Identifiants d'Application répétés sont conservés. Le texte de code construit est une URI GS1 Digital Link non compressée. Les paramètres de requête et les fragments d'URI non GS1 sont ignorés lors de l'analyse. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code HIBC LIC qui stocke les données primaires et secondaires. |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Classe de base pour l'encodage et le décodage du texte intégré dans le code HIBC LIC. |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code HIBC LIC qui stocke les données primaires. |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code HIBC LIC qui stocke les données secondaires. |
| [HIBCPASCodetext](./hibcpascodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord/) | Classe pour le stockage du registre HIBC PAS. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mail 2D Mailmark. |
| [MailmarkCodetext](./mailmarkcodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mailmark à 4 états. |
| [MaxiCodeCodetext](./maxicodecodetext/) | Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode. |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Classe pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour les modes 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Classe pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour les modes 3. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Classe de base pour l'encodage et le décodage du second message pour le code-barres MaxiCode. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Classe pour l'encodage et le décodage du texte de code MaxiCode pour les modes 4, 5 et 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Classe pour l'encodage et le décodage du second message standard pour le code-barres MaxiCode. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour les modes 2 et 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Classe pour l'encodage et le décodage du second message structuré pour le code-barres MaxiCode. |
| [PrimaryData](./primarydata/) | Classe pour le stockage des données primaires HIBC LIC. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Classe pour le stockage des données secondaires et supplémentaires HIBC LIC. |
| [SwissQRBill](./swissqrbill/) | Données de facture SwissQR |
| [SwissQRCodetext](./swissqrcodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code SwissQR. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code PDF417 du permis de conduire USA. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Classe pour les champs spécifiques à la juridiction pour le permis de conduire USA |
## Interfaces

| Interface | Description |
| --- | --- |
| [IComplexCodetext](./icomplexcodetext/) | Interface pour le texte de code complexe utilisé avec ComplexBarcodeGenerator. |
## Énumération

| Énumération | Description |
| --- | --- |
| [AddressType](./addresstype/) | Type d'adresse |
| [HIBCLICDateFormat](./hibclicdateformat/) | Spécifie les différents types de formats de date pour HIBC LIC. |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | Types d'emplacements de données HIBC PAS. |
| [HIBCPASDataType](./hibcpasdatatype/) | Types de données de l'enregistrement HIBC PAS. |
| [Mailmark2DType](./mailmark2dtype/) | Le type 2D Mailmark définit la taille du code‑barres Data Matrix |
| [USADriveIdCountry](./usadriveidcountry/) | Énumération pour l'identification du pays dans le permis de conduire américain |
| [USADriveIdEyeColor](./usadriveideyecolor/) | Énumération pour la couleur des yeux dans le permis de conduire américain |
| [USADriveIdHairColor](./usadriveidhaircolor/) | Énumération pour la couleur des cheveux dans le permis de conduire américain |
| [USADriveIdSex](./usadriveidsex/) | Énumération pour le champ sexe dans le permis de conduire américain |


