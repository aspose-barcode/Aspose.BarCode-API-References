---
title: "classe Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "classe Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings. Parametri di decodifica AustraliaPost. Contiene parametri che influenzano i dati riconosciuti della simbologia AustraliaPost in C++."
type: docs
weight: 200
url: /it/cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


Parametri di decodifica AustraliaPost. Contiene parametri che influenzano i dati riconosciuti della simbologia AustraliaPost.

```cpp
class AustraliaPostSettings : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() const | Interfaccia pubblica per la decodifica del campo Customer Information, utilizzata nella simbologia AustraliaPost. |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() const | Ottiene il Tipo di Interpretazione per le Informazioni Cliente di AustralianPost [BarCode.Default](../checksumvalidation/) è [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() const | Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento nel campo Customer Information durante la decodifica con il metodo CTable. Il metodo di codifica CTable non presenta lacune nella tabella di codifica e la sequenza "333" dei pattern di riempimento viene decodificata come lettera "z". |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | Interfaccia pubblica per la decodifica del campo Customer Information, utilizzata nella simbologia AustraliaPost. |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | Imposta il Tipo di Interpretazione per le Informazioni Cliente di AustralianPost [BarCode.Default](../checksumvalidation/) è [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento nel campo Customer Information durante la decodifica con il metodo CTable. Il metodo di codifica CTable non presenta lacune nella tabella di codifica e la sequenza "333" dei pattern di riempimento viene decodificata come lettera "z". |
## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
