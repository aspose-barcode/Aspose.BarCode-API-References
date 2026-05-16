---
title: BarCodeRegionParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: 인식된 바코드 영역 및 바코드 각도를 나타냅니다.
type: docs
weight: 17
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

인식된 바코드의 영역 및 바코드 각도를 나타냅니다

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

| Method | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 BarCodeRegionParameters 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getAngle()](#getAngle--) | 바코드의 각도(0-360)를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | 바코드 영역을 둘러싼 Point 배열을 가져옵니다 |
| [getQuadrangle()](#getQuadrangle--) | 바코드 영역을 둘러싼 Aspose.BarCode.BarCodeRecognition.Quadrangle을 가져옵니다 |
| [getRectangle()](#getRectangle--) | 바코드 영역을 둘러싼 System.Drawing.Rectangle를 가져옵니다 |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 이 BarCodeRegionParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 BarCodeRegionParameters 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object 값입니다. |

**Returns:**
boolean -  **true**  if obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않은 경우 **false**.
### getAngle() {#getAngle--}
```
public double getAngle()
```


바코드의 각도(0-360)를 가져옵니다.

값: 바코드의 각도 (0-360).

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


바코드 영역을 둘러싼 Point 배열을 가져옵니다

값: 바코드 영역을 둘러싼 Point 배열을 반환합니다

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


바코드 영역을 둘러싼 Aspose.BarCode.BarCodeRecognition.Quadrangle을 가져옵니다

값: 바코드 영역을 둘러싼 Aspose.BarCode.BarCodeRecognition.Quadrangle을 반환합니다

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


바코드 영역을 둘러싼 System.Drawing.Rectangle를 가져옵니다

값: 바코드 영역을 둘러싼 System.Drawing.Rectangle를 반환합니다

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드입니다.
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


이 BarCodeRegionParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다

**Returns:**
java.lang.String - 이 BarCodeRegionParameters를 나타내는 문자열
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

