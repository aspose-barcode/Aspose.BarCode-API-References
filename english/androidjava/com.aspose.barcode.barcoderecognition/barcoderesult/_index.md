---
title: BarCodeResult
second_title: Aspose.BarCode for Android via Java API Reference
description: Stores recognized barcode data like SingleDecodeType type string codetext BarCodeRegionParameters region and other parameters
type: docs
weight: 18
url: /androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Stores recognized barcode data like  SingleDecodeType  type,  string  codetext,  BarCodeRegionParameters  region and other parameters

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Creates a a copy of the  BarCodeResult  class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates a copy of  BarCodeResult  class. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified  BarCodeResult  value. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Gets the encoded code bytes |
| [getCodeText()](#getCodeText--) | Gets the code text |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | Gets the code text with encoding. |
| [getCodeType()](#getCodeType--) | Gets the barcode type |
| [getCodeTypeName()](#getCodeTypeName--) | Gets the name of the barcode type |
| [getConfidence()](#getConfidence--) | Gets recognition confidence level of the recognized barcode |
| [getExtended()](#getExtended--) | Gets extended parameters of recognized barcode |
| [getReadingQuality()](#getReadingQuality--) | Gets the reading quality. |
| [getRegion()](#getRegion--) | Gets the barcode region |
| [hashCode()](#hashCode--) | Returns the hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a human-readable string representation of this  BarCodeResult . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Creates a a copy of the  BarCodeResult  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | An copy  BarCodeResult  instance. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Creates a copy of  BarCodeResult  class.

**Returns:**
java.lang.Object - Returns copy of  BarCodeResult  class.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified  BarCodeResult  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | An  BarCodeResult  value to compare to this instance. |

**Returns:**
boolean -  **true**  if obj has the same value as this instance; otherwise,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


Gets the encoded code bytes

Value: The code bytes of the barcode

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Gets the code text

Value: The code text of the barcode

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
```


Gets the code text with encoding.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | java.nio.charset.Charset | The encoding for codetext. |

**Returns:**
java.lang.String - A string containing recognized code text.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Gets the barcode type

Value: The type information of the recognized barcode

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Gets the name of the barcode type

Value: The type name of the recognized barcode

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


Gets recognition confidence level of the recognized barcode

Value:  BarCodeConfidence.Strong  does not have fakes or misrecognitions,  BarCodeConfidence.Moderate  could sometimes have fakes or incorrect codetext because this confidence level for barcodews with weak cheksum or even without it,  BarCodeConfidence.None  always has incorrect codetext and could be fake recognitions

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Gets extended parameters of recognized barcode

Value: The extended parameters of recognized barcode

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Gets the reading quality. Works for 1D and postal barcodes.

Value: The reading quality percent

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Gets the barcode region

Value: The region of the recognized barcode

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for this instance.

**Returns:**
int - A 32-bit signed integer hash code.
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


Returns a human-readable string representation of this  BarCodeResult .

**Returns:**
java.lang.String - A string that represents this  BarCodeResult .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

