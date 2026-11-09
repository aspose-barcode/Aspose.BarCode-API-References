---
title: "AustraliaPostSettings"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Parametri di decodifica AustraliaPost."
type: docs
weight: 10
url: /it/java/com.aspose.barcode.barcoderecognition/australiapostsettings/
---
**Inheritance:**
java.lang.Object
```
public class AustraliaPostSettings
```

Parametri di decodifica AustraliaPost. Contiene parametri che influenzano i dati riconosciuti della simbologia AustraliaPost.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomerInformationDecoder()](#getCustomerInformationDecoder--) | Interfaccia pubblica per la decodifica del Customer Information Field, utilizzata nella simbologia AustraliaPost. |
| [getCustomerInformationInterpretingType()](#getCustomerInformationInterpretingType--) | Ottiene o imposta il Tipo di Interpretazione per le Informazioni Cliente del Codice a Barre AustralianPost. DEFAULT è CustomerInformationInterpretingType.OTHER. |
| [getIgnoreEndingFillingPatternsForCTable()](#getIgnoreEndingFillingPatternsForCTable--) | Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento nel campo Customer Information durante la decodifica con il metodo CTable. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)](#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-) | Interfaccia pubblica per la decodifica del Customer Information Field, utilizzata nella simbologia AustraliaPost. |
| [setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)](#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-) | Ottiene o imposta il Tipo di Interpretazione per le Informazioni Cliente del Codice a Barre AustralianPost. DEFAULT è CustomerInformationInterpretingType.OTHER. |
| [setIgnoreEndingFillingPatternsForCTable(boolean value)](#setIgnoreEndingFillingPatternsForCTable-boolean-) | Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento nel campo Customer Information durante la decodifica con il metodo CTable. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Interfaccia pubblica per la decodifica del Customer Information Field, utilizzata nella simbologia AustraliaPost.

**Returns:**
[AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) - Public interface for Customer Information Field decoding which is used in AustraliaPost symbology.
### getCustomerInformationInterpretingType() {#getCustomerInformationInterpretingType--}
```
public CustomerInformationInterpretingType getCustomerInformationInterpretingType()
```


Ottiene o imposta il Tipo di Interpretazione per le Informazioni Cliente del Codice a Barre AustralianPost. DEFAULT è CustomerInformationInterpretingType.OTHER.

**Returns:**
[CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) - The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode
### getIgnoreEndingFillingPatternsForCTable() {#getIgnoreEndingFillingPatternsForCTable--}
```
public boolean getIgnoreEndingFillingPatternsForCTable()
```


Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento nel campo Customer Information durante la decodifica con il metodo CTable. Il metodo di codifica CTable non presenta lacune nella tabella di codifica e la sequenza "333" dei pattern di riempimento è decodificata come la lettera "z". Esempio BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\\_TABLE); BufferedImage image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \\{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \\}

**Returns:**
boolean - Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento durante la decodifica con il metodo CTable
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


Interfaccia pubblica per la decodifica del Customer Information Field, utilizzata nella simbologia AustraliaPost.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) |  |

### setCustomerInformationInterpretingType(CustomerInformationInterpretingType value) {#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-}
```
public void setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)
```


Ottiene o imposta il Tipo di Interpretazione per le Informazioni Cliente del Codice a Barre AustralianPost. DEFAULT è CustomerInformationInterpretingType.OTHER.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Il tipo di interpretazione (CTable, NTable o Other) delle informazioni cliente per il Codice a Barre AustralianPost |

### setIgnoreEndingFillingPatternsForCTable(boolean value) {#setIgnoreEndingFillingPatternsForCTable-boolean-}
```
public void setIgnoreEndingFillingPatternsForCTable(boolean value)
```


Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento nel campo Customer Information durante la decodifica con il metodo CTable. Il metodo di codifica CTable non presenta lacune nella tabella di codifica e la sequenza "333" dei pattern di riempimento è decodificata come la lettera "z". Esempio BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\\_TABLE); BufferedImage image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \\{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \\}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

