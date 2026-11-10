---
title: "Κλάση AztecExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.AztecExtCodetextBuilder κλάση. Επεκταμένος γεννήτορας κώδικα κειμένου για γραμμωτούς κώδικες Aztec για τη λειτουργία ExtendedCodetext του AztecEncodeMode"
type: docs
weight: 950
url: /el/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

Εκτεταμένος δημιουργός κειμένου κώδικα για τα barcode Aztec για τη λειτουργία ExtendedCodetext του AztecEncodeMode

Χρησιμοποιήστε την ιδιότητα TwoDDisplayText του BarcodeGenerator για να ορίσετε το ορατό κείμενο αφαιρώντας χαρακτήρες διαχείρισης.

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Προσθέτει κώδικα κειμένου με Extended Channel Identifier |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Προσθέτει απλό κώδικα κειμένου στα στοιχεία του επεκταμένου κώδικα κειμένου |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Καθαρίζει τα στοιχεία του επεκταμένου κώδικα κειμένου |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | Δημιουργεί επεκταμένο κώδικα κειμένου από τη λίστα επεκταμένου κώδικα κειμένου. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το AztecExtCodetextBuilder σε λειτουργία Extended Mode.

```csharp
[C#]
//δημιουργία codetext
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//παραγωγή codetext
string codetext = textBuilder.GetExtendedCodetext();    

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Δείτε επίσης

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


