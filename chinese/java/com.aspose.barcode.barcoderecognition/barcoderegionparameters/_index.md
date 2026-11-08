---
title: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "表示已识别条码的区域和条码角度"
type: docs
weight: 16
url: /zh/java/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

表示已识别条形码的区域和条形码角度

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
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 BarCodeRegionParameters 值。 |
| [getAngle()](#getAngle--) | 获取条码的角度（0-360）。 |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | 获取界定条码区域的 Point 数组 |
| [getQuadrangle()](#getQuadrangle--) | 获取界定条码区域的 Aspose.BarCode.BarCodeRecognition.Quadrangle |
| [getRectangle()](#getRectangle--) | 获取界定条码区域的 System.Drawing.Rectangle |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回此 BarCodeRegionParameters 的人类可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 BarCodeRegionParameters 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 一个 System.Object 值，用于与此实例比较。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则，  **false** 。
### getAngle() {#getAngle--}
```
public double getAngle()
```


获取条码的角度（0-360）。

值：条码的角度（0-360）。

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


获取界定条码区域的 Point 数组

值：返回界定条码区域的 Point 数组

**Returns:**
java.awt.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


获取界定条码区域的 Aspose.BarCode.BarCodeRecognition.Quadrangle

值：返回界定条码区域的 Aspose.BarCode.BarCodeRecognition.Quadrangle

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取界定条码区域的 System.Drawing.Rectangle

值：返回界定条码区域的 System.Drawing.Rectangle

**Returns:**
java.awt.Rectangle
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


返回此 BarCodeRegionParameters 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 BarCodeRegionParameters 的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

