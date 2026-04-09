---
title: FontUnit
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Ορίζει μια συγκεκριμένη μορφή για κείμενο, συμπεριλαμβανομένου του μεγέθους γραμματοσειράς και των χαρακτηριστικών στυλ, όπου το μέγεθος βρίσκεται στην ιδιότητα Unit value.
type: docs
weight: 44
url: /el/androidjava/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

Ορίζει μια συγκεκριμένη μορφή για το κείμενο, συμπεριλαμβανομένης της γραμματοσειράς, του μεγέθους και των χαρακτηριστικών στυλ, όπου το μέγεθος βρίσκεται στην ιδιότητα Unit value property.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [FontUnit(FontUnit source)](#FontUnit-com.aspose.barcode.generation.FontUnit-) |  |
| [FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi)](#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-) |  |
| [FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style)](#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-int-) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | Λαμβάνει το όνομα γραμματοσειράς αυτού του Font. |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος αυτού του FontUnit σε Unit value. |
| [getStateHash()](#getStateHash--) |  |
| [getStyle()](#getStyle--) | Λαμβάνει πληροφορίες στυλ για αυτό το FontUnit. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(Typeface value)](#setFamilyName-android.graphics.Typeface-) | Ορίζει το όνομα γραμματοσειράς αυτού του Font. |
| [setStyle(int value)](#setStyle-int-) | Ορίζει πληροφορίες στυλ για αυτό το FontUnit. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontUnit(FontUnit source) {#FontUnit-com.aspose.barcode.generation.FontUnit-}
```
public FontUnit(FontUnit source)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| source | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi) {#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-}
```
public FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| familyName | android.graphics.Typeface |  |
| sizeValue | float |  |
| graphicsUnit | [GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit) |  |
| dpi | float |  |

### FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style) {#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-int-}
```
public FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| familyName | android.graphics.Typeface |  |
| sizeValue | float |  |
| graphicsUnit | [GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit) |  |
| dpi | float |  |
| style | int |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
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
### getFamilyName() {#getFamilyName--}
```
public Typeface getFamilyName()
```


Λαμβάνει το όνομα γραμματοσειράς αυτού του Font.

**Returns:**
android.graphics.Typeface
### getSize() {#getSize--}
```
public Unit getSize()
```


Λαμβάνει το μέγεθος αυτού του FontUnit σε Unit value.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStateHash() {#getStateHash--}
```
public int getStateHash()
```




**Returns:**
int
### getStyle() {#getStyle--}
```
public int getStyle()
```


Λαμβάνει πληροφορίες στυλ για αυτό το FontUnit.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFamilyName(Typeface value) {#setFamilyName-android.graphics.Typeface-}
```
public void setFamilyName(Typeface value)
```


Ορίζει το όνομα γραμματοσειράς αυτού του Font.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | android.graphics.Typeface |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Ορίζει πληροφορίες στυλ για αυτό το FontUnit.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

