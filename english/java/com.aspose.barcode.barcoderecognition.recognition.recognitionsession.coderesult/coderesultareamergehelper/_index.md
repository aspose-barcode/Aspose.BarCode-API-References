---
title: CodeResultAreaMergeHelper
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesultareamergehelper/
---
**Inheritance:**
java.lang.Object
```
public class CodeResultAreaMergeHelper
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CodeResultAreaMergeHelper()](#CodeResultAreaMergeHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [excludeIntersectedBarcodesFromList(List<CodeResult> aResultsList, IIntersectCodeResultSelector Selector, ITerminationCheck aTerminationCheck)](#excludeIntersectedBarcodesFromList-java.util.List-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult--com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.IIntersectCodeResultSelector-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Filters by Selector aResultsList intersected CodeResults |
| [excludeIntersectedBarcodesFromList(List<CodeResult> aResultsList, IIntersectCodeResultSelector Selector, double aMaxDist, ITerminationCheck aTerminationCheck)](#excludeIntersectedBarcodesFromList-java.util.List-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult--com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.IIntersectCodeResultSelector-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Filters by Selector aResultsList intersected CodeResults |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodeResultAreaMergeHelper() {#CodeResultAreaMergeHelper--}
```
public CodeResultAreaMergeHelper()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### excludeIntersectedBarcodesFromList(List<CodeResult> aResultsList, IIntersectCodeResultSelector Selector, ITerminationCheck aTerminationCheck) {#excludeIntersectedBarcodesFromList-java.util.List-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult--com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.IIntersectCodeResultSelector-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<CodeResult> excludeIntersectedBarcodesFromList(List<CodeResult> aResultsList, IIntersectCodeResultSelector Selector, ITerminationCheck aTerminationCheck)
```


Filters by Selector aResultsList intersected CodeResults

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResultsList | java.util.List<com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult> | Proceed objects with bounding quads |
| Selector | [IIntersectCodeResultSelector](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/iintersectcoderesultselector) | Selector which can select one or more object from intersected list |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[List](../../java.util/list) - filtered intersected CodeResults
### excludeIntersectedBarcodesFromList(List<CodeResult> aResultsList, IIntersectCodeResultSelector Selector, double aMaxDist, ITerminationCheck aTerminationCheck) {#excludeIntersectedBarcodesFromList-java.util.List-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult--com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.IIntersectCodeResultSelector-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<CodeResult> excludeIntersectedBarcodesFromList(List<CodeResult> aResultsList, IIntersectCodeResultSelector Selector, double aMaxDist, ITerminationCheck aTerminationCheck)
```


Filters by Selector aResultsList intersected CodeResults

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResultsList | java.util.List<com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult> | Proceed objects with bounding quads |
| Selector | [IIntersectCodeResultSelector](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/iintersectcoderesultselector) | Selector which can select one or more object from intersected list |
| aMaxDist | double | maximal distance from quad to quad, when distance more then 0, can intersect "nearest" quads |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[List](../../java.util/list) - filtered intersected CodeResults
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

