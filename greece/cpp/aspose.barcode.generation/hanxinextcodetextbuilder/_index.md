---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder κλάση"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε την κλάση Aspose::BarCode::Generation::HanXinExtCodetextBuilder σε C++."
type: docs
weight: 2800
url: /el/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Προσθέτει τμήμα κώδικα σε λειτουργία Auto |
| [AddBinary](./addbinary/)(System::String) | Προσθέτει τμήμα κώδικα σε λειτουργία Binary |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | Προσθέτει τμήμα κώδικα σε λειτουργία [Common](../../aspose.barcode.common/) Chinese Region One |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | Προσθέτει τμήμα κώδικα σε λειτουργία [Common](../../aspose.barcode.common/) Chinese Region Two |
| [AddECI](./addeci/)(System::String, int32_t) | Προσθέτει τμήμα κώδικα σε λειτουργία ECI |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | Προσθέτει τμήμα κώδικα σε λειτουργία GB18030 Four Byte |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | Προσθέτει τμήμα κώδικα σε λειτουργία GB18030 Two Byte |
| [AddNumeric](./addnumeric/)(System::String) | Προσθέτει τμήμα κώδικα σε λειτουργία Numeric |
| [AddText](./addtext/)(System::String) | Προσθέτει τμήμα κώδικα σε λειτουργία Text |
| [AddUnicode](./addunicode/)(System::String) | Προσθέτει τμήμα κώδικα σε λειτουργία Unicode |
| [AddURI](./adduri/)(System::String) | Προσθέτει τμήμα κώδικα σε λειτουργία URI |
| [GetExtendedCodetext](./getextendedcodetext/)() | Επιστρέφει κώδικα από τον δημιουργό κώδικα σε λειτουργία Extended |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## Σχόλια


Γεννήτρια κώδικα Extended για Han Xin Code για Extended Mode του EncodeMode


```cpp
[C#]
//Λειτουργία εκτεταμένου κειμένου κώδικα
//δημιουργία κειμένου κώδικα
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

//δημιουργία κειμένου κώδικα
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

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
