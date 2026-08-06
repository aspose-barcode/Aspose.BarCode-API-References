---
title: BarCodeRegionParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يمثل منطقة الباركودات المعترف بها وزاوية الباركود
type: docs
weight: 17
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

يمثل منطقة الباركود المعترف به وزاوية الباركود

--------------------

> ```
> This sample shows how to get barcode Angle and bounding quadrangle values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>     System.out.println("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
>  }
> ```
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة BarCodeRegionParameters المحددة. |
| [getAngle()](#getAngle--) | يحصل على زاوية الباركود (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | يحصل على مصفوفة Point s التي تحدد منطقة الباركود |
| [getQuadrangle()](#getQuadrangle--) | يحصل على Aspose.BarCode.BarCodeRecognition.Quadrangle التي تحدد منطقة الباركود |
| [getRectangle()](#getRectangle--) | يحصل على System.Drawing.Rectangle التي تحدد منطقة الباركود |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يعيد تمثيل نصي قابل للقراءة للإنسان لهذا BarCodeRegionParameters |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة BarCodeRegionParameters المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذا الكائن. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


يحصل على زاوية الباركود (0-360).

القيمة: الزاوية للباركود (0-360).

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


يحصل على مصفوفة Point s التي تحدد منطقة الباركود

القيمة: يعيد مصفوفة Point s التي تحدد منطقة الباركود

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


يحصل على Aspose.BarCode.BarCodeRecognition.Quadrangle التي تحدد منطقة الباركود

القيمة: يعيد Aspose.BarCode.BarCodeRecognition.Quadrangle التي تحدد منطقة الباركود

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


يحصل على System.Drawing.Rectangle التي تحدد منطقة الباركود

القيمة: يعيد System.Drawing.Rectangle التي تحدد منطقة الباركود

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


يعيد تمثيل نصي قابل للقراءة للإنسان لهذا BarCodeRegionParameters

**Returns:**
java.lang.String - سلسلة تمثل هذا BarCodeRegionParameters
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

