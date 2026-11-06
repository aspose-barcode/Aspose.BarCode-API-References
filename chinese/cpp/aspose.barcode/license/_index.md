---
title: "Aspose::BarCode::License 类"
linktitle: "许可证"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::License 类。提供在 C++ 中为组件授权的方法。"
type: docs
weight: 300
url: /zh/cpp/aspose.barcode/license/
---
## License class


提供对组件授权的方法。

```cpp
class License : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [License](./license/)() | 初始化此类的新实例。 |
| [SetLicense](./setlicense/)(System::String) | 为库授权。 |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | 为库授权。 |
## 备注


在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
@endverbatim
```

## 另见

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
