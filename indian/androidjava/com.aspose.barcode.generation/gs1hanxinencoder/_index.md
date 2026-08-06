---
title: GS1HanXinEncoder
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: GS1HanXin को एन्कोड करने के लिए फ़ंक्शन शामिल करता है।
type: docs
weight: 47
url: /hi/androidjava/com.aspose.barcode.generation/gs1hanxinencoder/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder, com.aspose.barcode.generation.HanXinEncoder
```
public class GS1HanXinEncoder extends HanXinEncoder
```

GS1HanXin को एन्कोड करने के लिए फ़ंक्शन शामिल करता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [GS1HanXinEncoder(HanXinEncoderParameters parameters)](#GS1HanXinEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters-) | इनपुट डेटा में मोडों को अलग करने के लिए केवल कोष्ठक () होने चाहिए, उदाहरण के लिए: (01)12345678901231(21)ASPOSE(30)9876। GS1 विशिष्टताओं के अनुसार, सभी पूर्वनिर्धारित लंबाई वाले GS1 डेटा स्ट्रिंग्स के बाद सभी गैर-पूर्वनिर्धारित लंबाई वाले GS1 डेटा स्ट्रिंग्स आने चाहिए। |
## Methods

| Method | विवरण |
| --- | --- |
| [encode(String str)](#encode-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlwaysShowChecksum()](#getAlwaysShowChecksum--) |  |
| [getChecksum()](#getChecksum--) |  |
| [getClass()](#getClass--) |  |
| [getEnableChecksum()](#getEnableChecksum--) |  |
| [getEncodeType()](#getEncodeType--) |  |
| [getHumanReadableCodeText()](#getHumanReadableCodeText--) |  |
| [getParameters()](#getParameters--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GS1HanXinEncoder(HanXinEncoderParameters parameters) {#GS1HanXinEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters-}
```
public GS1HanXinEncoder(HanXinEncoderParameters parameters)
```


इनपुट डेटा में मोडों को अलग करने के लिए केवल कोष्ठक () होने चाहिए, उदाहरण के लिए: (01)12345678901231(21)ASPOSE(30)9876। GS1 विशिष्टताओं के अनुसार, सभी पूर्वनिर्धारित लंबाई वाले GS1 डेटा स्ट्रिंग्स के बाद सभी गैर-पूर्वनिर्धारित लंबाई वाले GS1 डेटा स्ट्रिंग्स आने चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| पैरामीटर | com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters |  |

### encode(String str) {#encode-java.lang.String-}
```
public String encode(String str)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| str | java.lang.String |  |

**Returns:**
java.lang.String
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlwaysShowChecksum() {#getAlwaysShowChecksum--}
```
public boolean getAlwaysShowChecksum()
```




**Returns:**
boolean
### getChecksum() {#getChecksum--}
```
public String getChecksum()
```




**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableChecksum() {#getEnableChecksum--}
```
public EnableChecksum getEnableChecksum()
```




**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### getEncodeType() {#getEncodeType--}
```
public BaseEncodeType getEncodeType()
```




**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getHumanReadableCodeText() {#getHumanReadableCodeText--}
```
public String getHumanReadableCodeText()
```




**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public EncoderParameters getParameters()
```




**Returns:**
com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.EncoderParameters
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

