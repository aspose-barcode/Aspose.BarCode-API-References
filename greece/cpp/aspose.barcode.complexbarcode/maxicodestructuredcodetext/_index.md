---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext κλάση"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext κλάση. Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα MaxiCode για λειτουργίες 2 και 3 σε C++."
type: docs
weight: 2200
url: /el/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode για λειτουργίες 2 και 3.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [MaxiCodeStructuredCodetext](./) τιμή. |
| [get_CountryCode](./get_countrycode/)() const | Αναγνωρίζει κωδικό χώρας 3 ψηφίων. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Λαμβάνει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto. |
| [get_PostalCode](./get_postalcode/)() const | Αναγνωρίζει τον ταχυδρομικό κώδικα. Πρέπει να είναι 9 ψηφία στη λειτουργία 2 ή 6 αλφαριθμητικά σύμβολα στη λειτουργία 3. |
| [get_SecondMessage](./get_secondmessage/)() const | Αναγνωρίζει το δεύτερο μήνυμα του barcode. |
| [get_ServiceCategory](./get_servicecategory/)() const | Αναγνωρίζει την κατηγορία υπηρεσίας 3 ψηφίων. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Λαμβάνει τον τύπο barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Δημιουργεί κείμενο κώδικα |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | Λαμβάνει τη λειτουργία MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | Αναγνωρίζει κωδικό χώρας 3 ψηφίων. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto. |
| [set_PostalCode](./set_postalcode/)(System::String) | Αναγνωρίζει τον ταχυδρομικό κώδικα. Πρέπει να είναι 9 ψηφία στη λειτουργία 2 ή 6 αλφαριθμητικά σύμβολα στη λειτουργία 3. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Αναγνωρίζει το δεύτερο μήνυμα του barcode. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | Αναγνωρίζει την κατηγορία υπηρεσίας 3 ψηφίων. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να αποκωδικοποιήσετε ακατέργαστο κείμενο κώδικα MaxiCode σε παρουσία [MaxiCodeStructuredCodetext](./).
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

## Δείτε επίσης

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
