---
title: "QrParametersUI"
second_title: "Aspose.BarCode for Java API Referansı"
description: "com.aspose.barcode.generation.QrParameters sınıfı için UI sarmalayıcısı."
type: docs
weight: 17
url: /tr/java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

com.aspose.barcode.generation.QrParameters sınıfı için UI sarmalayıcısı.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D BarCode modülünün Yükseklik/Genişlik oranı. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) | QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Byte modunda kodlanıp kodlanmayacağını gösteren bir değeri alır veya ayarlar. |
| [getEncodeMode()](#getEncodeMode--) | BarCode'un kodlama modunun QR semboloji türü. |
| [getErrorLevel()](#getErrorLevel--) | QR, MicroQR ve RectMicroQR barkodları için Reed-Solomon hata düzeltme seviyesi. |
| [getMicroQrVersion()](#getMicroQrVersion--) | MicroQR Kodu sürümü. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR Kodu sürümü. |
| [getVersion()](#getVersion--) | QR Kodu sürümü. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D BarCode modülünün Yükseklik/Genişlik oranı. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) | QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Byte modunda kodlanıp kodlanmayacağını gösteren bir değeri alır veya ayarlar. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | BarCode'un kodlama modunun QR semboloji türü. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR, MicroQR ve RectMicroQR barkodları için Reed-Solomon hata düzeltme seviyesi. |
| [setMicroQrVersion(MicroQRVersion value)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR Kodu sürümü. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR Kodu sürümü. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR Kodu sürümü. |
| [toString()](#toString--) | Bu [QrParameters](../../com.aspose.barcode.generation/qrparameters) öğesinin insan tarafından okunabilir dize temsilini döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D BarCode modülünün Yükseklik/Genişlik oranı.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public int getECIEncoding()
```


Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içindeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya bilgi vermek için kullanılır. Mevcut uygulama, tüm bilinen karakter seti kodlamalarını içerir. MicroQR tarafından desteklenmez.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public boolean getEncodeGS1SeparatorInByteMode()
```


QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Byte modunda kodlanıp kodlanmayacağını gösteren bir değeri alır veya ayarlar.

Yanlış ise, QR spesifikasyonuna göre GS1 ayırıcıları Alfanümerik modda '%' olarak kodlanabilir.

Doğru ise, GS1 grup ayırıcıları Byte modunda 0x1D karakteri olarak kodlanır ve '%' karakterleri de veri olarak korunması için Byte modunda kodlanır.

Bu seçenek, byte seviyesinde GS1 grup ayırıcıları bekleyen çözücülerle uyumluluğu artırabilir ve '%' veri karakterlerinin GS1 ayırıcıları olarak yorumlanmasını önler.

**Returns:**
boolean
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


BarCode'un kodlama modunun QR semboloji türü. Varsayılan değer: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


QR, MicroQR ve RectMicroQR barkodları için Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: LevelL, LevelM, LevelQ, LevelH. bkz. QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQrVersion() {#getMicroQrVersion--}
```
public final MicroQRVersion getMicroQrVersion()
```


MicroQR Kodunun sürümü. M1 sürümünden M4 sürümüne. Varsayılan değer MicroQRVersion.Auto'dur.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


RectMicroQR Kodunun sürümü. R7x59 sürümünden R17x139 sürümüne. Varsayılan değer RectMicroQRVersion.Auto'dur.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


QR Kodunun sürümü. QR kodu için Version1'den Version40'a ve MicroQr için M1'den M4'e. Varsayılan değer QRVersion.Auto'dur.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D BarCode modülünün Yükseklik/Genişlik oranı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içindeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya bilgi vermek için kullanılır. Mevcut uygulama, tüm bilinen karakter seti kodlamalarını içerir. MicroQR tarafından desteklenmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public void setEncodeGS1SeparatorInByteMode(boolean value)
```


QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Byte modunda kodlanıp kodlanmayacağını gösteren bir değeri alır veya ayarlar.

Yanlış ise, QR spesifikasyonuna göre GS1 ayırıcıları Alfanümerik modda '%' olarak kodlanabilir.

Doğru ise, GS1 grup ayırıcıları Byte modunda 0x1D karakteri olarak kodlanır ve '%' karakterleri de veri olarak korunması için Byte modunda kodlanır.

Bu seçenek, byte seviyesinde GS1 grup ayırıcıları bekleyen çözücülerle uyumluluğu artırabilir ve '%' veri karakterlerinin GS1 ayırıcıları olarak yorumlanmasını önler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


BarCode'un kodlama modunun QR semboloji türü. Varsayılan değer: QREncodeMode.Auto.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR, MicroQR ve RectMicroQR barkodları için Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: LevelL, LevelM, LevelQ, LevelH. bkz. QRErrorLevel.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQrVersion(MicroQRVersion value) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQrVersion(MicroQRVersion value)
```


MicroQR Kodunun sürümü. M1 sürümünden M4 sürümüne. Varsayılan değer MicroQRVersion.Auto'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


RectMicroQR Kodunun sürümü. R7x59 sürümünden R17x139 sürümüne. Varsayılan değer RectMicroQRVersion.Auto'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR Kodunun sürümü. QR kodu için Version1'den Version40'a ve MicroQr için M1'den M4'e. Varsayılan değer QRVersion.Auto'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Bu [QrParameters](../../com.aspose.barcode.generation/qrparameters) öğesinin insan tarafından okunabilir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu [QrParameters](../../com.aspose.barcode.generation/qrparameters) öğesini temsil eden bir dize.
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

