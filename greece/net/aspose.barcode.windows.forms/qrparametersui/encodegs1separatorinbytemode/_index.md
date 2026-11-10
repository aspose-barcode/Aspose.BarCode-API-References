---
title: "QrParametersUI.EncodeGS1SeparatorInByteMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα QrParametersUI. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιηθούν σε λειτουργία Byte για κώδικες QR και RectMicroQR"
type: docs
weight: 30
url: /el/net/aspose.barcode.windows.forms/qrparametersui/encodegs1separatorinbytemode/
---
## QrParametersUI.EncodeGS1SeparatorInByteMode property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιηθούν σε λειτουργία Byte για τους κωδικούς QR και RectMicroQR.

Εάν είναι ψευδές, οι διαχωριστές GS1 μπορεί να κωδικοποιηθούν ως '%' σε αλφαριθμητική λειτουργία σύμφωνα με την προδιαγραφή QR.

Εάν είναι αληθές, οι διαχωριστές ομάδας GS1 κωδικοποιούνται σε λειτουργία Byte ως ο χαρακτήρας 0x1D, και οι χαρακτήρες '%' επίσης κωδικοποιούνται σε λειτουργία Byte για να διατηρηθούν ως δεδομένα.

Αυτή η επιλογή μπορεί να βελτιώσει τη συμβατότητα με αποκωδικοποιητές που αναμένουν διαχωριστές ομάδας GS1 σε επίπεδο byte και αποτρέπει τους χαρακτήρες δεδομένων '%' από το να ερμηνευτούν ως διαχωριστές GS1.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### Δείτε επίσης

* class [QrParametersUI](../)
* namespace [Aspose.BarCode.Windows.Forms](../../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../../)


