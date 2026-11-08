---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder clase"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar la clase Aspose::BarCode::Generation::HanXinExtCodetextBuilder en C++."
type: docs
weight: 2800
url: /es/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Agrega fragmento de codetext en modo Auto |
| [AddBinary](./addbinary/)(System::String) | Agrega fragmento de codetext en modo Binario |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | Agrega fragmento de codetext en modo Chinese Region One de [Common](../../aspose.barcode.common/) |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | Agrega fragmento de codetext en modo Chinese Region Two de [Common](../../aspose.barcode.common/) |
| [AddECI](./addeci/)(System::String, int32_t) | Agrega fragmento de codetext en modo ECI |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | Agrega fragmento de codetext en modo GB18030 Four Byte |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | Agrega fragmento de codetext en modo GB18030 Two Byte |
| [AddNumeric](./addnumeric/)(System::String) | Agrega fragmento de codetext en modo Numérico |
| [AddText](./addtext/)(System::String) | Agrega fragmento de codetext en modo Texto |
| [AddUnicode](./addunicode/)(System::String) | Agrega fragmento de codetext en modo Unicode |
| [AddURI](./adduri/)(System::String) | Agrega fragmento de codetext en modo URI |
| [GetExtendedCodetext](./getextendedcodetext/)() | Devuelve codetext del generador de codetext en modo Extended |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## Observaciones


Generador de codetext extendido para Han Xin Code para el Modo Extendido de EncodeMode


```cpp
[C#]
//Modo de texto de código extendido
//crear texto de código
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

//generar texto de código
var str = codeTextBuilder.GetExtendedCodetext();

//generar
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

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
