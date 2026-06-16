---
title: QREncodeMode
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Kodierungsmodus für QR-Barcodes.
type: docs
weight: 102
url: /de/androidjava/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

Kodierungsmodus für QR-Barcodes.

--------------------

> ```
> Example how to use ECI encoding
>  
>      BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>      generator.setCodeText("12345TEXT");
>      generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECI_ENCODING);
>      generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.png");
> ```

--------------------

> ```
> Example how to use FNC1 first position in Extended Mode
>   
>       QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>       textBuilder.addPlainCodetext("000%89%%0");
>       textBuilder.addFNC1GroupSeparator();
>       textBuilder.addPlainCodetext("12345<FNC1>");
>       //generate barcode
>       BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>       generator.setCodeText(textBuilder.getExtended());
>       generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
>       generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>       generator.save("d:/test.png");
>  
>       *
>  This sample shows how to use FNC1 second position in Extended Mode.
>  
> 
>     //create codetext
>     QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>     textBuilder.addFNC1SecondPosition("12");
>     textBuilder.addPlainCodetext("TRUE3456");
>     //generate barcode
>     BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>     generator.setCodeText(textBuilder.getExtended());
>     generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>     generator.save("d:/test.png");
>     
> 
>     This sample shows how to use multi ECI mode in Extended Mode.
>     
> 
>    //create codetext
>    QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>    textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>    textBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
>    textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
>    textBuilder.addPlainCodetext("t\e\\st");
>    //generate barcode
>    BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>    generator.setCodeText(textBuilder.getExtended());
>    generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
>    generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>    generator.save("d:/test.png");
> ```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [AUTO](#AUTO) | Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. |
| [BINARY](#BINARY) | Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. |
| [BYTES](#BYTES) | Kodieren Sie den Codetext als einfache Bytes. |
| [ECI](#ECI) | Im ECI‑Modus wird die gesamte Nachricht mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Bezeichner eingefügt wird. |
| [ECI_ENCODING](#ECI-ENCODING) | Kodiert den Codetext mit dem im ECIEncoding‑Eigenschaft festgelegten Wert. |
| [EXTENDED](#EXTENDED) | Erweiterter Kanalmodus, der die erste Position von FNC1, die zweite Position von FNC1 und mehrere ECI‑Modi unterstützt. Es ist besser, QrExtCodetextBuilder für die erweiterte Codetext‑Erzeugung zu verwenden. Verwenden Sie die Display2DText‑Eigenschaft, um sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen. Kodierungsprinzipien: Alle Symbole "\\" müssen im Codetext zu "\\\\" verdoppelt werden. FNC1 in der ersten Position wird im Codetext als "<FNC1>" gesetzt, FNC1 in der zweiten Position wird im Codetext als "<FNC1(value)>" gesetzt. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) | Erweiterter Kanalmodus, der die erste Position von FNC1, die zweite Position von FNC1 und mehrere ECI‑Modi unterstützt. Es ist besser, QrExtCodetextBuilder für die erweiterte Codetext‑Erzeugung zu verwenden. Verwenden Sie die Display2DText‑Eigenschaft, um sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen. Kodierungsprinzipien: Alle Symbole "\\" müssen im Codetext zu "\\\\" verdoppelt werden. FNC1 in der ersten Position wird im Codetext als "<FNC1>" gesetzt, FNC1 in der zweiten Position wird im Codetext als "<FNC1(value)>" gesetzt. |
| [UTF_16_BEBOM](#UTF-16-BEBOM) | Kodiert den Codetext mit UTF8‑Kodierung und dem ersten ByteOfMark‑Zeichen. |
| [UTF_8_BOM](#UTF-8-BOM) | Kodiert den Codetext mit UTF8‑Kodierung und dem ersten ByteOfMark‑Zeichen. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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


Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode‑Zeichen werden, wenn möglich, im Kanji‑Modus kodiert, andernfalls werden sie mit der im ECIEncoding angegebenen Kodierung und dem Einfügen eines ECI‑Identifikators erneut kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst.

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode‑Zeichen gefunden, wird eine Ausnahme ausgelöst.

### BYTES {#BYTES}
```
public static final QREncodeMode BYTES
```


Kodieren Sie den Codetext als einfache Bytes. Wenn ein Unicode‑Zeichen erkannt wird, wird das Zeichen als zwei Bytes kodiert, zuerst das niederwertige Byte.

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


Im ECI‑Modus wird die gesamte Nachricht mit der im ECIEncoding angegebenen Kodierung und dem Einfügen eines ECI‑Identifikators erneut kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige alte (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. Dieser Modus wird von MicroQR‑Barcodes nicht unterstützt.

### ECI_ENCODING {#ECI-ENCODING}
```
public static final QREncodeMode ECI_ENCODING
```


Kodiert den Codetext mit dem im ECIEncoding‑Eigenschaft festgelegten Wert. Es kann bei einigen alten (vor 2006) Barcode‑Scannern zu Problemen kommen. Dieser Modus wird von MicroQR‑Barcodes nicht unterstützt.

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


Erweiterter Kanalmodus, der die erste Position von FNC1, die zweite Position von FNC1 und mehrere ECI‑Modi unterstützt. Es ist besser, QrExtCodetextBuilder für die erweiterte Codetext‑Erzeugung zu verwenden. Verwenden Sie die Display2DText‑Eigenschaft, um sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen. Kodierungsprinzipien: Alle Symbole "\\" müssen im Codetext zu "\\\\" verdoppelt werden. FNC1 in der ersten Position wird im Codetext als "<FNC1>" gesetzt, FNC1 in der zweiten Position wird im Codetext als "<FNC1(value)>" gesetzt. Der Wert muss einzelne Symbole (a‑z, A‑Z) oder Ziffern von 0 bis 99 sein. Der Gruppentrenner für FNC1‑Modi wird als Zeichen 0x1D '\\\\u001D' festgelegt. Wenn Sie die Zeichenkette "<FNC1>" in den Barcode einfügen müssen, schreiben Sie sie als "<\\FNC1>". ECI‑Identifikatoren werden als einzelner Schrägstrich und sechsstelliger Identifikator "\\000026" - UTF8‑ECI‑Identifikator gesetzt. Um den aktuellen ECI‑Modus zu deaktivieren und in den Standard‑JIS8‑Modus (Null‑Modus) zu konvertieren, wird der ECI‑Identifikator "\\000000" gesetzt. Alle Unicode‑Zeichen nach dem ECI‑Identifikator werden automatisch in den korrekten Zeichensatz kodiert. Dieser Modus wird von MicroQR‑Barcodes nicht unterstützt.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final QREncodeMode EXTENDED_CODETEXT
```


Erweiterter Kanalmodus, der die erste Position von FNC1, die zweite Position von FNC1 und mehrere ECI‑Modi unterstützt. Es ist besser, QrExtCodetextBuilder für die erweiterte Codetext‑Erzeugung zu verwenden. Verwenden Sie die Display2DText‑Eigenschaft, um sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen. Kodierungsprinzipien: Alle Symbole "\\" müssen im Codetext zu "\\\\" verdoppelt werden. FNC1 in der ersten Position wird im Codetext als "<FNC1>" gesetzt, FNC1 in der zweiten Position wird im Codetext als "<FNC1(value)>" gesetzt. Der Wert muss einzelne Symbole (a‑z, A‑Z) oder Ziffern von 0 bis 99 sein. Der Gruppentrenner für FNC1‑Modi wird als Zeichen 0x1D '\\\\u001D' festgelegt. Wenn Sie die Zeichenkette "<FNC1>" in den Barcode einfügen müssen, schreiben Sie sie als "<\\FNC1>". ECI‑Identifikatoren werden als einzelner Schrägstrich und sechsstelliger Identifikator "\\000026" - UTF8‑ECI‑Identifikator gesetzt. Um den aktuellen ECI‑Modus zu deaktivieren und in den Standard‑JIS8‑Modus (Null‑Modus) zu konvertieren, wird der ECI‑Identifikator "\\000000" gesetzt. Alle Unicode‑Zeichen nach dem ECI‑Identifikator werden automatisch in den korrekten Zeichensatz kodiert. Dieser Modus wird von MicroQR‑Barcodes nicht unterstützt.

### UTF_16_BEBOM {#UTF-16-BEBOM}
```
public static final QREncodeMode UTF_16_BEBOM
```


Kodiert den Codetext mit UTF8‑Kodierung und dem ersten ByteOfMark‑Zeichen. Es kann bei einigen Barcode‑Scannern zu Problemen kommen.

### UTF_8_BOM {#UTF-8-BOM}
```
public static final QREncodeMode UTF_8_BOM
```


Kodiert den Codetext mit UTF8‑Kodierung und dem ersten ByteOfMark‑Zeichen.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

