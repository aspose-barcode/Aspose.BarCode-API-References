---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2 klass"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2 klass. Klass för kodning och avkodning av texten som är inbäddad i MaxiCode-koden för läge 2 i C++."
type: docs
weight: 1700
url: /sv/cpp/aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
## MaxiCodeCodetextMode2 class


Klass för kodning och avkodning av texten som är inbäddad i MaxiCode-koden för läge 2.

```cpp
class MaxiCodeCodetextMode2 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/) värde. |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() const | Identifierar 3-siffrig landskod. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Hämtar ECI-kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Hämtar ett MaxiCode-kodningsläge. Standardvärde: Auto. |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() const | Identifierar postnumret. Måste vara 9 siffror i läge 2 eller 6 alfanumeriska tecken i läge 3. |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | Identifierar andra meddelandet i streckkoden. |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() const | Identifierar 3-siffrig servicekategori. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Hämtar streckkodstyp. |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | Konstruerar kodtext |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [GetMode](./getmode/)() const override | Hämtar MaxiCode-läge. |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | Initierar objektet från konstruerad kodtext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | Identifierar 3-siffrig landskod. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Ställer in ECI-kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Ställer in ett MaxiCode-kodningsläge. Standardvärde: Auto. |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | Identifierar postnumret. Måste vara 9 siffror i läge 2 eller 6 alfanumeriska tecken i läge 3. |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identifierar andra meddelandet i streckkoden. |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | Identifierar 3-siffrig servicekategori. |
## Anmärkningar


Detta exempel visar hur man kodar och avkodar MaxiCode-kodtext för läge 2.
```cpp
[C#]
//Läge 2 med standard andra meddelandet
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Läge 2 med strukturerat andra meddelandet
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
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
//Avkodning av rå kodtext med standard andra meddelandet
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
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
//Avkodning av rå kodtext med strukturerat andra meddelandet
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
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

## Se även

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
