---
title: "Κλάση MaxiCodeExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.Generation.MaxiCodeExtCodetextBuilder. Επεκταμένος γεννήτορας κώδικα για barcodes MaxiCode για τη λειτουργία ExtendedCodetext του MaxiCodeEncodeMode"
type: docs
weight: 1470
url: /el/net/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

Γεννήτρια εκτεταμένου κώδικα κειμένου για MaxiCode barcode για τη λειτουργία ExtendedCodetext Mode του MaxiCodeEncodeMode

Χρησιμοποιήστε την ιδιότητα TwoDDisplayText του BarcodeGenerator για να ορίσετε το ορατό κείμενο αφαιρώντας χαρακτήρες διαχείρισης.

```csharp
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](maxicodeextcodetextbuilder/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Προσθέτει κώδικα κειμένου με Extended Channel Identifier |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Προσθέτει απλό κώδικα κειμένου στα στοιχεία του επεκταμένου κώδικα κειμένου |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Καθαρίζει τα στοιχεία του επεκταμένου κώδικα κειμένου |
| override [GetExtendedCodetext](../../aspose.barcode.generation/maxicodeextcodetextbuilder/getextendedcodetext/)() | Δημιουργεί επεκταμένο κώδικα κειμένου από τη λίστα επεκταμένου κώδικα κειμένου. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το MaxiCodeExtCodetextBuilder σε επεκταμένη λειτουργία.

```csharp
[C#]
//δημιουργία codetext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//παραγωγή codetext
string codetext = textBuilder.GetExtendedCodetext();    

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Δείτε επίσης

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


