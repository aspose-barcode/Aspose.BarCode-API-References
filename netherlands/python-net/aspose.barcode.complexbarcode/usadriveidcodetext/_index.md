---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

Klasse voor het coderen en decoderen van de tekst die is ingebed in de USA Driving License PDF417‑code.

Het USADriveIdCodetext-type biedt de volgende leden:
## Constructors
| Name | Beschrijving |
| :- | :- |
| USADriveIdCodetext() | Initialiseert een nieuw exemplaar van de USADriveIdCodetext klasse |
## Properties
| Name | Beschrijving |
| :- | :- |
| issuer_identification_number | Dit nummer identificeert uniek <br/>            de uitgevende jurisdictie en kan verkregen worden door contact op te nemen met de ISO<br/>            Uitgevende Autoriteit(AAMVA).  Het volledige 6-cijferige IIN moet worden gecodeerd. |
| aamva_version_number | AAMVA Versienummer 00-99 |
| jurisdiction_version_number | Jurisdictie Versienummer 00-99 |
| number_of_entries | Aantal 00-99 subfiles |
| subfile_designator | Bevat informatie over de volgende subfiles, types, offsets en lengtes. <br/>            Belangrijk: alleen type instellen, offset en lengte worden automatisch ingesteld. |
| mandatory_elements | Verplichte elementen (velden) van de kaart |
| optional_elements | Optionele elementen (velden) van de kaart |
| jurisdiction_specific_subfile | Jurisdictiespecifieke velden |
## Methods
| Name | Beschrijving |
| :- | :- |
| get_constructed_codetext() | Construeer codetext vanuit USA DL-gegevens |
| init_from_string(constructed_codetext) | Initialiseer USA DL-object vanuit codetext |
| get_barcode_type() | Retourneert barcode-type van USA DL (Pdf417) |
| save_to_xml(stream) | Slaat op in XML |

### Zie ook

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

