---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext classe"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext classe. Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode in C++."
type: docs
weight: 1600
url: /it/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


Classe base per la codifica e la decodifica del testo incorporato nel codice MaxiCode.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Ottiene la codifica ECI. Usata quando MaxiCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Ottiene una modalità di codifica MaxiCode. Valore predefinito: Auto. |
| [GetBarcodeType](./getbarcodetype/)() override | Ottiene il tipo di codice a barre. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Costruisce il codetext |
| virtual [GetMode](./getmode/)() const | Ottiene la modalità MaxiCode. |
| virtual [InitFromString](./initfromstring/)(System::String) | Inizializza l'istanza dal codetext costruito. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | Imposta la codifica ECI. Usata quando MaxiCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | Imposta una modalità di codifica MaxiCode. Valore predefinito: Auto. |
## Osservazioni


Questo esempio mostra come decodificare il codetext grezzo MaxiCode in un'istanza [MaxiCodeCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## Vedi anche

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
