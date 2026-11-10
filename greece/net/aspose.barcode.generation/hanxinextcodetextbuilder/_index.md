---
title: "Κλάση HanXinExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder class. Εκτεταμένος δημιουργός κώδικα κειμένου για Han Xin Code σε Εκτεταμένη Λειτουργία του EncodeMode"
type: docs
weight: 1380
url: /el/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

Γεννήτρια εκτεταμένου κώδικα κειμένου για Han Xin Code για τη λειτουργία Extended Mode του EncodeMode

```csharp
public class HanXinExtCodetextBuilder
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Auto |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Binary |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Common Chinese Region One |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Common Chinese Region Two |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία ECI |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία GB18030 Four Byte |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία GB18030 Two Byte |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Numeric |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | Προσθέτει τμήμα codetext σε λειτουργία Κειμένου |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | Προσθέτει τμήμα codetext σε λειτουργία Unicode |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | Προσθέτει τμήμα codetext σε λειτουργία URI |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | Επιστρέφει codetext από τον κατασκευαστή codetext σε λειτουργία Extended |

## Παραδείγματα

```csharp
[C#]
//Λειτουργία Extended codetext
//δημιουργία codetext
var codeTextBuilder = new HanXinExtCodetextBuilder();
codeTextBuilder.AddGB18030TwoByte("漄");
codeTextBuilder.AddGB18030FourByte("㐁");
codeTextBuilder.AddCommonChineseRegionOne("全");
codeTextBuilder.AddCommonChineseRegionTwo("螅");
codeTextBuilder.AddNumeric("123");
codeTextBuilder.AddText("qwe");
codeTextBuilder.AddUnicode("ıntəˈnæʃənəl");
codeTextBuilder.AddECI("ΑΒΓΔΕ", 9);
codeTextBuilder.AddAuto("abc");
codeTextBuilder.AddBinary("abc");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabc";

//παραγωγή codetext
var str = codeTextBuilder.GetExtendedCodetext();

//δημιουργία
using (var bg = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    bg.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    var img = bg.GenerateBarCodeImage();
    using (var r = new BarCodeReader(img, DecodeType.HanXin))
     {
        var found = r.ReadBarCodes();
        Assert.AreEqual(1, found.Length);
        Assert.AreEqual(expectedStr, found[0].CodeText);
      }
}
```

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


