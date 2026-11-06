---
title: "Mailmark2DCodetext"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mail 2D Mailmark."
type: docs
weight: 23
url: /it/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mail 2D Mailmark.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Crea un'istanza predefinita della classe Mailmark2DCodetext. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Ottiene il tipo di codice a barre. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Costruisci il codetext dai dati Mailmark. |
| [getCustomerContent()](#getCustomerContent--) | Spazio opzionale per l'uso da parte del cliente. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Modalità di codifica del codice a barre Datamatrix. |
| [getDataMatrixType()](#getDataMatrixType--) | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. |
| [getItemID()](#getItemID--) | Identifica l'elemento unico all'interno dell'ID della catena di fornitura. |
| [getRTSFlag()](#getRTSFlag--) | Flag che indica quale livello di servizio Return to Sender è richiesto. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Contiene il codice postale Return to Sender ma non il DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Identifica il gruppo unico di clienti coinvolti nella spedizione. |
| [getUPUCountryID()](#getUPUCountryID--) | Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri. |
| [getVersionID()](#getVersionID--) | Identifica la versione del codice a barre in base a ciascun ID del tipo di informazione. |
| [getclass()](#getclass--) | Identifica la classe dell'elemento. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inizializza i dati Mailmark dal codetext costruito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Spazio opzionale per l'uso da parte del cliente. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Modalità di codifica del codice a barre Datamatrix. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. |
| [setItemID(int value)](#setItemID-int-) | Identifica l'elemento unico all'interno dell'ID della catena di fornitura. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Flag che indica quale livello di servizio Return to Sender è richiesto. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Contiene il codice postale Return to Sender ma non il DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifica il gruppo unico di clienti coinvolti nella spedizione. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Identifica la versione del codice a barre in base a ciascun ID del tipo di informazione. |
| [setclass(String value)](#setclass-java.lang.String-) | Identifica la classe dell'elemento. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Crea un'istanza predefinita della classe Mailmark2DCodetext.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Ottiene il tipo di codice a barre.

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


Costruisci il codetext dai dati Mailmark.

**Returns:**
java.lang.String - Codetext costruito
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Spazio opzionale per l'uso del cliente. Lunghezza massima per Tipo: Tipo 7: 6 caratteri Tipo 9: 45 caratteri Tipo 29: 25 caratteri

**Returns:**
java.lang.String - Contenuto del cliente
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Modalità di codifica del codice a barre Datamatrix. Valore predefinito: DataMatrixEncodeMode.C40.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri. Area (1 o 2 caratteri) Distretto (1 o 2 caratteri) Settore (1 carattere) Unità (2 caratteri) DPS (2 caratteri). Il codice postale e il DPS devono rispettare un formato PAF® valido.

**Returns:**
java.lang.String - il codice postale dell'indirizzo di consegna con DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. Valori validi: '0' - Domestico Ordinato e Non Ordinato 'A' - Posta Online 'B' - Franking 'C' - Consolidamento

**Returns:**
java.lang.String - ID tipo di informazione
### getItemID() {#getItemID--}
```
public int getItemID()
```


Identifica l'elemento unico all'interno dell'ID della catena di fornitura. Ogni codice a barre Mailmark deve contenere un ID affinché possa essere identificato in modo univoco per almeno 90 giorni. Valore massimo: 99999999.

**Returns:**
int - elemento all'interno dell'ID della catena di fornitura
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Flag che indica quale livello di servizio Return to Sender è richiesto.

**Returns:**
java.lang.String - Flag RTS
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Contiene il codice postale di ritorno al mittente ma senza DPS. Il codice postale (senza DPS) deve rispettare un formato PAF®.

**Returns:**
java.lang.String - Codice postale di ritorno al mittente ma senza DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999.

**Returns:**
int - ID della catena di fornitura
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri.

**Returns:**
java.lang.String - ID Paese
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Identifica la versione del codice a barre in base a ciascun ID tipo di informazione. Valori validi: Attualmente '1'. '0' e da '2' a '9' e da 'A' a 'Z' sono riservati per potenziali usi futuri.

**Returns:**
java.lang.String - ID versione
### getclass() {#getclass--}
```
public String getclass()
```


Identifica la classe dell'elemento. Valori validi: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deferred (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Returns:**
java.lang.String - classe dell'elemento
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


Inizializza i dati Mailmark dal codetext costruito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Codetext costruito. |

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


Spazio opzionale per l'uso del cliente. Lunghezza massima per Tipo: Tipo 7: 6 caratteri Tipo 9: 45 caratteri Tipo 29: 25 caratteri

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Contenuto del cliente |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Modalità di codifica del codice a barre Datamatrix. Valore predefinito: EncodeMode.C40.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Modalità di codifica del codice a barre Datamatrix. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Dimensione del codice a barre Data Matrix |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri. Area (1 o 2 caratteri) Distretto (1 o 2 caratteri) Settore (1 carattere) Unità (2 caratteri) DPS (2 caratteri). Il codice postale e il DPS devono rispettare un formato PAF® valido.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | il codice postale dell'indirizzo di consegna con DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. Valori validi: '0' - Domestico Ordinato e Non Ordinato 'A' - Posta Online 'B' - Franking 'C' - Consolidamento

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | ID tipo di informazione |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Identifica l'elemento unico all'interno dell'ID della catena di fornitura. Ogni codice a barre Mailmark deve contenere un ID affinché possa essere identificato in modo univoco per almeno 90 giorni. Valore massimo: 99999999.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | elemento all'interno del Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Flag che indica quale livello di servizio Return to Sender è richiesto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Contiene il codice postale di ritorno al mittente ma senza DPS. Il codice postale (senza DPS) deve rispettare un formato PAF®.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Codice postale di ritorno al mittente ma senza DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | ID della catena di fornitura |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | ID del Paese |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Identifica la versione del codice a barre in base a ciascun ID tipo di informazione. Valori validi: Attualmente '1'. '0' e da '2' a '9' e da 'A' a 'Z' sono riservati per potenziali usi futuri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | ID della versione |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Identifica la classe dell'elemento. Valori validi: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deferred (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | classe dell'elemento |

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

