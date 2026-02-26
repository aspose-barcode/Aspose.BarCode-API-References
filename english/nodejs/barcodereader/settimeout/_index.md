---
title: "BarCodeReader.setTimeout"
linktitle: "setTimeout"
articleTitle: "setTimeout"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Sets the timeout of recognition process in milliseconds."
type: docs
weight: 110
url: /nodejs/barcodereader/settimeout/
---
## setTimeout(object) {#settimeout}

Sets the timeout of recognition process in milliseconds.

```javascript
setTimeout(value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | object | The timeout. |

## Examples

```javascript
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode CodeText: " + result.getCodeText());
}
```

### See Also

* class [BarCodeReader](../)
* assembly [Aspose.BarCode](../../)

