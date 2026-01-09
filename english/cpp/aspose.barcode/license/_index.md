---
title: Aspose::BarCode::License class
linktitle: License
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::License class. Provides methods to license the component in C++.'
type: docs
weight: 300
url: /cpp/aspose.barcode/license/
---
## License class


Provides methods to license the component.

```cpp
class License : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [License](./license/)() | Initializes a new instance of this class. |
| [SetLicense](./setlicense/)(System::String) | Licenses the library. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | Licenses the library. |
## Remarks


In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. 
```cpp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

## See Also

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
