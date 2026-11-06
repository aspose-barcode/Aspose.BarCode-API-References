---
title: "QREncodeMode"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Kodierungsmodus für QR-Barcodes."
type: docs
weight: 102
url: /de/androidjava/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

Kodierungsmodus für QR-Barcodes. Diese Beispiele zeigen, wie man QR-Barcodes mit erweiterten Datenformaten kodiert und speichert.

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
## Felder

| Feld | Beschreibung |
| --- | --- |
| [AUTO](#AUTO) | Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. |
| [BINARY](#BINARY) | Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. |
| [ECI](#ECI) | Im ECI‑Modus wird die gesamte Nachricht in der durch ECIEncoding angegebenen Kodierung mit dem Einfügen eines ECI‑Identifikators neu kodiert. |
| [EXTENDED](#EXTENDED) | Erweiterter Kanalmodus, der die erste Position FNC1, die zweite Position FNC1 und mehrere ECI‑Modi unterstützt. |
## Methoden

| Methode | Beschreibung |
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


In Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode‑Zeichen werden nach Möglichkeit im Kanji‑Modus kodiert, oder sie werden in der durch ECIEncoding angegebenen Kodierung mit dem Einfügen eines ECI‑Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst.

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode‑Zeichen gefunden, wird eine Ausnahme ausgelöst.

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


Im ECI‑Modus wird die gesamte Nachricht in der durch ECIEncoding angegebenen Kodierung mit dem Einfügen eines ECI‑Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige ältere (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. Dieser Modus wird von MicroQR‑Barcodes nicht unterstützt.

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


Erweiterter Kanalmodus, der die erste Position von FNC1, die zweite Position von FNC1 und mehrere ECI‑Modi unterstützt. Es ist besser, QrExtCodetextBuilder für die erweiterte Codetext‑Erzeugung zu verwenden. Verwenden Sie die Eigenschaft Display2DText, um sichtbaren Text festzulegen, indem Sie verwaltende Zeichen entfernen. Kodierungsprinzipien: Alle Symbole "\\" müssen im Codetext verdoppelt "\\\\" werden. FNC1 in der ersten Position wird im Codetext als "<FNC1>" gesetzt. FNC1 in der zweiten Position wird im Codetext als "<FNC1(value)>" gesetzt. Der Wert muss ein einzelnes Zeichen von a‑z oder A‑Z sein oder eine zweistellige Zahl von 00 bis 99. Der Gruppentrennzeichen für FNC1‑Modi ist das Zeichen 0x1D '\u001d'. Wenn Sie die Zeichenkette "<FNC1>" in den Barcode einfügen müssen, schreiben Sie sie als "<\\FNC1>". ECI‑Kennungen werden als einzelner Schrägstrich und sechsstellige Kennung angegeben, zum Beispiel "\\000026" für die UTF8‑ECI‑Kennung. Der Standard‑ECI‑Modus ist die ISO/IEC‑8859‑1‑ECI‑Kennung "\\000003". Sie muss nicht am Anfang des Codetextes kodiert werden. Um von einem anderen ECI‑Modus zum Standard‑ECI‑Modus zu wechseln, verwenden Sie "\\000003". Alle Unicode‑Zeichen nach der ECI‑Kennung werden automatisch in den korrekten Zeichensatz kodiert. QR‑Komprimierungsmodus‑Selektoren werden als einzelner Schrägstrich und Modusname angegeben: "\\auto", "\\num", "\\alnum", "\\byte", "\\kanji". "\\auto" setzt den automatischen Komprimierungsmodus, "\\num" setzt den numerischen Modus, "\\alnum" den alphanumerischen Modus, "\\byte" den Byte‑Modus und "\\kanji" den Kanji‑Modus. Der Standard‑Komprimierungsmodus ist "\\auto". Komprimierungsmodus‑Selektoren definieren den Kodierungsmodus für die folgenden Daten bis zum nächsten Komprimierungsmodus‑Selektor oder bis eine ECI‑Kennung gefunden wird. Wenn die Daten nicht im ausgewählten Komprimierungsmodus kodiert werden können, wird eine ArgumentException ausgelöst. Dieser Modus wird von MicroQR‑Barcodes nicht unterstützt.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QREncodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

