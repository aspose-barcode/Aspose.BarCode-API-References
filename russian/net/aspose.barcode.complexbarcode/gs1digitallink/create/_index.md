---
title: "GS1DigitalLink.Create"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Метод GS1DigitalLink. Создаёт GS1 Digital Link, копируя все элементы из GS1 codetext и выбирая единственный доступный первичный ключ"
type: docs
weight: 20
url: /ru/net/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## Create(string, GS1Codetext) {#create}

Создаёт GS1 Digital Link, копируя все элементы из кодового текста GS1 и выбирая единственный доступный первичный ключ.

```csharp
public static GS1DigitalLink Create(string uriStem, GS1Codetext codetext)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uriStem | String | Абсолютный префикс HTTP или HTTPS URI перед первичным ключом. |
| codetext | GS1Codetext | GS1‑текст кода, элементы которого скопированы. |

### Возвращаемое значение

GS1 Digital Link, содержащий скопированные элементы.

### См. также

* class [GS1Codetext](../../gs1codetext/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)

---

## Create(string, GS1Codetext, string) {#create_1}

Создаёт GS1 Digital Link, копируя все элементы из кодового текста GS1 и используя указанный первичный ключ.

```csharp
public static GS1DigitalLink Create(string uriStem, GS1Codetext codetext, 
    string primaryApplicationIdentifier)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uriStem | String | Абсолютный префикс HTTP или HTTPS URI перед первичным ключом. |
| codetext | GS1Codetext | GS1‑текст кода, элементы которого скопированы. |
| primaryApplicationIdentifier | String | Основной ключ AI. |

### Возвращаемое значение

GS1 Digital Link, содержащий скопированные элементы.

### См. также

* class [GS1Codetext](../../gs1codetext/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


