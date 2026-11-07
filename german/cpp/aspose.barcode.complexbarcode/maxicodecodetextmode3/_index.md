---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode3 Klasse"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode3 Klasse. Klasse für das Codieren und Dekodieren des in den MaxiCode-Code eingebetteten Textes für den Modus 3 in C++."
type: docs
weight: 1800
url: /de/cpp/aspose.barcode.complexbarcode/maxicodecodetextmode3/
---
## MaxiCodeCodetextMode3 class


Klasse zum Codieren und Dekodieren des im MaxiCode-Code für Modus 3 eingebetteten Textes.

```cpp
class MaxiCodeCodetextMode3 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)-Wert entspricht. |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() const | Identifiziert den 3-stelligen Ländercode. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Ruft die ECI-Codierung ab. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Ruft einen MaxiCode-Codierungsmodus ab. Standardwert: Auto. |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() const | Identifiziert die Postleitzahl. Muss 9 Ziffern im Modus 2 oder 6 alphanumerische Zeichen im Modus 3 sein. |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | Identifiziert die zweite Nachricht des Barcodes. |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() const | Identifiziert die 3-stellige Servicekategorie. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Liest den Barcode-Typ. |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | Erstellt Codetext |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [GetMode](./getmode/)() const override | Ruft den MaxiCode-Modus ab. |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | Initialisiert die Instanz aus dem erstellten Codetext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | Identifiziert den 3-stelligen Ländercode. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Setzt die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Setzt einen MaxiCode-Codierungsmodus. Standardwert: Auto. |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | Identifiziert die Postleitzahl. Muss 9 Ziffern im Modus 2 oder 6 alphanumerische Zeichen im Modus 3 sein. |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identifiziert die zweite Nachricht des Barcodes. |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | Identifiziert die 3-stellige Servicekategorie. |
## Hinweise


Dieses Beispiel zeigt, wie MaxiCode-Codetext für Modus 3 codiert und dekodiert wird.
```cpp
[C#]
//Modus 3 mit standardmäßiger zweiter Nachricht
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
//Modus 3 mit strukturierter zweiter Nachricht
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
//Dekodieren von rohem Codetext mit standardmäßiger zweiter Nachricht
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
//Dekodieren von rohem Codetext mit strukturierter zweiter Nachricht
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

## Siehe auch

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
