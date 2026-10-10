# Assuit SciDream — بوابة عباقرة كلية العلوم
# Assuit SciDream — Gateway of Science Talents

## مقدمة عربية
Assuit SciDream هو منصة وتطبيق أندرويد مصمم خصيصًا لطلاب كلية العلوم بجامعة أسيوط، ضمن فريق Dream Team. يهدف المشروع إلى تسهيل الحياة الأكاديمية للطلاب من خلال منصة موحدة تجمع بين الخدمات الدراسية، الإدارية، والجامعية في تجربة بسيطة وواضحة ومريحة.

الهدف الرئيسي هو دعم الطلاب في تنظيم الدراسة، متابعة المواد، التواصل مع الكلية، والاستفادة من الخدمات الذكية مثل المساعد الذكي، نظام الدرجات، والاختبارات الإلكترونية.

## English Overview
Assuit SciDream is a platform and Android application designed for students of the Faculty of Science at Assiut University by the Dream Team. The project aims to simplify university life by bringing academic, administrative, and student services into one unified experience. It helps students manage courses, follow announcements, stay connected to campus life, and benefit from smart features such as an AI assistant, GPA calculator, and online assessments.

---

## المميزات الرئيسية | Key Features

- تسجيل دخول بجوجل مع التوثيق بواسطة بطاقة الطالب
- Google sign-in with student card verification
- مواد وملفات لكل قسم
- Course materials and files for each department
- اختبارات أونلاين
- Online exams
- حاسبة GPA بالنظام المصري
- GPA calculator based on the Egyptian system
- ملاحظات شخصية
- Personal notes
- مساعد ذكي اسمه "قطب" عن اللائحة والمقررات
- Smart assistant named "Qotb" for regulations and courses
- إعلانات الكلية
- Faculty announcements
- جروبات وشات خاص مع الصور، الفيديو، ورسائل صوتية
- Groups and private chat with images, videos, and voice messages
- دورات تدريبية
- Training courses
- نظام تسجيل مواد لقسم الكيمياء الصناعية
- Course registration system for the Industrial Chemistry department
- أماكن المدرجات
- Lecture hall locations
- إشعارات
- Notifications
- لوحة تحكم للإدمن
- Admin dashboard

---

## منصة المشروع | Project Platform

المشروع يتكون من:
- الموقع: React + TanStack Start + Tailwind
- التطبيق: Expo + React Native
- الباك إند: Supabase
- التخزين/الملفات: Backblaze B2

### Stack
- Frontend Web: React + TanStack Start + Tailwind
- Mobile App: Expo + React Native
- Backend: Supabase
- Storage: Backblaze B2

---

## هيكل المشروع | Project Structure

```bash
assuit-scidream/
├── web/                  # الموقع الإلكتروني
├── mobile/               # تطبيق Android/iOS باستخدام Expo + React Native
├── backend/              # إعدادات Supabase أو منطق الخدمة
├── docs/                 # وثائق المشروع
├── README.md             # توثيق المشروع
├── .gitignore
└── package.json
```

> ملاحظة: هذا المشروع يمكن تطويره كـ monorepo يضم الموقع والتطبيق والباك إند بشكل منظم.

---

## تحميل التطبيق | Download App

### رابط التحميل المباشر | Direct Download Link
يمكنك تحميل ملف APK مباشرة من صفحة Releases:

https://github.com/pedoow1/assuit-scidream-app/releases/latest

إذا كان لديك ملف APK معين، استخدم الرابط التالي كنسخة جاهزة للتعديل:
https://github.com/pedoow1/assuit-scidream-app/releases/latest/download/assuit-scidream.apk

> ملاحظة: يرجى استبدال اسم الملف الفعلي في الرابط حسب ملف الـ APK الذي تم إصداره في Releases.

### خطوات التثبيت | Installation Steps

1. حمل ملف APK من صفحة Releases.
2. افتح الملف بعد انتهاء التحميل.
3. عند ظهور رسالة "تثبيت تطبيق من مصدر غير معروف" أو "Install unknown apps":
   - اضغط على السماح
   - أو اختر "Allow" / "Install anyway"
4. إذا ظهرت رسالة Play Protect:
   - اقرأ التحذير
   - اضغط على "Install anyway" أو "More details"
   - تأكد أنك تقوم بالتنزيل من مصدر موثوق
5. بعد التثبيت، افتح التطبيق وقم بتسجيل الدخول باستخدام حسابك الجامعي أو Google.

### SHA-256 | Fingerprint
للتأكد من سلامة الملف، يمكن مقارنة الـ SHA-256 الخاص بـ APK مع القيمة التالية:

```bash
SHA-256: PASTE_SHA256_HERE
```

> استخدم هذه القيمة بعد بناء الملف أو بعد إصدار APK الرسمي في Releases.

---

## تجربة المستخدم | User Experience

التصميم موجه بشكل أساسي لطلاب كلية العلوم، مع تركيز كبير على:
- البساطة
- الوضوح
- سهولة الوصول إلى الخدمات
- التفاعل السريع
- دعم الفهم الأكاديمي

نحن نسعى إلى بناء تجربة مرنة تناسب الطلاب في مختلف المراحل الدراسية، وتساعدهم على إدارة وقتهم وتواصلهم مع الجامعة بشكل أفضل.

---

## الأمان والخصوصية | Security & Privacy

- لا نقوم بتخزين أي كلمات مرور أو مفاتيح شخصية داخل المشروع
- لا يتم تضمين أي بيانات سرية أو حسابات شخصية في المستودع
- يتم استخدام مفاتيح البيئة فقط عند الحاجة إلى إعدادات التشغيل المحلية
- يوصى باستخدام متغيرات البيئة في البيئات الآمنة فقط

> هذا المشروع لا يحتوي على أي بيانات حساسة أو معلومات شخصية، ولا ينبغي إدراج أي مفاتيح أو توكنات أو بريد إلكتروني شخصي في مستودع المشروع.

---

## الفئة المستهدفة | Target Audience

- طلاب كلية العلوم جامعة أسيوط
- أعضاء هيئة التدريس
- الإداريون
- الطالبات والطلاب في الأقسام المختلفة
- موظفو الكلية والمشرفون

---

## التطوير المستقبلي | Future Development

- تحسين تجربة التطبيق والواجهة
- إضافة دعم أكثر للـ PWA أو التطبيق الويب
- توسيع دعم الأقسام والمواد
- تطوير نظام التنبيهات الذكية
- تحسين المساعد الذكي "قطب" باستخدام استجابات أكاديمية أكثر دقة
- ربط النظام مع أنظمة الجامعة بشكل أوسع
- تطوير لوحة إحصائيات للطلاب والإدارة

---

## Team Dream Team

هذا المشروع من تطوير فريق Dream Team، بهدف دعم الطلاب وتحسين تجربة الحياة الجامعية في كلية العلوم بجامعة أسيوط.

---

## الترخيص | License

هذا المشروع مُجهز للتطوير داخل فريق العمل، ويُستخدم بموجب ترخيص مناسب يحدد حقوق الاستخدام والتعديل والتوزيع.
This project is prepared for internal development and usage under an appropriate license agreement defining rights for use, modification, and distribution.

---

## ملاحظات نهائية | Final Notes

Assuit SciDream هو مشروع تعليمي وتجاري/جامعي يهدف إلى جعل الخدمات الجامعية أكثر سهولة وفعالية.
يمكن تطويره بشكل أكبر ليصبح منصة متكاملة للطلاب، مع دعم ذكي، إدارة تعليمية، وتنظيم أكاديمي متقدم.

إذا كنت تريد، أستطيع الآن أن أجهز لك نسخة ثانية من README:
- نسخة أقصر جدًا لسوق GitHub
- نسخة احترافية أكثر
- نسخة عربية فقط
- نسخة تحتاج شعار، صور، وأيقونات جاهزة
- نسخة مناسبة لوضعها في المشروع فعليًا مع تنسيق احترافي كامل
