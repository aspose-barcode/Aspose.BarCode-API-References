---
title: "enum"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " enum. Λειτουργία κωδικοποίησης Han Xin Code. Συνιστάται η χρήση του Auto με χαρακτήρες ASCII / Κινέζικους ή Unicode για χαρακτήρες Unicode σε C++."
type: docs
weight: 6900
url: /el/cpp/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enum


Λειτουργία κωδικοποίησης Han Xin Code. Συνιστάται η χρήση Auto με χαρακτήρες ASCII / Κινέζικους ή Unicode για χαρακτήρες Unicode.

```cpp
enum class HanXinEncodeMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Αυτόματο | 0 | Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Οι χαρακτήρες Unicode κωδικοποιούνται χρησιμοποιώντας κωδικοποίηση GB18030 σύμφωνα με την προδιαγραφή barcode HanXin. |
| Δυαδικό | 1 | Σε δυαδική λειτουργία, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Εάν βρεθεί χαρακτήρας Unicode, ρίχνεται εξαίρεση. |
| ECI | 2 | Σε λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά στην κωδικοποίηση που καθορίζεται από το ECIEncoding με την εισαγωγή ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. Παρακαλούμε σημειώστε ότι ορισμένα παλαιά (πριν το 2006) σαρωτές ενδέχεται να μην υποστηρίζουν αυτή τη λειτουργία. |
| Unicode | 3 | Η λειτουργία Unicode σχεδιάζει έναν τρόπο να αντιπροσωπεύει οποιαδήποτε κειμενικά δεδομένα με αναφορά στην κωδικοποίηση/σύνολο χαρακτήρων UTF8 στον Han Xin Code. |
| URI | 4 | Η λειτουργία URI υποδεικνύει ότι τα δεδομένα που αντιπροσωπεύονται στον Han Xin Code είναι Uniform Resource Identifier (URI) αναφορά σύμφωνα με το RFC 3986. |
| Extended | 5 | Η λειτουργία Extended επιτρέπει συνδυασμούς εσωτερικών λειτουργιών: Auto, Binary, Text, Numeric, URI, Unicode, ECI, [Common](../../aspose.barcode.common/) Chinese Region One, [Common](../../aspose.barcode.common/) Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Το Codetext μπορεί να δημιουργηθεί χειροκίνητα με προθέματα και διπλές ανάστροφες κάθετες, π.χ.: ":abc\\000009:ΑΒΓΔΕ:ab\\c" ή χρησιμοποιώντας το [HanXinExtCodetextBuilder](../hanxinextcodetextbuilder/). Εάν το codetext περιέχει ένα τμήμα ECI, τότε μόνο οι ακόλουθες λειτουργίες μπορούν να εμφανιστούν σε αυτό το codetext μετά το τμήμα ECI: Auto, Binary, Text, Numeric, URI, ECI. |

## Σχόλια



```cpp
[C#]
// Λειτουργία Auto
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Λειτουργία Binary
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// Λειτουργία ECI
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Λειτουργία Unicode
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// Λειτουργία URI
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Λειτουργία Extended
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Χρήση του HanXinExtCodetextBuilder για τη λειτουργία Extended (ίδιο codetext όπως στο προηγούμενο παράδειγμα)
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
codeTextBuilder.AddURI(@"backslashes_should_be_doubled\000555:test");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

//δημιουργία κειμένου κώδικα
var str = codeTextBuilder.GetExtendedCodetext();

//δημιουργία
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
