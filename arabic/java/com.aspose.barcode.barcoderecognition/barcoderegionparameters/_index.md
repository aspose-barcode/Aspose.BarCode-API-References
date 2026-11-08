---
title: "BarCodeRegionParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "يمثل منطقة الباركودات المعترف بها وزاوية الباركود"
type: docs
weight: 16
url: /ar/java/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
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
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>     System.out.println("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
>  }
> ```
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة BarCodeRegionParameters المحددة. |
| [getAngle()](#getAngle--) | يحصل على زاوية الباركود (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | يحصل على مصفوفة Point التي تحدد منطقة الباركود |
| [getQuadrangle()](#getQuadrangle--) | يحصل على Aspose.BarCode.BarCodeRecognition.Quadrangle التي تحدد منطقة الباركود |
| [getRectangle()](#getRectangle--) | يحصل على System.Drawing.Rectangle التي تحدد منطقة الباركود |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا قابلًا للقراءة لهذا BarCodeRegionParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة BarCodeRegionParameters المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذه المثيلة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا،  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


يحصل على زاوية الباركود (0-360).

القيمة: زاوية الباركود (0-360).

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


يحصل على مصفوفة Point التي تحدد منطقة الباركود

القيمة: يرجع مصفوفة Point التي تحدد منطقة الباركود

**Returns:**
java.awt.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


يحصل على Aspose.BarCode.BarCodeRecognition.Quadrangle التي تحدد منطقة الباركود

القيمة: يرجع Aspose.BarCode.BarCodeRecognition.Quadrangle التي تحدد منطقة الباركود

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


يحصل على System.Drawing.Rectangle التي تحدد منطقة الباركود

القيمة: يرجع System.Drawing.Rectangle التي تحدد منطقة الباركود

**Returns:**
java.awt.Rectangle
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة لهذه المثيلة.

**Returns:**
int - رمز تجزئة عدد صحيح موقع 32-بت.
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


يرجع تمثيلًا نصيًا قابلًا للقراءة لهذا BarCodeRegionParameters.

**Returns:**
java.lang.String - سلسلة تمثل هذا BarCodeRegionParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

