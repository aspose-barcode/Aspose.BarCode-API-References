---
title: "License.SetLicense"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Μέθοδος License. Αδειοδοτεί τη βιβλιοθήκη"
type: docs
weight: 20
url: /el/net/aspose.barcode/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Αδειοδοτεί τη βιβλιοθήκη.

```csharp
public void SetLicense(string licenseName)
```

## Σχόλια

Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

1. Ρητή διαδρομή.

2. Ο φάκελος που περιέχει το σύνολο (assembly) του στοιχείου Aspose.

3. Ο φάκελος που περιέχει το σύνολο (assembly) κλήσης του πελάτη.

4. Ο φάκελος που περιέχει το κύριο (εκκίνηση) σύνολο (assembly).

5. Ένας ενσωματωμένος πόρος στο σύνολο (assembly) κλήσης του πελάτη.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ρητή διαδρομή.

2. Ένας ενσωματωμένος πόρος στο σύνολο (assembly) κλήσης του πελάτη.

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το component, στον φάκελο που περιέχει το calling assembly, στον φάκελο του entry assembly και, τέλος, στους ενσωματωμένους πόρους του calling assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου.

### Δείτε επίσης

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)

---

## SetLicense(Stream) {#setlicense}

Αδειοδοτεί τη βιβλιοθήκη.

```csharp
public void SetLicense(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ένα ρεύμα (stream) που περιέχει την άδεια. |

## Σχόλια

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από ένα ρεύμα.

## Παραδείγματα

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Δείτε επίσης

* class [License](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)


