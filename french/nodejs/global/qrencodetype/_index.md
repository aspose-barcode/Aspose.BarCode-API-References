---
title: "QREncodeType"
linktitle: "QREncodeType"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Mode de sélection QR / MicroQR."
type: docs
weight: 490
url: /fr/nodejs/global/qrencodetype/
---

## QREncodeType

Mode de sélection QR / MicroQR. Sélectionnez FORCE_QR pour les symboles QR standard, AUTO pour MicroQR. FORCE_MICRO_QR est utilisé pour la génération de symboles MicroQR fortement si cela est possible.

## Valeurs

| Nom | Description |
| --- | --- |
| AUTO | Le mode démarre la négociation de version du code-barres à partir de MicroQR V1 |
| FORCE_QR | Le mode démarre la négociation de version du code-barres à partir de QR V1 |
| FORCE_MICRO_QR | Le mode démarre la négociation de version du code-barres de MicroQR V1 à V4. Si les données ne peuvent pas être encodées en MicroQR, une exception est levée. |
