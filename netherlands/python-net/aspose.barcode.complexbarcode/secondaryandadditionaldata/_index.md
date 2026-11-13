---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Klasse voor het opslaan van secundaire en aanvullende HIBC LIC‑gegevens.

Het type SecondaryAndAdditionalData exposeert de volgende leden:
## Constructors
| Name | Beschrijving |
| :- | :- |
| SecondaryAndAdditionalData() | Initialiseert een nieuw exemplaar van de klasse SecondaryAndAdditionalData |
## Properties
| Name | Beschrijving |
| :- | :- |
| expiry_date_format | Identificeert het formaat van de vervaldatum. |
| expiry_date | Identificeert vervaldatum. Wordt gebruikt als ExpiryDateFormat niet is ingesteld op None. |
| lot_number | Identificeert lot- of batchnummer. Het lot-/batchnummer moet een alfanumerieke string zijn met een maximale lengte van 18 tekens. |
| serial_number | Identificeert serienummer. Het serienummer moet een alfanumerieke string zijn met een maximale lengte van 18 tekens. |
| date_of_manufacture | Identificeert productiedatum.<br/>            De productiedatum kan worden ingesteld op DateTime.MinValue om dit veld niet te gebruiken.<br/>            Standaardwaarde: DateTime.MinValue |
| quantity | Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500. <br/>            Hoeveelheid kan worden ingesteld op -1 om dit veld niet te gebruiken.<br/>            Standaardwaarde: -1 |
## Methods
| Name | Beschrijving |
| :- | :- |
| parse_from_string(secondary_data_codetext) | Instantieert secundaire en extra aanvullende gegevens vanuit een tekenreeks volgens de HIBC LIC-specificatie. |

### Zie ook

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

