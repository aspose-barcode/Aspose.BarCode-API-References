---
title: "μέθοδος"
linktitle: "set_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε τη μέθοδο set_EncodeGS1SeparatorInByteMode της κλάσης Aspose::BarCode::Generation::QrParameters σε C++."
type: docs
weight: 1800
url: /el/cpp/aspose.barcode.generation/qrparameters/set_encodegs1separatorinbytemode/
---
## QrParameters::set_EncodeGS1SeparatorInByteMode method




```cpp
void Aspose::BarCode::Generation::QrParameters::set_EncodeGS1SeparatorInByteMode(bool value)
```

## Σχόλια


Ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιούνται σε λειτουργία Byte για τους κωδικούς QR και RectMicroQR.

Εάν είναι ψευδές, οι διαχωριστές GS1 μπορεί να κωδικοποιηθούν ως '' σε αλφαριθμητική λειτουργία σύμφωνα με την προδιαγραφή QR.

Εάν είναι αληθές, οι διαχωριστές ομάδας GS1 κωδικοποιούνται σε λειτουργία Byte ως ο χαρακτήρας 0x1D, και οι χαρακτήρες '' κωδικοποιούνται επίσης σε λειτουργία Byte για να διατηρηθούν ως δεδομένα.

Αυτή η επιλογή μπορεί να βελτιώσει τη συμβατότητα με αποκωδικοποιητές που αναμένουν διαχωριστές ομάδας GS1 σε επίπεδο byte και αποτρέπει τους χαρακτήρες δεδομένων '' από το να ερμηνευτούν ως διαχωριστές GS1.
## Δείτε επίσης

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
