---
title: "Quadrangle"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Bir Quadrangle bölgesini temsil eden dört Point kümesini depolar."
type: docs
weight: 39
url: /tr/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Dört  Point  öğesinden oluşan bir küme depolar; bu öğeler bir  Quadrangle  bölgeyi temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Tanımlayıcı noktalarla  Quadrangle  sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EMPTY](#EMPTY) | Özellikleri başlatılmamış bir  Quadrangle  sınıfını temsil eder. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Belirtilen  Quadrangle  bu  Quadrangle  sınıfı içinde mi yoksa kesişiyor mu belirler. |
| [contains(int x, int y)](#contains-int-int-) | Belirtilen noktanın bu  Quadrangle  sınıfı içinde olup olmadığını belirler. |
| [contains(Point pt)](#contains-java.awt.Point-) | Belirtilen  Point  bu  Quadrangle  sınıfı içinde olup olmadığını belirler. |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Belirtilen  Rectangle  bu  Quadrangle  sınıfı içinde mi yoksa kesişiyor mu belirler. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen  Quadrangle  değeriyle eşit olup olmadığını gösteren bir değer döndürür. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Bu  Quadrangle ı sınırlayan  Rectangle  oluşturur |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Quadrangle bölgesinin sol-alt köşe  Point  değerini alır |
| [getLeftTop()](#getLeftTop--) | Quadrangle bölgesinin sol-üst köşe  Point  değerini alır |
| [getRightBottom()](#getRightBottom--) | Quadrangle bölgesinin sağ-alt köşe  Point  değerini alır |
| [getRightTop()](#getRightTop--) | Quadrangle bölgesinin sağ-üst köşe  Point  değerini alır |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [isEmpty()](#isEmpty--) | Bu  Quadrangle  içindeki tüm  Point  s değerinin sıfır olup olmadığını test eder. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Quadrangle bölgesinin sol-alt köşe  Point  değerini alır |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Quadrangle bölgesinin sol-üst köşe  Point  değerini alır |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Quadrangle bölgesinin sağ-alt köşe  Point  değerini alır |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Quadrangle bölgesinin sağ-üst köşe  Point  değerini alır |
| [toString()](#toString--) | Bu Quadrangle nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


Tanımlayıcı noktalarla  Quadrangle  sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftTop | java.awt.Point | Quadrangle'ın sol-üst köşesini temsil eden bir Point. |
| rightTop | java.awt.Point | Quadrangle'ın sağ-üst köşesini temsil eden bir Point. |
| rightBottom | java.awt.Point | Quadrangle'ın sağ-alt köşesini temsil eden bir Point. |
| leftBottom | java.awt.Point | Quadrangle'ın sol-alt köşesini temsil eden bir Point. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Özellikleri başlatılmamış bir  Quadrangle  sınıfını temsil eder.

Değer: Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Belirtilen  Quadrangle  bu  Quadrangle  sınıfı içinde mi yoksa kesişiyor mu belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Test edilecek Quadrangle. |

**Returns:**
boolean - Quadrangle bu Quadrangle sınıfı içinde bulunuyorsa veya kesişiyorsa **true** döndürür; aksi takdirde **false**.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Belirtilen noktanın bu  Quadrangle  sınıfı içinde olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | x noktasının koordinatı. |
| y | int | y noktasının koordinatı. |

**Returns:**
boolean - point bu Quadrangle sınıfı içinde bulunuyorsa **true** döndürür; aksi takdirde **false**.
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Belirtilen  Point  bu  Quadrangle  sınıfı içinde olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | java.awt.Point | Test edilecek Point. |

**Returns:**
boolean - Point bu Quadrangle sınıfı içinde bulunuyorsa **true** döndürür; aksi takdirde **false**.
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Belirtilen  Rectangle  bu  Quadrangle  sınıfı içinde mi yoksa kesişiyor mu belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | java.awt.Rectangle | Test edilecek Rectangle. |

**Returns:**
boolean - Rectangle bu Quadrangle sınıfı içinde bulunuyorsa veya kesişiyorsa **true** döndürür; aksi takdirde **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen  Quadrangle  değeriyle eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak bir Quadrangle değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnek ile aynı değere sahipse; aksi takdirde,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Bu  Quadrangle ı sınırlayan  Rectangle  oluşturur

**Returns:**
java.awt.Rectangle - bu Quadrangle'ı sınırlayan Rectangle'ı döndürür
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


Quadrangle bölgesinin sol-alt köşe  Point  değerini alır

Değer: Quadrangle bölgesinin sol-alt köşe Point

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Quadrangle bölgesinin sol-üst köşe  Point  değerini alır

Değer: Quadrangle bölgesinin sol-üst köşe Point

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Quadrangle bölgesinin sağ-alt köşe  Point  değerini alır

Değer: Quadrangle bölgesinin sağ-alt köşe Point

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Quadrangle bölgesinin sağ-üst köşe  Point  değerini alır

Değer: Quadrangle bölgesinin sağ-üst köşe Point

**Returns:**
java.awt.Point
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


Bu  Quadrangle  içindeki tüm  Point  s değerinin sıfır olup olmadığını test eder.

Değer: Bu Quadrangle'ın tüm Point'leri sıfır değerine sahipse **true**, aksi takdirde **false** döndürür.

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




### setLeftBottom(Point value) {#setLeftBottom-java.awt.Point-}
```
public void setLeftBottom(Point value)
```


Quadrangle bölgesinin sol-alt köşe  Point  değerini alır

Değer: Quadrangle bölgesinin sol-alt köşe Point

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Quadrangle bölgesinin sol-üst köşe  Point  değerini alır

Değer: Quadrangle bölgesinin sol-üst köşe Point

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Quadrangle bölgesinin sağ-alt köşe  Point  değerini alır

Değer: Quadrangle bölgesinin sağ-alt köşe Point

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Quadrangle bölgesinin sağ-üst köşe  Point  değerini alır

Değer: Quadrangle bölgesinin sağ-üst köşe Point

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


Bu Quadrangle nesnesinin insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - bu Quadrangle'ı temsil eden bir dize.
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

