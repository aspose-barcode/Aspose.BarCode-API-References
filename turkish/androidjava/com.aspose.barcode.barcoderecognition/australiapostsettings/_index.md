---
title: "AustraliaPostSettings"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "AustraliaPost kod çözme parametreleri."
type: docs
weight: 10
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/australiapostsettings/
---
**Inheritance:**
java.lang.Object
```
public class AustraliaPostSettings
```

AustraliaPost kod çözme parametreleri. AustraliaPost sembolojisinin tanınan verileri üzerinde etkisi olan parametreleri içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomerInformationDecoder()](#getCustomerInformationDecoder--) | AustraliaPost sembolojisinde kullanılan Müşteri Bilgi Alanı kod çözümü için genel arayüz. |
| [getCustomerInformationInterpretingType()](#getCustomerInformationInterpretingType--) | AustralianPost BarCode için Müşteri Bilgisi'nin Yorumlama Türünü alır veya ayarlar. DEFAULT, CustomerInformationInterpretingType.OTHER'dır. |
| [getIgnoreEndingFillingPatternsForCTable()](#getIgnoreEndingFillingPatternsForCTable--) | CTable yöntemiyle kod çözerken AustraliaPost çözücüsünün Müşteri Bilgisi Alanındaki son doldurma desenlerini yok saymasını zorlayan bayrak. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)](#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-) | AustraliaPost sembolojisinde kullanılan Müşteri Bilgi Alanı kod çözümü için genel arayüz. |
| [setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)](#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-) | AustralianPost BarCode için Müşteri Bilgisi'nin Yorumlama Türünü alır veya ayarlar. DEFAULT, CustomerInformationInterpretingType.OTHER'dır. |
| [setIgnoreEndingFillingPatternsForCTable(boolean value)](#setIgnoreEndingFillingPatternsForCTable-boolean-) | CTable yöntemiyle kod çözerken AustraliaPost çözücüsünün Müşteri Bilgisi Alanındaki son doldurma desenlerini yok saymasını zorlayan bayrak. |
| [toString()](#toString--) |  |
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
### getCustomerInformationDecoder() {#getCustomerInformationDecoder--}
```
public AustraliaPostCustomerInformationDecoder getCustomerInformationDecoder()
```


AustraliaPost sembolojisinde kullanılan Müşteri Bilgi Alanı kod çözümü için genel arayüz.

**Returns:**
[AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) - Public interface for Customer Information Field decoding which is used in AustraliaPost symbology.
### getCustomerInformationInterpretingType() {#getCustomerInformationInterpretingType--}
```
public CustomerInformationInterpretingType getCustomerInformationInterpretingType()
```


AustralianPost BarCode için Müşteri Bilgisi'nin Yorumlama Türünü alır veya ayarlar. DEFAULT, CustomerInformationInterpretingType.OTHER'dır.

**Returns:**
[CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) - The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode
### getIgnoreEndingFillingPatternsForCTable() {#getIgnoreEndingFillingPatternsForCTable--}
```
public boolean getIgnoreEndingFillingPatternsForCTable()
```


CTable yöntemiyle kod çözerken AustraliaPost çözücüsünün Müşteri Bilgisi Alanındaki son doldurma desenlerini yok saymasını zorlayan bayrak. CTable kodlama yöntemi, kodlama tablosunda hiçbir boşluk içermez ve "333" doldurma deseni dizisi "z" harfi olarak çözülür. Örnek BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); Bitmap image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
boolean - CTable yöntemiyle kod çözerken AustraliaPost çözücüsünün son doldurma desenlerini yok saymasını zorlayan bayrak
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




### setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value) {#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-}
```
public void setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)
```


AustraliaPost sembolojisinde kullanılan Müşteri Bilgi Alanı kod çözümü için genel arayüz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) |  |

### setCustomerInformationInterpretingType(CustomerInformationInterpretingType value) {#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-}
```
public void setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)
```


AustralianPost BarCode için Müşteri Bilgisi'nin Yorumlama Türünü alır veya ayarlar. DEFAULT, CustomerInformationInterpretingType.OTHER'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | AustralianPost BarCode için müşteri bilgilerinin yorumlama türü (CTable, NTable veya Other) |

### setIgnoreEndingFillingPatternsForCTable(boolean value) {#setIgnoreEndingFillingPatternsForCTable-boolean-}
```
public void setIgnoreEndingFillingPatternsForCTable(boolean value)
```


CTable yöntemiyle kod çözerken AustraliaPost çözücüsünün Müşteri Bilgisi Alanındaki son doldurma desenlerini yok saymasını zorlayan bayrak. CTable kodlama yöntemi, kodlama tablosunda hiçbir boşluk içermez ve "333" doldurma deseni dizisi "z" harfi olarak çözülür. Örnek BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); Bitmap image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

