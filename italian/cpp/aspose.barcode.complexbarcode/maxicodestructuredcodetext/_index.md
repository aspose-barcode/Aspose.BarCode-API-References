---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext classe"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext classe. Classe base per la codifica e la decodifica del testo incorporato nel codice MaxiCode per le modalità 2 e 3 in C++."
type: docs
weight: 2200
url: /it/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


Classe base per la codifica e la decodifica del testo incorporato nel codice MaxiCode per le modalità 2 e 3.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [MaxiCodeStructuredCodetext](./) specificato. |
| [get_CountryCode](./get_countrycode/)() const | Identifica il codice paese a 3 cifre. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Ottiene la codifica ECI. Usata quando MaxiCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Ottiene una modalità di codifica MaxiCode. Valore predefinito: Auto. |
| [get_PostalCode](./get_postalcode/)() const | Identifica il codice postale. Deve essere di 9 cifre nella modalità 2 o di 6 simboli alfanumerici nella modalità 3. |
| [get_SecondMessage](./get_secondmessage/)() const | Identifica il secondo messaggio del codice a barre. |
| [get_ServiceCategory](./get_servicecategory/)() const | Identifica la categoria di servizio a 3 cifre. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Ottiene il tipo di codice a barre. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Costruisce il codetext |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | Ottiene la modalità MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | Inizializza l'istanza dal codetext costruito. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | Identifica il codice paese a 3 cifre. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Imposta la codifica ECI. Usata quando MaxiCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Imposta una modalità di codifica MaxiCode. Valore predefinito: Auto. |
| [set_PostalCode](./set_postalcode/)(System::String) | Identifica il codice postale. Deve essere di 9 cifre nella modalità 2 o di 6 simboli alfanumerici nella modalità 3. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identifica il secondo messaggio del codice a barre. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | Identifica la categoria di servizio a 3 cifre. |
## Osservazioni


Questo esempio mostra come decodificare il codetext MaxiCode grezzo in un'istanza [MaxiCodeStructuredCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

## Vedi anche

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
