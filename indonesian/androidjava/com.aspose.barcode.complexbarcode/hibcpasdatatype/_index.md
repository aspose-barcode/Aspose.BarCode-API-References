---
title: HIBCPASDataType
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Tipe data catatan HIBC PAS.
type: docs
weight: 20
url: /id/androidjava/com.aspose.barcode.complexbarcode/hibcpasdatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HIBCPASDataType extends System.Enum
```

Jenis data rekaman HIBC PAS.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ADMINISTRABLE_PRODUCT_IDENTIFICATION](#ADMINISTRABLE-PRODUCT-IDENTIFICATION) | F - Identifikasi Produk yang Dapat Dikelola |
| [ASSET_IDENTIFICATION](#ASSET-IDENTIFICATION) | N - Identifikasi Aset |
| [BLOOD_PRODUCT_IDENTIFICATION](#BLOOD-PRODUCT-IDENTIFICATION) | K - Identifikasi Produk Darah |
| [BUSINESS_CONTROL_NUMBER](#BUSINESS-CONTROL-NUMBER) | S - Nomor Kontrol Bisnis |
| [DATE_TIME](#DATE-TIME) | M - DateTime dalam format YYYDDDHHMMG |
| [DEMOGRAPHIC_DATA](#DEMOGRAPHIC-DATA) | L - Data Demografis |
| [DIETARY_ITEM_IDENTIFICATION](#DIETARY-ITEM-IDENTIFICATION) | P - Identifikasi Item Diet |
| [EPISODE_OF_CARE_IDENTIFICATION](#EPISODE-OF-CARE-IDENTIFICATION) | T - Identifikasi Episode Perawatan |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [HEALTH_INDUSTRY_NUMBER](#HEALTH-INDUSTRY-NUMBER) | U - Nomor Industri Kesehatan |
| [HOSPITAL_ITEM_IDENTIFICATION](#HOSPITAL-ITEM-IDENTIFICATION) | H - Identifikasi Item Rumah Sakit |
| [IMPLANTABLE_PRODUCT_INFORMATION](#IMPLANTABLE-PRODUCT-INFORMATION) | G - Informasi Produk Implan |
| [LABELER_IDENTIFICATION_CODE](#LABELER-IDENTIFICATION-CODE) | A - Kode Identifikasi Pemberi Label |
| [LIBRARY_MATERIALS_IDENTIFICATION](#LIBRARY-MATERIALS-IDENTIFICATION) | R - Identifikasi Bahan Perpustakaan |
| [MANUFACTURER_SERIAL_NUMBER](#MANUFACTURER-SERIAL-NUMBER) | Q - Nomor Seri Produsen |
| [MEDICAL_PROCEDURE_IDENTIFICATION](#MEDICAL-PROCEDURE-IDENTIFICATION) | I - Identifikasi Prosedur Medis |
| [PATIENT_IDENTIFICATION](#PATIENT-IDENTIFICATION) | C - Identifikasi Pasien |
| [PATIENT_VISIT_ID](#PATIENT-VISIT-ID) | V - ID Kunjungan Pasien |
| [PERSONNEL_IDENTIFICATION](#PERSONNEL-IDENTIFICATION) | E - Identifikasi Personil |
| [PURCHASE_ORDER_NUMBER](#PURCHASE-ORDER-NUMBER) | O - Nomor Pesanan Pembelian |
| [REIMBURSEMENT_CATEGORY](#REIMBURSEMENT-CATEGORY) | J - Kategori Penggantian |
| [SERVICE_IDENTIFICATION](#SERVICE-IDENTIFICATION) | B - Identifikasi Layanan |
| [SPECIMEN_IDENTIFICATION](#SPECIMEN-IDENTIFICATION) | D - Identifikasi Spesimen |
| [USER_DEFINED](#USER-DEFINED) | Z - Ditetapkan Pengguna |
| [XML_DOCUMENT](#XML-DOCUMENT) | X - Dokumen XML |
## Methods

| Method | Deskripsi |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T that)](#CloneTo-T-) |  |
| [CloneTo(System.Enum that)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type enumType, Object value, String format)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> enumType, long value, String format)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type enumType, Object value)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> enumType, long value)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type enumType)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> enumType)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type enumType)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> enumType)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> enumType, String name)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type enumType)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type enumType, Object value)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type enumType, String value)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type enumType, long value)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> enumType, long value)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type enumType, String value)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type enumType, String value, Boolean ignoreCase)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> enumType, String value)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> enumType, String value, Boolean ignoreCase)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum e)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type enumType, Object value)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> enumType, long value)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ADMINISTRABLE_PRODUCT_IDENTIFICATION {#ADMINISTRABLE-PRODUCT-IDENTIFICATION}
```
public static final int ADMINISTRABLE_PRODUCT_IDENTIFICATION
```


F - Identifikasi Produk yang Dapat Dikelola

### ASSET_IDENTIFICATION {#ASSET-IDENTIFICATION}
```
public static final int ASSET_IDENTIFICATION
```


N - Identifikasi Aset

### BLOOD_PRODUCT_IDENTIFICATION {#BLOOD-PRODUCT-IDENTIFICATION}
```
public static final int BLOOD_PRODUCT_IDENTIFICATION
```


K - Identifikasi Produk Darah

### BUSINESS_CONTROL_NUMBER {#BUSINESS-CONTROL-NUMBER}
```
public static final int BUSINESS_CONTROL_NUMBER
```


S - Nomor Kontrol Bisnis

### DATE_TIME {#DATE-TIME}
```
public static final int DATE_TIME
```


M - DateTime dalam format YYYDDDHHMMG

### DEMOGRAPHIC_DATA {#DEMOGRAPHIC-DATA}
```
public static final int DEMOGRAPHIC_DATA
```


L - Data Demografis

### DIETARY_ITEM_IDENTIFICATION {#DIETARY-ITEM-IDENTIFICATION}
```
public static final int DIETARY_ITEM_IDENTIFICATION
```


P - Identifikasi Item Diet

### EPISODE_OF_CARE_IDENTIFICATION {#EPISODE-OF-CARE-IDENTIFICATION}
```
public static final int EPISODE_OF_CARE_IDENTIFICATION
```


T - Identifikasi Episode Perawatan

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### HEALTH_INDUSTRY_NUMBER {#HEALTH-INDUSTRY-NUMBER}
```
public static final int HEALTH_INDUSTRY_NUMBER
```


U - Nomor Industri Kesehatan

### HOSPITAL_ITEM_IDENTIFICATION {#HOSPITAL-ITEM-IDENTIFICATION}
```
public static final int HOSPITAL_ITEM_IDENTIFICATION
```


H - Identifikasi Item Rumah Sakit

### IMPLANTABLE_PRODUCT_INFORMATION {#IMPLANTABLE-PRODUCT-INFORMATION}
```
public static final int IMPLANTABLE_PRODUCT_INFORMATION
```


G - Informasi Produk Implan

### LABELER_IDENTIFICATION_CODE {#LABELER-IDENTIFICATION-CODE}
```
public static final int LABELER_IDENTIFICATION_CODE
```


A - Kode Identifikasi Pemberi Label

### LIBRARY_MATERIALS_IDENTIFICATION {#LIBRARY-MATERIALS-IDENTIFICATION}
```
public static final int LIBRARY_MATERIALS_IDENTIFICATION
```


R - Identifikasi Bahan Perpustakaan

### MANUFACTURER_SERIAL_NUMBER {#MANUFACTURER-SERIAL-NUMBER}
```
public static final int MANUFACTURER_SERIAL_NUMBER
```


Q - Nomor Seri Produsen

### MEDICAL_PROCEDURE_IDENTIFICATION {#MEDICAL-PROCEDURE-IDENTIFICATION}
```
public static final int MEDICAL_PROCEDURE_IDENTIFICATION
```


I - Identifikasi Prosedur Medis

### PATIENT_IDENTIFICATION {#PATIENT-IDENTIFICATION}
```
public static final int PATIENT_IDENTIFICATION
```


C - Identifikasi Pasien

### PATIENT_VISIT_ID {#PATIENT-VISIT-ID}
```
public static final int PATIENT_VISIT_ID
```


V - ID Kunjungan Pasien

### PERSONNEL_IDENTIFICATION {#PERSONNEL-IDENTIFICATION}
```
public static final int PERSONNEL_IDENTIFICATION
```


E - Identifikasi Personil

### PURCHASE_ORDER_NUMBER {#PURCHASE-ORDER-NUMBER}
```
public static final int PURCHASE_ORDER_NUMBER
```


O - Nomor Pesanan Pembelian

### REIMBURSEMENT_CATEGORY {#REIMBURSEMENT-CATEGORY}
```
public static final int REIMBURSEMENT_CATEGORY
```


J - Kategori Penggantian

### SERVICE_IDENTIFICATION {#SERVICE-IDENTIFICATION}
```
public static final int SERVICE_IDENTIFICATION
```


B - Identifikasi Layanan

### SPECIMEN_IDENTIFICATION {#SPECIMEN-IDENTIFICATION}
```
public static final int SPECIMEN_IDENTIFICATION
```


D - Identifikasi Spesimen

### USER_DEFINED {#USER-DEFINED}
```
public static final int USER_DEFINED
```


Z - Ditetapkan Pengguna

### XML_DOCUMENT {#XML-DOCUMENT}
```
public static final int XML_DOCUMENT
```


X - Dokumen XML

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T that) {#CloneTo-T-}
```
public abstract void CloneTo(T that)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| itu | T |  |

### CloneTo(System.Enum that) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum that)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| itu | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type enumType, Object value, String format) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type enumType, Object value, String format)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| nilai | java.lang.Object |  |
| format | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> enumType, long value, String format) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> enumType, long value, String format)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| nilai | long |  |
| format | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type enumType, Object value) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type enumType, Object value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| nilai | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> enumType, long value) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| nilai | long |  |

**Returns:**
java.lang.String
### getNames(System.Type enumType) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type enumType)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> enumType) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type enumType) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type enumType)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> enumType) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> enumType, String name) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> enumType, String name)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| name | java.lang.String |  |

**Returns:**
long
### getValues(System.Type enumType) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type enumType)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type enumType, Object value) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type enumType, Object value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type enumType, String value) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type enumType, String value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| nilai | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type enumType, long value) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type enumType, long value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| nilai | long |  |

**Returns:**
boolean
### isDefined(Class<?> enumType, long value) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| nilai | long |  |

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




### parse(System.Type enumType, String value) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type enumType, String value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| nilai | java.lang.String |  |

**Returns:**
long
### parse(System.Type enumType, String value, Boolean ignoreCase) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| nilai | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> enumType, String value) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> enumType, String value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| nilai | java.lang.String |  |

**Returns:**
long
### parse(Class<?> enumType, String value, Boolean ignoreCase) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| nilai | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum e) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum e)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| e | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type enumType, Object value) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type enumType, Object value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| nilai | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> enumType, long value) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| nilai | long |  |

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

