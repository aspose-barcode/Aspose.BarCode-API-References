---
title: "EnableChecksum"
linktitle: "EnableChecksum"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Activer la somme de contrôle lors de la génération pour les codes-barres 1D."
type: docs
weight: 250
url: /fr/nodejs/global/enablechecksum/
---

## EnableChecksum

Activer la somme de contrôle lors de la génération pour les codes-barres 1D. La valeur par défaut est considérée comme Oui pour les symbologies qui doivent contenir une somme de contrôle, et comme Non lorsque la somme de contrôle n'est possible que facultativement. Somme de contrôle jamais utilisée : Codabar. Somme de contrôle possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Somme de contrôle toujours utilisée : le reste des symbologies.

## Valeurs

| Nom | Description |
| --- | --- |
| DEFAULT | Si la somme de contrôle est requise par la spécification - elle sera jointe. |
| OUI | Utilisez toujours la somme de contrôle si possible. |
| NON | N'utilisez pas la somme de contrôle. |
