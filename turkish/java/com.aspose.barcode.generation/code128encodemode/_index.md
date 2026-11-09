---
title: "Code128EncodeMode"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Code128 barkodları için kodlama modu."
type: docs
weight: 78
url: /tr/java/com.aspose.barcode.generation/code128encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Code128EncodeMode extends Enum<Code128EncodeMode>
```

Code128 barkodları için kodlama modu.  Code 128  spesifikasyonu.

--------------------

> ```
> Thos code demonstrates how to generate code 128 with different encodings
>  
> 
>  //Generate code 128 with ISO 15417 encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO);
>  generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG);
> 
>  //Generate code 128 only with Codeset A encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A);
>  generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);
> ```
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AUTO](#AUTO) | Kod metnini klasik ISO 15417 modunda kodlayın. |
| [CODE_A](#CODE-A) | Kod metnini yalnızca 128A kod kümesinde kodlayın. |
| [CODE_AB](#CODE-AB) | Kod metnini yalnızca 128A ve 128B kod kümelerinde kodlayın. |
| [CODE_AC](#CODE-AC) | Kod metnini yalnızca 128A ve 128C kod kümelerinde kodlayın. |
| [CODE_B](#CODE-B) | Kod metnini yalnızca 128B kod kümesinde kodlayın. |
| [CODE_BC](#CODE-BC) | Kod metnini yalnızca 128B ve 128C kod kümelerinde kodlayın. |
| [CODE_C](#CODE-C) | Kod metnini yalnızca 128C kod kümesinde kodlayın. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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
| [valueOf(int value)](#valueOf-int-) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final Code128EncodeMode AUTO
```


Kod metnini klasik ISO 15417 modunda kodlayın. Mod, tüm olağan durumlarda kullanılmalıdır.

### CODE_A {#CODE-A}
```
public static final Code128EncodeMode CODE_A
```


Kod metnini yalnızca 128A kod kümesinde kodlayın.

### CODE_AB {#CODE-AB}
```
public static final Code128EncodeMode CODE_AB
```


Kod metnini yalnızca 128A ve 128B kod kümelerinde kodlayın.

### CODE_AC {#CODE-AC}
```
public static final Code128EncodeMode CODE_AC
```


Kod metnini yalnızca 128A ve 128C kod kümelerinde kodlayın.

### CODE_B {#CODE-B}
```
public static final Code128EncodeMode CODE_B
```


Kod metnini yalnızca 128B kod kümesinde kodlayın.

### CODE_BC {#CODE-BC}
```
public static final Code128EncodeMode CODE_BC
```


Kod metnini yalnızca 128B ve 128C kod kümelerinde kodlayın.

### CODE_C {#CODE-C}
```
public static final Code128EncodeMode CODE_C
```


Kod metnini yalnızca 128C kod kümesinde kodlayın.

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
public static Code128EncodeMode fromValue(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
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
### valueOf(int value) {#valueOf-int-}
```
public static Code128EncodeMode valueOf(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Code128EncodeMode valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### values() {#values--}
```
public static Code128EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Code128EncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

