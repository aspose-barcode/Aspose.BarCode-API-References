---
title: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Tanımlanan barkodların bölgesini ve barkod açısını temsil eder"
type: docs
weight: 16
url: /tr/java/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Tanımlanan barkodun bölgesini ve barkod açısını temsil eder.

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
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen  BarCodeRegionParameters  değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getAngle()](#getAngle--) | Barkodun açısını (0-360) alır. |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Barkod bölgesini sınırlayan Point dizisini alır |
| [getQuadrangle()](#getQuadrangle--) | Barkod bölgesini sınırlayan Aspose.BarCode.BarCodeRecognition.Quadrangle değerini alır |
| [getRectangle()](#getRectangle--) | Barkod bölgesini sınırlayan System.Drawing.Rectangle değerini alır |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu  BarCodeRegionParameters  nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
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
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak bir System.Object değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnek ile aynı değere sahipse; aksi takdirde,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Barkodun açısını (0-360) alır.

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
java.awt.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Barkod bölgesini sınırlayan Aspose.BarCode.BarCodeRecognition.Quadrangle değerini alır

Değer: Barkod bölgesini sınırlayan Aspose.BarCode.BarCodeRecognition.Quadrangle değerini döndürür

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Barkod bölgesini sınırlayan System.Drawing.Rectangle değerini alır

Değer: Barkod bölgesini sınırlayan System.Drawing.Rectangle değerini döndürür

**Returns:**
java.awt.Rectangle
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


Bu  BarCodeRegionParameters  nesnesinin insan tarafından okunabilir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu  BarCodeRegionParameters  nesnesini temsil eden bir dize.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

