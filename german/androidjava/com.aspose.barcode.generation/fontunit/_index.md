---
title: "FontUnit"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stilattribute, wobei die Größe in der Eigenschaft Unit-Wert angegeben wird."
type: docs
weight: 43
url: /de/androidjava/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stilattribute, wobei die Größe in der Eigenschaft Unit-Wert angegeben wird.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontUnit(FontUnit source)](#FontUnit-com.aspose.barcode.generation.FontUnit-) |  |
| [FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi)](#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-) |  |
| [FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style)](#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-int-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | Gibt den Schriftartnamen dieses Fonts zurück. |
| [getSize()](#getSize--) | Gibt die Größe dieses FontUnit im Unit-Wert zurück. |
| [getStyle()](#getStyle--) | Gibt Stilinformationen für dieses FontUnit zurück. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(Typeface value)](#setFamilyName-android.graphics.Typeface-) | Setzt den Schriftartnamen dieses Fonts. |
| [setStyle(int value)](#setStyle-int-) | Setzt Stilinformationen für dieses FontUnit. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontUnit(FontUnit source) {#FontUnit-com.aspose.barcode.generation.FontUnit-}
```
public FontUnit(FontUnit source)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi) {#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-}
```
public FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| familyName | android.graphics.Typeface |  |
| sizeValue | float |  |
| graphicsUnit | [GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit) |  |
| dpi | float |  |
| Stil | int |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Gibt den Schriftartnamen dieses Fonts zurück.

**Returns:**
android.graphics.Typeface
### getSize() {#getSize--}
```
public Unit getSize()
```


Gibt die Größe dieses FontUnit im Unit-Wert zurück.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStyle() {#getStyle--}
```
public int getStyle()
```


Gibt Stilinformationen für dieses FontUnit zurück.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
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


Setzt den Schriftartnamen dieses Fonts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | android.graphics.Typeface |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Setzt Stilinformationen für dieses FontUnit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

