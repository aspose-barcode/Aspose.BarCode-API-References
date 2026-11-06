---
title: "HanXinParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Han Xin parametreleri."
type: docs
weight: 49
url: /tr/androidjava/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

Han Xin parametreleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [getEncodeMode()](#getEncodeMode--) | HanXin kodlama modu. |
| [getErrorLevel()](#getErrorLevel--) | Han Xin barkodu için Reed-Solomon hata düzeltme seviyesi. |
| [getVersion()](#getVersion--) | HanXin Kodu sürümü. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | HanXin kodlama modu. |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Han Xin barkodu için Reed-Solomon hata düzeltme seviyesi. |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | HanXin Kodu sürümü. |
| [toString()](#toString--) | Bu [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) öğesinin insan tarafından okunabilir dize temsili döndürür. |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içindeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya bilgi vermek için kullanılır. Mevcut uygulama tüm bilinen karakter seti kodlamalarını içerir.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


HanXin kodlama modu. Varsayılan değer: EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


Han Xin barkodu için Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: L1, L2, L3, L4. ErrorLevel bölümüne bakın.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


HanXin Kodu sürümü. Han Xin kodu için Version01'den Version84'e kadar. Varsayılan değer Version.Auto'dur.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
### hashCode() {#hashCode--}
```
public final int hashCode()
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içindeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya bilgi vermek için kullanılır. Mevcut uygulama tüm bilinen karakter seti kodlamalarını içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


HanXin kodlama modu. Varsayılan değer: EncodeMode.Mixed.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


Han Xin barkodu için Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: L1, L2, L3, L4. ErrorLevel bölümüne bakın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


HanXin Kodu sürümü. Han Xin kodu için Version01'den Version84'e kadar. Varsayılan değer Version.Auto'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


Bu [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) öğesinin insan tarafından okunabilir dize temsili döndürür.

**Returns:**
java.lang.String - Bu [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) öğesini temsil eden bir dize.
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

