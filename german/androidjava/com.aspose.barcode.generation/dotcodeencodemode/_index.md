---
title: DotCodeEncodeMode
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Kodierungsmodus für DotCode-Barcodes.
type: docs
weight: 85
url: /de/androidjava/com.aspose.barcode.generation/dotcodeencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DotCodeEncodeMode extends Enum<DotCodeEncodeMode>
```

Kodierungsmodus für DotCode-Barcodes.

--------------------

> ```
> //Auto mode with macros
>  String codetext = ""[)>05CodetextWithMacros05"";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  {
>      generator.save("test.bmp");
>  }
> 
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  {
>      generator.getParameters().getBarcode().getDotCode().setECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.bmp");
>  }
> 
>  //Bytes mode
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE);
>  {
>      generator.setCodetext(encodedArr);
>      generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.BINARY);
>      generator.save("test.bmp");
>  }
>  //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  //generate codetext
>  String codetext = textBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  {
>      generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  	   generator.save("test.bmp");
>  }
> ```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [AUTO](#AUTO) | Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. |
| [BINARY](#BINARY) | Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. |
| [BYTES](#BYTES) | Kodieren Sie den Codetext als einfache Bytes. |
| [ECI](#ECI) | Im ECI‑Modus wird die gesamte Nachricht mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Bezeichner eingefügt wird. |
| [EXTENDED](#EXTENDED) |  |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
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
public static final DotCodeEncodeMode AUTO
```


Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode‑Zeichen werden mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Bezeichner eingefügt wird. Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst.

### BINARY {#BINARY}
```
public static final DotCodeEncodeMode BINARY
```


Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode‑Zeichen gefunden, wird eine Ausnahme ausgelöst.

### BYTES {#BYTES}
```
public static final DotCodeEncodeMode BYTES
```


Kodieren Sie den Codetext als einfache Bytes. Wenn ein Unicode‑Zeichen erkannt wird, wird das Zeichen als zwei Bytes kodiert, zuerst das niederwertige Byte.

### ECI {#ECI}
```
public static final DotCodeEncodeMode ECI
```


Im ECI‑Modus wird die gesamte Nachricht mit der im ECIEncoding angegebenen Kodierung neu kodiert, wobei ein ECI‑Bezeichner eingefügt wird. Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige alte (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen.

### EXTENDED {#EXTENDED}
```
public static final DotCodeEncodeMode EXTENDED
```


Erweiterter Modus, der mehrere ECI‑Modi unterstützt.

Es ist besser, DotCodeExtCodetextBuilder für die erweiterte Codetext-Generierung zu verwenden.

Verwenden Sie die Display2DText‑Eigenschaft, um den sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen.

ECI‑Bezeichner werden als einzelner Schrägstrich und sechsstelliger Bezeichner "\\000026" – UTF8‑ECI‑Bezeichner gesetzt.

Alle Unicode‑Zeichen nach dem ECI‑Bezeichner werden automatisch in den korrekten Zeichensatz kodiert.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DotCodeEncodeMode EXTENDED_CODETEXT
```


Erweiterter Modus, der mehrere ECI‑Modi unterstützt.

Es ist besser, DotCodeExtCodetextBuilder für die erweiterte Codetext-Generierung zu verwenden.

Verwenden Sie die Display2DText‑Eigenschaft, um den sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen.

ECI‑Bezeichner werden als einzelner Schrägstrich und sechsstelliger Bezeichner "\\000026" – UTF8‑ECI‑Bezeichner gesetzt.

Alle Unicode‑Zeichen nach dem ECI‑Bezeichner werden automatisch in den korrekten Zeichensatz kodiert.

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
public static DotCodeEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### values() {#values--}
```
public static DotCodeEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DotCodeEncodeMode[]
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

