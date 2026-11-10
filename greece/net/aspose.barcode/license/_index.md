---
title: "Κλάση License"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.License. Παρέχει μεθόδους για την αδειοδότηση του στοιχείου"
type: docs
weight: 1760
url: /el/net/aspose.barcode/license/
---
## License class

Παρέχει μεθόδους για την άδεια του στοιχείου.

```csharp
public class License
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [License](license/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense)(Stream) | Αδειοδοτεί τη βιβλιοθήκη. |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense_1)(string) | Αδειοδοτεί τη βιβλιοθήκη. |

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το component, στον φάκελο που περιέχει το calling assembly, στον φάκελο του entry assembly και, τέλος, στους ενσωματωμένους πόρους του calling assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Δείτε επίσης

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


