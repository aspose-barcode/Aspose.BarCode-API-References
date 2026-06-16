---
title: MaxiCodeStructuredCodetext
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Kelas dasar untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode untuk mode 2 dan 3.
type: docs
weight: 32
url: /id/androidjava/com.aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public abstract class MaxiCodeStructuredCodetext extends MaxiCodeCodetext
```

Kelas dasar untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode untuk mode 2 dan 3. Contoh ini menunjukkan cara mendekode codetext MaxiCode mentah menjadi instance MaxiCodeStructuredCodetext.

```
BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  for (BarCodeResult result : reader.readBarCodes())
  {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
      if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
      {
          MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
          System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
          System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
          System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
      }
  }
```
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [MaxiCodeStructuredCodetext()](#MaxiCodeStructuredCodetext--) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai MaxiCodeStructuredCodetext yang ditentukan. |
| [getBarcodeType()](#getBarcodeType--) | Mendapatkan tipe barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Menyusun codetext |
| [getCountryCode()](#getCountryCode--) | Mengidentifikasi kode negara 3 digit. |
| [getECIEncoding()](#getECIEncoding--) | Mendapatkan enkoding ECI. |
| [getEncodeMode()](#getEncodeMode--) | Mendapatkan mode enkode MaxiCode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Mendapatkan mode enkode MaxiCode. |
| [getMode()](#getMode--) | Mendapatkan mode MaxiCode. |
| [getPostalCode()](#getPostalCode--) | Mengidentifikasi kode pos. |
| [getSecondMessage()](#getSecondMessage--) | Mengidentifikasi pesan kedua dari barcode. |
| [getServiceCategory()](#getServiceCategory--) | Mengidentifikasi kategori layanan 3 digit. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Menginisialisasi instance dari codetext yang disusun. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | Mengidentifikasi kode negara 3 digit. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Mengatur enkoding ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Mengatur mode enkode MaxiCode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Mengatur mode enkode MaxiCode. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Mengidentifikasi kode pos. |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | Mengidentifikasi pesan kedua dari barcode. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | Mengidentifikasi kategori layanan 3 digit. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStructuredCodetext() {#MaxiCodeStructuredCodetext--}
```
public MaxiCodeStructuredCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai MaxiCodeStructuredCodetext yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai MaxiCodeStructuredCodetext untuk dibandingkan dengan instance ini |

**Returns:**
boolean - **true** jika obj memiliki nilai yang sama dengan instance ini; jika tidak, **false**
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Mendapatkan tipe barcode.

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


Menyusun codetext

**Returns:**
java.lang.String - Codetext yang dibangun
### getCountryCode() {#getCountryCode--}
```
public int getCountryCode()
```


Mengidentifikasi kode negara 3 digit.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Mendapatkan enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1

**Returns:**
int - enkoding ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Mendapatkan mode enkode MaxiCode. Nilai default: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Mendapatkan mode enkode MaxiCode. Nilai default: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public abstract int getMode()
```


Mendapatkan mode MaxiCode.

**Returns:**
int - mode MaxiCode
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Mengidentifikasi kode pos. Harus 9 digit pada mode 2 atau 6 simbol alfanumerik pada mode 3.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public MaxiCodeSecondMessage getSecondMessage()
```


Mengidentifikasi pesan kedua dari barcode.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public int getServiceCategory()
```


Mengidentifikasi kategori layanan 3 digit.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Menginisialisasi instance dari codetext yang disusun.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Codetext yang dibangun. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCountryCode(int value) {#setCountryCode-int-}
```
public void setCountryCode(int value)
```


Mengidentifikasi kode negara 3 digit.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Mengatur enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | Enkoding ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Mengatur mode enkode MaxiCode. Nilai default: Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | sebuah mode enkode MaxiCode. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Mengatur mode enkode MaxiCode. Nilai default: Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | sebuah mode enkode MaxiCode. |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Mengidentifikasi kode pos. Harus 9 digit pada mode 2 atau 6 simbol alfanumerik pada mode 3.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public void setSecondMessage(MaxiCodeSecondMessage value)
```


Mengidentifikasi pesan kedua dari barcode.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public void setServiceCategory(int value)
```


Mengidentifikasi kategori layanan 3 digit.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

