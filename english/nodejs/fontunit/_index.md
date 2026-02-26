---
title: FontUnit Class
linktitle: FontUnit
articleTitle: FontUnit
second_title: Aspose.BarCode for Node.js via Java
description: Defines a particular format for text, including font face, size, and style attributes where size in Unit value property.
type: docs
weight: 690
url: /nodejs/fontunit/
---
## FontUnit class

Defines a particular format for text, including font face, size, and style attributes where size in Unit value property.

```javascript
public class FontUnit : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [FontUnit](./fontunit/#constructor)(*object*) | Initializes a new instance of the FontUnit class. |

## Methods

| Name | Description |
| --- | --- |
| [getFamilyName](./getfamilyname/) | Gets the face name of this Font. |
| [getSize](./getsize/) | Gets size of this FontUnit in Unit value. |
| [getStyle](./getstyle/) | Gets style information for this FontUnit. |
| [init](./init/) |  |
| [initFontUnit](./initfontunit/)(*object*) |  |
| [setFamilyName](./setfamilyname/)(*object*) | Sets the face name of this Font. |
| [setStyle](./setstyle/)(*object*) | Sets style information for this FontUnit. |

## Fields

| Name | Description |
| --- | --- |
| [_size](./_size/) |  |

## Examples

This sample shows how to create and save a BarCode image.

```javascript
let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
generator.getParameters().getCaptionAbove().setText("CAPTION ABOOVE");
generator.getParameters().getCaptionAbove().setVisible(true);
generator.getParameters().getCaptionAbove().getFont().setStyle(FontStyle.ITALIC);
generator.getParameters().getCaptionAbove().getFont().getSize().setPoint(25);
```

### See Also

* assembly [Aspose.BarCode](../)

