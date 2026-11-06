---
title: "BarCodeRegionParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Tanımlanan barkodların bölgesini ve barkod açısını temsil eder"
type: docs
weight: 16
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Tanınan barkodun bölgesini ve barkod açısını temsil eder

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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen  BarCodeRegionParameters  değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getAngle()](#getAngle--) | Barkodun açısını alır (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Barkod bölgesini sınırlayan Point dizisini alır |
| [getQuadrangle()](#getQuadrangle--) | Barkod bölgesini sınırlayan Aspose.BarCode.BarCodeRecognition.Quadrangle'ı alır |
| [getRectangle()](#getRectangle--) | Barkod bölgesini sınırlayan System.Drawing.Rectangle'ı alır |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu  BarCodeRegionParameters  için insan tarafından okunabilir bir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen  BarCodeRegionParameters  değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak bir System.Object değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Barkodun açısını alır (0-360).

Değer: Barkodun açısı (0-360).

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


Barkod bölgesini sınırlayan Point dizisini alır

Değer: Barkod bölgesini sınırlayan Point dizisini döndürür

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Barkod bölgesini sınırlayan Aspose.BarCode.BarCodeRecognition.Quadrangle'ı alır

Değer: Barkod bölgesini sınırlayan Aspose.BarCode.BarCodeRecognition.Quadrangle'ı döndürür

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


Barkod bölgesini sınırlayan System.Drawing.Rectangle'ı alır

Değer: Barkod bölgesini sınırlayan System.Drawing.Rectangle'ı döndürür

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodu döndürür.

**Returns:**
int - 32 bit işaretli tamsayı karma kodu.
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


Bu  BarCodeRegionParameters  için insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu  BarCodeRegionParameters  öğesini temsil eden bir dize.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

