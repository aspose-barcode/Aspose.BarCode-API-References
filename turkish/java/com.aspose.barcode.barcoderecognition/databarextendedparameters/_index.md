---
title: "DataBarExtendedParameters"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Tanımlanan barkodun DataBar ek bilgilerini depolar BarCodeReader reader  new BarCodeReaderctest.png DecodeType.DATABAR_OMNI_DIRECTIONAL forBarCodeResult result  reader.readBarCodes    System.out.printlnBarCode Type   result.getCodeTypeName    System.out.printlnBarCode CodeText   result.getCodeText    System.out.printlnQR Structured Append Quantity   result.getExtended.getQR.getQRStructuredAppendModeBarCodesQuantity"
type: docs
weight: 28
url: /tr/java/com.aspose.barcode.barcoderecognition/databarextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public class DataBarExtendedParameters extends BaseExtendedParameters
```

Tanımlanan barkodun DataBar ek bilgilerini depolar BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen DataBarExtendedParameters değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [is2DCompositeComponent()](#is2DCompositeComponent--) | DataBar 2D birleşik bileşen bayrağını alır. |
| [isEmpty()](#isEmpty--) | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu DataBarExtendedParameters nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen DataBarExtendedParameters değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak bir System.Object değeri. |

**Returns:**
boolean - **true** eğer nesne bu örnekle aynı değere sahipse; aksi takdirde **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodu döndürür.

**Returns:**
int - 32 bit işaretli tamsayı karma kodu.
### is2DCompositeComponent() {#is2DCompositeComponent--}
```
public boolean is2DCompositeComponent()
```


DataBar 2D birleşik bileşen bayrağını alır. Varsayılan değer false'tur.

**Returns:**
boolean - DataBar 2D birleşik bileşen bayrağı.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder.

Değer: Tüm parametreler yalnızca varsayılan değerlere sahipse **true** döndürür; aksi takdirde **false**.

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




### toString() {#toString--}
```
public String toString()
```


Bu DataBarExtendedParameters nesnesinin insan tarafından okunabilir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu DataBarExtendedParameters nesnesini temsil eden bir dize.
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

