---
title: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "認識されたバーコードの領域とバーコードの角度を表します"
type: docs
weight: 16
url: /ja/java/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

認識されたバーコードの領域とバーコード角度を表します

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
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された BarCodeRegionParameters の値と等しいかどうかを示す値を返します。 |
| [getAngle()](#getAngle--) | バーコードの角度 (0-360) を取得します。 |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | バーコード領域を囲む Point 配列を取得します |
| [getQuadrangle()](#getQuadrangle--) | バーコード領域を囲む Aspose.BarCode.BarCodeRecognition.Quadrangle を取得します |
| [getRectangle()](#getRectangle--) | バーコード領域を囲む System.Drawing.Rectangle を取得します |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この BarCodeRegionParameters の人間が読みやすい文字列表現を返します |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された BarCodeRegionParameters の値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための System.Object 値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は **false** 。
### getAngle() {#getAngle--}
```
public double getAngle()
```


バーコードの角度 (0-360) を取得します。

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
java.awt.Point[]
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
public Rectangle getRectangle()
```


バーコード領域を囲む System.Drawing.Rectangle を取得します

値: バーコード領域を囲む System.Drawing.Rectangle を返します

**Returns:**
java.awt.Rectangle
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32ビット符号付き整数のハッシュコード。
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


この BarCodeRegionParameters の人間が読みやすい文字列表現を返します

**Returns:**
java.lang.String - この BarCodeRegionParameters を表す文字列です。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

