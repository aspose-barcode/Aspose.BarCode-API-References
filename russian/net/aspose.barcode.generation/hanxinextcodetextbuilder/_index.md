---
title: "Класс HanXinExtCodetextBuilder"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder класс. Расширенный генератор кодового текста для Han Xin Code в расширенном режиме EncodeMode"
type: docs
weight: 1380
url: /ru/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

Расширенный генератор кодового текста для Han Xin Code в расширенном режиме EncodeMode

```csharp
public class HanXinExtCodetextBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Добавляет фрагмент кодового текста в режиме Auto |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Добавляет фрагмент кодового текста в режиме Binary |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Добавляет фрагмент кодового текста в режиме Common Chinese Region One |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Добавляет фрагмент кодового текста в режиме Common Chinese Region Two |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | Добавляет фрагмент кодового текста в режиме ECI |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | Добавляет фрагмент кодового текста в режиме GB18030 Four Byte |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | Добавляет фрагмент кодового текста в режиме GB18030 Two Byte |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Добавляет фрагмент кодового текста в режиме Numeric |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | Добавляет фрагмент кодового текста в режиме Text |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | Добавляет фрагмент кодового текста в режиме Unicode |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | Добавляет фрагмент кодового текста в режиме URI |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | Возвращает кодовый текст из билдера кодового текста в расширенном режиме |

## Примеры

```csharp
[C#]
//Режим расширенного кодового текста
//создать кодовый текст
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

//сгенерировать кодовый текст
var str = codeTextBuilder.GetExtendedCodetext();

//сгенерировать
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

### См. также

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


