---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext classe"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext classe. Classe per la codifica e decodifica del testo incorporato nel codice PDF417 della Patente di Guida USA in C++."
type: docs
weight: 2900
url: /it/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


Classe per la codifica e decodifica del testo incorporato nella Patente di Guida USA [License](../../aspose.barcode/license/) codice PDF417.

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | Numero di versione AAMVA 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | Questo numero identifica in modo univoco la giurisdizione emittente e può essere ottenuto contattando l'Autorità Emittente ISO (AAMVA). Il IIN a 6 cifre completo deve essere codificato. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | Campi specifici della giurisdizione |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | Numero di versione della giurisdizione 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | Elementi obbligatori (campi) della carta |
| [get_NumberOfEntries](./get_numberofentries/)() const | Numero 00-99 di sottofile |
| [get_OptionalElements](./get_optionalelements/)() const | Elementi opzionali (campi) della carta |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | Contiene informazioni sui seguenti sottofile, tipi, offset e lunghezze. Importante: impostare solo il tipo, offset e lunghezza verranno impostati automaticamente. |
| [GetBarcodeType](./getbarcodetype/)() override | Restituisce il tipo di codice a barre della DL USA (Pdf417) |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Costruisci il codetext dai dati DL USA |
| [InitFromString](./initfromstring/)(System::String) override | Inizializza l'oggetto DL USA dal codetext |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | Salva in XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | Numero di versione AAMVA 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | Questo numero identifica in modo univoco la giurisdizione emittente e può essere ottenuto contattando l'Autorità Emittente ISO (AAMVA). Il IIN a 6 cifre completo deve essere codificato. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | Campi specifici della giurisdizione |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | Numero di versione della giurisdizione 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | Elementi obbligatori (campi) della carta |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | Numero 00-99 di sottofile |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | Elementi opzionali (campi) della carta |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | Contiene informazioni sui seguenti sottofile, tipi, offset e lunghezze. Importante: impostare solo il tipo, offset e lunghezza verranno impostati automaticamente. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | Costruttore predefinito |
## Vedi anche

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
