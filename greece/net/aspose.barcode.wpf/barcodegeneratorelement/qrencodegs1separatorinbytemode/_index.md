---
title: "BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "BarcodeGeneratorElement ιδιότητα. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιούνται σε λειτουργία Byte για κωδικούς QR και RectMicroQR"
type: docs
weight: 1290
url: /el/net/aspose.barcode.wpf/barcodegeneratorelement/qrencodegs1separatorinbytemode/
---
## BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιηθούν σε λειτουργία Byte για τους κωδικούς QR και RectMicroQR.

Εάν είναι ψευδές, οι διαχωριστές GS1 μπορεί να κωδικοποιηθούν ως '%' σε αλφαριθμητική λειτουργία σύμφωνα με την προδιαγραφή QR.

Εάν είναι αληθές, οι διαχωριστές ομάδας GS1 κωδικοποιούνται σε λειτουργία Byte ως ο χαρακτήρας 0x1D, και οι χαρακτήρες '%' επίσης κωδικοποιούνται σε λειτουργία Byte για να διατηρηθούν ως δεδομένα.

Αυτή η επιλογή μπορεί να βελτιώσει τη συμβατότητα με αποκωδικοποιητές που αναμένουν διαχωριστές ομάδας GS1 σε επίπεδο byte και αποτρέπει τους χαρακτήρες δεδομένων '%' από το να ερμηνευτούν ως διαχωριστές GS1.

```csharp
public bool QREncodeGS1SeparatorInByteMode { get; set; }
```

### Δείτε επίσης

* class [BarcodeGeneratorElement](../)
* namespace [Aspose.BarCode.WPF](../../../aspose.barcode.wpf/)
* assembly [Aspose.BarCode](../../../)


