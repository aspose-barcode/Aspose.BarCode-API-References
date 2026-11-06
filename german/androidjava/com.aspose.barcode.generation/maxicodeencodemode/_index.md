---
title: "MaxiCodeEncodeMode"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Kodierungsmodus für MaxiCode-Barcodes."
type: docs
weight: 94
url: /de/androidjava/com.aspose.barcode.generation/maxicodeencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeEncodeMode extends Enum<MaxiCodeEncodeMode>
```

Kodierungsmodus für MaxiCode-Barcodes.

```
//Auto mode
 String codetext = "\u72acRight\u72d7";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 {
     generator.getParameters().getBarcode().getMaxiCode().setECIEncoding(ECIEncodings.UTF8);
     generator.save("test.bmp");
 }

 //Bytes mode
 byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE);
 generator.setCodetext(encodedArr);
 generator.getParameters().getBarcode().getMaxiCode().setMaxiCodeEncodeMode(MaxiCodeEncodeMode.BINARY);
 generator.save("test.bmp");

 //Extended codetext mode
 //create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 // generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext);
 generator.getParameters().getBarcode().getMaxiCode().setMaxiCodeEncodeMode(MaxiCodeEncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [AUTO](#AUTO) | Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. |
| [BINARY](#BINARY) | Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. |
| [ECI](#ECI) | Im ECI‑Modus wird die gesamte Nachricht in der durch ECIEncoding angegebenen Kodierung mit dem Einfügen eines ECI‑Identifikators neu kodiert. |
| [EXTENDED](#EXTENDED) |  |
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
public static final MaxiCodeEncodeMode AUTO
```


Im Auto‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode‑Zeichen werden in der durch ECIEncoding angegebenen Kodierung mit dem Einfügen eines ECI‑Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst.

### BINARY {#BINARY}
```
public static final MaxiCodeEncodeMode BINARY
```


Im Binär‑Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode‑Zeichen gefunden, wird eine Ausnahme ausgelöst.

### ECI {#ECI}
```
public static final MaxiCodeEncodeMode ECI
```


Im ECI‑Modus wird die gesamte Nachricht in der durch ECIEncoding angegebenen Kodierung mit dem Einfügen eines ECI‑Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI‑Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige ältere (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen.

### EXTENDED {#EXTENDED}
```
public static final MaxiCodeEncodeMode EXTENDED
```


Erweiterter Modus, der mehrere ECI-Modi unterstützt.

Es ist besser, MaxiCodeExtCodetextBuilder für die erweiterte Codetext-Generierung zu verwenden.

Verwenden Sie die Eigenschaft Display2DText, um den sichtbaren Text festzulegen, indem verwaltende Zeichen entfernt werden.

ECI-Identifikatoren werden als einzelner Schrägstrich und sechsstelliger Bezeichner "\\000026" festgelegt – UTF8 ECI-Identifikator.

Alle Unicode-Zeichen nach dem ECI-Identifikator werden automatisch in das korrekte Zeichensatz kodiert.

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
public static MaxiCodeEncodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode)
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
public static MaxiCodeEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode)
### values() {#values--}
```
public static MaxiCodeEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.MaxiCodeEncodeMode[]
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

