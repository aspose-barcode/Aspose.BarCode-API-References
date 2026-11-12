---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "USA DL के लिए अधिकार क्षेत्र विशिष्ट फ़ील्ड्स की क्लास।"
type: docs
weight: 950
url: /hi/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

USA DL के लिए अधिकार क्षेत्र विशिष्ट फ़ील्ड्स की क्लास।

```js
new USADriveIdJurisdSubfile()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | एक नया DataElement निर्दिष्ट पहचानकर्ता और मान के साथ जोड़ता है, या मौजूदा तत्व को प्रतिस्थापित करता है यदि प्रविष्टि के साथ sa |
| [addOrReplaceNode(node)](#addorreplacenode) | यदि ElementID पहले से मौजूद है तो नया DataElement जोड़ता है या उसे प्रतिस्थापित करता है। |
| [clear()](#clear) | सभी डेटा तत्वों को साफ़ करता है |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | 3-अक्षर के id द्वारा डेटा तत्व की खोज करता है |
| [get(indexOrId)](#get) | डेटा तत्व को उसके अनुक्रमणिका या 3-अक्षर ID द्वारा प्राप्त करता है। |
| [insert(index, node)](#insert) | निर्दिष्ट DataElement को दिए गए अनुक्रमणिका पर सम्मिलित करता है। यदि समान ElementID वाला DataElement पहले से मौजूद है, तो यह b |
| [remove(indexOrId)](#remove) | उसके अनुक्रमणिका या 3-अक्षर ID द्वारा तत्व को हटाने का प्रयास करता है। |
| [set(indexOrId, value)](#set) | उसके अनुक्रमणिका या 3-अक्षर ID द्वारा डेटा तत्व सेट करता है। |
| [size()](#size) | डेटा तत्वों की संख्या लौटाता है |

### addOrReplace(id, value) {#addorreplace}

निर्दिष्ट पहचानकर्ता और मान के साथ एक नया DataElement जोड़ता है, या यदि समान ElementID वाली प्रविष्टि पहले से मौजूद है तो मौजूदा तत्व को प्रतिस्थापित करता है।

| पैरामीटर | विवरण |
| --- | --- |
| आईडी | एक 3-अक्षर पहचानकर्ता जो अधिकार-सम्बंधित डेटा तत्व को विशिष्ट रूप से निर्दिष्ट करता है। |
| मान | डेटा तत्व को सौंपा गया पाठ मान; यदि तत्व पहले से मौजूद है तो यह मान मौजूदा को अधिलेखित कर देगा। |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

यदि ElementID पहले से मौजूद है तो नया DataElement जोड़ता है या उसे प्रतिस्थापित करता है।

| पैरामीटर | विवरण |
| --- | --- |
| नोड | जोड़ने के लिए DataElement |

**Returns:** Added/replaced data element

### clear() {#clear}

सभी डेटा तत्वों को साफ़ करता है

### findDataElement(id, isOpenOrCreate) {#finddataelement}

3-अक्षर के id द्वारा डेटा तत्व की खोज करता है

| पैरामीटर | विवरण |
| --- | --- |
| आईडी | 3-अक्षर आईडी |
| isOpenOrCreate | यदि सत्य है, तो यह नहीं मिलने पर बनाया जाएगा |

**Returns:** Found data element

### get(indexOrId) {#get}

डेटा तत्व को उसके अनुक्रमणिका या 3-अक्षर ID द्वारा प्राप्त करता है।

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| indexOrId | संख्या\ | स्ट्रिंग | पूर्णांक अनुक्रमणिका या 3-अक्षर तत्व आईडी। |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

निर्दिष्ट DataElement को दिए गए अनुक्रमणिका पर सम्मिलित करता है। यदि समान ElementID वाला DataElement पहले से मौजूद है, तो इसे प्रतिस्थापित किया जाएगा।

| पैरामीटर | विवरण |
| --- | --- |
| सूचकांक | शून्य-आधारित सूचकांक जहाँ तत्व को सम्मिलित किया जाना चाहिए। |
| नोड | लक्ष्य स्थिति पर सम्मिलित या प्रतिस्थापित करने के लिए DataElement उदाहरण। |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

उसके अनुक्रमणिका या 3-अक्षर ID द्वारा तत्व को हटाने का प्रयास करता है।

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| indexOrId | संख्या\ | स्ट्रिंग | पूर्णांक अनुक्रमणिका या 3-अक्षर तत्व आईडी। |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

उसके अनुक्रमणिका या 3-अक्षर ID द्वारा डेटा तत्व सेट करता है।

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| indexOrId | संख्या\ | स्ट्रिंग | पूर्णांक अनुक्रमणिका या 3-अक्षर तत्व आईडी। |
| मान | DataElement | सेट करने के लिए डेटा तत्व। |

### size() {#size}

डेटा तत्वों की संख्या लौटाता है
