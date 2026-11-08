---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext klass"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext klass. Basisklass för kodning och avkodning av text som är inbäddad i MaxiCode-koden för lägen 2 och 3 i C++."
type: docs
weight: 2200
url: /sv/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


Basklass för kodning och avkodning av texten som är inbäddad i MaxiCode-koden för lägena 2 och 3.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [MaxiCodeStructuredCodetext](./) värde. |
| [get_CountryCode](./get_countrycode/)() const | Identifierar 3-siffrig landskod. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Hämtar ECI-kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Hämtar ett MaxiCode-kodningsläge. Standardvärde: Auto. |
| [get_PostalCode](./get_postalcode/)() const | Identifierar postnumret. Måste vara 9 siffror i läge 2 eller 6 alfanumeriska tecken i läge 3. |
| [get_SecondMessage](./get_secondmessage/)() const | Identifierar andra meddelandet i streckkoden. |
| [get_ServiceCategory](./get_servicecategory/)() const | Identifierar 3-siffrig servicekategori. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Hämtar streckkodstyp. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Konstruerar kodtext |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | Hämtar MaxiCode-läge. |
| [InitFromString](./initfromstring/)(System::String) override | Initierar objektet från konstruerad kodtext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | Identifierar 3-siffrig landskod. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Ställer in ECI-kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Ställer in ett MaxiCode-kodningsläge. Standardvärde: Auto. |
| [set_PostalCode](./set_postalcode/)(System::String) | Identifierar postnumret. Måste vara 9 siffror i läge 2 eller 6 alfanumeriska tecken i läge 3. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identifierar andra meddelandet i streckkoden. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | Identifierar 3-siffrig servicekategori. |
## Anmärkningar


Detta exempel visar hur man avkodar rå MaxiCode-kodtext till en [MaxiCodeStructuredCodetext](./)-instans.
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

## Se även

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
