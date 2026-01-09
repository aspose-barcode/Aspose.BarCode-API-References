---
title:  method
linktitle: SetLicense
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Licenses the library in C++.'
type: docs
weight: 200
url: /cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


Licenses the library.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | System::String | Can be a full or short file name or name of an embedded resource. |
## Remarks


Tries to find the license in the following locations:

1. Explicit path.

2. The folder that contains the **Aspose** component assembly.

3. The folder that contains the client's calling assembly.

4. The folder that contains the entry (startup) assembly.

5. An embedded resource in the client's calling assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit path.

2. An embedded resource in the client's calling assembly.

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. 
```cpp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```


## See Also

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Licenses the library.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | A stream that contains the license. |
## Remarks



Use this method to load a license from a stream.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## See Also

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
