---
title: "AustraliaPostSettings"
second_title: "Référence d'API Aspose.BarCode pour Android via Java"
description: "Paramètres de décodage AustraliaPost."
type: docs
weight: 10
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/australiapostsettings/
---
**Inheritance:**
java.lang.Object
```
public class AustraliaPostSettings
```

Paramètres de décodage AustraliaPost. Contient des paramètres qui influencent les données reconnues de la symbologie AustraliaPost.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomerInformationDecoder()](#getCustomerInformationDecoder--) | Interface publique pour le décodage du champ d'information client utilisé dans la symbologie AustraliaPost. |
| [getCustomerInformationInterpretingType()](#getCustomerInformationInterpretingType--) | Obtient ou définit le type d'interprétation pour les informations client du code-barres AustralianPost. DEFAULT est CustomerInformationInterpretingType.OTHER. |
| [getIgnoreEndingFillingPatternsForCTable()](#getIgnoreEndingFillingPatternsForCTable--) | Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'informations client lors du décodage avec la méthode CTable. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)](#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-) | Interface publique pour le décodage du champ d'information client utilisé dans la symbologie AustraliaPost. |
| [setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)](#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-) | Obtient ou définit le type d'interprétation pour les informations client du code-barres AustralianPost. DEFAULT est CustomerInformationInterpretingType.OTHER. |
| [setIgnoreEndingFillingPatternsForCTable(boolean value)](#setIgnoreEndingFillingPatternsForCTable-boolean-) | Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'informations client lors du décodage avec la méthode CTable. |
| [toString()](#toString--) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomerInformationDecoder() {#getCustomerInformationDecoder--}
```
public AustraliaPostCustomerInformationDecoder getCustomerInformationDecoder()
```


Interface publique pour le décodage du champ d'information client utilisé dans la symbologie AustraliaPost.

**Returns:**
[AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) - Public interface for Customer Information Field decoding which is used in AustraliaPost symbology.
### getCustomerInformationInterpretingType() {#getCustomerInformationInterpretingType--}
```
public CustomerInformationInterpretingType getCustomerInformationInterpretingType()
```


Obtient ou définit le type d'interprétation pour les informations client du code-barres AustralianPost. DEFAULT est CustomerInformationInterpretingType.OTHER.

**Returns:**
[CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) - The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode
### getIgnoreEndingFillingPatternsForCTable() {#getIgnoreEndingFillingPatternsForCTable--}
```
public boolean getIgnoreEndingFillingPatternsForCTable()
```


Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'informations client lors du décodage avec la méthode CTable. La méthode d'encodage CTable ne comporte aucun vide dans la table d'encodage et la séquence "333" de motifs de remplissage est décodée comme la lettre "z". Exemple BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); Bitmap image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
booléen - Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage lors du décodage avec la méthode CTable
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




### setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value) {#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-}
```
public void setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)
```


Interface publique pour le décodage du champ d'information client utilisé dans la symbologie AustraliaPost.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) |  |

### setCustomerInformationInterpretingType(CustomerInformationInterpretingType value) {#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-}
```
public void setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)
```


Obtient ou définit le type d'interprétation pour les informations client du code-barres AustralianPost. DEFAULT est CustomerInformationInterpretingType.OTHER.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Le type d'interprétation (CTable, NTable ou Other) des informations client pour le code-barres AustralianPost |

### setIgnoreEndingFillingPatternsForCTable(boolean value) {#setIgnoreEndingFillingPatternsForCTable-boolean-}
```
public void setIgnoreEndingFillingPatternsForCTable(boolean value)
```


Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'informations client lors du décodage avec la méthode CTable. La méthode d'encodage CTable ne comporte aucun vide dans la table d'encodage et la séquence "333" de motifs de remplissage est décodée comme la lettre "z". Exemple BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); Bitmap image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

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

