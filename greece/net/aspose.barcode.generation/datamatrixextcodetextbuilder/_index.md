---
title: "Κλάση DataMatrixExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder κλάση. Επεκταμένος γεννήτορας κώδικα κειμένου για 2D DataMatrix γραμμωτούς κώδικες για τη λειτουργία ExtendedCodetext του EncodeMode"
type: docs
weight: 1210
url: /el/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

Γεννήτρια εκτεταμένου κώδικα κειμένου για 2D DataMatrix barcode για τη λειτουργία ExtendedCodetext Mode του EncodeMode

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | Προσθέτει κώδικα κειμένου με καθορισμένη λειτουργία κωδικοποίησης στα στοιχεία του επεκταμένου κώδικα κειμένου |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Προσθέτει κώδικα κειμένου με Extended Channel Identifier |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | Προσθέτει κώδικα κειμένου με Extended Channel Identifier με καθορισμένη λειτουργία κωδικοποίησης |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Προσθέτει απλό κώδικα κειμένου στα στοιχεία του επεκταμένου κώδικα κειμένου |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Καθαρίζει τα στοιχεία του επεκταμένου κώδικα κειμένου |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | Δημιουργεί επεκταμένο κώδικα κειμένου από τη λίστα επεκταμένου κώδικα κειμένου. |

## Παραδείγματα

```csharp
[C#]
//Λειτουργία Extended codetext

//δημιουργία codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//παραγωγή codetext
string codetext = textBuilder.GetExtendedCodetext();    

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Δείτε επίσης

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


