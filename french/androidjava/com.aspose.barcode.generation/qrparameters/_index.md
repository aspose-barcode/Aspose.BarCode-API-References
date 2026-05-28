---
title: QrParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Paramètres QR.
type: docs
weight: 64
url: /fr/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

Paramètres QR.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Ratio hauteur/largeur du module du code-barres 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Identifiants d'interprétation de canal étendu. |
| [getEncodeMode()](#getEncodeMode--) | Type de symbologie QR du mode d'encodage du code-barres. |
| [getErrorLevel()](#getErrorLevel--) | Niveau de correction d'erreurs Reed-Solomon pour les codes-barres QR, MicroQR et RectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version du MicroQR Code. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Identifiants d'interprétation de canal étendu. |
| [getQrEncodeMode()](#getQrEncodeMode--) | Type de symbologie QR du mode d'encodage du code-barres. |
| [getQrEncodeType()](#getQrEncodeType--) | Mode de sélection QR / MicroQR. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Niveau de correction d'erreurs Reed-Solomon pour les codes-barres QR, MicroQR et RectMicroQR. |
| [getQrVersion()](#getQrVersion--) | Version du code QR. De Version1 à Version40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Version du RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | Paramètres d'ajout structuré QR. |
| [getVersion()](#getVersion--) | Version du code QR. De Version1 à Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Ratio hauteur/largeur du module du code-barres 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifiants d'interprétation de canal étendu. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Type de symbologie QR du mode d'encodage du code-barres. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Niveau de correction d'erreurs Reed-Solomon pour les codes-barres QR, MicroQR et RectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Version du MicroQR Code. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | Mode de sélection QR / MicroQR. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Version du RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | Paramètres d'ajout structuré QR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Version du code QR. De Version1 à Version40. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Ratio hauteur/largeur du module du code-barres 2D.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus. Non pris en charge par MicroQR.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Niveau de correction d'erreurs Reed-Solomon pour les codes-barres QR, MicroQR et RectMicroQR. Du bas au haut : LevelL, LevelM, LevelQ, LevelH. Voir QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version du code MicroQR. De la version M1 à la version M4. La valeur par défaut est MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus. Non pris en charge par MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


Mode de sélection QR / MicroQR. Sélectionnez ForceQR pour les symboles QR standard, Auto pour MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


Niveau de correction d'erreurs Reed-Solomon pour les codes-barres QR, MicroQR et RectMicroQR. Du bas au haut : LevelL, LevelM, LevelQ, LevelH. Voir QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


Version du code QR. De Version1 à Version40. La valeur par défaut est QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Version du code RectMicroQR. De la version R7x59 à la version R17x139. La valeur par défaut est RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


Paramètres d'ajout structuré QR. Le mode d'ajout structuré n'est pas pris en charge par les codes-barres MicroQR et RectMicroQR.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version du code QR. De Version1 à Version40. La valeur par défaut est QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Ratio hauteur/largeur du module du code-barres 2D.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus. Non pris en charge par MicroQR.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Niveau de correction d'erreurs Reed-Solomon pour les codes-barres QR, MicroQR et RectMicroQR. Du bas au haut : LevelL, LevelM, LevelQ, LevelH. Voir QRErrorLevel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Version du code MicroQR. De la version M1 à la version M4. La valeur par défaut est MicroQRVersion.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


Mode de sélection QR / MicroQR. Sélectionnez ForceQR pour les symboles QR standard, Auto pour MicroQR.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Version du code RectMicroQR. De la version R7x59 à la version R17x139. La valeur par défaut est RectMicroQRVersion.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


Paramètres d'ajout structuré QR. Le mode d'ajout structuré n'est pas pris en charge par les codes-barres MicroQR et RectMicroQR.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Version du code QR. De Version1 à Version40. La valeur par défaut est QRVersion.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de cet [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - Une chaîne qui représente ce [QrParameters](../../com.aspose.barcode.generation/qrparameters).
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

