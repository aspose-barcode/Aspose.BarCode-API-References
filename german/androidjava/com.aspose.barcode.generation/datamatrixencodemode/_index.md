---
title: DataMatrixEncodeMode
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Der Kodierungsmodus der DataMatrix‑Kodierer ist standardmäßig auf Auto eingestellt
type: docs
weight: 83
url: /de/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

Kodierungsmodus des DataMatrix-Encoders, standardmäßig Auto

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ANSIX12](#ANSIX12) | Verwendet ANSI‑X12‑Kodierung. |
| [ASCII](#ASCII) | Kodiert ein alphanumerisches oder zwei numerische Zeichen pro Byte |
| [AUTO](#AUTO) | Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. |
| [BASE_256](#BASE-256) | 8‑Bit‑Werte kodieren |
| [BINARY](#BINARY) | Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. |
| [BYTES](#BYTES) | 8‑Bit‑Werte kodieren |
| [C40](#C40) | Verwendet C40‑Kodierung. |
| [ECI](#ECI) | Im ECI‑Modus wird die gesamte Nachricht mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Bezeichner eingefügt wird. |
| [EDIFACT](#EDIFACT) | Verwendet EDIFACT‑Kodierung. |
| [EXTENDED](#EXTENDED) | Der ExtendedCodetext‑Modus ermöglicht das manuelle Umschalten von Kodierungsschemata und ECI‑Kodierungen im Codetext. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | Verwendet Text‑Kodierung. |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


Verwendet ANSI‑X12‑Kodierung.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Kodiert ein alphanumerisches oder zwei numerische Zeichen pro Byte

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode‑Zeichen werden mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Bezeichner eingefügt wird. Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


8‑Bit‑Werte kodieren

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode‑Zeichen gefunden, wird eine Ausnahme ausgelöst.

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


8‑Bit‑Werte kodieren

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Verwendet C40‑Kodierung. Kodiert Großbuchstaben‑Alphanumerisch, Kleinbuchstaben und Sonderzeichen.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


Im ECI‑Modus wird die gesamte Nachricht mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Bezeichner eingefügt wird. Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige alte (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Verwendet EDIFACT‑Kodierung. Verwendet sechs Bits pro Zeichen, kodiert Ziffern, Großbuchstaben und viele Satzzeichen, unterstützt jedoch keine Kleinbuchstaben.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


Der ExtendedCodetext‑Modus ermöglicht das manuelle Umschalten von Kodierungsschemata und ECI‑Kodierungen im Codetext. Es ist besser, DataMatrixExtCodetextBuilder für die Erzeugung von erweitertem Codetext zu verwenden. Verwenden Sie die Display2DText‑Eigenschaft, um den sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen. ECI‑Bezeichner werden als einzelner Schrägstrich und sechsstelliger Bezeichner "\\000026" – UTF8‑ECI‑Bezeichner gesetzt. Alle Unicode‑Zeichen nach dem ECI‑Bezeichner werden automatisch in den korrekten Zeichensatz kodiert. Kodierungsschemata werden im folgenden Format festgelegt: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Zulässige Kodierungsschemata sind: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Alle Rückwärtsschrägstriche (\\) müssen im Text verdoppelt werden.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


Der ExtendedCodetext‑Modus ermöglicht das manuelle Umschalten von Kodierungsschemata und ECI‑Kodierungen im Codetext.

Es ist besser, DataMatrixExtCodetextBuilder für die Erzeugung von erweitertem Codetext zu verwenden.

Verwenden Sie die Display2DText‑Eigenschaft, um den sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen.

ECI‑Bezeichner werden als einzelner Schrägstrich und sechsstelliger Bezeichner "\\000026" – UTF8‑ECI‑Bezeichner gesetzt.

Alle Unicode‑Zeichen nach dem ECI‑Bezeichner werden automatisch in den korrekten Zeichensatz kodiert.

Kodierungsschemata werden im folgenden Format festgelegt: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text".

Zulässige Kodierungsschemata sind: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.

Alle Rückwärtsschrägstriche (\\) müssen im Text verdoppelt werden.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Verwendet Text‑Kodierung. Kodiert Kleinbuchstaben‑Alphanumerisch, Großbuchstaben und Sonderzeichen.

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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
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

