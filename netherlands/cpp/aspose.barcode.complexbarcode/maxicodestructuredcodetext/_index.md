---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext klasse"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext klasse. Basisklasse voor het coderen en decoderen van de tekst die is ingebed in de MaxiCode-code voor modus 2 en 3 in C++."
type: docs
weight: 2200
url: /nl/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


Basisklasse voor het coderen en decoderen van de in de MaxiCode-code ingebedde tekst voor modus 2 en 3.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Geeft een waarde terug die aangeeft of deze instantie gelijk is aan een opgegeven [MaxiCodeStructuredCodetext](./) waarde. |
| [get_CountryCode](./get_countrycode/)() const | Identificeert de 3-cijferige landcode. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Haalt ECI-codering op. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Haalt een MaxiCode-codemodus op. Standaardwaarde: Auto. |
| [get_PostalCode](./get_postalcode/)() const | Identificeert de postcode. Moet 9 cijfers zijn in modus 2 of 6 alfanumerieke tekens in modus 3. |
| [get_SecondMessage](./get_secondmessage/)() const | Identificeert het tweede bericht van de barcode. |
| [get_ServiceCategory](./get_servicecategory/)() const | Identificeert de 3-cijferige servicecategorie. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Haalt het type barcode op. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construeert codetext |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | Haalt MaxiCode-modus op. |
| [InitFromString](./initfromstring/)(System::String) override | Initialiseert instantie vanuit geconstrueerde codetext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | Identificeert de 3-cijferige landcode. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Stelt ECI-codering in. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Stelt een MaxiCode-codemodus in. Standaardwaarde: Auto. |
| [set_PostalCode](./set_postalcode/)(System::String) | Identificeert de postcode. Moet 9 cijfers zijn in modus 2 of 6 alfanumerieke tekens in modus 3. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identificeert het tweede bericht van de barcode. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | Identificeert de 3-cijferige servicecategorie. |
## Opmerkingen


Dit voorbeeld toont hoe ruwe MaxiCode-codetekst te decoderen naar een [MaxiCodeStructuredCodetext](./) instantie.
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

## Zie ook

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
