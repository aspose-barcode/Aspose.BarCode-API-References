---
title: "Aspose::BarCode::Generation::HanXinParameters class"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::HanXinParameters class. Han Xin-parameters in C++."
type: docs
weight: 2900
url: /nl/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Han Xin-parameters.

```cpp
class HanXinParameters : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bevat alle bekende charset-coderingen. |
| [get_EncodeMode](./get_encodemode/)() const | HanXin-coderingmodus. Standaardwaarde: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | Niveau van Reed-Solomon-foutcorrectie voor Han Xin-barcode. Van laag naar hoog: L1, L2, L3, L4. zie ErrorLevel. |
| [get_Version](./get_version/)() const | Versie van HanXin-code. Van Version01 tot Version84 voor Han Xin-code. Standaardwaarde is [Version.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bevat alle bekende charset-coderingen. |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | HanXin-coderingmodus. Standaardwaarde: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Niveau van Reed-Solomon-foutcorrectie voor Han Xin-barcode. Van laag naar hoog: L1, L2, L3, L4. zie ErrorLevel. |
| [set_Version](./set_version/)(HanXinVersion) | Versie van HanXin-code. Van Version01 tot Version84 voor Han Xin-code. Standaardwaarde is [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [HanXinParameters](./). |
## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
