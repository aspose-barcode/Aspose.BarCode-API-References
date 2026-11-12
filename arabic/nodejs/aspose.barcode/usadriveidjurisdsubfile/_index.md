---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة للحقول الخاصة بالاختصاص القضائي لرخصة القيادة الأمريكية."
type: docs
weight: 950
url: /ar/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

فئة للحقول الخاصة بالاختصاص القضائي لرخصة القيادة الأمريكية.

```js
new USADriveIdJurisdSubfile()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | يضيف DataElement جديد بالمعرف والقيمة المحددين، أو يستبدل العنصر الموجود إذا كان هناك إدخال بنفس |
| [addOrReplaceNode(node)](#addorreplacenode) | يضيف DataElement جديد أو يستبدله إذا كان ElementID موجودًا بالفعل. |
| [clear()](#clear) | يمسح جميع عناصر البيانات |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | يبحث عن عنصر البيانات بواسطة معرف مكوّن من 3 أحرف |
| [get(indexOrId)](#get) | يحصل على عنصر البيانات بواسطة فهرسه أو معرفه المكوّن من 3 أحرف. |
| [insert(index, node)](#insert) | يدرج DataElement المحدد في الفهرس المعطى. إذا كان هناك DataElement بنفس ElementID موجود بالفعل، فسيتم b |
| [remove(indexOrId)](#remove) | يحاول إزالة عنصر بواسطة فهرسه أو معرفه المكوّن من 3 أحرف. |
| [set(indexOrId, value)](#set) | يضبط عنصر البيانات بواسطة فهرسه أو معرفه المكوّن من 3 أحرف. |
| [size()](#size) | يرجع عدد عناصر البيانات |

### addOrReplace(id, value) {#addorreplace}

يضيف DataElement جديد بالمعرف والقيمة المحددين، أو يستبدل العنصر الموجود إذا كان هناك إدخال بنفس ElementID موجود بالفعل.

| معامل | الوصف |
| --- | --- |
| المعرّف | معرّف مكوّن من 3 أحرف يحدد بشكل فريد عنصر البيانات المتعلق بالاختصاص. |
| القيمة | قيمة النص المعينة لعنصر البيانات؛ هذه القيمة ستحل محل القيمة الموجودة إذا كان العنصر موجودًا بالفعل. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

يضيف DataElement جديد أو يستبدله إذا كان ElementID موجودًا بالفعل.

| معامل | الوصف |
| --- | --- |
| العقدة | DataElement للإضافة |

**Returns:** Added/replaced data element

### clear() {#clear}

يمسح جميع عناصر البيانات

### findDataElement(id, isOpenOrCreate) {#finddataelement}

يبحث عن عنصر البيانات بواسطة معرف مكوّن من 3 أحرف

| معامل | الوصف |
| --- | --- |
| المعرّف | معرّف مكوّن من 3 أحرف |
| isOpenOrCreate | إذا كان صحيحًا، سيتم إنشاؤه إذا لم يُعثر عليه |

**Returns:** Found data element

### get(indexOrId) {#get}

يحصل على عنصر البيانات بواسطة فهرسه أو معرفه المكوّن من 3 أحرف.

| معامل | نوع | الوصف |
| --- | --- | --- |
| indexOrId | عدد\ | سلسلة | فهرس صحيح أو معرف عنصر مكوّن من 3 أحرف. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

يدرج DataElement المحدد في الفهرس المعطى. إذا كان هناك DataElement بنفس ElementID موجود بالفعل، فسيتم استبداله.

| معامل | الوصف |
| --- | --- |
| الفهرس | الفهرس الصفري الذي يجب إدراج العنصر عنده. |
| العقدة | مثيل DataElement لإدراجه أو استبداله في الموضع المستهدف. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

يحاول إزالة عنصر بواسطة فهرسه أو معرفه المكوّن من 3 أحرف.

| معامل | نوع | الوصف |
| --- | --- | --- |
| indexOrId | عدد\ | سلسلة | فهرس صحيح أو معرف عنصر مكوّن من 3 أحرف. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

يضبط عنصر البيانات بواسطة فهرسه أو معرفه المكوّن من 3 أحرف.

| معامل | نوع | الوصف |
| --- | --- | --- |
| indexOrId | عدد\ | سلسلة | فهرس صحيح أو معرف عنصر مكوّن من 3 أحرف. |
| القيمة | DataElement | عنصر البيانات لتعيينه. |

### size() {#size}

يرجع عدد عناصر البيانات
