---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder класс"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать класс Aspose::BarCode::Generation::HanXinExtCodetextBuilder в C++."
type: docs
weight: 2800
url: /ru/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Добавляет фрагмент кода текста в режиме Auto |
| [AddBinary](./addbinary/)(System::String) | Добавляет фрагмент кода текста в режиме Binary |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | Добавляет фрагмент кода текста в режиме [Common](../../aspose.barcode.common/) Chinese Region One |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | Добавляет фрагмент кода текста в режиме [Common](../../aspose.barcode.common/) Chinese Region Two |
| [AddECI](./addeci/)(System::String, int32_t) | Добавляет фрагмент кода текста в режиме ECI |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | Добавляет фрагмент кода текста в режиме GB18030 Four Byte |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | Добавляет фрагмент кода текста в режиме GB18030 Two Byte |
| [AddNumeric](./addnumeric/)(System::String) | Добавляет фрагмент кода текста в режиме Numeric |
| [AddText](./addtext/)(System::String) | Добавляет фрагмент кода текста в режиме Text |
| [AddUnicode](./addunicode/)(System::String) | Добавляет фрагмент кода текста в режиме Unicode |
| [AddURI](./adduri/)(System::String) | Добавляет фрагмент кода текста в режиме URI |
| [GetExtendedCodetext](./getextendedcodetext/)() | Возвращает код текста из построителя кода текста в режиме Extended |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## Примечания


Генератор расширенного кода текста для Han Xin Code для расширенного режима EncodeMode


```cpp
[C#]
//Режим расширенного текста кода
//создать текст кода
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

//генерировать текст кода
var str = codeTextBuilder.GetExtendedCodetext();

//генерировать
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

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
