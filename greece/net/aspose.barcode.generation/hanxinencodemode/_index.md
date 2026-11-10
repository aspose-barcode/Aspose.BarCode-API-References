---
title: "Απαρίθμηση HanXinEncodeMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Απαρίθμηση Aspose.BarCode.Generation.HanXinEncodeMode. Λειτουργία κωδικοποίησης Han Xin Code. Συνιστάται η χρήση του Auto με χαρακτήρες ASCII / Κινέζικους ή Unicode για χαρακτήρες Unicode."
type: docs
weight: 1360
url: /el/net/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enumeration

Λειτουργία κωδικοποίησης Han Xin Code. Συνιστάται η χρήση Auto με χαρακτήρες ASCII / Κινέζικους ή Unicode για χαρακτήρες Unicode.

```csharp
public enum HanXinEncodeMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Auto | `0` | Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Οι χαρακτήρες Unicode κωδικοποιούνται χρησιμοποιώντας την κωδικοποίηση GB18030 σύμφωνα με την προδιαγραφή του barcode HanXin. |
| Binary | `1` | Σε λειτουργία Binary, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Εάν βρεθεί χαρακτήρας Unicode, ρίχνεται εξαίρεση. |
| ECI | `2` | Σε λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά στην κωδικοποίηση που ορίζεται από το ECIEncoding με την προσθήκη ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. Παρακαλούμε σημειώστε ότι ορισμένα παλιά (πριν το 2006) σαρωτές ενδέχεται να μην υποστηρίζουν αυτή τη λειτουργία. |
| Unicode | `3` | Η λειτουργία Unicode σχεδιάζει έναν τρόπο να αντιπροσωπεύει οποιαδήποτε κειμενικά δεδομένα με αναφορά στην κωδικοποίηση/σύνολο χαρακτήρων UTF8 στον Han Xin Code. |
| URI | `4` | Η λειτουργία URI υποδεικνύει ότι τα δεδομένα που αντιπροσωπεύονται στον Han Xin Code είναι αναφορά Uniform Resource Identifier (URI) σύμφωνα με το RFC 3986. |
| Extended | `5` | Η εκτεταμένη λειτουργία επιτρέπει συνδυασμούς εσωτερικών λειτουργιών: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Το κείμενο κώδικα μπορεί να δημιουργηθεί χειροκίνητα με προθέματα και διπλές ανάστροφες κάθετες, π.χ.: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" ή χρησιμοποιώντας το HanXinExtCodetextBuilder. Εάν το κείμενο κώδικα περιέχει ένα τμήμα ECI, τότε μόνο οι ακόλουθες λειτουργίες μπορούν να εμφανιστούν σε αυτό το κείμενο κώδικα μετά το τμήμα ECI: Auto, Binary, Text, Numeric, URI, ECI. |

## Παραδείγματα

```csharp
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

// Εκτεταμένη λειτουργία
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Χρήση του HanXinExtCodetextBuilder για την Εκτεταμένη λειτουργία (ίδιο κείμενο κώδικα όπως στο προηγούμενο παράδειγμα)
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
codeTextBuilder.AddURI(@"backslashes_should_be_doubled\000555:test");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

//παραγωγή codetext
var str = codeTextBuilder.GetExtendedCodetext();

//δημιουργία
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


