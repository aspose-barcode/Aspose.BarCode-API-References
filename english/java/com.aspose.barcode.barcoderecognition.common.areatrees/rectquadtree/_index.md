---
title: RectQuadTree
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 16
url: /java/com.aspose.barcode.barcoderecognition.common.areatrees/rectquadtree/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.barcoderecognition.common.areatrees.Rect2DTree
```
public class RectQuadTree<T> extends Rect2DTree<T>
```
## Constructors

| Constructor | Description |
| --- | --- |
| [RectQuadTree(int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)](#RectQuadTree-int-int-int-boolean-int-) |  |
| [RectQuadTree(System.Drawing.Rectangle AreaRect, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)](#RectQuadTree-com.aspose.ms.System.Drawing.Rectangle-int-int-int-boolean-int-) |  |
| [RectQuadTree(List<T> ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)](#RectQuadTree-java.util.List-T--int-int-int-boolean-int-) |  |
| [RectQuadTree(T[] ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)](#RectQuadTree-T---int-int-int-boolean-int-) |  |
| [RectQuadTree(List<T> ElementList)](#RectQuadTree-java.util.List-T--) |  |
| [RectQuadTree(T[] ElementList)](#RectQuadTree-T---) |  |
| [RectQuadTree(System.Drawing.Rectangle AreaRect)](#RectQuadTree-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [RectQuadTree()](#RectQuadTree--) |  |
## Methods

| Method | Description |
| --- | --- |
| [add(T Element)](#add-T-) |  |
| [addRange(T[] ElementList)](#addRange-T---) |  |
| [addRange(List<T> ElementList)](#addRange-java.util.List-T--) |  |
| [balanceTree()](#balanceTree--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findElementsIntersectElement(T aElement, int aInflation)](#findElementsIntersectElement-T-int-) |  |
| [findElementsIntersectRect(System.Drawing.Rectangle aRect, int aInflation)](#findElementsIntersectRect-com.aspose.ms.System.Drawing.Rectangle-int-) |  |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) |  |
| [hashCode()](#hashCode--) |  |
| [isElementExist(T aElement)](#isElementExist-T-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(T Element)](#remove-T-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectQuadTree(int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize) {#RectQuadTree-int-int-int-boolean-int-}
```
public RectQuadTree(int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aMaxDataInNode | int |  |
| aMinNodeArea | int |  |
| aMinNodeSide | int |  |
| isBalance | boolean |  |
| InflateSize | int |  |

### RectQuadTree(System.Drawing.Rectangle AreaRect, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize) {#RectQuadTree-com.aspose.ms.System.Drawing.Rectangle-int-int-int-boolean-int-}
```
public RectQuadTree(System.Drawing.Rectangle AreaRect, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| AreaRect | com.aspose.ms.System.Drawing.Rectangle |  |
| aMaxDataInNode | int |  |
| aMinNodeArea | int |  |
| aMinNodeSide | int |  |
| isBalance | boolean |  |
| InflateSize | int |  |

### RectQuadTree(List<T> ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize) {#RectQuadTree-java.util.List-T--int-int-int-boolean-int-}
```
public RectQuadTree(List<T> ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | java.util.List<T> |  |
| aMaxDataInNode | int |  |
| aMinNodeArea | int |  |
| aMinNodeSide | int |  |
| isBalance | boolean |  |
| InflateSize | int |  |

### RectQuadTree(T[] ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize) {#RectQuadTree-T---int-int-int-boolean-int-}
```
public RectQuadTree(T[] ElementList, int aMaxDataInNode, int aMinNodeArea, int aMinNodeSide, boolean isBalance, int InflateSize)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | T[] |  |
| aMaxDataInNode | int |  |
| aMinNodeArea | int |  |
| aMinNodeSide | int |  |
| isBalance | boolean |  |
| InflateSize | int |  |

### RectQuadTree(List<T> ElementList) {#RectQuadTree-java.util.List-T--}
```
public RectQuadTree(List<T> ElementList)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | java.util.List<T> |  |

### RectQuadTree(T[] ElementList) {#RectQuadTree-T---}
```
public RectQuadTree(T[] ElementList)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | T[] |  |

### RectQuadTree(System.Drawing.Rectangle AreaRect) {#RectQuadTree-com.aspose.ms.System.Drawing.Rectangle-}
```
public RectQuadTree(System.Drawing.Rectangle AreaRect)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| AreaRect | com.aspose.ms.System.Drawing.Rectangle |  |

### RectQuadTree() {#RectQuadTree--}
```
public RectQuadTree()
```


### add(T Element) {#add-T-}
```
public void add(T Element)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Element | T |  |

### addRange(T[] ElementList) {#addRange-T---}
```
public void addRange(T[] ElementList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | T[] |  |

### addRange(List<T> ElementList) {#addRange-java.util.List-T--}
```
public void addRange(List<T> ElementList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ElementList | java.util.List<T> |  |

### balanceTree() {#balanceTree--}
```
public void balanceTree()
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
### findElementsIntersectElement(T aElement, int aInflation) {#findElementsIntersectElement-T-int-}
```
public List<T> findElementsIntersectElement(T aElement, int aInflation)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aElement | T |  |
| aInflation | int |  |

**Returns:**
[List](../../java.util/list)
### findElementsIntersectRect(System.Drawing.Rectangle aRect, int aInflation) {#findElementsIntersectRect-com.aspose.ms.System.Drawing.Rectangle-int-}
```
public System.Collections.Generic.List<T> findElementsIntersectRect(System.Drawing.Rectangle aRect, int aInflation)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRect | com.aspose.ms.System.Drawing.Rectangle |  |
| aInflation | int |  |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public List<T> getElements()
```




**Returns:**
[List](../../java.util/list)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isElementExist(T aElement) {#isElementExist-T-}
```
public boolean isElementExist(T aElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aElement | T |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(T Element) {#remove-T-}
```
public void remove(T Element)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Element | T |  |

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

