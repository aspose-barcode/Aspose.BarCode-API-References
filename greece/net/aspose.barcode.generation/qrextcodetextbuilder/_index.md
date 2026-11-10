---
title: "Κλάση QrExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.QrExtCodetextBuilder κλάση. Εκτεταμένος δημιουργός κώδικα κειμένου για 2D QR barcode για λειτουργία ExtendedCodetext Mode του EncodeMode"
type: docs
weight: 1630
url: /el/net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

Γεννήτρια εκτεταμένου κώδικα κειμένου για 2D QR barcode για τη λειτουργία ExtendedCodetext Mode του EncodeMode

Χρησιμοποιήστε την ιδιότητα TwoDDisplayText του BarcodeGenerator για να ορίσετε το ορατό κείμενο αφαιρώντας χαρακτήρες διαχείρισης.

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddCodetextWithCompactionMode](../../aspose.barcode.generation/qrextcodetextbuilder/addcodetextwithcompactionmode/)(QrExtCompactionMode, string) | Προσθέτει κώδικα κειμένου με τη συγκεκριμένη λειτουργία συμπίεσης QR στα στοιχεία εκτεταμένου κώδικα κειμένου. |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Προσθέτει κώδικα κειμένου με Extended Channel Identifier |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | Ορίζει το FNC1 στην πρώτη θέση. Εάν είχε οριστεί άλλη λειτουργία FNC1 προηγουμένως, αντικαθίσταται. |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | Προσθέτει το Διαχωριστικό Ομάδας (GS - '\\u001D') στα στοιχεία εκτεταμένου κώδικα κειμένου |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | Ορίζει το FNC1 στη δεύτερη θέση. Εάν είχε οριστεί άλλη λειτουργία FNC1 προηγουμένως, αντικαθίσταται. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Προσθέτει απλό κώδικα κειμένου στα στοιχεία του επεκταμένου κώδικα κειμένου |
| override [Clear](../../aspose.barcode.generation/qrextcodetextbuilder/clear/)() | Καθαρίζει τα στοιχεία του επεκταμένου κώδικα κειμένου |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | Δημιουργεί επεκταμένο κώδικα κειμένου από τη λίστα επεκταμένου κώδικα κειμένου. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το FNC1 στην πρώτη θέση στη Λειτουργία Επεκτάσιμη.

```csharp
[C#]
//δημιουργία codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//παραγωγή codetext
string codetext = TextBuilder.GetExtendedCodetext();

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το FNC1 στη δεύτερη θέση στη Λειτουργία Επεκτάσιμη.

```csharp
[C#]
//δημιουργία codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//παραγωγή codetext
string codetext = TextBuilder.GetExtendedCodetext();

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία multi ECI στη Λειτουργία Επεκτάσιμη.

```csharp
[C#]
//δημιουργία codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//παραγωγή codetext
string codetext = TextBuilder.GetExtendedCodetext();

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Δείτε επίσης

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


