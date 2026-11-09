---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode for Java API Referansı"
description: "USA Sürücü Belgesi PDF417 koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 37
url: /tr/java/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

USA Sürücü Belgesi PDF417 koduna gömülü metni kodlamak ve çözmek için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | Varsayılan yapıcı |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | AAMVA Sürüm Numarası 00-99 |
| [getBarcodeType()](#getBarcodeType--) | USA DL (Pdf417) barkod tipini döndürür |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | USA DL verilerinden kod metni oluştur |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | Bu sayı, veren yargı bölgesini benzersiz şekilde tanımlar ve ISO Issuing Authority(AAMVA) ile iletişime geçilerek elde edilebilir. |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | Yargı Bölgesi Özel Alanları |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | Yargı Bölgesi Sürüm Numarası 00-99 |
| [getMandatoryElements()](#getMandatoryElements--) | Kartın zorunlu öğeleri (alanları) |
| [getNumberOfEntries()](#getNumberOfEntries--) | Alt dosyaların 00-99 numarası |
| [getOptionalElements()](#getOptionalElements--) | Kartın isteğe bağlı öğeleri (alanları) |
| [getSubfileDesignator()](#getSubfileDesignator--) | Aşağıdaki alt dosyalar, tipler, ofsetler ve uzunluklar hakkında bilgi içerir. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Kod metninden USA DL nesnesini başlat |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | XML'e kaydeder |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | AAMVA Sürüm Numarası 00-99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | Bu sayı, veren yargı bölgesini benzersiz şekilde tanımlar ve ISO Issuing Authority(AAMVA) ile iletişime geçilerek elde edilebilir. |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | Yargı Bölgesi Özel Alanları |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | Yargı Bölgesi Sürüm Numarası 00-99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | Kartın zorunlu öğeleri (alanları) |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | Alt dosyaların 00-99 numarası |
| [setOptionalElements(USADriveIdCodetext.OptionalFields value)](#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-) | Kartın isteğe bağlı öğeleri (alanları) |
| [setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)](#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--) | Aşağıdaki alt dosyalar, tipler, ofsetler ve uzunluklar hakkında bilgi içerir. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdCodetext() {#USADriveIdCodetext--}
```
public USADriveIdCodetext()
```


Varsayılan yapıcı

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
### getAAMVAVersionNumber() {#getAAMVAVersionNumber--}
```
public final String getAAMVAVersionNumber()
```


AAMVA Sürüm Numarası 00-99

**Returns:**
java.lang.String
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


USA DL (Pdf417) barkod tipini döndürür

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type (Pdf417)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public final String getConstructedCodetext()
```


USA DL verilerinden kod metni oluştur

**Returns:**
java.lang.String - Oluşturulmuş kod metni
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


Bu sayı, veren yargı bölgesini benzersiz şekilde tanımlar ve ISO Issuing Authority(AAMVA) ile iletişime geçilerek elde edilebilir. Tam 6 haneli IIN kodlanmalıdır.

**Returns:**
java.lang.String
### getJurisdictionSpecificSubfile() {#getJurisdictionSpecificSubfile--}
```
public final USADriveIdJurisdSubfile getJurisdictionSpecificSubfile()
```


Yargı Bölgesi Özel Alanları

**Returns:**
[USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile)
### getJurisdictionVersionNumber() {#getJurisdictionVersionNumber--}
```
public final String getJurisdictionVersionNumber()
```


Yargı Bölgesi Sürüm Numarası 00-99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


Kartın zorunlu öğeleri (alanları)

**Returns:**
[MandatoryFields](../../com.aspose.barcode.complexbarcode/mandatoryfields)
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


Alt dosyaların 00-99 numarası

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


Kartın isteğe bağlı öğeleri (alanları)

**Returns:**
[OptionalFields](../../com.aspose.barcode.complexbarcode/optionalfields)
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


Aşağıdaki alt dosyalar, tipler, ofsetler ve uzunluklar hakkında bilgi içerir. Önemli: sadece tip ayarlandığında, ofset ve uzunluk otomatik olarak ayarlanacaktır.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public final void initFromString(String constructedCodetext)
```


Kod metninden USA DL nesnesini başlat

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Oluşturulmuş kod metni |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveToXml(OutputStream stream) {#saveToXml-java.io.OutputStream-}
```
public final void saveToXml(OutputStream stream)
```


XML'e kaydeder

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Kaydedilecek akış |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


AAMVA Sürüm Numarası 00-99

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


Bu sayı, veren yargı bölgesini benzersiz şekilde tanımlar ve ISO Issuing Authority(AAMVA) ile iletişime geçilerek elde edilebilir. Tam 6 haneli IIN kodlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


Yargı Bölgesi Özel Alanları

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


Yargı Bölgesi Sürüm Numarası 00-99

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


Kartın zorunlu öğeleri (alanları)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MandatoryFields](../../com.aspose.barcode.complexbarcode/mandatoryfields) |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


Alt dosyaların 00-99 numarası

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


Kartın isteğe bağlı öğeleri (alanları)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [OptionalFields](../../com.aspose.barcode.complexbarcode/optionalfields) |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


Aşağıdaki alt dosyalar, tipler, ofsetler ve uzunluklar hakkında bilgi içerir. Önemli: sadece tip ayarlandığında, ofset ve uzunluk otomatik olarak ayarlanacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties> |  |

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

