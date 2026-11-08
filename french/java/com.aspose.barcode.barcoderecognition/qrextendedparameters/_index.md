---
title: "QRExtendedParameters"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Stocke des informations QR Structured Append du code‑barres reconnu"
type: docs
weight: 38
url: /fr/java/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Stocke des informations QR Structured Append du code‑barres reconnu

Cet exemple montre comment obtenir les données QR Structured Append

```
{
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourne une valeur indiquant si cette instance est égale à une valeur spécifiée de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Niveau de correction d'erreur Reed-Solomon du code-barres reconnu. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version du MicroQR Code reconnu. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Version du RectMicroQR Code reconnu. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Obtient l'index du code-barres en mode d'ajout structuré QR. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Obtient la quantité de codes-barres en mode d'ajout structuré QR. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Obtient les données de parité du mode d'ajout structuré QR. |
| [getVersion()](#getVersion--) | Version du QR Code reconnu. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [isEmpty()](#isEmpty--) | Teste si tous les paramètres n'ont que les valeurs par défaut. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible de cet [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourne une valeur indiquant si cette instance est égale à une valeur spécifiée de [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur System.Object à comparer à cette instance. |

**Returns:**
booléen -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
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


Niveau de correction d'erreur Reed-Solomon du code-barres reconnu. Du plus bas au plus haut : LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version du MicroQR Code reconnu. De M1 à M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Version du RectMicroQR Code reconnu. De R7x43 à R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Obtient l'index du code-barres en mode d'ajout structuré QR. L'index commence à 0. La valeur par défaut est -1.

Valeur : La quantité de codes-barres en mode d'ajout structuré QR.

**Returns:**
int - l'index du code-barres en mode d'ajout structuré QR.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Obtient la quantité de codes-barres en mode d'ajout structuré QR. La valeur par défaut est -1.

Valeur : La quantité de codes-barres en mode d'ajout structuré QR.

**Returns:**
int - la quantité de codes-barres en mode d'ajout structuré QR.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Obtient les données de parité du mode d'ajout structuré QR. La valeur par défaut est -1.

Valeur : L'index du code-barres en mode d'ajout structuré QR.

**Returns:**
int - les données de parité du mode d'ajout structuré QR.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version du QR Code reconnu. De Version1 à Version40.

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


Teste si tous les paramètres n'ont que les valeurs par défaut.

Valeur : Retourne **true** si tous les paramètres n’ont que les valeurs par défaut ; sinon, **false**.

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




### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible de cet [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String - Une chaîne qui représente cet [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
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

