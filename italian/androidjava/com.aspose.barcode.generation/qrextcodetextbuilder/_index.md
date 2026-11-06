---
title: "QrExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: 
type: docs
weight: 61
url: /it/androidjava/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

Generatore di codetext esteso per codici a barre QR 2D per la modalità ExtendedCodetext di EncodeMode

Utilizza la proprietà TwoDDisplayText di BarcodeGenerator per impostare il testo visibile rimuovendo i caratteri di gestione.

Questo esempio mostra come utilizzare la prima posizione FNC1 in Modalità Estesa.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

Questo esempio mostra come utilizzare la seconda posizione FNC1 in Modalità Estesa.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

Questo esempio mostra come utilizzare la modalità multi ECI in Modalità Estesa.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.WIN_1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF_8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF_16_BE, "Power");
 textBuilder.addPlainCodetext("t\\e\\\\st");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.ALPHA_NUMERIC, "ASPOSE2001");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.NUMERIC, "20012026");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | Aggiunge codetext con la modalità di compattazione QR specificata agli elementi di codetext esteso. |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Aggiunge codetext con Identificatore di Canale Esteso |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | Imposta FNC1 nella prima posizione. |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Aggiunge il Separatore di Gruppo (GS - '\\\\u001D') agli elementi di codetext esteso |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | Imposta FNC1 nella seconda posizione. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Aggiunge codetext semplice agli elementi di codetext esteso |
| [clear()](#clear--) | Cancella gli elementi di codetext esteso |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genera codetext esteso dall'elenco di codetext esteso. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
```


### addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext) {#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-}
```
public final void addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)
```


Aggiunge codetext con la modalità di compattazione QR specificata agli elementi di codetext esteso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | Modalità di compattazione QR per il codetext. |
| codetext | java.lang.String | Codetext in Unicode da aggiungere come elemento di codetext esteso. |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Aggiunge codetext con Identificatore di Canale Esteso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ECIEncoding | int | Identificatore di Canale Esteso |
| codetext | java.lang.String | Codetext in Unicode da aggiungere come elemento di codetext esteso con Identificatore di Canale Esteso |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


Imposta FNC1 nella prima posizione. Se era stata impostata un'altra modalità FNC1 prima, viene sostituita.

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


Aggiunge il Separatore di Gruppo (GS - '\\\\u001D') agli elementi di codetext esteso

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


Imposta FNC1 nella seconda posizione. Se era stata impostata un'altra modalità FNC1 prima, viene sostituita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codetext | java.lang.String | Valore di FNC1 nella seconda posizione. Il valore deve essere una singola lettera da a-z o A-Z, oppure un numero a due cifre da 00 a 99. |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Aggiunge codetext semplice agli elementi di codetext esteso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in Unicode da aggiungere come elemento di codetext esteso |

### clear() {#clear--}
```
public void clear()
```


Cancella gli elementi di codetext esteso

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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Genera codetext esteso dall'elenco di codetext esteso.

**Returns:**
java.lang.String - Codetext esteso come stringa
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

