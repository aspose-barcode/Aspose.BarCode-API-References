---
title: "QREncodeMode"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "QR barkodları için kodlama modu."
type: docs
weight: 102
url: /tr/androidjava/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

QR barkodları için kodlama modu. Bu örnekler, QR barkodunu genişletilmiş veri formatlarıyla nasıl kodlayıp kaydedeceğinizi gösterir.

```
{@code
 //This sample shows how to use ECI encoding and save a BarCode image.

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText("12345TEXT");
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECI_ENCODING);
 generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
 generator.save("test.png");

 //This sample shows how to use FNC1 first position in Extended Mode.
 Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes.
 It is better to use QrExtCodetextBuilder for extended codetext generation.
 Use Display2DText property to set visible text by removing managing characters.
 Encoding Principles:
 All symbols "\" must be doubled "\\" in the codetext.
 FNC1 in first position is set in codetext as "<FNC1>".
 FNC1 in second position is set in codetext as "<FNC1(value)>". The value must be a single character from a-z or A-Z, or a two-digit number from 00 to 99.
 Group Separator for FNC1 modes is set as 0x1D character ''.
 If you need to insert "<FNC1>" string into barcode write it as "<\FNC1>".
 ECI identifiers are set as single slash and six digits identifier, for example "\000026" for UTF8 ECI identifier.
 The default ECI mode is ISO/IEC 8859-1 ECI identifier "\000003". It does not need to be encoded at the beginning of the codetext.
 To switch from another ECI mode to the default ECI mode, use "\000003".
 All unicode characters after ECI identifier are automatically encoded into correct character codeset.
 QR compaction mode selectors are set as single slash and mode name: "\auto", "\num", "\alnum", "\byte", "\kanji".
 "\auto" sets automatic compaction mode, "\num" sets Numeric mode, "\alnum" sets AlphaNumeric mode, "\byte" sets Bytes mode, and "\kanji" sets Kanji mode.
 The default compaction mode is "\auto".
 Compaction mode selectors define the encoding mode for the following data until the next compaction mode selector or ECI identifier is found.
 If the data cannot be encoded in the selected compaction mode, an ArgumentException is thrown.
 This mode is not supported by MicroQR barcodes.

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.GetExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.Extended);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.png");

 //This sample shows how to use FNC1 second position in Extended Mode.
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.GetExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.Extended);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.png");

 //This sample shows how to use multi ECI mode in Extended Mode.
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
 textBuilder.addPlainCodetext"t\e\\st");
 textBuilder.addAlphaNumericCodetext("ASPOSE2001");
 textBuilder.addNumericCodetext(@"20012026");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.getExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text";
 generator.save("test.png");
```
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AUTO](#AUTO) | Otomatik modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. |
| [BINARY](#BINARY) | İkili modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. |
| [ECI](#ECI) | ECI modunda, tüm mesaj belirtilen ECIEncoding kodlamasıyla, bir ECI tanımlayıcısı eklenerek yeniden kodlanır. |
| [EXTENDED](#EXTENDED) | FNC1 birinci konumu, FNC1 ikinci konumu ve çoklu ECI modlarını destekleyen Genişletilmiş Kanal modu. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final QREncodeMode AUTO
```


Auto modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Unicode karakterleri mümkünse kanji modunda kodlanır, aksi takdirde belirtilen ECIEncoding kodlamasıyla bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa bir istisna fırlatılır.

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


İkili modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Bir Unicode karakteri bulunursa, bir istisna fırlatılır.

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


ECI modunda, tüm mesaj belirtilen ECIEncoding kodlamasıyla bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa bir istisna fırlatılır. Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın. Bu mod MicroQR barkodları tarafından desteklenmez.

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


Genişletilmiş Kanal modu, FNC1 birinci konumu, FNC1 ikinci konumu ve çoklu ECI modlarını destekler. Genişletilmiş kod metni oluşturmak için QrExtCodetextBuilder kullanılması daha iyidir. Görünür metni yönetim karakterlerini kaldırarak ayarlamak için Display2DText özelliğini kullanın. Kodlama Prensipleri: Tüm "\\" sembolleri kodmetninde "\\\\" olarak iki katına çıkarılmalıdır. İlk konumdaki FNC1 kodmetninde "<FNC1>" olarak ayarlanır. İkinci konumdaki FNC1 kodmetninde "<FNC1(value)>" olarak ayarlanır. Değer a-z veya A-Z aralığından tek bir karakter ya da 00 ile 99 arasında iki basamaklı bir sayı olmalıdır. FNC1 modları için Grup Ayırıcı 0x1D karakteri '\u001d' olarak ayarlanır. Kodbarda "<FNC1>" dizesi eklemeniz gerekiyorsa "<\\FNC1>" olarak yazın. ECI tanımlayıcıları tek eğik çizgi ve altı basamaklı tanımlayıcı olarak ayarlanır, örneğin UTF8 ECI tanımlayıcısı için "\\000026". Varsayılan ECI modu ISO/IEC 8859-1 ECI tanımlayıcısı "\\000003"'tür. Bu, kodmetninin başında kodlanmasına gerek yoktur. Başka bir ECI modundan varsayılan ECI moduna geçmek için "\\000003" kullanın. ECI tanımlayıcısından sonraki tüm unicode karakterler otomatik olarak doğru karakter kodlamasına kodlanır. QR sıkıştırma modu seçicileri tek eğik çizgi ve mod adıyla ayarlanır: "\\auto", "\\num", "\\alnum", "\\byte", "\\kanji". "\\auto" otomatik sıkıştırma modunu, "\\num" Sayısal modu, "\\alnum" Alfasayısal modu, "\\byte" Bayt modunu ve "\\kanji" Kanji modunu ayarlar. Varsayılan sıkıştırma modu "\\auto"'dır. Sıkıştırma modu seçicileri, bir sonraki sıkıştırma modu seçicisi ya da ECI tanımlayıcısı bulunana kadar sonraki verinin kodlama modunu tanımlar. Veri seçilen sıkıştırma modunda kodlanamıyorsa ArgumentException fırlatılır. Bu mod MicroQR barkodları tarafından desteklenmez.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QREncodeMode fromValue(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static QREncodeMode valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### values() {#values--}
```
public static QREncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.QREncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

