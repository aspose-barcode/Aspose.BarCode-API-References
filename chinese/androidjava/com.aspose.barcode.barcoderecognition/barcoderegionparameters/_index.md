---
title: BarCodeRegionParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: Represents the recognized barcodes region and barcode angle
type: docs
weight: 17
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

表示已识别条码的区域和条码角度

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

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified  BarCodeRegionParameters  value. |
| [getAngle()](#getAngle--) | Gets the angle of the barcode (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | 获取  Point s 数组的条形码区域边界 |
| [getQuadrangle()](#getQuadrangle--) | 获取  Aspose.BarCode.BarCodeRecognition.Quadrangle 的条形码区域边界 |
| [getRectangle()](#getRectangle--) | 获取  System.Drawing.Rectangle 的条形码区域边界 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回此  BarCodeRegionParameters 的人类可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified  BarCodeRegionParameters  value.

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 一个 System.Object 值，用于与此实例进行比较。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则， **false** 。
### getAngle() {#getAngle--}
```
public double getAngle()
```


Gets the angle of the barcode (0-360).

值：条形码的角度（0-360）。

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


获取  Point s 数组的条形码区域边界

值：返回  Point s 数组，表示条形码区域的边界

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


获取  Aspose.BarCode.BarCodeRecognition.Quadrangle 的条形码区域边界

值：返回  Aspose.BarCode.BarCodeRecognition.Quadrangle 的条形码区域边界

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


获取  System.Drawing.Rectangle 的条形码区域边界

值：返回  System.Drawing.Rectangle 的条形码区域边界

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 32 位有符号整数哈希码。
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


返回此  BarCodeRegionParameters 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此  BarCodeRegionParameters 的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

