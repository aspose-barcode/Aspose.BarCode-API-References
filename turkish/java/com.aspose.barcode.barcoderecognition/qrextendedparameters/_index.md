---
title: "QRExtendedParameters"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Tanımlanan barkodun QR Structured Append bilgilerini depolar"
type: docs
weight: 38
url: /tr/java/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Tanımlanan barkodun QR Structured Append bilgilerini depolar

Bu örnek QR Structured Append verisinin nasıl alınacağını gösterir

```
{
```
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Tanımlanan barkodun Reed-Solomon hata düzeltme seviyesi. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Tanımlanan MicroQR Kodunun sürümü. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Tanımlanan RectMicroQR Kodunun sürümü. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | QR yapılandırılmış ekleme modu barkodunun indeksini alır. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | QR yapılandırılmış ekleme modu barkodlarının miktarını alır. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | QR yapılandırılmış ekleme modu eşlik verisini alır. |
| [getVersion()](#getVersion--) | Tanımlanan QR Kodunun sürümü. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [isEmpty()](#isEmpty--) | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder. |
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


Bu örneğin belirtilen [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak bir System.Object değeri. |

**Returns:**
boolean -  **true**  eğer obj bu örnek ile aynı değere sahipse; aksi takdirde,  **false** .
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


QR yapılandırılmış ekleme modu barkodunun indeksini alır. İndeks 0'dan başlar. Varsayılan değer -1'dir.

Değer: QR yapılandırılmış ekleme modu barkodunun miktarı.

**Returns:**
int - QR yapılandırılmış ekleme modu barkodunun indeksi.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


QR yapılandırılmış ekleme modu barkodlarının miktarını alır. Varsayılan değer -1.

Değer: QR yapılandırılmış ekleme modu barkodunun miktarı.

**Returns:**
int - QR yapılandırılmış ekleme modu barkodlarının miktarı.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


QR yapılandırılmış ekleme modu eşlik verisini alır. Varsayılan değer -1.

Değer: QR yapılandırılmış ekleme modu barkodunun indeksi.

**Returns:**
int - QR yapılandırılmış ekleme modu eşlik verisi.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Tanımlanan QR Kodunun sürümü. Version1'den Version40'a.

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


Bu [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) öğesinin insan tarafından okunabilir dize temsili döndürür.

**Returns:**
java.lang.String - Bu [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) öğesini temsil eden bir dize.
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

