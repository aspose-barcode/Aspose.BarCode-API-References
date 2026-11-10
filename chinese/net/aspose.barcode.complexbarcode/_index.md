---
title: "Aspose.BarCode.ComplexBarcode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode 包含用于实现复杂条码生成函数的一般类"
type: docs
weight: 40
url: /zh/net/aspose.barcode.complexbarcode/
---
该 **Aspose.BarCode.ComplexBarcode** 包含用于实现复杂 BarCode 生成函数的一般类。

## 类

| 类 | 描述 |
| --- | --- |
| [Address](./address/) | 债权人或债务人的地址。 |
| [AlternativeScheme](./alternativescheme/) | 替代支付方案说明 |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator 用于后端复杂条码（例如 SwissQR）图像生成。 |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader 将代码文本解码为指定的复杂条码类型。 |
| [GS1Codetext](./gs1codetext/) | 表示用于编码和解码的 GS1 代码文本，作为 Application Identifier 元素的有序序列。保留源顺序和重复的 Application Identifier。括号表示形式为 (AI)value(AI)value。值内部的字面左括号 '(' 必须写成 \(；这是唯一支持的转义序列。值内部的右括号 ')' 无需转义。 |
| [GS1DigitalLink](./gs1digitallink/) | 表示用于编码和解码的 GS1 Digital Link 代码文本，作为 Application Identifier 元素的有序序列。保留源顺序和重复的 Application Identifier。构建的代码文本是未压缩的 GS1 Digital Link URI。解析时会忽略非 GS1 的查询参数和 URI 片段。 |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | 用于编码和解码嵌入 HIBC LIC 代码中的文本的类，该代码存储主数据和次要数据。 |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | 用于对嵌入在 HIBC LIC 代码中的文本进行编码和解码的基类. |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | 用于对嵌入在 HIBC LIC 代码中存储主数据的文本进行编码和解码的类. |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | 用于对嵌入在 HIBC LIC 代码中存储次要数据的文本进行编码和解码的类. |
| [HIBCPASCodetext](./hibcpascodetext/) | 用于对嵌入在 HIBC PAS 代码中的文本进行编码和解码的类. |
| [HIBCPASRecord](./hibcpasrecord/) | 用于存储 HIBC PAS 记录的类. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | 用于对嵌入在 Royal Mail 2D Mailmark 代码中的文本进行编码和解码的类. |
| [MailmarkCodetext](./mailmarkcodetext/) | 用于对嵌入在 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类. |
| [MaxiCodeCodetext](./maxicodecodetext/) | 用于对嵌入在 MaxiCode 代码中的文本进行编码和解码的基类. |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | 用于对嵌入在 MaxiCode 代码中模式 2 的文本进行编码和解码的类. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | 用于对嵌入在 MaxiCode 代码中模式 3 的文本进行编码和解码的类. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | 用于对 MaxiCode 条码的第二消息进行编码和解码的基类. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | 用于对 MaxiCode 代码文本在模式 4、5 和 6 中进行编码和解码的类. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | 用于对 MaxiCode 条码的标准第二消息进行编码和解码的类. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | 用于对嵌入在 MaxiCode 代码中模式 2 和 3 的文本进行编码和解码的基类. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | 用于对 MaxiCode 条码的结构化第二消息进行编码和解码的类. |
| [PrimaryData](./primarydata/) | 用于存储 HIBC LIC 主数据的类. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | 用于存储 HIBC LIC 次要和附加数据的类. |
| [SwissQRBill](./swissqrbill/) | SwissQR 账单数据 |
| [SwissQRCodetext](./swissqrcodetext/) | 用于对嵌入在 SwissQR 代码中的文本进行编码和解码的类. |
| [USADriveIdCodetext](./usadriveidcodetext/) | 用于对嵌入在美国驾照 PDF417 代码中的文本进行编码和解码的类. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | 用于美国驾照（USA DL）特定司法辖区字段的类 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IComplexCodetext](./icomplexcodetext/) | 用于与 ComplexBarcodeGenerator 一起使用的复杂代码文本的接口. |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AddressType](./addresstype/) | 地址类型 |
| [HIBCLICDateFormat](./hibclicdateformat/) | 指定 HIBC LIC 的不同日期格式类型. |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | HIBC PAS 数据位置类型. |
| [HIBCPASDataType](./hibcpasdatatype/) | HIBC PAS 记录的数据类型。 |
| [Mailmark2DType](./mailmark2dtype/) | 2D Mailmark 类型定义 Data Matrix 条码的大小 |
| [USADriveIdCountry](./usadriveidcountry/) | 美国驾驶执照中用于国家识别的枚举 |
| [USADriveIdEyeColor](./usadriveideyecolor/) | 美国驾驶执照中用于眼睛颜色的枚举 |
| [USADriveIdHairColor](./usadriveidhaircolor/) | 美国驾驶执照中用于发色的枚举 |
| [USADriveIdSex](./usadriveidsex/) | 美国驾驶执照中用于性别字段的枚举 |


