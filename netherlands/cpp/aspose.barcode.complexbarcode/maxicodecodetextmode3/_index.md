---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode3 klasse"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode3 klasse. Klasse voor het coderen en decoderen van de tekst die is ingebed in de MaxiCode-code voor modus 3 in C++."
type: docs
weight: 1800
url: /nl/cpp/aspose.barcode.complexbarcode/maxicodecodetextmode3/
---
## MaxiCodeCodetextMode3 class


Klasse voor het coderen en decoderen van de in de MaxiCode-code ingebedde tekst voor modus 3.

```cpp
class MaxiCodeCodetextMode3 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | Geeft een waarde terug die aangeeft of deze instantie gelijk is aan een opgegeven [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/) waarde. |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() const | Identificeert de 3-cijferige landcode. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Haalt ECI-codering op. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Haalt een MaxiCode-codemodus op. Standaardwaarde: Auto. |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() const | Identificeert de postcode. Moet 9 cijfers zijn in modus 2 of 6 alfanumerieke tekens in modus 3. |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | Identificeert het tweede bericht van de barcode. |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() const | Identificeert de 3-cijferige servicecategorie. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Haalt het type barcode op. |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | Construeert codetext |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [GetMode](./getmode/)() const override | Haalt MaxiCode-modus op. |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | Initialiseert instantie vanuit geconstrueerde codetext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | Identificeert de 3-cijferige landcode. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Stelt ECI-codering in. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Stelt een MaxiCode-codemodus in. Standaardwaarde: Auto. |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | Identificeert de postcode. Moet 9 cijfers zijn in modus 2 of 6 alfanumerieke tekens in modus 3. |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identificeert het tweede bericht van de barcode. |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | Identificeert de 3-cijferige servicecategorie. |
## Opmerkingen


Dit voorbeeld toont hoe MaxiCode-codetekst te coderen en te decoderen voor modus 3.
```cpp
[C#]
//Modus 3 met standaard tweede bericht
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Modus 3 met gestructureerd tweede bericht
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Decoderen van ruwe codetekst met standaard tweede bericht
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode3){
            MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStandardSecondMessage){
                MaxiCodeStandardSecondMessage secondMessage = (MaxiCodeStandardSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message: " + secondMessage.Message);
            }
        }
    }
}
//Decoderen van ruwe codetekst met gestructureerd tweede bericht
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode3){
            MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStructuredSecondMessage){
                MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message:");
                foreach (var identifier in secondMessage.Identifiers){
                    Console.WriteLine(identifier);
                }
            }
        }
    }
}
```

## Zie ook

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
