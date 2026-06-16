---
title: TwoDComponentType
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: Type of 2D component  This sample shows how to create and save a GS1 Composite Bar image.
type: docs
weight: 110
url: /ar/androidjava/com.aspose.barcode.generation/twodcomponenttype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TwoDComponentType extends Enum<TwoDComponentType>
```

نوع المكوّن ثنائي الأبعاد  هذا المثال يظهر كيفية إنشاء وحفظ صورة شريط مركب GS1. لاحظ أن نص الترميز أحادي البعد ونص الترميز ثنائي البعد مفصولان بالرمز '/' `String codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext); generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128); generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A); // Aspect ratio of 2D component generator.getParameters().getBarcode().getPdf417().setAspectRatio(3); // X-Dimension of 1D and 2D components generator.getParameters().getBarcode().getXDimension().setPixels(3); // Height of 1D component generator.getParameters().getBarcode().getBarHeight().setPixels(100); generator.save("test.png");`
## الحقول

| حقل | الوصف |
| --- | --- |
| [AUTO](#AUTO) | اختيار تلقائي لنوع المكوّن ثنائي الأبعاد |
| [CC_A](#CC-A) | نوع CC-A للمكوّن ثنائي الأبعاد. |
| [CC_B](#CC-B) | نوع CC-B للمكوّن ثنائي الأبعاد. |
| [CC_C](#CC-C) | نوع CC-C للمكوّن ثنائي الأبعاد. |
## Methods

| Method | الوصف |
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
public static final TwoDComponentType AUTO
```


اختيار تلقائي لنوع المكوّن ثنائي الأبعاد

### CC_A {#CC-A}
```
public static final TwoDComponentType CC_A
```


نوع CC-A من المكوّن ثنائي الأبعاد. إنه متغيّر هيكلي لـ MicroPDF417

### CC_B {#CC-B}
```
public static final TwoDComponentType CC_B
```


نوع CC-B من المكوّن ثنائي الأبعاد. إنه رمز MicroPDF417.

### CC_C {#CC-C}
```
public static final TwoDComponentType CC_C
```


نوع CC-C من المكوّن ثنائي الأبعاد. إنه رمز PDF417.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
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
public static TwoDComponentType valueOf(String name)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

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
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

