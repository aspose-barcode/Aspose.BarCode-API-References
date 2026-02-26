---
title: "MaxiCodeCodetextMode3 Class"
linktitle: "MaxiCodeCodetextMode3"
articleTitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Class for encoding and decoding the text embedded in the MaxiCode code for modes 3. This sample shows how to encode and decode MaxiCode codetext for mode 3."
type: docs
weight: 200
url: /nodejs/maxicodecodetextmode3/
---
## MaxiCodeCodetextMode3 class

Class for encoding and decoding the text embedded in the MaxiCode code for modes 3. This sample shows how to encode and decode MaxiCode codetext for mode 3.

```javascript
public class MaxiCodeCodetextMode3 : MaxiCodeStructuredCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/#constructor) | Initializes a new instance of the MaxiCodeCodetextMode3 class. |

## Methods

| Name | Description |
| --- | --- |
| [construct](./construct/)(*object*) |  |
| [equals](../maxicodestructuredcodetext/equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified [`MaxiCodeStructuredCodetext`](..//maxicodestructuredcodetext/) value. *(Inherited from MaxiCodeStructuredCodetext)* |
| [getBarcodeType](../maxicodecodetext/getbarcodetype/) | Gets barcode type. *(Inherited from MaxiCodeCodetext)* |
| [getConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/) | Constructs codetext. *(Inherited from MaxiCodeStructuredCodetext)* |
| [getCountryCode](../maxicodestructuredcodetext/getcountrycode/) | Identifies 3 digit country code. *(Inherited from MaxiCodeStructuredCodetext)* |
| [getECIEncoding](../maxicodecodetext/geteciencoding/) | Gets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. *(Inherited from MaxiCodeCodetext)* |
| [getEncodeMode](../maxicodecodetext/getencodemode/) | Gets a MaxiCode encode mode. Default value: Auto. *(Inherited from MaxiCodeCodetext)* |
| [getHashCode](../maxicodestructuredcodetext/gethashcode/) | Returns the hash code for this instance. *(Inherited from MaxiCodeStructuredCodetext)* |
| [getMaxiCodeEncodeMode](../maxicodecodetext/getmaxicodeencodemode/) | Gets a MaxiCode encode mode. *(Inherited from MaxiCodeCodetext)* |
| [getMode](./getmode/) | Gets MaxiCode mode. |
| [getPostalCode](../maxicodestructuredcodetext/getpostalcode/) | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. *(Inherited from MaxiCodeStructuredCodetext)* |
| [getSecondMessage](../maxicodestructuredcodetext/getsecondmessage/) | Identifies second message of the barcode. *(Inherited from MaxiCodeStructuredCodetext)* |
| [getServiceCategory](../maxicodestructuredcodetext/getservicecategory/) | Identifies 3 digit service category. *(Inherited from MaxiCodeStructuredCodetext)* |
| [init](./init/) |  |
| [initFromString](../maxicodestructuredcodetext/initfromstring/)(*object*) | Initializes instance from constructed codetext. *(Inherited from MaxiCodeStructuredCodetext)* |
| [setCountryCode](../maxicodestructuredcodetext/setcountrycode/)(*object*) | Identifies 3 digit country code. *(Inherited from MaxiCodeStructuredCodetext)* |
| [setECIEncoding](../maxicodecodetext/seteciencoding/)(*object*) | Sets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. *(Inherited from MaxiCodeCodetext)* |
| [setEncodeMode](../maxicodecodetext/setencodemode/)(*object*) | Sets a MaxiCode encode mode. Default value: Auto. *(Inherited from MaxiCodeCodetext)* |
| [setMaxiCodeEncodeMode](../maxicodecodetext/setmaxicodeencodemode/)(*object*) | Sets a MaxiCode encode mode. *(Inherited from MaxiCodeCodetext)* |
| [setPostalCode](../maxicodestructuredcodetext/setpostalcode/)(*object*) | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. *(Inherited from MaxiCodeStructuredCodetext)* |
| [setSecondMessage](../maxicodestructuredcodetext/setsecondmessage/)(*object*) | Identifies second message of the barcode. *(Inherited from MaxiCodeStructuredCodetext)* |
| [setServiceCategory](../maxicodestructuredcodetext/setservicecategory/)(*object*) | Identifies 3 digit service category. *(Inherited from MaxiCodeStructuredCodetext)* |

## Fields

| Name | Description |
| --- | --- |
| [JAVA_CLASS_NAME](./java_class_name/) |  |
| [maxiCodeSecondMessage](../maxicodestructuredcodetext/maxicodesecondmessage/) | *(Inherited from MaxiCodeStructuredCodetext)* |

## Examples

```javascript
//Mode 3 with standart second message
let maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.setPostalCode("B1050");
maxiCodeCodetext.setCountryCode(056);
maxiCodeCodetext.setServiceCategory(999);
let MaxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
MaxiCodeStandardSecondMessage.setMessage("Test message");
maxiCodeCodetext.setSecondMessage(MaxiCodeStandardSecondMessage);
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

```javascript
//Mode 3 with structured second message
let maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.setPostalCode("B1050");
maxiCodeCodetext.setCountryCode(056);
maxiCodeCodetext.setServiceCategory(999);
let maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.add("PITTSBURGH");
maxiCodeStructuredSecondMessage.add("PA");
maxiCodeStructuredSecondMessage.setYear(99);
maxiCodeCodetext.setSecondMessage(maxiCodeStructuredSecondMessage);
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

```javascript
//Decoding raw codetext with standart second message
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
if (resultMaxiCodeCodetext instanceOf MaxiCodeCodetextMode3)
{
let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
if (maxiCodeStructuredCodetext.getSecondMessage() instanceOf MaxiCodeStandardSecondMessage)
{
let secondMessage = maxiCodeStructuredCodetext.getSecondMessage();
console.log("Message: " + secondMessage.getMessage());
}
}
}
```

```javascript
//Decoding raw codetext with structured second message
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
if (resultMaxiCodeCodetext instanceOf MaxiCodeCodetextMode3)
{
let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
if (maxiCodeStructuredCodetext.getSecondMessage() instanceOf MaxiCodeStructuredSecondMessage)
{
let secondMessage = maxiCodeStructuredCodetext.getSecondMessage();
console.log("Message:");
let identifiers = secondMessage.getIdentifiers();
for(let i = 0; i < identifiers.length; i++)
{
let identifier = identifiers[i];
console.log(identifier);
}
}
}
}
```

### See Also

* assembly [Aspose.BarCode](../)

