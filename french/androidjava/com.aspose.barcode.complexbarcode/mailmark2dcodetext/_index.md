---
title: Mailmark2DCodetext
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Classe pour encoder et décoder le texte intégré dans le code Royal Mail 2D Mailmark.
type: docs
weight: 23
url: /fr/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Classe pour encoder et décoder le texte intégré dans le code Royal Mail 2D Mailmark.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Créer une instance par défaut de la classe Mailmark2DCodetext. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Obtient le type de code-barres. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construire le texte de code à partir des données Mailmark. |
| [getCustomerContent()](#getCustomerContent--) | Espace optionnel à l’usage du client. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Mode d’encodage du code-barres Datamatrix. |
| [getDataMatrixType()](#getDataMatrixType--) | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contient le code postal de l’adresse de livraison avec le DPS. Si intérieur, le code postal/DP contient le nombre de caractères suivant. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifie la charge utile du code-barres Mailmark de Royal Mail pour chaque type de produit. |
| [getItemID()](#getItemID--) | Identifie l’élément unique au sein de l’ID de la chaîne d’approvisionnement. |
| [getRTSFlag()](#getRTSFlag--) | Indicateur qui indique le niveau de service Retour à l'expéditeur demandé. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Contient le code postal Retour à l'expéditeur mais sans DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Identifie le groupe unique de clients impliqués dans l'envoi. |
| [getUPUCountryID()](#getUPUCountryID--) | Identifie l'ID pays UPU. Longueur maximale : 4 caractères. |
| [getVersionID()](#getVersionID--) | Identifie la version du code-barres pertinente pour chaque ID de type d'information. |
| [getclass()](#getclass--) | Identifie la classe de l'élément. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialise les données Mailmark à partir du texte de code construit. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Espace optionnel à l’usage du client. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Mode d’encodage du code-barres Datamatrix. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contient le code postal de l’adresse de livraison avec le DPS. Si intérieur, le code postal/DP contient le nombre de caractères suivant. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifie la charge utile du code-barres Mailmark de Royal Mail pour chaque type de produit. |
| [setItemID(int value)](#setItemID-int-) | Identifie l’élément unique au sein de l’ID de la chaîne d’approvisionnement. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Indicateur qui indique le niveau de service Retour à l'expéditeur demandé. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Contient le code postal Retour à l'expéditeur mais sans DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifie le groupe unique de clients impliqués dans l'envoi. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifie l'ID pays UPU. Longueur maximale : 4 caractères. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Identifie la version du code-barres pertinente pour chaque ID de type d'information. |
| [setclass(String value)](#setclass-java.lang.String-) | Identifie la classe de l'élément. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Créer une instance par défaut de la classe Mailmark2DCodetext.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Obtient le type de code-barres.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Construire le texte de code à partir des données Mailmark.

**Returns:**
java.lang.String - Texte de code construit
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Espace optionnel à l'usage du client. Longueur maximale par type : Type 7 : 6 caractères Type 9 : 45 caractères Type 29 : 25 caractères

**Returns:**
java.lang.String - Contenu client
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Mode d'encodage du code-barres Datamatrix. Valeur par défaut : DataMatrixEncodeMode.C40.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


Le type Mailmark 2D définit la taille du code-barres Data Matrix.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


Contient le code postal de l'adresse de livraison avec DPS. Si l'adresse est intérieure, le code postal/DP comporte le nombre de caractères suivant : Zone (1 ou 2 caractères) District (1 ou 2 caractères) Secteur (1 caractère) Unité (2 caractères) DPS (2 caractères). Le code postal et le DPS doivent être conformes à un format PAF® valide.

**Returns:**
java.lang.String - le code postal de l'adresse de livraison avec DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit. Valeurs valides : '0' - Domestique trié et non trié 'A' - Affranchissement en ligne 'B' - Marquage 'C' - Consolidation

**Returns:**
java.lang.String - ID du type d'information
### getItemID() {#getItemID--}
```
public int getItemID()
```


Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. Chaque code-barres Mailmark doit porter un ID afin d'être identifié de manière unique pendant au moins 90 jours. Valeur maximale : 99999999.

**Returns:**
int - élément au sein de l'ID de la chaîne d'approvisionnement
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Indicateur qui indique le niveau de service Retour à l'expéditeur demandé.

**Returns:**
java.lang.String - Indicateur RTS
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Contient le code postal Retour à l'expéditeur mais sans DPS. Le code postal (sans DPS) doit être conforme à un format PAF®.

**Returns:**
java.lang.String - Code postal Retour à l'expéditeur sans DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Identifie le groupe unique de clients impliqués dans l'envoi. Valeur maximale : 9999999.

**Returns:**
int - ID de la chaîne d'approvisionnement
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Identifie l'ID pays UPU. Longueur maximale : 4 caractères.

**Returns:**
java.lang.String - ID du pays
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Identifie la version du code-barres pertinente pour chaque ID de type d'information. Valeurs valides : actuellement '1'. '0' et '2' à '9' ainsi que 'A' à 'Z' sont réservés pour une utilisation future éventuelle.

**Returns:**
java.lang.String - ID de version
### getclass() {#getclass--}
```
public String getclass()
```


Identifie la classe de l'élément. Valeurs valides : '1' - 1C (Vente au détail) '2' - 2C (Vente au détail) '3' - Économie (Vente au détail) '5' - Différé (Vente au détail) '8' - Premium (Accès réseau) '9' - Standard (Accès réseau)

**Returns:**
java.lang.String - classe de l'élément
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialise les données Mailmark à partir du texte de code construit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Texte de code construit. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


Espace optionnel à l'usage du client. Longueur maximale par type : Type 7 : 6 caractères Type 9 : 45 caractères Type 29 : 25 caractères

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Customer content |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.C40.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Mode d’encodage du code-barres Datamatrix. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


Le type Mailmark 2D définit la taille du code-barres Data Matrix.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Size of Data Matrix barcode |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Contient le code postal de l'adresse de livraison avec DPS. Si l'adresse est intérieure, le code postal/DP comporte le nombre de caractères suivant : Zone (1 ou 2 caractères) District (1 ou 2 caractères) Secteur (1 caractère) Unité (2 caractères) DPS (2 caractères). Le code postal et le DPS doivent être conformes à un format PAF® valide.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | the Postcode of the Delivery Address with DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit. Valeurs valides : '0' - Domestique trié et non trié 'A' - Affranchissement en ligne 'B' - Marquage 'C' - Consolidation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Information type ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. Chaque code-barres Mailmark doit porter un ID afin d'être identifié de manière unique pendant au moins 90 jours. Valeur maximale : 99999999.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | item within the Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Indicateur qui indique le niveau de service Retour à l'expéditeur demandé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Contient le code postal Retour à l'expéditeur mais sans DPS. Le code postal (sans DPS) doit être conforme à un format PAF®.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Return to Sender Post Code but no DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Identifie le groupe unique de clients impliqués dans l'envoi. Valeur maximale : 9999999.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Supply chain ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Identifie l'ID pays UPU. Longueur maximale : 4 caractères.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Country ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Identifie la version du code-barres pertinente pour chaque ID de type d'information. Valeurs valides : actuellement '1'. '0' et '2' à '9' ainsi que 'A' à 'Z' sont réservés pour une utilisation future éventuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Version ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Identifie la classe de l'élément. Valeurs valides : '1' - 1C (Vente au détail) '2' - 2C (Vente au détail) '3' - Économie (Vente au détail) '5' - Différé (Vente au détail) '8' - Premium (Accès réseau) '9' - Standard (Accès réseau)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | class of the item |

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

