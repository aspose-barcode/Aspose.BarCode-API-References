---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

Klasse voor het coderen en decoderen van de tekst die is ingebed in de 4‑state Royal Mailmark‑code.

Het type MailmarkCodetext exposeert de volgende leden:
## Constructors
| Name | Beschrijving |
| :- | :- |
| MailmarkCodetext() | Initialiseert een nieuw exemplaar van de MailmarkCodetext-klasse |
## Properties
| Name | Beschrijving |
| :- | :- |
| format | "0" – Null of Test<br/>            "1" – Brief<br/>            "2" – Grote Brief |
| version_id | Momenteel "1" – Voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik) |
| klass | "0" - Null of Test<br/>            "1" - 1C (Retail)<br/>            "2" - 2C (Retail)<br/>            "3" - 3C (Retail)<br/>            "4" - Premium (RetailPublishing Mail) (voor potentieel toekomstig gebruik)<br/>            "5" - Uitgesteld (Retail)<br/>            "6" - Air (Retail) (voor potentieel toekomstig gebruik)<br/>            "7" - Surface (Retail) (voor potentieel toekomstig gebruik)<br/>            "8" - Premium (Network Access)<br/>            "9" - Standaard (Network Access) |
| supply_chain_id | Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L. |
| item_id | Maximumwaarde is 99999999. |
| destination_post_code_and_dps | De PC en DP moeten voldoen aan een PAF-formaat.<br/>            Negen tekens lange tekenreeks die een internationale "XY11     " aangeeft (let op de 5 achterliggende spaties) of een patroon<br/>            van tekens die een binnenlandse sorteercode aangeeft.<br/>            Een binnenlandse sorteercode bestaat uit een outward postcode, een inward postcode en een Delivery Point Suffix. |
## Methods
| Name | Beschrijving |
| :- | :- |
| get_constructed_codetext() | Construeer codetext uit Mailmark-gegevens. |
| init_from_string(constructed_codetext) | Initialiseert Mailmark-gegevens vanuit geconstrueerde codetext. |
| get_barcode_type() | Verkrijgt barcode-type. |

### Zie ook

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

