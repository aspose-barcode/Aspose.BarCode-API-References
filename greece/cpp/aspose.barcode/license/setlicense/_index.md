---
title: "μέθοδος"
linktitle: "SetLicense"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Εγκαθιστά την άδεια της βιβλιοθήκης σε C++."
type: docs
weight: 200
url: /el/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


Αδειοδοτεί τη βιβλιοθήκη.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseName | System::String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. |
## Σχόλια


Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

1. Ρητή διαδρομή.

2. Ο φάκελος που περιέχει το **Aspose** component assembly.

3. Ο φάκελος που περιέχει τη συναρμολόγηση κλήσης του πελάτη.

4. Ο φάκελος που περιέχει τη συναρμολόγηση εκκίνησης (startup).

5. Ένας ενσωματωμένος πόρος στη συναρμολόγηση κλήσης του πελάτη.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ρητή διαδρομή.

2. Ένας ενσωματωμένος πόρος στη συναρμολόγηση κλήσης του πελάτη.

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει το καλούντο assembly, στον φάκελο του entry assembly και, στη συνέχεια, στους ενσωματωμένους πόρους του καλούντος assembly.
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
@endverbatim
```


## Δείτε επίσης

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Αδειοδοτεί τη βιβλιοθήκη.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | System::SharedPtr\<System::IO::Stream\> | Μία ροή που περιέχει την άδεια. |
## Σχόλια



Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από μια ροή.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## Δείτε επίσης

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
