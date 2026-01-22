---
title: Class License
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.License class. Provides methods to license the component
type: docs
weight: 1670
url: /net/aspose.barcode/license/
---
## License class

Provides methods to license the component.

```csharp
public class License
```

## Constructors

| Name | Description |
| --- | --- |
| [License](license/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense)(Stream) | Licenses the library. |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense_1)(string) | Licenses the library. |

## Examples

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### See Also

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


