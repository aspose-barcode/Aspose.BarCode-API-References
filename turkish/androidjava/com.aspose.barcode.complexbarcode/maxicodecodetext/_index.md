---
title: "MaxiCodeCodetext"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "MaxiCode koduna gömülü metni kodlamak ve çözmek için temel sınıf."
type: docs
weight: 25
url: /tr/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class MaxiCodeCodetext implements IComplexCodetext
```

MaxiCode koduna gömülü metni kodlamak ve çözmek için temel sınıf.

Bu örnek, ham MaxiCode kod metninin MaxiCodeCodetext örneğine nasıl çözüleceğini gösterir.

```

 BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
 for (BarCodeResult result : reader.readBarCodes())
 {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMode(), result.getCodeText());
      System.out.println("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
      System.out.println("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
      System.out.println("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
 }
 
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MaxiCodeCodetext()](#MaxiCodeCodetext--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Barkod tipini alır. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Kod metnini oluşturur |
| [getECIEncoding()](#getECIEncoding--) | ECI kodlamasını alır. |
| [getEncodeMode()](#getEncodeMode--) | Bir MaxiCode kodlama modunu alır. |
| [getMode()](#getMode--) | MaxiCode modunu alır. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Oluşturulmuş kod metninden örneği başlatır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI kodlamasını ayarlar. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Bir MaxiCode kodlama modunu ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeCodetext() {#MaxiCodeCodetext--}
```
public MaxiCodeCodetext()
```


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
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Barkod tipini alır.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public abstract String getConstructedCodetext()
```


Kod metnini oluşturur

**Returns:**
java.lang.String - Oluşturulmuş kod metni
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI kodlamasını alır. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Returns:**
int - ECI kodlaması.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Bir MaxiCode kodlama modunu alır. Varsayılan değer: Otomatik.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public abstract MaxiCodeMode getMode()
```


MaxiCode modunu alır.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public abstract void initFromString(String constructedCodetext)
```


Oluşturulmuş kod metninden örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Oluşturulmuş kod metni. |

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


ECI kodlamasını ayarlar. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | ECI kodlaması. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Bir MaxiCode kodlama modunu ayarlar. Varsayılan değer: Otomatik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | bir MaxiCode kodlama modu. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

