---
title: "QRExtendedParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Tanımlanan barkodun QR Structured Append bilgisini depolar"
type: docs
weight: 40
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Tanımlanan barkodun QR Structured Append bilgisini depolar

Bu örnek, QR Structured Append verisinin nasıl alınacağını gösterir

```
{
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örnek, bu örneklemenin belirtilen [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Tanımlanan barkodun Reed-Solomon hata düzeltme seviyesi. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Tanımlanan MicroQR Kodunun sürümü. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Tanımlanan RectMicroQR Kodunun sürümü. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | QR structured append modundaki barkodun indeksini alır. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | QR structured append modundaki barkodların miktarını alır. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | QR structured append modundaki parite verisini alır. |
| [getVersion()](#getVersion--) | Tanımlanan QR Kodunun sürümü. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [isEmpty()](#isEmpty--) | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) öğesinin insan tarafından okunabilir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örnek, bu örneklemenin belirtilen [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak bir System.Object değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnekle aynı değere sahipse; aksi takdirde,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Tanımlanan barkodun Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Tanımlanan MicroQR Kodunun sürümü. M1'den M4'e.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Tanımlanan RectMicroQR Kodunun sürümü. R7x43'ten R17x139'a.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


QR structured append modundaki barkodun indeksini alır. İndeks 0'dan başlar. Varsayılan değer -1'dir.

Değer: QR structured append modundaki barkod miktarı.

**Returns:**
int - QR structured append modundaki barkodun indeksi.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


QR structured append modundaki barkodların miktarını alır. Varsayılan değer -1'dir.

Değer: QR structured append modundaki barkod miktarı.

**Returns:**
int - QR structured append modundaki barkodların miktarı.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


QR structured append modundaki parite verisini alır. Varsayılan değer -1'dir.

Değer: QR structured append modundaki barkod indeksi.

**Returns:**
int - QR structured append modundaki parite verisi.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Tanımlanan QR Kodunun sürümü. Version1'den Version40'a kadar.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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


Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder

Değer: Tüm parametrelerin yalnızca varsayılan değerlere sahip olması durumunda  **true**  döndürür; aksi takdirde  **false** .

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


Bu [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) öğesinin insan tarafından okunabilir dize temsili döndürür.

**Returns:**
java.lang.String - Bu [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) öğesini temsil eden bir dize.
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

