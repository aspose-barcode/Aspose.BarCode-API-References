---
title: QRExtendedParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Stocke les informations QR Structured Append du code‑barres reconnu
type: docs
weight: 42
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Stocke les informations QR Structured Append du code‑barres reconnu

Cet exemple montre comment obtenir les données QR Structured Append

```
{
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Niveau de correction d'erreur Reed-Solomon du code-barres reconnu. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version du MicroQR Code reconnu. |
| [getQRErrorLevel()](#getQRErrorLevel--) | Niveau de correction d'erreur Reed-Solomon du code-barres reconnu. |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | Obtient l'index du code-barres en mode QR structured append. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | Obtient la quantité de codes-barres en mode QR structured append. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | Obtient les données de parité du mode d'ajout structuré QR. |
| [getQRVersion()](#getQRVersion--) | Version du code QR reconnu. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Version du code RectMicroQR reconnu. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Obtient l'index du code-barres en mode QR structured append. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Obtient la quantité de codes-barres en mode QR structured append. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Obtient les données de parité du mode d'ajout structuré QR. |
| [getVersion()](#getVersion--) | Version du code QR reconnu. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [isEmpty()](#isEmpty--) | Teste si tous les paramètres n'ont que des valeurs par défaut |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Renvoie une valeur indiquant si la première valeur de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) est égale à la seconde. |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Renvoie une valeur indiquant si la première valeur de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) est différente de la seconde. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur System.Object à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Niveau de correction d'erreurs Reed-Solomon du code-barres reconnu. Du plus bas au plus élevé : LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version du code MicroQR reconnu. De M1 à M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


Niveau de correction d'erreurs Reed-Solomon du code-barres reconnu. Du plus bas au plus élevé : LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


Obtient l'index du code-barres en mode d'ajout structuré QR. L'index commence à 0. La valeur par défaut est -1.

Valeur : la quantité de codes-barres en mode d'ajout structuré QR.

**Returns:**
int - l'index du code-barres en mode d'ajout structuré QR.
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


Obtient la quantité de codes-barres en mode d'ajout structuré QR. La valeur par défaut est -1.

Valeur : la quantité de codes-barres en mode d'ajout structuré QR.

**Returns:**
int - la quantité de codes-barres en mode d'ajout structuré QR.
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


Obtient les données de parité du mode d'ajout structuré QR. La valeur par défaut est -1.

Valeur : l'index du code-barres en mode d'ajout structuré QR.

**Returns:**
int - les données de parité du mode d'ajout structuré QR.
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


Version du code QR reconnu. De Version1 à Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Version du code RectMicroQR reconnu. De R7x43 à R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Obtient l'index du code-barres en mode d'ajout structuré QR. L'index commence à 0. La valeur par défaut est -1.

Valeur : la quantité de codes-barres en mode d'ajout structuré QR.

**Returns:**
int - l'index du code-barres en mode d'ajout structuré QR.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Obtient la quantité de codes-barres en mode d'ajout structuré QR. La valeur par défaut est -1.

Valeur : la quantité de codes-barres en mode d'ajout structuré QR.

**Returns:**
int - la quantité de codes-barres en mode d'ajout structuré QR.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Obtient les données de parité du mode d'ajout structuré QR. La valeur par défaut est -1.

Valeur : l'index du code-barres en mode d'ajout structuré QR.

**Returns:**
int - les données de parité du mode d'ajout structuré QR.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version du code QR reconnu. De Version1 à Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Teste si tous les paramètres n'ont que des valeurs par défaut

Valeur : Renvoie  **true**  si tous les paramètres n'ont que des valeurs par défaut ; sinon,  **false** .

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




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


Renvoie une valeur indiquant si la première valeur de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) est égale à la seconde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Une première valeur comparée |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Une seconde valeur comparée |

**Returns:**
boolean -  **true**  si le premier a la même valeur que le second ; sinon,  **false** .
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


Renvoie une valeur indiquant si la première valeur de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) est différente de la seconde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Une première valeur comparée |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Une seconde valeur comparée |

**Returns:**
boolean -  **true**  si le premier a une valeur différente du second ; sinon,  **false** .
### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String - Une chaîne qui représente ce [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

