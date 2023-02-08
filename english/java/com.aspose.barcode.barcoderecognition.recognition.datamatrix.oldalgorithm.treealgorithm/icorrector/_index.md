---
title: ICorrector
second_title: Aspose.BarCode for Java API Reference
description: An interface for correctors
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/icorrector/
---```
public interface ICorrector
```

An interface for correctors
## Methods

| Method | Description |
| --- | --- |
| [modifies(ModelHolder model)](#modifies-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-) | Modifies a context |
### modifies(ModelHolder model) {#modifies-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-}
```
public abstract boolean modifies(ModelHolder model)
```


Modifies a context

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | [ModelHolder](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder) | Model holder |

**Returns:**
boolean - True - if can be modified again. Else false.
