---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext classe"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext classe. Classe per la codifica e decodifica del codetext MaxiCode per le modalità 4, 5 e 6 in C++."
type: docs
weight: 2000
url: /it/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


Classe per la codifica e la decodifica del testo codificato MaxiCode per le modalità 4, 5 e 6.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [MaxiCodeStandardCodetext](./) specificato. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Ottiene la codifica ECI. Usata quando MaxiCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Ottiene una modalità di codifica MaxiCode. Valore predefinito: Auto. |
| [get_Message](./get_message/)() const | Ottiene il messaggio. |
| [get_Mode](./get_mode/)() | Ottiene la modalità MaxiCode. Il codetext standard può essere usato solo con le modalità 4, 5 e 6. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Ottiene il tipo di codice a barre. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Costruisce il codetext |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [GetMode](./getmode/)() const override | Ottiene la modalità MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | Inizializza l'istanza dal codetext costruito. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Imposta la codifica ECI. Usata quando MaxiCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Imposta una modalità di codifica MaxiCode. Valore predefinito: Auto. |
| [set_Message](./set_message/)(System::String) | Imposta il messaggio. |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | Imposta la modalità MaxiCode. Il codetext standard può essere usato solo con le modalità 4, 5 e 6. |
## Osservazioni


//Modalità 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Modalità 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Modalità 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## Vedi anche

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
