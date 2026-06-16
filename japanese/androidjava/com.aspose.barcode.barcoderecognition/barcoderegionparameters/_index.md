---
title: BarCodeRegionParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: 認識されたバーコードの領域とバーコードの角度を表します。
type: docs
weight: 17
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

認識されたバーコードの領域とバーコードの角度を表します

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

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された BarCodeRegionParameters の値と等しいかどうかを示す値を返します。 |
| [getAngle()](#getAngle--) | バーコードの角度（0〜360）を取得します。 |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | バーコード領域を囲む Point 配列を取得します |
| [getQuadrangle()](#getQuadrangle--) | バーコード領域を囲む Aspose.BarCode.BarCodeRecognition.Quadrangle を取得します |
| [getRectangle()](#getRectangle--) | バーコード領域を囲む System.Drawing.Rectangle を取得します |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この BarCodeRegionParameters の人間が読める文字列表現を返します |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された BarCodeRegionParameters の値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための System.Object 値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は **false** 。
### getAngle() {#getAngle--}
```
public double getAngle()
```


バーコードの角度（0〜360）を取得します。

値: バーコードの角度 (0-360)。

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


バーコード領域を囲む Point 配列を取得します

値: バーコード領域を囲む Point 配列を返します

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


バーコード領域を囲む Aspose.BarCode.BarCodeRecognition.Quadrangle を取得します

値: バーコード領域を囲む Aspose.BarCode.BarCodeRecognition.Quadrangle を返します

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


バーコード領域を囲む System.Drawing.Rectangle を取得します

値: バーコード領域を囲む System.Drawing.Rectangle を返します

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
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


この BarCodeRegionParameters の人間が読める文字列表現を返します

**Returns:**
java.lang.String - この BarCodeRegionParameters を表す文字列
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

