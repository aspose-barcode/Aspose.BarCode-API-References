---
title: "HanXinExtCodetextBuilder Class"
linktitle: "HanXinExtCodetextBuilder"
articleTitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java"
description: ""
type: docs
weight: 780
url: /nodejs/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

//Extended codetext mode //create codetext let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //generate codetext let str = codeTextBuilder.getExtendedCodetext(); //generate let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```javascript
public class HanXinExtCodetextBuilder : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/#constructor) | Initializes a new instance of the HanXinExtCodetextBuilder class. |

## Methods

| Name | Description |
| --- | --- |
| [addAuto](./addauto/)(*object*) | Adds codetext fragment in Auto mode. |
| [addBinary](./addbinary/)(*object*) | Adds codetext fragment in Binary mode. |
| [addCommonChineseRegionOne](./addcommonchineseregionone/)(*object*) | Adds codetext fragment in Common Chinese Region One mode. |
| [addCommonChineseRegionTwo](./addcommonchineseregiontwo/)(*object*) | Adds codetext fragment in Common Chinese Region Two mode. |
| [addECI](./addeci/)(*object, object*) | Adds codetext fragment in ECI mode. |
| [addGB18030FourByte](./addgb18030fourbyte/)(*object*) | Adds codetext fragment in GB18030 Four Byte mode. |
| [addGB18030TwoByte](./addgb18030twobyte/)(*object*) | Adds codetext fragment in GB18030 Two Byte mode. |
| [addGS1](./addgs1/)(*object*) | Adds codetext fragment in GS1 mode. |
| [addNumeric](./addnumeric/)(*object*) | Adds codetext fragment in Numeric mode. |
| [addText](./addtext/)(*object*) | Adds codetext fragment in Text mode. |
| [addURI](./adduri/)(*object*) | Adds codetext fragment in URI mode. |
| [addUnicode](./addunicode/)(*object*) | Adds codetext fragment in Unicode mode. |
| [getExtendedCodetext](./getextendedcodetext/) | Returns codetext from Extended mode codetext builder. |
| [init](./init/) |  |

## Fields

| Name | Description |
| --- | --- |
| [JAVA_CLASS_NAME](./java_class_name/) |  |

### See Also

* assembly [Aspose.BarCode](../)

