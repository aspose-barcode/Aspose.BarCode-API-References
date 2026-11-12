---
title: "EnableChecksum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Prüfsumme während der Erzeugung für 1D-Barcodes aktivieren."
type: docs
weight: 250
url: /de/nodejs/global/enablechecksum/
---

## EnableChecksum

Prüfsumme während der Erzeugung für 1D-Barcodes aktivieren. Standardmäßig wird Yes (Ja) verwendet für Symbologien, die zwingend eine Prüfsumme enthalten müssen, und No (Nein) dort, wo eine Prüfsumme nur optional ist. Prüfsumme wird nie verwendet: Codabar. Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Prüfsumme wird immer verwendet: alle übrigen Symbologien.

## Werte

| Name | Beschreibung |
| --- | --- |
| DEFAULT | Falls die Prüfsumme gemäß der Spezifikation erforderlich ist - sie wird angehängt. |
| YES | Prüfsumme immer verwenden, wenn möglich. |
| NO | Keine Prüfsumme verwenden. |
