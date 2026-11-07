---
title: "Aspose::BarCode::ComplexBarcode namespace"
linktitle: "Aspose::BarCode::ComplexBarcode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare il namespace Aspose::BarCode::ComplexBarcode in C++."
type: docs
weight: 1100
url: /it/cpp/aspose.barcode.complexbarcode/
---



## Classi

| Classe | Descrizione |
| --- | --- |
| [Address](./address/) | [Indirizzo](./address/) di creditore o debitore. |
| [AlternativeScheme](./alternativescheme/) | Istruzioni per lo schema di pagamento alternativo |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | [ComplexBarcodeGenerator](./complexbarcodegenerator/) per la generazione di immagini di codici a barre complessi backend (ad es. SwissQR). |
| [ComplexCodetextReader](./complexcodetextreader/) | [ComplexCodetextReader](./complexcodetextreader/) decodifica il testo del codice nel tipo di codice a barre complesso specificato. |
| [GS1Codetext](./gs1codetext/) | Rappresenta il codetext GS1 per la codifica e decodifica come una sequenza ordinata di elementi Identificatore di Applicazione. L'ordine di origine e gli Identificatori di Applicazione ripetuti sono conservati. La rappresentazione tra parentesi ha la forma (AI)valore(AI)valore. Una parentesi aperta letterale '(' all'interno di un valore deve essere scritta come (; questa è l'unica sequenza di escape supportata. Una parentesi chiusa ')' all'interno di un valore non richiede escape. |
| [GS1DigitalLink](./gs1digitallink/) | Rappresenta il codetext GS1 Digital Link per la codifica e decodifica come una sequenza ordinata di elementi Identificatore di Applicazione. L'ordine di origine e gli Identificatori di Applicazione ripetuti sono conservati. Il codetext costruito è un URI GS1 Digital Link non compresso. I parametri di query e i frammenti URI non GS1 vengono ignorati durante l'analisi. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza dati primari e secondari. |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Classe base per la codifica e decodifica del testo incorporato nel codice HIBC LIC. |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza dati primari. |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza dati secondari. |
| [HIBCPASCodetext](./hibcpascodetext/) | Classe per la codifica e decodifica del testo incorporato nel codice HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord/) | Classe per la memorizzazione del record HIBC PAS. |
| [IComplexCodetext](./icomplexcodetext/) | Interfaccia per il codetext complesso utilizzato con [ComplexBarcodeGenerator](./complexbarcodegenerator/). |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mail 2D Mailmark. |
| [MailmarkCodetext](./mailmarkcodetext/) | Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mailmark a 4 stati. |
| [MaxiCodeCodetext](./maxicodecodetext/) | Classe base per la codifica e la decodifica del testo incorporato nel codice MaxiCode. |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Classe per la codifica e la decodifica del testo incorporato nel codice MaxiCode per la modalità 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Classe per la codifica e la decodifica del testo incorporato nel codice MaxiCode per la modalità 3. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Classe base per la codifica e la decodifica del secondo messaggio per il codice a barre MaxiCode. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Classe per la codifica e la decodifica del testo codificato MaxiCode per le modalità 4, 5 e 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Classe per la codifica e la decodifica del messaggio secondario standard per il codice a barre MaxiCode. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Classe base per la codifica e la decodifica del testo incorporato nel codice MaxiCode per le modalità 2 e 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Classe per la codifica e la decodifica del secondo messaggio strutturato per il codice a barre MaxiCode. |
| [Payments](./payments/) | Validazioni dei campi relative agli standard di pagamento svizzeri. |
| [PrimaryData](./primarydata/) | Classe per l'archiviazione dei dati primari HIBC LIC. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Classe per l'archiviazione dei dati secondari e aggiuntivi HIBC LIC. |
| [SwissQRBill](./swissqrbill/) | Dati della fattura SwissQR |
| [SwissQRCodetext](./swissqrcodetext/) | Classe per la codifica e la decodifica del testo incorporato nel codice SwissQR. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Classe per la codifica e la decodifica del testo incorporato nel codice PDF417 della patente di guida USA [License](../aspose.barcode/license/). |
| [USADriveIdHelper](./usadriveidhelper/) |  |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Classe per i campi specifici della giurisdizione per USA DL |
## Enums

| Enumerazione | Descrizione |
| --- | --- |
| [HIBCLICDateFormat](./hibclicdateformat/) | Specifica i diversi tipi di formati data per HIBC LIC. |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | Tipi di posizione dei dati HIBC PAS. |
| [HIBCPASDataType](./hibcpasdatatype/) | Tipi di dati del record HIBC PAS. |
| [Mailmark2DType](./mailmark2dtype/) | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix |
| [Mailmark1DType](./mailmark1dtype/) | Tipi di codice a barre Mailmark a 4 stati |
| [AddressType](./addresstype/) | [Address](./address/) tipo |
| [USADriveIdSex](./usadriveidsex/) | Enum per il campo Sesso nella [License](../aspose.barcode/license/) del conducente USA |
| [USADriveIdCountry](./usadriveidcountry/) | Enum per l'Identificazione del Paese nella [License](../aspose.barcode/license/) del conducente USA |
| [USADriveIdEyeColor](./usadriveideyecolor/) | Enum per il colore degli occhi nella [Licenza](../aspose.barcode/license/) di guida statunitense |
| [USADriveIdHairColor](./usadriveidhaircolor/) | Enum per il colore dei capelli nella [Licenza](../aspose.barcode/license/) di guida statunitense |
