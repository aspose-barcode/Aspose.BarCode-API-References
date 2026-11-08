---
title: "USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "USA DL सबफ़ाइल गुणों का ऑफ़सेट और लंबाई स्वचालित रूप से सेट की जाती है।"
type: docs
weight: 12
url: /hi/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

USA DL सबफ़ाइल प्रॉपर्टीज़, ऑफ़सेट और लंबाई स्वचालित रूप से सेट की जाती हैं।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
| [SubfileProperties()](#SubfileProperties--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 ये बाइट्स एक 4 अंकों का संख्यात्मक मान रखती हैं जो सबफ़ाइल की लंबाई बाइट्स में निर्दिष्ट करती है। सेगमेंट टर्मिनेटर को सबफ़ाइल की लंबाई की गणना में शामिल किया जाना चाहिए। एक सेगमेंट टर्मिनेटर = 1। |
| [getOffset()](#getOffset--) | 4 अंकों का संख्यात्मक मान जो फ़ाइल की शुरुआत से लेकर उस स्थान तक बाइट्स की संख्या निर्दिष्ट करता है जहाँ विशेष सबफ़ाइल से संबंधित डेटा स्थित है। फ़ाइल में पहला बाइट ऑफ़सेट 0 पर स्थित है। |
| [getType()](#getType--) | 2 बाइट का सबफ़ाइल प्रकार, जैसे "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 ये बाइट्स एक 4 अंकों का संख्यात्मक मान रखती हैं जो सबफ़ाइल की लंबाई बाइट्स में निर्दिष्ट करती है। सेगमेंट टर्मिनेटर को सबफ़ाइल की लंबाई की गणना में शामिल किया जाना चाहिए। एक सेगमेंट टर्मिनेटर = 1। |
| [setOffset(int value)](#setOffset-int-) | 4 अंकों का संख्यात्मक मान जो फ़ाइल की शुरुआत से लेकर उस स्थान तक बाइट्स की संख्या निर्दिष्ट करता है जहाँ विशेष सबफ़ाइल से संबंधित डेटा स्थित है। फ़ाइल में पहला बाइट ऑफ़सेट 0 पर स्थित है। |
| [setType(String value)](#setType-java.lang.String-) | 2 बाइट का सबफ़ाइल प्रकार, जैसे "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रकार | java.lang.String |  |

### SubfileProperties() {#SubfileProperties--}
```
public SubfileProperties()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
### getLength() {#getLength--}
```
public final int getLength()
```


4 ये बाइट्स एक 4 अंकों का संख्यात्मक मान रखती हैं जो सबफ़ाइल की लंबाई बाइट्स में निर्दिष्ट करती है। सेगमेंट टर्मिनेटर को सबफ़ाइल की लंबाई की गणना में शामिल किया जाना चाहिए। एक सेगमेंट टर्मिनेटर = 1। प्रत्येक सबफ़ाइल को दो-अक्षर वाले Subfile Type से शुरू होना चाहिए और इन दो अक्षरों को भी लंबाई में शामिल किया जाना चाहिए।

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4 अंकों का संख्यात्मक मान जो फ़ाइल की शुरुआत से लेकर उस स्थान तक बाइट्स की संख्या निर्दिष्ट करता है जहाँ विशेष सबफ़ाइल से संबंधित डेटा स्थित है। फ़ाइल में पहला बाइट ऑफ़सेट 0 पर स्थित है।

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


2 बाइट का सबफ़ाइल प्रकार, जैसे "DL"

**Returns:**
java.lang.String
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




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 ये बाइट्स एक 4 अंकों का संख्यात्मक मान रखती हैं जो सबफ़ाइल की लंबाई बाइट्स में निर्दिष्ट करती है। सेगमेंट टर्मिनेटर को सबफ़ाइल की लंबाई की गणना में शामिल किया जाना चाहिए। एक सेगमेंट टर्मिनेटर = 1। प्रत्येक सबफ़ाइल को दो-अक्षर वाले Subfile Type से शुरू होना चाहिए और इन दो अक्षरों को भी लंबाई में शामिल किया जाना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4 अंकों का संख्यात्मक मान जो फ़ाइल की शुरुआत से लेकर उस स्थान तक बाइट्स की संख्या निर्दिष्ट करता है जहाँ विशेष सबफ़ाइल से संबंधित डेटा स्थित है। फ़ाइल में पहला बाइट ऑफ़सेट 0 पर स्थित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


2 बाइट का सबफ़ाइल प्रकार, जैसे "DL"

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

