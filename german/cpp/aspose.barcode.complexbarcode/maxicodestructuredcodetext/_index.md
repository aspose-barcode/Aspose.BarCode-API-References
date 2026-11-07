---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext Klasse"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext Klasse. Basisklasse für das Codieren und Dekodieren des in den MaxiCode-Code eingebetteten Textes für die Modi 2 und 3 in C++."
type: docs
weight: 2200
url: /de/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


Basisklasse zum Codieren und Dekodieren des im MaxiCode-Code für die Modi 2 und 3 eingebetteten Textes.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [MaxiCodeStructuredCodetext](./)-Wert entspricht. |
| [get_CountryCode](./get_countrycode/)() const | Identifiziert den 3-stelligen Ländercode. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Ruft die ECI-Codierung ab. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Ruft einen MaxiCode-Codierungsmodus ab. Standardwert: Auto. |
| [get_PostalCode](./get_postalcode/)() const | Identifiziert die Postleitzahl. Muss 9 Ziffern im Modus 2 oder 6 alphanumerische Zeichen im Modus 3 sein. |
| [get_SecondMessage](./get_secondmessage/)() const | Identifiziert die zweite Nachricht des Barcodes. |
| [get_ServiceCategory](./get_servicecategory/)() const | Identifiziert die 3-stellige Servicekategorie. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Liest den Barcode-Typ. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Erstellt Codetext |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | Ruft den MaxiCode-Modus ab. |
| [InitFromString](./initfromstring/)(System::String) override | Initialisiert die Instanz aus dem erstellten Codetext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | Identifiziert den 3-stelligen Ländercode. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Setzt die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Setzt einen MaxiCode-Codierungsmodus. Standardwert: Auto. |
| [set_PostalCode](./set_postalcode/)(System::String) | Identifiziert die Postleitzahl. Muss 9 Ziffern im Modus 2 oder 6 alphanumerische Zeichen im Modus 3 sein. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identifiziert die zweite Nachricht des Barcodes. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | Identifiziert die 3-stellige Servicekategorie. |
## Hinweise


Dieses Beispiel zeigt, wie roher MaxiCode-Codetext in eine [MaxiCodeStructuredCodetext](./)-Instanz dekodiert wird.
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

## Siehe auch

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
