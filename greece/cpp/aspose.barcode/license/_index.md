---
title: "Aspose::BarCode::License κλάση"
linktitle: "Άδεια"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::License κλάση. Παρέχει μεθόδους για την αδειοδότηση του στοιχείου σε C++."
type: docs
weight: 300
url: /el/cpp/aspose.barcode/license/
---
## License class


Παρέχει μεθόδους για την αδειοδότηση του στοιχείου.

```cpp
class License : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [License](./license/)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |
| [SetLicense](./setlicense/)(System::String) | Αδειοδοτεί τη βιβλιοθήκη. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | Αδειοδοτεί τη βιβλιοθήκη. |
## Σχόλια


Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει το καλούντο assembly, στον φάκελο του entry assembly και, στη συνέχεια, στους ενσωματωμένους πόρους του καλούντος assembly.
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
@endverbatim
```

## Δείτε επίσης

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
