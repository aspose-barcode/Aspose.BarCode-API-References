---
title: "HIBCPASDataType"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Tipi di dati dei record HIBC PAS."
type: docs
weight: 20
url: /it/java/com.aspose.barcode.complexbarcode/hibcpasdatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HIBCPASDataType extends System.Enum
```

Tipi di dati del record HIBC PAS.
## Campi

| Campo | Descrizione |
| --- | --- |
| [ADMINISTRABLE_PRODUCT_IDENTIFICATION](#ADMINISTRABLE-PRODUCT-IDENTIFICATION) | F - Identificazione del prodotto amministrabile |
| [ASSET_IDENTIFICATION](#ASSET-IDENTIFICATION) | N - Identificazione dell'asset |
| [BLOOD_PRODUCT_IDENTIFICATION](#BLOOD-PRODUCT-IDENTIFICATION) | K - Identificazione del prodotto sanguigno |
| [BUSINESS_CONTROL_NUMBER](#BUSINESS-CONTROL-NUMBER) | S - Numero di controllo aziendale |
| [DATE_TIME](#DATE-TIME) | M - Data e ora in formato YYYDDDHHMMG |
| [DEMOGRAPHIC_DATA](#DEMOGRAPHIC-DATA) | L - Dati demografici |
| [DIETARY_ITEM_IDENTIFICATION](#DIETARY-ITEM-IDENTIFICATION) | P - Identificazione dell'elemento dietetico |
| [EPISODE_OF_CARE_IDENTIFICATION](#EPISODE-OF-CARE-IDENTIFICATION) | T - Identificazione dell'episodio di cura |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [HEALTH_INDUSTRY_NUMBER](#HEALTH-INDUSTRY-NUMBER) | U - Numero dell'industria sanitaria |
| [HOSPITAL_ITEM_IDENTIFICATION](#HOSPITAL-ITEM-IDENTIFICATION) | H - Identificazione dell'elemento ospedaliero |
| [IMPLANTABLE_PRODUCT_INFORMATION](#IMPLANTABLE-PRODUCT-INFORMATION) | G - Informazioni sul prodotto impiantabile |
| [LABELER_IDENTIFICATION_CODE](#LABELER-IDENTIFICATION-CODE) | A - Codice di identificazione dell'etichettatore |
| [LIBRARY_MATERIALS_IDENTIFICATION](#LIBRARY-MATERIALS-IDENTIFICATION) | R - Identificazione dei materiali di biblioteca |
| [MANUFACTURER_SERIAL_NUMBER](#MANUFACTURER-SERIAL-NUMBER) | Q - Numero di serie del produttore |
| [MEDICAL_PROCEDURE_IDENTIFICATION](#MEDICAL-PROCEDURE-IDENTIFICATION) | I - Identificazione della procedura medica |
| [PATIENT_IDENTIFICATION](#PATIENT-IDENTIFICATION) | C - Identificazione del paziente |
| [PATIENT_VISIT_ID](#PATIENT-VISIT-ID) | V - ID visita del paziente |
| [PERSONNEL_IDENTIFICATION](#PERSONNEL-IDENTIFICATION) | E - Identificazione del personale |
| [PURCHASE_ORDER_NUMBER](#PURCHASE-ORDER-NUMBER) | O - Numero dell'ordine di acquisto |
| [REIMBURSEMENT_CATEGORY](#REIMBURSEMENT-CATEGORY) | J - Categoria di rimborso |
| [SERVICE_IDENTIFICATION](#SERVICE-IDENTIFICATION) | B - Identificazione del servizio |
| [SPECIMEN_IDENTIFICATION](#SPECIMEN-IDENTIFICATION) | D - Identificazione del campione |
| [USER_DEFINED](#USER-DEFINED) | Z - Definito dall'Utente |
| [XML_DOCUMENT](#XML-DOCUMENT) | X - Documento XML |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ADMINISTRABLE_PRODUCT_IDENTIFICATION {#ADMINISTRABLE-PRODUCT-IDENTIFICATION}
```
public static final int ADMINISTRABLE_PRODUCT_IDENTIFICATION
```


F - Identificazione del prodotto amministrabile

### ASSET_IDENTIFICATION {#ASSET-IDENTIFICATION}
```
public static final int ASSET_IDENTIFICATION
```


N - Identificazione dell'asset

### BLOOD_PRODUCT_IDENTIFICATION {#BLOOD-PRODUCT-IDENTIFICATION}
```
public static final int BLOOD_PRODUCT_IDENTIFICATION
```


K - Identificazione del prodotto sanguigno

### BUSINESS_CONTROL_NUMBER {#BUSINESS-CONTROL-NUMBER}
```
public static final int BUSINESS_CONTROL_NUMBER
```


S - Numero di controllo aziendale

### DATE_TIME {#DATE-TIME}
```
public static final int DATE_TIME
```


M - Data e ora in formato YYYDDDHHMMG

### DEMOGRAPHIC_DATA {#DEMOGRAPHIC-DATA}
```
public static final int DEMOGRAPHIC_DATA
```


L - Dati demografici

### DIETARY_ITEM_IDENTIFICATION {#DIETARY-ITEM-IDENTIFICATION}
```
public static final int DIETARY_ITEM_IDENTIFICATION
```


P - Identificazione dell'elemento dietetico

### EPISODE_OF_CARE_IDENTIFICATION {#EPISODE-OF-CARE-IDENTIFICATION}
```
public static final int EPISODE_OF_CARE_IDENTIFICATION
```


T - Identificazione dell'episodio di cura

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### HEALTH_INDUSTRY_NUMBER {#HEALTH-INDUSTRY-NUMBER}
```
public static final int HEALTH_INDUSTRY_NUMBER
```


U - Numero dell'industria sanitaria

### HOSPITAL_ITEM_IDENTIFICATION {#HOSPITAL-ITEM-IDENTIFICATION}
```
public static final int HOSPITAL_ITEM_IDENTIFICATION
```


H - Identificazione dell'elemento ospedaliero

### IMPLANTABLE_PRODUCT_INFORMATION {#IMPLANTABLE-PRODUCT-INFORMATION}
```
public static final int IMPLANTABLE_PRODUCT_INFORMATION
```


G - Informazioni sul prodotto impiantabile

### LABELER_IDENTIFICATION_CODE {#LABELER-IDENTIFICATION-CODE}
```
public static final int LABELER_IDENTIFICATION_CODE
```


A - Codice di identificazione dell'etichettatore

### LIBRARY_MATERIALS_IDENTIFICATION {#LIBRARY-MATERIALS-IDENTIFICATION}
```
public static final int LIBRARY_MATERIALS_IDENTIFICATION
```


R - Identificazione dei materiali di biblioteca

### MANUFACTURER_SERIAL_NUMBER {#MANUFACTURER-SERIAL-NUMBER}
```
public static final int MANUFACTURER_SERIAL_NUMBER
```


Q - Numero di serie del produttore

### MEDICAL_PROCEDURE_IDENTIFICATION {#MEDICAL-PROCEDURE-IDENTIFICATION}
```
public static final int MEDICAL_PROCEDURE_IDENTIFICATION
```


I - Identificazione della procedura medica

### PATIENT_IDENTIFICATION {#PATIENT-IDENTIFICATION}
```
public static final int PATIENT_IDENTIFICATION
```


C - Identificazione del paziente

### PATIENT_VISIT_ID {#PATIENT-VISIT-ID}
```
public static final int PATIENT_VISIT_ID
```


V - ID visita del paziente

### PERSONNEL_IDENTIFICATION {#PERSONNEL-IDENTIFICATION}
```
public static final int PERSONNEL_IDENTIFICATION
```


E - Identificazione del personale

### PURCHASE_ORDER_NUMBER {#PURCHASE-ORDER-NUMBER}
```
public static final int PURCHASE_ORDER_NUMBER
```


O - Numero dell'ordine di acquisto

### REIMBURSEMENT_CATEGORY {#REIMBURSEMENT-CATEGORY}
```
public static final int REIMBURSEMENT_CATEGORY
```


J - Categoria di rimborso

### SERVICE_IDENTIFICATION {#SERVICE-IDENTIFICATION}
```
public static final int SERVICE_IDENTIFICATION
```


B - Identificazione del servizio

### SPECIMEN_IDENTIFICATION {#SPECIMEN-IDENTIFICATION}
```
public static final int SPECIMEN_IDENTIFICATION
```


D - Identificazione del campione

### USER_DEFINED {#USER-DEFINED}
```
public static final int USER_DEFINED
```


Z - Definito dall'Utente

### XML_DOCUMENT {#XML-DOCUMENT}
```
public static final int XML_DOCUMENT
```


X - Documento XML

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

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
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

