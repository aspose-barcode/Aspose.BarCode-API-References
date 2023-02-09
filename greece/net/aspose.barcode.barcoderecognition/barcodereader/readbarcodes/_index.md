---
title: ReadBarCodes
second_title: Aspose.BarCode για Αναφορά API .NET
description: ΔιαβάζειBarCodeResultaspose.barcode.barcoderecognition/barcoderesult/ s από την εικόνα.
type: docs
weight: 100
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader.ReadBarCodes method

Διαβάζει[`BarCodeResult`](../../barcoderesult/) s από την εικόνα.

```csharp
public BarCodeResult[] ReadBarCodes()
```

### Επιστρεφόμενη Αξία

Επιστρέφει σειρά αναγνωρισμένων[`BarCodeResult`](../../barcoderesult/)s στην εικόνα. Εάν δεν αναγνωρίζεται τίποτα, επιστρέφεται μηδενικός πίνακας.

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να διαβάζετε γραμμικούς κώδικες με το BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using

Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Δείτε επίσης

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->