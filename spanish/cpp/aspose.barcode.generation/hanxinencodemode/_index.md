---
title: "enum"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Modo de codificación del código Han Xin. Se recomienda usar Auto con caracteres ASCII / chinos o Unicode para caracteres Unicode en C++."
type: docs
weight: 6900
url: /es/cpp/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enum


Modo de codificación Han Xin Code. Se recomienda usar Auto con caracteres ASCII / chinos o Unicode para caracteres Unicode.

```cpp
enum class HanXinEncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Automático | 0 | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. Los caracteres Unicode se codifican usando la codificación GB18030 según la especificación del código de barras HanXin. |
| Binario | 1 | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | 2 | En modo ECI, todo el mensaje se vuelve a codificar en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no ser compatibles con este modo. |
| Unicode | 3 | El modo Unicode define una forma de representar cualquier dato de texto haciendo referencia a la codificación/conjunto de caracteres UTF8 en el código Han Xin. |
| URI | 4 | El modo URI indica que los datos representados en el código Han Xin son un Identificador Uniforme de Recursos (URI) según la referencia RFC 3986. |
| Extended | 5 | El modo Extended permite combinaciones de modos internos: Auto, Binary, Text, Numeric, URI, Unicode, ECI, [Common](../../aspose.barcode.common/) Chinese Region One, [Common](../../aspose.barcode.common/) Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. El codetext puede construirse manualmente con prefijos y barras invertidas dobles, p. ej.: ":abc\000009:ΑΒΓΔΕ:ab\c" o usando el [HanXinExtCodetextBuilder](../hanxinextcodetextbuilder/). Si el codetext contiene un fragmento ECI, entonces solo los siguientes modos pueden estar en ese codetext después del fragmento ECI: Auto, Binary, Text, Numeric, URI, ECI. |

## Observaciones



```cpp
[C#]
// Modo Auto
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Modo binario
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// Modo ECI
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Modo Unicode
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// Modo URI
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Modo extendido
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Usando HanXinExtCodetextBuilder para el modo extendido (el mismo codetext que en el ejemplo anterior)
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
codeTextBuilder.AddURI(@"backslashes_should_be_doubled\000555:test");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

//generar texto de código
var str = codeTextBuilder.GetExtendedCodetext();

//generar
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
