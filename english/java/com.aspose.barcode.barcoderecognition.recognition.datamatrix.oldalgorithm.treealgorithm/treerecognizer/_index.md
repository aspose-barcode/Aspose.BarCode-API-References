---
title: TreeRecognizer
second_title: Aspose.BarCode for Java API Reference
description: Class for recognizing a tree of algorithms.
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/treerecognizer/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.BaseRecognizer
```
public class TreeRecognizer extends BaseRecognizer
```

Class for recognizing a tree of algorithms. Firstly it applies owner algorithm (if needed), secondly applies children algorithms (leafs or tree recognizers)
## Constructors

| Constructor | Description |
| --- | --- |
| [TreeRecognizer(IAlgorithm ownerAlgorithm, System.Type[] writableType)](#TreeRecognizer-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm-com.aspose.ms.System.Type...-) | Initializes a new instance of the [TreeRecognizer](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/treerecognizer) class. |
| [TreeRecognizer()](#TreeRecognizer--) | Initializes a new instance of the [TreeRecognizer](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/treerecognizer) class without owner algorithm |
## Fields

| Field | Description |
| --- | --- |
| [_firstSuccessOnly](#-firstSuccessOnly) | If one of algorithms at current level is succesfull, next algorithms from this level will not be applied |
## Methods

| Method | Description |
| --- | --- |
| [addCreateTree()](#addCreateTree--) | Creates a tree recognizer(without owner algorithm) and adds it as a child |
| [addCreateTree(IAlgorithm algorithm)](#addCreateTree-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm-) | Creates a tree recognizer with owner algorithm. |
| [addLeaf(IAlgorithm algorithm, System.Type[] writableTypes)](#addLeaf-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm-com.aspose.ms.System.Type...-) | Adds a leaf algorithm as a child. |
| [addLeafs(IAlgorithm[] algorithms)](#addLeafs-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm...-) | Adds leafs |
| [addTree(TreeRecognizer treeRecognizer)](#addTree-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.TreeRecognizer-) | Adds a tree recognizer as a child |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChilren()](#getChilren--) | Gets children algorithms |
| [getClass()](#getClass--) |  |
| [getOwner()](#getOwner--) | Gets owner algorithm |
| [hashCode()](#hashCode--) |  |
| [makeCycle(ICorrector iterator)](#makeCycle-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ICorrector-) | Makes a cycle at this node owner |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [run(ModelHolder modelHolder)](#run-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-) | Applies the algorithm of tree recognition |
| [setCorrector(ICorrector corrector)](#setCorrector-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ICorrector-) | Sets a corrector for the owner algorithm |
| [setFirstSuccessOnly(IAlgorithm isFirstSuccessOnly)](#setFirstSuccessOnly-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm-) | If set true, if one of algorithms at current level is succesfull, next algorithms from this level will not be applied |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TreeRecognizer(IAlgorithm ownerAlgorithm, System.Type[] writableType) {#TreeRecognizer-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm-com.aspose.ms.System.Type...-}
```
public TreeRecognizer(IAlgorithm ownerAlgorithm, System.Type[] writableType)
```


Initializes a new instance of the [TreeRecognizer](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/treerecognizer) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerAlgorithm | [IAlgorithm](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm) | First algorithm, which will be applied before leafs. |
| writableType | com.aspose.ms.System.Type[] | Algorithm can rewrite this types |

### TreeRecognizer() {#TreeRecognizer--}
```
public TreeRecognizer()
```


Initializes a new instance of the [TreeRecognizer](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/treerecognizer) class without owner algorithm

### _firstSuccessOnly {#-firstSuccessOnly}
```
public IAlgorithm _firstSuccessOnly
```


If one of algorithms at current level is succesfull, next algorithms from this level will not be applied

### addCreateTree() {#addCreateTree--}
```
public final TreeRecognizer addCreateTree()
```


Creates a tree recognizer(without owner algorithm) and adds it as a child

**Returns:**
[TreeRecognizer](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/treerecognizer)
### addCreateTree(IAlgorithm algorithm) {#addCreateTree-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm-}
```
public final TreeRecognizer addCreateTree(IAlgorithm algorithm)
```


Creates a tree recognizer with owner algorithm. Adds created recognizer as a child

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| algorithm | [IAlgorithm](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm) | Owner algorithm for a tree reconizer |

**Returns:**
[TreeRecognizer](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/treerecognizer) - Created tree recognizer
### addLeaf(IAlgorithm algorithm, System.Type[] writableTypes) {#addLeaf-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm-com.aspose.ms.System.Type...-}
```
public final void addLeaf(IAlgorithm algorithm, System.Type[] writableTypes)
```


Adds a leaf algorithm as a child.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| algorithm | [IAlgorithm](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm) | Leaf algorithm |
| writableTypes | com.aspose.ms.System.Type[] | Algorithm can rewrite this types |

### addLeafs(IAlgorithm[] algorithms) {#addLeafs-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm...-}
```
public final TreeRecognizer addLeafs(IAlgorithm[] algorithms)
```


Adds leafs

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| algorithms | [IAlgorithm\[\]](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm) | An array of algorithms |

**Returns:**
[TreeRecognizer](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/treerecognizer) - This
### addTree(TreeRecognizer treeRecognizer) {#addTree-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.TreeRecognizer-}
```
public final void addTree(TreeRecognizer treeRecognizer)
```


Adds a tree recognizer as a child

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| treeRecognizer | [TreeRecognizer](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/treerecognizer) | A tree recognizer |

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
### getChilren() {#getChilren--}
```
public final System.Collections.Generic.List<BaseRecognizer> getChilren()
```


Gets children algorithms

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - Children algorithms
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOwner() {#getOwner--}
```
public final LeafRecognizer getOwner()
```


Gets owner algorithm

**Returns:**
com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.LeafRecognizer - Owner algorithm
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### makeCycle(ICorrector iterator) {#makeCycle-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ICorrector-}
```
public final TreeRecognizer makeCycle(ICorrector iterator)
```


Makes a cycle at this node owner

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| iterator | [ICorrector](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/icorrector) | An iterator for a cycle |

**Returns:**
[TreeRecognizer](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/treerecognizer) - This
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### run(ModelHolder modelHolder) {#run-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-}
```
public boolean run(ModelHolder modelHolder)
```


Applies the algorithm of tree recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modelHolder | [ModelHolder](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder) | Model holder. Contains input and output models for algorithms |

**Returns:**
boolean - Is succesfully applied and got a result
### setCorrector(ICorrector corrector) {#setCorrector-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ICorrector-}
```
public final void setCorrector(ICorrector corrector)
```


Sets a corrector for the owner algorithm

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| corrector | [ICorrector](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/icorrector) |  |

### setFirstSuccessOnly(IAlgorithm isFirstSuccessOnly) {#setFirstSuccessOnly-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm-}
```
public final void setFirstSuccessOnly(IAlgorithm isFirstSuccessOnly)
```


If set true, if one of algorithms at current level is succesfull, next algorithms from this level will not be applied

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isFirstSuccessOnly | [IAlgorithm](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm) | Is first success only |

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

