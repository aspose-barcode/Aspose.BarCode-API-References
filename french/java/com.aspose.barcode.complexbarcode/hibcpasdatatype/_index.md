---
title: "HIBCPASDataType"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Types de données des enregistrements HIBC PAS."
type: docs
weight: 20
url: /fr/java/com.aspose.barcode.complexbarcode/hibcpasdatatype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HIBCPASDataType extends System.Enum
```

Types de données des enregistrements HIBC PAS.
## Champs

| Champ | Description |
| --- | --- |
| [ADMINISTRABLE_PRODUCT_IDENTIFICATION](#ADMINISTRABLE-PRODUCT-IDENTIFICATION) | F - Identification du produit administrable |
| [ASSET_IDENTIFICATION](#ASSET-IDENTIFICATION) | N - Identification de l'actif |
| [BLOOD_PRODUCT_IDENTIFICATION](#BLOOD-PRODUCT-IDENTIFICATION) | K - Identification du produit sanguin |
| [BUSINESS_CONTROL_NUMBER](#BUSINESS-CONTROL-NUMBER) | S - Numéro de contrôle commercial |
| [DATE_TIME](#DATE-TIME) | M - DateHeure au format YYYDDDHHMMG |
| [DEMOGRAPHIC_DATA](#DEMOGRAPHIC-DATA) | L - Données démographiques |
| [DIETARY_ITEM_IDENTIFICATION](#DIETARY-ITEM-IDENTIFICATION) | P - Identification de l'article alimentaire |
| [EPISODE_OF_CARE_IDENTIFICATION](#EPISODE-OF-CARE-IDENTIFICATION) | T - Identification de l'épisode de soins |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [HEALTH_INDUSTRY_NUMBER](#HEALTH-INDUSTRY-NUMBER) | U - Numéro de l'industrie de la santé |
| [HOSPITAL_ITEM_IDENTIFICATION](#HOSPITAL-ITEM-IDENTIFICATION) | H - Identification de l'article hospitalier |
| [IMPLANTABLE_PRODUCT_INFORMATION](#IMPLANTABLE-PRODUCT-INFORMATION) | G - Informations sur le produit implantable |
| [LABELER_IDENTIFICATION_CODE](#LABELER-IDENTIFICATION-CODE) | A - Code d'identification du labelisateur |
| [LIBRARY_MATERIALS_IDENTIFICATION](#LIBRARY-MATERIALS-IDENTIFICATION) | R - Identification des matériaux de bibliothèque |
| [MANUFACTURER_SERIAL_NUMBER](#MANUFACTURER-SERIAL-NUMBER) | Q - Numéro de série du fabricant |
| [MEDICAL_PROCEDURE_IDENTIFICATION](#MEDICAL-PROCEDURE-IDENTIFICATION) | I - Identification de la procédure médicale |
| [PATIENT_IDENTIFICATION](#PATIENT-IDENTIFICATION) | C - Identification du patient |
| [PATIENT_VISIT_ID](#PATIENT-VISIT-ID) | V - Identifiant de visite du patient |
| [PERSONNEL_IDENTIFICATION](#PERSONNEL-IDENTIFICATION) | E - Identification du personnel |
| [PURCHASE_ORDER_NUMBER](#PURCHASE-ORDER-NUMBER) | O - Numéro de bon de commande |
| [REIMBURSEMENT_CATEGORY](#REIMBURSEMENT-CATEGORY) | J - Catégorie de remboursement |
| [SERVICE_IDENTIFICATION](#SERVICE-IDENTIFICATION) | B - Identification du service |
| [SPECIMEN_IDENTIFICATION](#SPECIMEN-IDENTIFICATION) | D - Identification de l'échantillon |
| [USER_DEFINED](#USER-DEFINED) | Z - Défini par l'utilisateur |
| [XML_DOCUMENT](#XML-DOCUMENT) | X - Document XML |
## Méthodes

| Méthode | Description |
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


F - Identification du produit administrable

### ASSET_IDENTIFICATION {#ASSET-IDENTIFICATION}
```
public static final int ASSET_IDENTIFICATION
```


N - Identification de l'actif

### BLOOD_PRODUCT_IDENTIFICATION {#BLOOD-PRODUCT-IDENTIFICATION}
```
public static final int BLOOD_PRODUCT_IDENTIFICATION
```


K - Identification du produit sanguin

### BUSINESS_CONTROL_NUMBER {#BUSINESS-CONTROL-NUMBER}
```
public static final int BUSINESS_CONTROL_NUMBER
```


S - Numéro de contrôle commercial

### DATE_TIME {#DATE-TIME}
```
public static final int DATE_TIME
```


M - DateHeure au format YYYDDDHHMMG

### DEMOGRAPHIC_DATA {#DEMOGRAPHIC-DATA}
```
public static final int DEMOGRAPHIC_DATA
```


L - Données démographiques

### DIETARY_ITEM_IDENTIFICATION {#DIETARY-ITEM-IDENTIFICATION}
```
public static final int DIETARY_ITEM_IDENTIFICATION
```


P - Identification de l'article alimentaire

### EPISODE_OF_CARE_IDENTIFICATION {#EPISODE-OF-CARE-IDENTIFICATION}
```
public static final int EPISODE_OF_CARE_IDENTIFICATION
```


T - Identification de l'épisode de soins

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### HEALTH_INDUSTRY_NUMBER {#HEALTH-INDUSTRY-NUMBER}
```
public static final int HEALTH_INDUSTRY_NUMBER
```


U - Numéro de l'industrie de la santé

### HOSPITAL_ITEM_IDENTIFICATION {#HOSPITAL-ITEM-IDENTIFICATION}
```
public static final int HOSPITAL_ITEM_IDENTIFICATION
```


H - Identification de l'article hospitalier

### IMPLANTABLE_PRODUCT_INFORMATION {#IMPLANTABLE-PRODUCT-INFORMATION}
```
public static final int IMPLANTABLE_PRODUCT_INFORMATION
```


G - Informations sur le produit implantable

### LABELER_IDENTIFICATION_CODE {#LABELER-IDENTIFICATION-CODE}
```
public static final int LABELER_IDENTIFICATION_CODE
```


A - Code d'identification du labelisateur

### LIBRARY_MATERIALS_IDENTIFICATION {#LIBRARY-MATERIALS-IDENTIFICATION}
```
public static final int LIBRARY_MATERIALS_IDENTIFICATION
```


R - Identification des matériaux de bibliothèque

### MANUFACTURER_SERIAL_NUMBER {#MANUFACTURER-SERIAL-NUMBER}
```
public static final int MANUFACTURER_SERIAL_NUMBER
```


Q - Numéro de série du fabricant

### MEDICAL_PROCEDURE_IDENTIFICATION {#MEDICAL-PROCEDURE-IDENTIFICATION}
```
public static final int MEDICAL_PROCEDURE_IDENTIFICATION
```


I - Identification de la procédure médicale

### PATIENT_IDENTIFICATION {#PATIENT-IDENTIFICATION}
```
public static final int PATIENT_IDENTIFICATION
```


C - Identification du patient

### PATIENT_VISIT_ID {#PATIENT-VISIT-ID}
```
public static final int PATIENT_VISIT_ID
```


V - Identifiant de visite du patient

### PERSONNEL_IDENTIFICATION {#PERSONNEL-IDENTIFICATION}
```
public static final int PERSONNEL_IDENTIFICATION
```


E - Identification du personnel

### PURCHASE_ORDER_NUMBER {#PURCHASE-ORDER-NUMBER}
```
public static final int PURCHASE_ORDER_NUMBER
```


O - Numéro de bon de commande

### REIMBURSEMENT_CATEGORY {#REIMBURSEMENT-CATEGORY}
```
public static final int REIMBURSEMENT_CATEGORY
```


J - Catégorie de remboursement

### SERVICE_IDENTIFICATION {#SERVICE-IDENTIFICATION}
```
public static final int SERVICE_IDENTIFICATION
```


B - Identification du service

### SPECIMEN_IDENTIFICATION {#SPECIMEN-IDENTIFICATION}
```
public static final int SPECIMEN_IDENTIFICATION
```


D - Identification de l'échantillon

### USER_DEFINED {#USER-DEFINED}
```
public static final int USER_DEFINED
```


Z - Défini par l'utilisateur

### XML_DOCUMENT {#XML-DOCUMENT}
```
public static final int XML_DOCUMENT
```


X - Document XML

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

