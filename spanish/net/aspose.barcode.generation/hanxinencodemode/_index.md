---
title: "Enum HanXinEncodeMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Enum Aspose.BarCode.Generation.HanXinEncodeMode. Modo de codificación Han Xin Code. Se recomienda usar Auto con caracteres ASCII / chinos o Unicode para caracteres Unicode"
type: docs
weight: 1360
url: /es/net/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enumeration

Modo de codificación Han Xin Code. Se recomienda usar Auto con caracteres ASCII / chinos o Unicode para caracteres Unicode.

```csharp
public enum HanXinEncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. Los caracteres Unicode se codifican usando la codificación GB18030 según la especificación del código de barras HanXin. |
| Binary | `1` | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | `2` | En modo ECI, todo el mensaje se re‑codifica en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no soportar este modo. |
| Unicode | `3` | El modo Unicode define una forma de representar cualquier referencia de datos de texto a la codificación/conjunto de caracteres UTF8 en Han Xin Code. |
| URI | `4` | El modo URI indica que los datos representados en Han Xin Code son una referencia de Identificador Uniforme de Recursos (URI) según RFC 3986. |
| Extended | `5` | El modo Extendido permite combinaciones de modos internos: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. El Codetext puede construirse manualmente con prefijos y barras invertidas dobles, p.ej.: @\"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c\" o usando el HanXinExtCodetextBuilder. Si el codetext contiene un fragmento ECI, entonces solo los siguientes modos pueden estar en ese codetext después del fragmento ECI: Auto, Binary, Text, Numeric, URI, ECI. |

## Ejemplos

```csharp
[C#]
// Modo Auto
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Modo Binario
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

// Modo Extendido
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Usando HanXinExtCodetextBuilder para el modo Extendido (el mismo codetext que en el ejemplo anterior)
//crear codetext
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

//generar codetext
var str = codeTextBuilder.GetExtendedCodetext();

//generar
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


