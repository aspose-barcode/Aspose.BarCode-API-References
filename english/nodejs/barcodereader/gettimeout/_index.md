---
title: BarCodeReader.getTimeout
linktitle: getTimeout
articleTitle: getTimeout
second_title: Aspose.BarCode for Node.js via Java
description: Gets the timeout of recognition process in milliseconds.
type: docs
weight: 100
url: /nodejs/barcodereader/gettimeout/
---
## getTimeout() {#gettimeout}

Gets the timeout of recognition process in milliseconds.

```javascript
getTimeout()
```

### Return Value

The

timeout.

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

