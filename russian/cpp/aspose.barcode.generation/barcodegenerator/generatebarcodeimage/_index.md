---
title: "method"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Сгенерировать изображение штрихкода с текущими настройками в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


Сгенерировать изображение штрихкода с текущими настройками.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

Изображение штрихкода. См. [Bitmap](../).
## Примечания



Этот пример показывает, как создать и сохранить изображение штрих‑кода.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## См. также

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
