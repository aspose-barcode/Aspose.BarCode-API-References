---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext classe"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext classe. Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mailmark a 4 stati in C++."
type: docs
weight: 1500
url: /it/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mailmark a 4 stati.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - Nullo o Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (per uso futuro) "5" - Differito (Retail) "6" - Aria (Retail) (per uso futuro) "7" - Superficie (Retail) (per uso futuro) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | Il PC e il DP devono conformarsi a un formato PAF. Stringa di nove caratteri che indica l'internazionale "XY11     " (nota le 5 spazi finali) o un modello di caratteri che indica un codice di smistamento domestico. Un codice di smistamento domestico è composto da un codice postale esterno, un codice postale interno e un suffisso del punto di consegna. |
| [get_Format](./get_format/)() const | "0" – Nullo o Test "1" – Lettera "2" – Lettera grande |
| [get_ItemID](./get_itemid/)() const | Il valore massimo è 99999999. |
| [get_SupplychainID](./get_supplychainid/)() const | I valori massimi sono 99 per il codice a barre C e 999999 per il codice a barre L. |
| [get_VersionID](./get_versionid/)() const | Attualmente "1" – Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro) |
| [GetBarcodeType](./getbarcodetype/)() override | Ottiene il tipo di codice a barre. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Costruisci il testo codificato dai dati Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | Inizializza i dati Mailmark dal testo codificato costruito. |
| [MailmarkCodetext](./mailmarkcodetext/)() | Inizializza una nuova istanza della classe [MailmarkCodetext](./). |
| [set_Class](./set_class/)(System::String) | "0" - Nullo o Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (per uso futuro) "5" - Differito (Retail) "6" - Aria (Retail) (per uso futuro) "7" - Superficie (Retail) (per uso futuro) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | Il PC e il DP devono conformarsi a un formato PAF. Stringa di nove caratteri che indica l'internazionale "XY11     " (nota le 5 spazi finali) o un modello di caratteri che indica un codice di smistamento domestico. Un codice di smistamento domestico è composto da un codice postale esterno, un codice postale interno e un suffisso del punto di consegna. |
| [set_Format](./set_format/)(int32_t) | "0" – Nullo o Test "1" – Lettera "2" – Lettera grande |
| [set_ItemID](./set_itemid/)(int32_t) | Il valore massimo è 99999999. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | I valori massimi sono 99 per il codice a barre C e 999999 per il codice a barre L. |
| [set_VersionID](./set_versionid/)(int32_t) | Attualmente "1" – Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro) |
## Vedi anche

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
