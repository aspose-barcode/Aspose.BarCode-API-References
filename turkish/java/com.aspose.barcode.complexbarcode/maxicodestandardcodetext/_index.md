---
title: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Mod 4, 5 ve 6 için MaxiCode kod metnini kodlamak ve çözmek için sınıf."
type: docs
weight: 29
url: /tr/java/com.aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public class MaxiCodeStandardCodetext extends MaxiCodeCodetext
```

Mod 4, 5 ve 6 için MaxiCode kod metnini kodlamak ve kodunu çözmek için sınıf.

```
//Mode 4
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 5
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_5);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 6
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_6);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MaxiCodeStandardCodetext()](#MaxiCodeStandardCodetext--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen bir MaxiCodeStandardCodetext değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [getBarcodeType()](#getBarcodeType--) | Barkod tipini alır. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Kod metnini oluşturur. |
| [getECIEncoding()](#getECIEncoding--) | ECI kodlamasını alır. |
| [getEncodeMode()](#getEncodeMode--) | Bir MaxiCode kodlama modunu alır. |
| [getMessage()](#getMessage--) | Mesajı alır. |
| [getMode()](#getMode--) | MaxiCode modunu alır. |
| [hashCode()](#hashCode--) | Bu örnek için karma kodu döndürür. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Oluşturulan kod metninden örneği başlatır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI kodlamasını ayarlar. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Bir MaxiCode kodlama modunu ayarlar. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Mesajı ayarlar. |
| [setMode(MaxiCodeMode mode)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | MaxiCode modunu ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStandardCodetext() {#MaxiCodeStandardCodetext--}
```
public MaxiCodeStandardCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen bir MaxiCodeStandardCodetext değerine eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırmak için bir MaxiCodeStandardCodetext değeri. |

**Returns:**
boolean - eğer obj bu örnekle aynı değere sahipse; aksi takdirde, **false**.
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
public String getConstructedCodetext()
```


Kod metnini oluşturur.

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


Bir MaxiCode kodlama modunu alır. Varsayılan değer: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMessage() {#getMessage--}
```
public String getMessage()
```


Mesajı alır.

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public MaxiCodeMode getMode()
```


MaxiCode modunu alır.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için karma kodu döndürür.

**Returns:**
int - 32 bit işaretli tamsayı karma kodu
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Oluşturulan kod metninden örneği başlatır.

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


ECI kodlamasını ayarlar. MaxiCodeEncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | ECI kodlaması. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Bir MaxiCode kodlama modunu ayarlar. Varsayılan değer: Auto.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | bir MaxiCode kodlama modu. |

### setMessage(String value) {#setMessage-java.lang.String-}
```
public void setMessage(String value)
```


Mesajı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setMode(MaxiCodeMode mode) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public void setMode(MaxiCodeMode mode)
```


MaxiCode modunu ayarlar. Standart kod metni yalnızca mod 4, 5 ve 6 ile kullanılabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) |  |

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

