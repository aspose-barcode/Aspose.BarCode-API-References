---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder classe"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare la classe Aspose::BarCode::Generation::HanXinExtCodetextBuilder in C++."
type: docs
weight: 2800
url: /it/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Aggiunge frammento di codetext in modalità Auto |
| [AddBinary](./addbinary/)(System::String) | Aggiunge frammento di codetext in modalità Binaria |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | Aggiunge frammento di codetext in modalità [Common](../../aspose.barcode.common/) Chinese Region One |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | Aggiunge frammento di codetext in modalità [Common](../../aspose.barcode.common/) Chinese Region Two |
| [AddECI](./addeci/)(System::String, int32_t) | Aggiunge frammento di codetext in modalità ECI |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | Aggiunge frammento di codetext in modalità GB18030 Four Byte |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | Aggiunge frammento di codetext in modalità GB18030 Two Byte |
| [AddNumeric](./addnumeric/)(System::String) | Aggiunge frammento di codetext in modalità Numerica |
| [AddText](./addtext/)(System::String) | Aggiunge frammento di codetext in modalità Testo |
| [AddUnicode](./addunicode/)(System::String) | Aggiunge frammento di codetext in modalità Unicode |
| [AddURI](./adduri/)(System::String) | Aggiunge frammento di codetext in modalità URI |
| [GetExtendedCodetext](./getextendedcodetext/)() | Restituisce il codetext dal Extended mode codetext builder |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## Osservazioni


Generatore di codetext esteso per Han Xin Code per Modalità Estesa di EncodeMode


```cpp
[C#]
//Modalità codetext estesa
//crea codetext
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

//genera codetext
var str = codeTextBuilder.GetExtendedCodetext();

//genera
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

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
