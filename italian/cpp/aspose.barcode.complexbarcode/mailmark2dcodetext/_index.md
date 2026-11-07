---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext class"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext class. Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mail 2D Mailmark in C++."
type: docs
weight: 1400
url: /it/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mail 2D Mailmark.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Class](./get_class/)() const | Identifica la classe dell'elemento. |
| [get_CustomerContent](./get_customercontent/)() const | Spazio opzionale per l'uso del cliente. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Modalità di codifica del codice a barre Datamatrix. Valore predefinito: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | Contiene il codice postale dell'[Indirizzo](../address/) di consegna con DPS. Se interno, il codice postale/DP contiene i seguenti numeri di caratteri: Area (1 o 2 caratteri) Distretto (1 o 2 caratteri) Settore (1 carattere) Unità (2 caratteri) DPS (2 caratteri). Il codice postale e il DPS devono rispettare un formato PAF® valido. |
| [get_InformationTypeID](./get_informationtypeid/)() const | Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. |
| [get_ItemID](./get_itemid/)() const | Identifica l'elemento unico all'interno dell'ID della catena di fornitura. Ogni codice a barre Mailmark deve contenere un ID affinché possa essere identificato in modo univoco per almeno 90 giorni. Valore massimo: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Contiene il codice postale di ritorno al mittente ma senza DPS. Il CP (senza DPS) deve rispettare un formato PAF®. |
| [get_RTSFlag](./get_rtsflag/)() const | Flag che indica quale livello di servizio di ritorno al mittente è richiesto. |
| [get_SupplyChainID](./get_supplychainid/)() const | Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri. |
| [get_VersionID](./get_versionid/)() const | Identifica la versione del codice a barre in base a ciascun ID tipo di informazione. |
| [GetBarcodeType](./getbarcodetype/)() override | Ottiene il tipo di codice a barre. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Costruisci il testo codificato dai dati Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | Inizializza i dati Mailmark dal testo codificato costruito. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | Costruttore. Crea un'istanza predefinita della classe [Mailmark2DCodetext](./). |
| [set_Class](./set_class/)(System::String) | Identifica la classe dell'elemento. |
| [set_CustomerContent](./set_customercontent/)(System::String) | Spazio opzionale per l'uso del cliente. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Modalità di codifica del codice a barre Datamatrix. Valore predefinito: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | Contiene il codice postale dell'[Indirizzo](../address/) di consegna con DPS. Se interno, il codice postale/DP contiene i seguenti numeri di caratteri: Area (1 o 2 caratteri) Distretto (1 o 2 caratteri) Settore (1 carattere) Unità (2 caratteri) DPS (2 caratteri). Il codice postale e il DPS devono rispettare un formato PAF® valido. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. |
| [set_ItemID](./set_itemid/)(int32_t) | Identifica l'elemento unico all'interno dell'ID della catena di fornitura. Ogni codice a barre Mailmark deve contenere un ID affinché possa essere identificato in modo univoco per almeno 90 giorni. Valore massimo: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Contiene il codice postale di ritorno al mittente ma senza DPS. Il CP (senza DPS) deve rispettare un formato PAF®. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | Flag che indica quale livello di servizio di ritorno al mittente è richiesto. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri. |
| [set_VersionID](./set_versionid/)(System::String) | Identifica la versione del codice a barre in base a ciascun ID tipo di informazione. |
## Vedi anche

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
