---
title: "QrParametersUI"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Enveloppe UI pour la classe com.aspose.barcode.generation.QrParameters."
type: docs
weight: 17
url: /fr/java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

Enveloppe UI pour la classe com.aspose.barcode.generation.QrParameters.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapport hauteur/largeur du module de code-barres 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Identifiants d'interprétation de canal étendu. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) | Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes-barres QR et RectMicroQR. |
| [getEncodeMode()](#getEncodeMode--) | Type de symbologie QR du mode d'encodage du BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Niveau de correction d'erreurs Reed-Solomon pour les codes-barres QR, MicroQR et RectMicroQR. |
| [getMicroQrVersion()](#getMicroQrVersion--) | Version du code MicroQR. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Version du code RectMicroQR. |
| [getVersion()](#getVersion--) | Version du code QR. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapport hauteur/largeur du module de code-barres 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifiants d'interprétation de canal étendu. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) | Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes-barres QR et RectMicroQR. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Type de symbologie QR du mode d'encodage du BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Niveau de correction d'erreurs Reed-Solomon pour les codes-barres QR, MicroQR et RectMicroQR. |
| [setMicroQrVersion(MicroQRVersion value)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | Version du code MicroQR. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Version du code RectMicroQR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Version du code QR. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
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


Rapport hauteur/largeur du module de code-barres 2D.

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
public int getECIEncoding()
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour encoder les données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeu de caractères bien connus. Non pris en charge par MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public boolean getEncodeGS1SeparatorInByteMode()
```


Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes-barres QR et RectMicroQR.

Si false, les séparateurs GS1 peuvent être encodés comme '%' en mode Alphanumérique selon la spécification QR.

Si true, les séparateurs de groupe GS1 sont encodés en mode Octet comme le caractère 0x1D, et les caractères '%' sont également encodés en mode Octet pour les préserver en tant que données.

Cette option peut améliorer la compatibilité avec les décodeurs qui attendent des séparateurs de groupe GS1 au niveau octet et empêche les caractères de données '%' d'être interprétés comme des séparateurs GS1.

**Returns:**
boolean
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Type de symbologie QR du mode d'encodage du BarCode. Valeur par défaut : QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. ver QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQrVersion() {#getMicroQrVersion--}
```
public final MicroQRVersion getMicroQrVersion()
```


Version du code MicroQR. De la version M1 à la version M4. La valeur par défaut est MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Version du code RectMicroQR. De la version R7x59 à la version R17x139. La valeur par défaut est RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version du code QR. De Version1 à Version40 pour le code QR et de M1 à M4 pour MicroQr. La valeur par défaut est QRVersion.Auto.

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


Rapport hauteur/largeur du module de code-barres 2D.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour encoder les données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeu de caractères bien connus. Non pris en charge par MicroQR.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public void setEncodeGS1SeparatorInByteMode(boolean value)
```


Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes-barres QR et RectMicroQR.

Si false, les séparateurs GS1 peuvent être encodés comme '%' en mode Alphanumérique selon la spécification QR.

Si true, les séparateurs de groupe GS1 sont encodés en mode Octet comme le caractère 0x1D, et les caractères '%' sont également encodés en mode Octet pour les préserver en tant que données.

Cette option peut améliorer la compatibilité avec les décodeurs qui attendent des séparateurs de groupe GS1 au niveau octet et empêche les caractères de données '%' d'être interprétés comme des séparateurs GS1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Type de symbologie QR du mode d'encodage du BarCode. Valeur par défaut : QREncodeMode.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Nivel de corrección de errores Reed-Solomon para códigos de barras QR, MicroQR y RectMicroQR. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. ver QRErrorLevel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQrVersion(MicroQRVersion value) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQrVersion(MicroQRVersion value)
```


Version du code MicroQR. De la version M1 à la version M4. La valeur par défaut est MicroQRVersion.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Version du code RectMicroQR. De la version R7x59 à la version R17x139. La valeur par défaut est RectMicroQRVersion.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Version du code QR. De Version1 à Version40 pour le code QR et de M1 à M4 pour MicroQr. La valeur par défaut est QRVersion.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - Une chaîne qui représente cet [QrParameters](../../com.aspose.barcode.generation/qrparameters).
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

