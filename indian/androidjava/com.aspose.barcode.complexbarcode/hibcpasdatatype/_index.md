---
title: HIBCPASDataType
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: HIBC PAS रिकॉर्ड डेटा प्रकार।
type: docs
weight: 20
url: /hi/androidjava/com.aspose.barcode.complexbarcode/hibcpasdatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HIBCPASDataType extends System.Enum
```

HIBC PAS रिकॉर्ड के डेटा प्रकार।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ADMINISTRABLE_PRODUCT_IDENTIFICATION](#ADMINISTRABLE-PRODUCT-IDENTIFICATION) | F - प्रबंधनीय उत्पाद पहचान |
| [ASSET_IDENTIFICATION](#ASSET-IDENTIFICATION) | N - संपत्ति पहचान |
| [BLOOD_PRODUCT_IDENTIFICATION](#BLOOD-PRODUCT-IDENTIFICATION) | K - रक्त उत्पाद पहचान |
| [BUSINESS_CONTROL_NUMBER](#BUSINESS-CONTROL-NUMBER) | S - व्यापार नियंत्रण संख्या |
| [DATE_TIME](#DATE-TIME) | M - YYYDDDHHMMG स्वरूप में तिथि-समय |
| [DEMOGRAPHIC_DATA](#DEMOGRAPHIC-DATA) | L - जनसांख्यिकीय डेटा |
| [DIETARY_ITEM_IDENTIFICATION](#DIETARY-ITEM-IDENTIFICATION) | P - आहार वस्तु पहचान |
| [EPISODE_OF_CARE_IDENTIFICATION](#EPISODE-OF-CARE-IDENTIFICATION) | T - देखभाल एपिसोड पहचान |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [HEALTH_INDUSTRY_NUMBER](#HEALTH-INDUSTRY-NUMBER) | U - स्वास्थ्य उद्योग संख्या |
| [HOSPITAL_ITEM_IDENTIFICATION](#HOSPITAL-ITEM-IDENTIFICATION) | H - अस्पताल आइटम पहचान |
| [IMPLANTABLE_PRODUCT_INFORMATION](#IMPLANTABLE-PRODUCT-INFORMATION) | G - इम्प्लांटेबल उत्पाद जानकारी |
| [LABELER_IDENTIFICATION_CODE](#LABELER-IDENTIFICATION-CODE) | A - लेबलर पहचान कोड |
| [LIBRARY_MATERIALS_IDENTIFICATION](#LIBRARY-MATERIALS-IDENTIFICATION) | R - पुस्तकालय सामग्री पहचान |
| [MANUFACTURER_SERIAL_NUMBER](#MANUFACTURER-SERIAL-NUMBER) | Q - निर्माता सीरियल नंबर |
| [MEDICAL_PROCEDURE_IDENTIFICATION](#MEDICAL-PROCEDURE-IDENTIFICATION) | I - चिकित्सा प्रक्रिया पहचान |
| [PATIENT_IDENTIFICATION](#PATIENT-IDENTIFICATION) | C - रोगी पहचान |
| [PATIENT_VISIT_ID](#PATIENT-VISIT-ID) | V - रोगी विज़िट आईडी |
| [PERSONNEL_IDENTIFICATION](#PERSONNEL-IDENTIFICATION) | E - कर्मचारी पहचान |
| [PURCHASE_ORDER_NUMBER](#PURCHASE-ORDER-NUMBER) | O - खरीद आदेश संख्या |
| [REIMBURSEMENT_CATEGORY](#REIMBURSEMENT-CATEGORY) | J - प्रतिपूर्ति श्रेणी |
| [SERVICE_IDENTIFICATION](#SERVICE-IDENTIFICATION) | B - सेवा पहचान |
| [SPECIMEN_IDENTIFICATION](#SPECIMEN-IDENTIFICATION) | D - नमूना पहचान |
| [USER_DEFINED](#USER-DEFINED) | Z - उपयोगकर्ता द्वारा परिभाषित |
| [XML_DOCUMENT](#XML-DOCUMENT) | X - XML दस्तावेज़ |
## Methods

| Method | विवरण |
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


F - प्रबंधनीय उत्पाद पहचान

### ASSET_IDENTIFICATION {#ASSET-IDENTIFICATION}
```
public static final int ASSET_IDENTIFICATION
```


N - संपत्ति पहचान

### BLOOD_PRODUCT_IDENTIFICATION {#BLOOD-PRODUCT-IDENTIFICATION}
```
public static final int BLOOD_PRODUCT_IDENTIFICATION
```


K - रक्त उत्पाद पहचान

### BUSINESS_CONTROL_NUMBER {#BUSINESS-CONTROL-NUMBER}
```
public static final int BUSINESS_CONTROL_NUMBER
```


S - व्यापार नियंत्रण संख्या

### DATE_TIME {#DATE-TIME}
```
public static final int DATE_TIME
```


M - YYYDDDHHMMG स्वरूप में तिथि-समय

### DEMOGRAPHIC_DATA {#DEMOGRAPHIC-DATA}
```
public static final int DEMOGRAPHIC_DATA
```


L - जनसांख्यिकीय डेटा

### DIETARY_ITEM_IDENTIFICATION {#DIETARY-ITEM-IDENTIFICATION}
```
public static final int DIETARY_ITEM_IDENTIFICATION
```


P - आहार वस्तु पहचान

### EPISODE_OF_CARE_IDENTIFICATION {#EPISODE-OF-CARE-IDENTIFICATION}
```
public static final int EPISODE_OF_CARE_IDENTIFICATION
```


T - देखभाल एपिसोड पहचान

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### HEALTH_INDUSTRY_NUMBER {#HEALTH-INDUSTRY-NUMBER}
```
public static final int HEALTH_INDUSTRY_NUMBER
```


U - स्वास्थ्य उद्योग संख्या

### HOSPITAL_ITEM_IDENTIFICATION {#HOSPITAL-ITEM-IDENTIFICATION}
```
public static final int HOSPITAL_ITEM_IDENTIFICATION
```


H - अस्पताल आइटम पहचान

### IMPLANTABLE_PRODUCT_INFORMATION {#IMPLANTABLE-PRODUCT-INFORMATION}
```
public static final int IMPLANTABLE_PRODUCT_INFORMATION
```


G - इम्प्लांटेबल उत्पाद जानकारी

### LABELER_IDENTIFICATION_CODE {#LABELER-IDENTIFICATION-CODE}
```
public static final int LABELER_IDENTIFICATION_CODE
```


A - लेबलर पहचान कोड

### LIBRARY_MATERIALS_IDENTIFICATION {#LIBRARY-MATERIALS-IDENTIFICATION}
```
public static final int LIBRARY_MATERIALS_IDENTIFICATION
```


R - पुस्तकालय सामग्री पहचान

### MANUFACTURER_SERIAL_NUMBER {#MANUFACTURER-SERIAL-NUMBER}
```
public static final int MANUFACTURER_SERIAL_NUMBER
```


Q - निर्माता सीरियल नंबर

### MEDICAL_PROCEDURE_IDENTIFICATION {#MEDICAL-PROCEDURE-IDENTIFICATION}
```
public static final int MEDICAL_PROCEDURE_IDENTIFICATION
```


I - चिकित्सा प्रक्रिया पहचान

### PATIENT_IDENTIFICATION {#PATIENT-IDENTIFICATION}
```
public static final int PATIENT_IDENTIFICATION
```


C - रोगी पहचान

### PATIENT_VISIT_ID {#PATIENT-VISIT-ID}
```
public static final int PATIENT_VISIT_ID
```


V - रोगी विज़िट आईडी

### PERSONNEL_IDENTIFICATION {#PERSONNEL-IDENTIFICATION}
```
public static final int PERSONNEL_IDENTIFICATION
```


E - कर्मचारी पहचान

### PURCHASE_ORDER_NUMBER {#PURCHASE-ORDER-NUMBER}
```
public static final int PURCHASE_ORDER_NUMBER
```


O - खरीद आदेश संख्या

### REIMBURSEMENT_CATEGORY {#REIMBURSEMENT-CATEGORY}
```
public static final int REIMBURSEMENT_CATEGORY
```


J - प्रतिपूर्ति श्रेणी

### SERVICE_IDENTIFICATION {#SERVICE-IDENTIFICATION}
```
public static final int SERVICE_IDENTIFICATION
```


B - सेवा पहचान

### SPECIMEN_IDENTIFICATION {#SPECIMEN-IDENTIFICATION}
```
public static final int SPECIMEN_IDENTIFICATION
```


D - नमूना पहचान

### USER_DEFINED {#USER-DEFINED}
```
public static final int USER_DEFINED
```


Z - उपयोगकर्ता द्वारा परिभाषित

### XML_DOCUMENT {#XML-DOCUMENT}
```
public static final int XML_DOCUMENT
```


X - XML दस्तावेज़

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| वह | T |  |

### CloneTo(System.Enum that) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum that)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| वह | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type enumType, Object value, String format) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type enumType, Object value, String format)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.Object |  |
| फ़ॉर्मेट | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> enumType, long value, String format) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> enumType, long value, String format)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | लॉन्ग |  |
| फ़ॉर्मेट | java.lang.String |  |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> enumType, long value) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | लॉन्ग |  |

**Returns:**
java.lang.String
### getNames(System.Type enumType) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type enumType)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> enumType) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type enumType) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type enumType)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> enumType) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> enumType)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> enumType, String name) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> enumType, String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| नाम | java.lang.String |  |

**Returns:**
लॉन्ग
### getValues(System.Type enumType) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type enumType)
```




**Parameters:**
| Parameter | Type | विवरण |
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
लॉन्ग
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type enumType, String value) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type enumType, String value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type enumType, long value) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type enumType, long value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | लॉन्ग |  |

**Returns:**
boolean
### isDefined(Class<?> enumType, long value) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> enumType, long value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | लॉन्ग |  |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.String |  |

**Returns:**
लॉन्ग
### parse(System.Type enumType, String value, Boolean ignoreCase) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
लॉन्ग
### parse(Class<?> enumType, String value) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> enumType, String value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | java.lang.String |  |

**Returns:**
लॉन्ग
### parse(Class<?> enumType, String value, Boolean ignoreCase) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> enumType, String value, Boolean ignoreCase)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | java.lang.String |  |
| ignoreCase | java.lang.Boolean |  |

**Returns:**
लॉन्ग
### register(System.Enum.AbstractEnum e) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum e)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| e | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type enumType, Object value) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type enumType, Object value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | com.aspose.ms.System.Type |  |
| मान | java.lang.Object |  |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| enumType | java.lang.Class<?> |  |
| मान | लॉन्ग |  |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

