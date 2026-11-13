---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Klasse voor het coderen en decoderen van de tekst die is ingebed in de Royal Mail 2D Mailmark‑code.

Het Mailmark2DCodetext-type geeft de volgende leden weer:
## Constructors
| Name | Beschrijving |
| :- | :- |
| Mailmark2DCodetext() | Initialiseert een nieuw exemplaar van de Mailmark2DCodetext-klasse |
## Properties
| Name | Beschrijving |
| :- | :- |
| upu_country_id | Identificeert de UPU-land-ID. Maximale lengte: 4 tekens. |
| information_type_id | Identificeert de payload van de Royal Mail Mailmark-barcode voor elk producttype. |
| version_id | Identificeert de barcodeversie die relevant is voor elk Information Type ID. |
| klass | Identificeert de klasse van het item. |
| supply_chain_id | Identificeert de unieke groep klanten die bij de verzending betrokken zijn.<br/>            Max waarde: 9999999. |
| item_id | Identificeert het unieke item binnen de Supply Chain ID.<br/>            Elke Mailmark-barcode moet een ID bevatten<br/>            zodat het gedurende ten minste 90 dagen uniek kan worden geïdentificeerd.<br/>            Max waarde: 99999999. |
| destination_post_code_and_dps | Bevat de postcode van het afleveradres met DPS<br/>            Als het binnenland betreft, bevat de postcode/DP het volgende aantal tekens.<br/>            Gebied (1 of 2 tekens) District (1 of 2 tekens)<br/>            Sector (1 teken) Eenheid (2 tekens) DPS (2 tekens).<br/>            De postcode en DPS moeten voldoen aan een geldig PAF®-formaat. |
| rts_flag | Vlag die aangeeft welk niveau van Return to Sender-service wordt aangevraagd. |
| return_to_sender_post_code | Bevat de Return to Sender-postcode maar geen DPS.<br/>            De PC (zonder DPS) moet voldoen aan een PAF®-formaat. |
| customer_content | Optionele ruimte voor gebruik door de klant. |
| customer_content_encode_mode | Encodeermodus van de Datamatrix-barcode.<br/>            Standaardwaarde: EncodeMode.C40. |
| data_matrix_type | 2D Mailmark-type definieert de grootte van de Data Matrix-barcode. |
## Methods
| Name | Beschrijving |
| :- | :- |
| get_constructed_codetext() | Construeer codetext uit Mailmark-gegevens. |
| init_from_string(constructed_codetext) | Initialiseert Mailmark-gegevens vanuit geconstrueerde codetext. |
| get_barcode_type() | Verkrijgt barcode-type. |

### Zie ook

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

