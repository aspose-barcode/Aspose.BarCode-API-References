---
title: BarCodeRegionParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Представляет область распознанных штрихкодов и угол штрихкода
type: docs
weight: 17
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Представляет регион распознанного штрихкода и угол штрихкода

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
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению  BarCodeRegionParameters . |
| [getAngle()](#getAngle--) | Получает угол штрихкода (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Получает массив точек, ограничивающих область штрихкода |
| [getQuadrangle()](#getQuadrangle--) | Получает объект Aspose.BarCode.BarCodeRecognition.Quadrangle, ограничивающий область штрихкода |
| [getRectangle()](#getRectangle--) | Получает объект System.Drawing.Rectangle, ограничивающий область штрихкода |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого BarCodeRegionParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли данный экземпляр указанному значению  BarCodeRegionParameters .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение System.Object для сравнения с этим экземпляром. |

**Returns:**
boolean —  **true**  если obj имеет то же значение, что и этот экземпляр; в противном случае  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Получает угол штрихкода (0-360).

Значение: Угол для штрихкода (0-360).

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


Получает массив точек, ограничивающих область штрихкода

Значение: Возвращает массив точек, ограничивающих область штрихкода.

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Получает объект Aspose.BarCode.BarCodeRecognition.Quadrangle, ограничивающий область штрихкода

Значение: Возвращает объект Aspose.BarCode.BarCodeRecognition.Quadrangle, ограничивающий область штрихкода.

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


Получает объект System.Drawing.Rectangle, ограничивающий область штрихкода

Значение: Возвращает объект System.Drawing.Rectangle, ограничивающий область штрихкода.

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этого экземпляра.

**Returns:**
int — 32‑битный знаковый целочисленный хеш‑код.
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


Возвращает человекочитаемое строковое представление этого BarCodeRegionParameters.

**Returns:**
java.lang.String — строка, представляющая этот BarCodeRegionParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

