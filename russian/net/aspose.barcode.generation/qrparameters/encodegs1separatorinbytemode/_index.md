---
title: "QrParameters.EncodeGS1SeparatorInByteMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Свойство QrParameters. Получает или задает значение, указывающее, следует ли кодировать специальные символы GS1 в режиме Byte для штрихкодов QR и RectMicroQR."
type: docs
weight: 30
url: /ru/net/aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/
---
## QrParameters.EncodeGS1SeparatorInByteMode property

Получает или задает значение, указывающее, следует ли специальные символы GS1 кодировать в байтовом режиме для штрихкодов QR и RectMicroQR.

Если false, разделители GS1 могут быть закодированы как '%' в альфа-числовом режиме согласно спецификации QR.

Если true, групповые разделители GS1 кодируются в байтовом режиме как символ 0x1D, а символы '%' также кодируются в байтовом режиме, чтобы сохранить их как данные.

Эта опция может улучшить совместимость с декодерами, ожидающими байтовые групповые разделители GS1, и предотвращает интерпретацию символов данных '%' как разделителей GS1.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### См. также

* class [QrParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


