---
title: "QrExtCodetextBuilder Class"
linktitle: "QrExtCodetextBuilder"
articleTitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java"
description: ""
type: docs
weight: 710
url: /nodejs/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

//Example how to generate FNC1 first position for Extended Mode //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); lTextBuilder.addFNC1FirstPosition(); lTextBuilder.addPlainCodetext("000%89%%0"); lTextBuilder.addFNC1GroupSeparator(); lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext();

```javascript
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/#constructor) | Initializes a new instance of the QrExtCodetextBuilder class. |

## Methods

| Name | Description |
| --- | --- |
| [addECICodetext](../extcodetextbuilder/addecicodetext/)(*object, object*) | Adds codetext with Extended Channel Identifier. *(Inherited from ExtCodetextBuilder)* |
| [addFNC1FirstPosition](./addfnc1firstposition/) | Adds FNC1 in first position to the extended codetext items. |
| [addFNC1GroupSeparator](./addfnc1groupseparator/) | Adds Group Separator (GS - '\\u001D') to the extended codetext items. |
| [addFNC1SecondPosition](./addfnc1secondposition/)(*object*) | Adds FNC1 in second position to the extended codetext items. |
| [addPlainCodetext](../extcodetextbuilder/addplaincodetext/)(*object*) | Adds plain codetext to the extended codetext items. *(Inherited from ExtCodetextBuilder)* |
| [clear](../extcodetextbuilder/clear/) | Clears extended codetext items. *(Inherited from ExtCodetextBuilder)* |
| [getExtendedCodetext](./getextendedcodetext/) | Generates Extended codetext from the extended codetext list. |
| [init](./init/) |  |
| [javaClassName](./javaclassname/) |  |

## Examples

```javascript
//Example how to generate FNC1 first position for Extended Mode
//create codetext
QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder();
lTextBuilder.addFNC1FirstPosition();
lTextBuilder.addPlainCodetext("000%89%%0");
lTextBuilder.addFNC1GroupSeparator();
lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
//generate codetext
String lCodetext = lTextBuilder.getExtendedCodetext();
```

```javascript
//Example how to generate FNC1 second position for Extended Mode
//create codetext
QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder();
lTextBuilder.addFNC1SecondPosition("12");
lTextBuilder.addPlainCodetext("TRUE3456");
//generate codetext
String lCodetext = lTextBuilder.getExtendedCodetext();
```

```javascript
//Example how to generate multi ECI mode for Extended Mode
//create codetext
QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder();
lTextBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
lTextBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
lTextBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
lTextBuilder.addPlainCodetext("t\\e\\\\st");
//generate codetext
String lCodetext = lTextBuilder.getExtendedCodetext();
```

### See Also

* assembly [Aspose.BarCode](../)

