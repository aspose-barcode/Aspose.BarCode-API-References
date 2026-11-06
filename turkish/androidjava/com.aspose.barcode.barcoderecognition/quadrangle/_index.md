---
title: "Quadrangle"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Bir Quadrangle bölgesini temsil eden dört Point kümesini depolar."
type: docs
weight: 41
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Dört adet Point'i depolar; bu Point'ler bir Quadrangle bölgesini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Tanımlayıcı noktalarla Quadrangle yapısının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EMPTY](#EMPTY) | Özellikleri başlatılmamış bir Quadrangle sınıfını temsil eder. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Belirtilen Point'in bu Quadrangle sınıfı içinde bulunup bulunmadığını belirler. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Belirtilen Rectangle'in bu Quadrangle sınıfı içinde bulunup bulunmadığını veya kesişip kesişmediğini belirler. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Belirtilen Quadrangle'in bu Quadrangle sınıfı içinde bulunup bulunmadığını veya kesişip kesişmediğini belirler. |
| [contains(int x, int y)](#contains-int-int-) | Belirtilen noktanın bu Quadrangle sınıfı içinde bulunup bulunmadığını belirler. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen Quadrangle değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Bu Quadrangle'ı sınırlayan Rectangle oluşturur |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Quadrangle bölgesinin sol-alt köşe Point'ini alır |
| [getLeftTop()](#getLeftTop--) | Quadrangle bölgesinin sol-üst köşe Point'ini alır |
| [getRightBottom()](#getRightBottom--) | Quadrangle bölgesinin sağ-alt köşe Point'ini alır |
| [getRightTop()](#getRightTop--) | Quadrangle bölgesinin sağ-üst köşe Point'ini alır |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [isEmpty()](#isEmpty--) | Bu Quadrangle'ın tüm Point'lerinin sıfır değerine sahip olup olmadığını test eder. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Quadrangle bölgesinin sol-alt köşe Point'ini alır |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Quadrangle bölgesinin sol-üst köşe Point'ini alır |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Quadrangle bölgesinin sağ-alt köşe Point'ini alır |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Quadrangle bölgesinin sağ-üst köşe Point'ini alır |
| [toString()](#toString--) | Bu Quadrangle'ın insan tarafından okunabilir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


Tanımlayıcı noktalarla Quadrangle yapısının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftTop | android.graphics.Point | Quadrangle'ın sol-üst köşesini temsil eden bir Point. |
| rightTop | android.graphics.Point | Sağ-üst köşesini temsil eden bir Nokta. |
| rightBottom | android.graphics.Point | Sağ-alt köşesini temsil eden bir Nokta. |
| leftBottom | android.graphics.Point | Sol-alt köşesini temsil eden bir Nokta. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Özellikleri başlatılmamış bir Quadrangle sınıfını temsil eder.

Value: Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Point pt) {#contains-android.graphics.Point-}
```
public boolean contains(Point pt)
```


Belirtilen Point'in bu Quadrangle sınıfı içinde bulunup bulunmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | android.graphics.Point | Test edilecek Nokta. |

**Returns:**
boolean - **true** döndürür eğer Point bu Quadrangle sınıfı içinde bulunuyorsa; aksi takdirde **false** .
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Belirtilen Rectangle'in bu Quadrangle sınıfı içinde bulunup bulunmadığını veya kesişip kesişmediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | android.graphics.Rect | Test edilecek Dikdörtgen. |

**Returns:**
boolean - **true** döndürür eğer Rectangle bu Quadrangle sınıfı içinde bulunur veya kesişirse; aksi takdirde **false** .
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Belirtilen Quadrangle'in bu Quadrangle sınıfı içinde bulunup bulunmadığını veya kesişip kesişmediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Test edilecek Quadrangle. |

**Returns:**
boolean - **true** döndürür eğer Quadrangle bu Quadrangle sınıfı içinde bulunur veya kesişirse; aksi takdirde **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Belirtilen noktanın bu Quadrangle sınıfı içinde bulunup bulunmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | x noktasının koordinatı. |
| y | int | y noktasının koordinatı. |

**Returns:**
boolean - **true** döndürür eğer nokta bu Quadrangle sınıfı içinde bulunuyorsa; aksi takdirde **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen Quadrangle değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırmak için bir Quadrangle değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Bu Quadrangle'ı sınırlayan Rectangle oluşturur

**Returns:**
android.graphics.Rect - bu Quadrangle'ı sınırlayan Rectangle'ı döndürür
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public Point getLeftBottom()
```


Quadrangle bölgesinin sol-alt köşe Point'ini alır

Değer: Quadrangle bölgesinin sol-alt köşe Noktası

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Quadrangle bölgesinin sol-üst köşe Point'ini alır

Değer: Quadrangle bölgesinin sol-üst köşe Noktası

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Quadrangle bölgesinin sağ-alt köşe Point'ini alır

Değer: Quadrangle bölgesinin sağ-alt köşe Noktası

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Quadrangle bölgesinin sağ-üst köşe Point'ini alır

Value: Sağ üst köşe Quadrangle bölgesinin Point

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodu döndürür.

**Returns:**
int - 32 bit işaretli tamsayı karma kodu.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu Quadrangle'ın tüm Point'lerinin sıfır değerine sahip olup olmadığını test eder.

Value: Bu Quadrangle'ın tüm Point'lerinin değeri sıfırsa **true** döndürür; aksi takdirde **false** döndürür.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLeftBottom(Point value) {#setLeftBottom-android.graphics.Point-}
```
public void setLeftBottom(Point value)
```


Quadrangle bölgesinin sol-alt köşe Point'ini alır

Değer: Quadrangle bölgesinin sol-alt köşe Noktası

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Quadrangle bölgesinin sol-üst köşe Point'ini alır

Değer: Quadrangle bölgesinin sol-üst köşe Noktası

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Quadrangle bölgesinin sağ-alt köşe Point'ini alır

Değer: Quadrangle bölgesinin sağ-alt köşe Noktası

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Quadrangle bölgesinin sağ-üst köşe Point'ini alır

Value: Sağ üst köşe Quadrangle bölgesinin Point

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Bu Quadrangle'ın insan tarafından okunabilir dize temsili döndürür.

**Returns:**
java.lang.String - Bu Quadrangle'ı temsil eden bir dize.
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

