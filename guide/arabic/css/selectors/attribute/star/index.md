---
title: Star
localeTitle: نجمة
---
## نجمة

يتم استخدام محدد السمة Star CSS أو \* لتحديد السمات التي تحتوي على قيمة محددة.

#### مثال

إذا كنت تريد البحث في جميع روابط الربط التي تحتوي على "رمز" في أي مكان في قيمة عنوان URL وجعلها صفراء ، فيمكنك إجراء ذلك على النحو التالي:

 `a[href*="code"] { 
   color: yellow; 
 } 
`