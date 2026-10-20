# Omnia Ahmed | Portfolio Template

## قالب برتفوليو ثنائي اللغة

قالب Portfolio شخصي حديث ومتجاوب لأمنية أحمد، مصمم باللغتين العربية والإنجليزية مع دعم اتجاهي RTL وLTR.

---

## English

### About the Template

This is a bilingual personal portfolio website for Omnia Ahmed:

> AI Web Developer | WordPress & Landing Pages

The template is designed to present professional experience, technical skills, certifications, projects, client testimonials, and contact links in a polished dark and gold visual style.

### Features

- Arabic and English language toggle.
- Automatic RTL and LTR direction switching.
- Direction-aware decorative accents that flip with the text direction.
- Responsive design for desktop, tablet, and mobile.
- Dark interface with gold accents.
- Animated custom cursor on desktop.
- Gold cursor particles and hover effects.
- Scroll reveal animations.
- Reading progress bar.
- Responsive navigation menu.
- Large project image slider.
- Client testimonial slider.
- LinkedIn, GitHub, and Upwork buttons.
- Upwork link in the main project button.
- CV download button (`Omnia Ahmed ATS.pdf`) in the secondary hero position.
- About section with two side-by-side cards: the full written pitch (no button or CTA link) next to a macOS-style `about-me.js` code editor card.
- Interactive skills showcase with six color-coded pill-style tabs and auto-cycling panels.
- Professional experience cards.
- Certificates timeline.
- Contact form using `mailto:`.
- Project image support from the `images` folder.

### Page Sections Order

The navigation menu and the page sections follow the same order:

1. Hero.
2. About Me.
3. Services.
4. Skills & Tools.
5. Professional Experience.
6. Projects.
7. Certificates.
8. Testimonials.
9. Contact.

### About Section

The About section is built as exactly two cards side by side:

- **Text card**: the complete pitch written as plain text — the value proposition ("I help small businesses and startups launch fast, reliable websites without overpaying for agency work."), a short bio with the name, a "What I do" list (business websites, landing pages, portfolios — fixes, redesign, and speed improvement — brand-aligned design — testing before delivery), the "How I work" steps (reference + requirements — confirm scope, price and deadline — build + test + 2 free revisions), and a highlighted closing note: "I reply within 1 hour." The old gold CTA button was removed; this note is plain text, not a link.
- **Code editor card**: a macOS-style editor window (`about-me.js`) with traffic-light dots, numbered lines, and syntax coloring. The bilingual slogan is the highlighted `mission` line — "أكثر من مجرد كود" (Arabic) / "More than just code" (English) — in glowing gold with a blinking cursor.

Implementation notes:

- Every text in the section is bilingual (`data-ar` / `data-en`) and switches with the language toggle, including the slogan inside the editor.
- The gold accent bars on the list items use logical CSS properties (`border-inline-start`), so they sit on the correct side in both RTL and LTR.
- The Tools card was removed from this section to avoid duplicating the "Skills & Tools" section.
- On screens up to 600px wide, the two cards stack vertically in one column.

### Technologies

- HTML5.
- CSS3.
- JavaScript.
- SVG icons.
- CSS Grid and Flexbox.
- Responsive media queries.

### Project Structure

```text
omnia-portfolio/
├── index.html
├── Omnia Ahmed ATS.pdf
├── README.md
├── Gemini_Generated_Image_6yerpd6yerpd6yer.jpg
└── images/
    ├── qa4all.png
    ├── website-project.png
    └── ai-workflow.png
```

### How to Run Locally

1. Download or clone the repository.
2. Keep `index.html`, the profile image, and `Omnia Ahmed ATS.pdf` in the same folder.
3. Keep the project images inside the `images` folder.
4. Open `index.html` in a browser.

For a better local development experience, use VS Code with the Live Server extension.

### Image Paths

The project cards use these paths:

```html
images/qa4all.png
images/website-project.png
images/ai-workflow.png
```

The filenames and folder names are case-sensitive. Make sure they match exactly.

### GitHub Pages Deployment

1. Create a GitHub repository.
2. Upload `index.html`, the profile image, `Omnia Ahmed ATS.pdf`, and the `images` folder.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select the `main` branch and the `/root` folder.
6. Click **Save**.
7. Open the published GitHub Pages link.

For a personal GitHub Pages website, you can name the repository:

```text
topweb4all.github.io
```

The website can then be available at:

```text
https://topweb4all.github.io
```

For a project repository such as `omnia-portfolio`, the URL will usually be:

```text
https://topweb4all.github.io/omnia-portfolio
```

### Customization

Before publishing, replace the temporary email in `index.html`:

```text
your.email@example.com
```

Update the following sections with your real information when needed:

- Email address.
- Project names and descriptions.
- Project links.
- Client testimonials.
- Project images.
- Social media links.
- The CV file (`Omnia Ahmed ATS.pdf`).
- About section texts: every element carries both `data-ar` and `data-en`; edit them together so the language toggle stays in sync (the slogan inside the code editor is updated the same way).

### Adding Project Images

Place your images inside the `images` folder, then update the relevant image path:

```html
<img src="images/your-project-image.png" alt="Your project preview">
```

Recommended image formats:

- PNG for screenshots and interfaces.
- JPG for photographs.
- WebP for smaller web images.

### Adding Client Testimonials

Replace the placeholder testimonial text with a real quote only after receiving permission from the client to publish it.

Each testimonial can include:

- Client name.
- Company or role.
- Testimonial text.
- Optional client image or company logo.

### Main Links

- GitHub: [github.com/topweb4all](https://github.com/topweb4all)
- LinkedIn: [linkedin.com/in/omniabdm](https://www.linkedin.com/in/omniabdm/)
- Upwork: [Upwork profile](https://www.upwork.com/freelancers/~01653dc0f1da32ace6?mp_source=share)

### License

You may use and customize this template for your personal portfolio. Replace the personal content and links with your own information before publishing.

---

## العربية

### نبذة عن القالب

هذا قالب Portfolio شخصي ثنائي اللغة لأمنية أحمد، ويعرض هويتها المهنية:

> مطورة ويب بالذكاء الاصطناعي | ووردبريس وصفحات الهبوط

تم تصميم القالب بأسلوب داكن مع لمسات ذهبية، ويحتوي على أقسام الخبرات، المهارات، التقنيات، الشهادات، المشاريع، تقييمات العملاء وطرق التواصل.

### المزايا

- زر للتبديل بين العربية والإنجليزية.
- تغيير اتجاه الصفحة تلقائيًا بين RTL وLTR.
- زخارف ومؤشرات جمالية تتبع اتجاه النص تلقائيًا.
- تصميم متجاوب مع الكمبيوتر والتابلت والهاتف.
- واجهة داكنة بلمسات ذهبية.
- مؤشر مخصص متحرك على الكمبيوتر.
- جزيئات ولمعات ذهبية عند تحريك المؤشر.
- تأثيرات ظهور أثناء التمرير.
- شريط يوضح تقدم القراءة.
- قائمة تنقل متجاوبة.
- Slider للمشاريع بصورة كبيرة.
- Slider لتقييمات العملاء.
- أزرار LinkedIn وGitHub وUpwork.
- زر بدء المشروع يفتح حساب Upwork.
- زر تحميل السيرة الذاتية (`Omnia Ahmed ATS.pdf`) في قسم البداية.
- قسم «نبذة عني» بصندوقين جنب بعض: صندوق نصوص كامل بدون زر بجانب صندوق محرر أكواد بستايل ماك (`about-me.js`).
- عرض مهارات تفاعلي بستة تبويبات دائرية ملوّنة تتبدل تلقائيًا.
- بطاقات للخبرات المهنية.
- Timeline للشهادات والتعليم.
- نموذج تواصل يعمل باستخدام `mailto:`.
- دعم صور المشاريع من مجلد `images`.

### ترتيب أقسام الصفحة

قائمة التنقل وأقسام الصفحة تتبعان نفس الترتيب:

1. البداية.
2. نبذة عني.
3. الخدمات.
4. المهارات والأدوات.
5. الخبرات المهنية.
6. المشاريع.
7. الشهادات.
8. آراء العملاء.
9. تواصل.

### قسم «نبذة عني»

صُمم قسم النبذة كصندوقين جنب بعض:

- **صندوق النصوص**: نص النبذة كاملًا مكتوب كنصوص عادية — جملة الافتتاحية («أساعد الشركات الصغيرة والشركات الناشئة على إطلاق مواقع سريعة وموثوقة دون دفع مبالغ زائدة مقابل أعمال الوكالات»)، التعريف بالاسم، قائمة «ماذا أقدم» (مواقع أعمال وصفحات هبوط وبورتفوليو — إصلاح وإعادة تصميم وتحسين سرعة — تصميم متوافق مع الهوية — اختبار قبل التسليم)، خطوات «كيف أعمل» (إرسال مرجع ومتطلبات — تأكيد النطاق والسعر والموعد — تنفيذ واختبار مع تعديلين مجانيين)، وفي النهاية ملاحظة مميزة «أرد خلال ساعة واحدة» كنص بارز وليس زرًا أو رابطًا؛ حيث حُذف الزر الذهبي القديم.
- **صندوق محرر الأكواد**: نافذة محرر بستايل ماك (`about-me.js`) بنقاط التحكم الثلاث، وأرقام للأسطر، وتلوين تركيبي، ويظهر فيها الشعار ثنائي اللغة كقيمة `mission` باللون الذهبي المضيء مع مؤشر كتابة وامض — «أكثر من مجرد كود» بالعربية و«More than just code» بالإنجليزية.

ملاحظات تنفيذية:

- كل نصوص القسم ثنائية اللغة (`data-ar` / `data-en`) وتتغير مع زر التبديل، بما في ذلك الشعار داخل المحرر.
- الأشرطة الذهبية في القوائم تستخدم خصائص CSS منطقية (`border-inline-start`) لتظهر في الجهة الصحيحة في RTL وLTR.
- حُذفت بطاقة الأدوات من هذا القسم لتجنب تكرار قسم «المهارات والأدوات».
- على الشاشات بعرض 600px أو أقل يترص الصندوقان في عمود واحد.

### التقنيات المستخدمة

- HTML5.
- CSS3.
- JavaScript.
- أيقونات SVG.
- CSS Grid وFlexbox.
- Media Queries للتجاوب.

### هيكل المشروع

```text
omnia-portfolio/
├── index.html
├── Omnia Ahmed ATS.pdf
├── README.md
├── Gemini_Generated_Image_6yerpd6yerpd6yer.jpg
└── images/
    ├── qa4all.png
    ├── website-project.png
    └── ai-workflow.png
```

### تشغيل القالب محليًا

1. حمّلي المستودع أو انسخيه إلى جهازك.
2. ضعي ملف `index.html` وصورة البروفايل وملف `Omnia Ahmed ATS.pdf` في نفس المجلد.
3. ضعي صور المشاريع داخل مجلد `images`.
4. افتحي ملف `index.html` باستخدام المتصفح.

يفضل استخدام VS Code مع إضافة Live Server أثناء التطوير المحلي.

### مسارات الصور

يستخدم قسم المشاريع المسارات التالية:

```html
images/qa4all.png
images/website-project.png
images/ai-workflow.png
```

يجب الانتباه إلى أن أسماء الملفات والمجلدات حساسة لحالة الأحرف، لذلك يجب أن تكون مطابقة تمامًا.

### رفع الموقع على GitHub Pages

1. أنشئي مستودعًا جديدًا على GitHub.
2. ارفعي ملف `index.html` وصورة البروفايل وملف `Omnia Ahmed ATS.pdf` ومجلد `images`.
3. افتحي **Settings → Pages**.
4. اختاري **Deploy from a branch**.
5. اختاري فرع `main` ومجلد `/root`.
6. اضغطي **Save**.
7. افتحي رابط GitHub Pages الذي سيظهر لك.

لإنشاء موقع شخصي مباشر، يمكنك تسمية المستودع:

```text
topweb4all.github.io
```

وسيكون الرابط غالبًا:

```text
https://topweb4all.github.io
```

أما إذا كان اسم المستودع مثل `omnia-portfolio` فسيكون الرابط غالبًا:

```text
https://topweb4all.github.io/omnia-portfolio
```

### تخصيص القالب

قبل النشر، استبدلي البريد الإلكتروني المؤقت داخل ملف `index.html`:

```text
your.email@example.com
```

ويمكنك تحديث الأقسام التالية عند الحاجة:

- البريد الإلكتروني.
- أسماء المشاريع ووصفها.
- روابط المشاريع.
- شهادات العملاء.
- صور المشاريع.
- روابط وسائل التواصل الاجتماعي.
- ملف السيرة الذاتية (`Omnia Ahmed ATS.pdf`).
- نصوص قسم «نبذة عني»: كل عنصر يحمل `data-ar` و`data-en` معًا، عدّليهما معًا حتى يبقى تبديل اللغة متزامنًا (الشعار داخل محرر الأكواد يُعدَّل بالطريقة نفسها).

### إضافة صور المشاريع

ضعي الصور داخل مجلد `images`، ثم حدّثي مسار الصورة داخل البطاقة المناسبة:

```html
<img src="images/your-project-image.png" alt="صورة معاينة المشروع">
```

صيغ الصور المقترحة:

- PNG لصور الواجهات ولقطات الشاشة.
- JPG للصور الفوتوغرافية.
- WebP للحصول على حجم أقل وسرعة تحميل أفضل.

### إضافة تقييمات العملاء

استبدلي النص التجريبي بتقييم حقيقي فقط بعد الحصول على موافقة العميل على نشره.

يمكن أن يحتوي كل تقييم على:

- اسم العميل.
- الشركة أو المسمى الوظيفي.
- نص التقييم.
- صورة العميل أو شعار الشركة اختياريًا.

### الروابط الرئيسية

- GitHub: [github.com/topweb4all](https://github.com/topweb4all)
- LinkedIn: [linkedin.com/in/omniabdm](https://www.linkedin.com/in/omniabdm/)
- Upwork: [حساب Upwork](https://www.upwork.com/freelancers/~01653dc0f1da32ace6?mp_source=share)

### الترخيص

يمكنك استخدام القالب وتعديله لعمل Portfolio شخصي. استبدلي البيانات والروابط الشخصية بمعلوماتك الخاصة قبل النشر.
