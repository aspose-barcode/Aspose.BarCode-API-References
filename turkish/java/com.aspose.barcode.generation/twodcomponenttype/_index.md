---
title: "TwoDComponentType"
second_title: "Aspose.BarCode for Java API Referansı"
description: "2D bileşen tipi  Bu örnek, bir GS1 Composite Bar görüntüsü nasıl oluşturulur ve kaydedilir gösterir."
type: docs
weight: 108
url: /tr/java/com.aspose.barcode.generation/twodcomponenttype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TwoDComponentType extends Enum<TwoDComponentType>
```

2D bileşenin türü  Bu örnek, bir GS1 Composite Bar görüntüsü nasıl oluşturulur ve kaydedilir gösterir. 1D kod metni ve 2D kod metninin '/' sembolü ile ayrıldığını unutmayın `String codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext); generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128); generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A); // Aspect ratio of 2D component generator.getParameters().getBarcode().getPdf417().setAspectRatio(3); // X-Dimension of 1D and 2D components generator.getParameters().getBarcode().getXDimension().setPixels(3); // Height of 1D component generator.getParameters().getBarcode().getBarHeight().setPixels(100); generator.save("test.png");`
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AUTO](#AUTO) | 2D bileşenin türünü otomatik seç |
| [CC_A](#CC-A) | CC-A 2D bileşen türü. |
| [CC_B](#CC-B) | CC-B 2D bileşen türü. |
| [CC_C](#CC-C) | CC-C 2D bileşen türü. |
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
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final TwoDComponentType AUTO
```


2D bileşenin türünü otomatik seç

### CC_A {#CC-A}
```
public static final TwoDComponentType CC_A
```


CC-A 2D bileşen türü. MicroPDF417'nin yapısal bir varyantıdır

### CC_B {#CC-B}
```
public static final TwoDComponentType CC_B
```


CC-B 2D bileşen türü. Bir MicroPDF417 sembolüdür.

### CC_C {#CC-C}
```
public static final TwoDComponentType CC_C
```


CC-C 2D bileşen türü. Bir PDF417 sembolüdür.

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
public static TwoDComponentType fromValue(int value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

**Returns:**
[TwoDComponentType](../../com.aspose.barcode.generation/twodcomponenttype)
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
public static TwoDComponentType valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[TwoDComponentType](../../com.aspose.barcode.generation/twodcomponenttype)
### values() {#values--}
```
public static TwoDComponentType[] values()
```




**Returns:**
com.aspose.barcode.generation.TwoDComponentType[]
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

