---
title: "Κλάση DotCodeExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.Generation.DotCodeExtCodetextBuilder. Επεκτασμένος δημιουργός κωδικού κειμένου για 2D γραμμωτού κώδικα DotCode για τη λειτουργία ExtendedCodetext του DotCodeEncodeMode"
type: docs
weight: 1250
url: /el/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

Γεννήτρια εκτεταμένου κώδικα κειμένου για 2D DotCode barcode για τη λειτουργία ExtendedCodetext Mode του DotCodeEncodeMode

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Προσθέτει κώδικα κειμένου με Extended Channel Identifier |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | Προσθέτει το αναγνωριστικό μορφής FNC1 στα στοιχεία του επεκταμένου κωδικού κειμένου |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | Προσθέτει την αρχικοποίηση του αναγνώστη FNC3 στα στοιχεία του επεκταμένου κωδικού κειμένου |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | Προσθέτει το διαχωριστικό συμβόλου FNC3 στα στοιχεία του επεκταμένου κωδικού κειμένου |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Προσθέτει απλό κώδικα κειμένου στα στοιχεία του επεκταμένου κώδικα κειμένου |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | Προσθέτει τη λειτουργία δομημένης προσθήκης στα στοιχεία του επεκταμένου κωδικού κειμένου |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Καθαρίζει τα στοιχεία του επεκταμένου κώδικα κειμένου |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | Δημιουργεί επεκταμένο κώδικα κειμένου από τη λίστα επεκταμένου κώδικα κειμένου. |

## Παραδείγματα

```csharp
[C#]
//Λειτουργία Extended codetext
//δημιουργία codetext
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//παραγωγή codetext
string codetext = textBuilder.GetExtendedCodetext();    

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Δείτε επίσης

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


