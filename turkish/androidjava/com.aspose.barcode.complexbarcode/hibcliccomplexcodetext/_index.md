---
title: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "HIBC LIC koduna gömülü metni kodlamak ve çözmek için temel sınıf."
type: docs
weight: 15
url: /tr/androidjava/com.aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class HIBCLICComplexCodetext implements IComplexCodetext
```

HIBC LIC koduna gömülü metni kodlamak ve çözmek için temel sınıf.

--------------------

> ```
> This sample shows how to decode raw HIBC LIC codetext to HIBCLICComplexCodetext instance.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.HIBC_AZTEC_LIC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
>      System.out.println("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
>      System.out.println("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
>  }
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HIBCLICComplexCodetext()](#HIBCLICComplexCodetext--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Barkod tipini alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Kod metnini oluşturur |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Oluşturulmuş kod metninden örneği başlatır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Barkod tipini alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICComplexCodetext() {#HIBCLICComplexCodetext--}
```
public HIBCLICComplexCodetext()
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
public BaseEncodeType getBarcodeType()
```


Barkod tipini alır veya ayarlar. HIBC LIC kod metni, HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC ve HIBCQRLIC kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39LIC.

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




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Barkod tipini alır veya ayarlar. HIBC LIC kod metni, HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC ve HIBCQRLIC kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39LIC.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

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

