---
title: "method"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。为库在 C++ 中授权。"
type: docs
weight: 200
url: /zh/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


为库授权。

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| licenseName | System::String | 可以是完整或简短的文件名，或嵌入资源的名称。 |
## 备注


尝试在以下位置查找许可证：

1. 明确路径。

2. 包含 **Aspose** 组件程序集的文件夹。

3. 包含客户端调用程序集的文件夹。

4. 包含入口（启动）程序集的文件夹。

5. 客户端调用程序集中的嵌入资源。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明确路径。

2. 客户端调用程序集中的嵌入资源。

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
@endverbatim
```


## 另见

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


为库授权。

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | 包含许可证的流。 |
## 备注



使用此方法从流中加载许可证。


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## 另见

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
