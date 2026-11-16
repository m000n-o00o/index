# Index · فهرس

Save the useful links you come across, sort them into your own categories, and find them again with a quick search. One page, no account, no server.

**Live:** https://m000n-o00o.github.io/index/

[العربية](#فهرس)

## What it does

- **Save a link** with a title, a category and an optional note. Paste a whole message that contains a link and the text around it becomes the title.
- **Search** across titles, notes, links, categories and accounts. Matches are highlighted.
- **Source detection.** Links from X, LinkedIn, Telegram, YouTube and GitHub are recognised automatically, including the account name. Links from WhatsApp can be tagged by hand.
- **Track progress** on each link: New, In progress, Done.
- **Your own categories.** Everyone starts with one general category and adds their own.
- **Arabic and English**, with dark and light themes. Both are set from Settings.

## Use it

1. Open the link above.
2. On iPhone: tap Share, then **Add to Home Screen**. Open it from the icon from then on.
3. Tap **Add link**, paste a link, pick a category, save.

## Where your data lives

By default, links are stored **in your browser on this device only**. Nothing is sent anywhere, and there is no tracking.

Because of that:

- Links saved on your phone don't appear on your laptop, and the other way round.
- Clearing the browser's data deletes them. Use **Settings → Backup** to download a copy now and then. You can restore it on any device.

## Optional: sync between devices with GitHub

If you want the same links on every device, the page can store them in a **private** GitHub repository of your own.

1. Create a new **private** repository, for example `links-data`.
2. Create a **fine-grained** personal access token at `github.com/settings/personal-access-tokens/new`:
   - **Repository access:** Only select repositories → your data repository only.
   - **Permissions:** Contents → **Read and write**. Nothing else.
   - **Expiration:** a date you'll remember to renew, for example one year.
3. In the page, open **Settings → Data → GitHub**, and enter your username, the repository name and the token.
4. Optional: add a `categories.txt` file to the repository, one category per line.

Keep the token safe:

- Never put it in code, a public repository, a screenshot or a chat.
- The token is stored only in the browser of the device where you enter it.
- If it is ever exposed, delete it from GitHub's settings straight away and create a new one. A token scoped as above can only touch that one repository.

## Host your own copy

The whole app is one `index.html` file plus its icons. No build step and no dependencies.

1. Fork this repository.
2. In **Settings → Pages**, choose **Deploy from a branch**, then `main` and `/ (root)`.
3. Your copy will be live at `https://<your-username>.github.io/<repository>/`.

---

<div dir="rtl">

## فهرس

احفظ الروابط المفيدة التي تمر عليك، وصنّفها بتصنيفاتك الخاصة، واعثر عليها بسرعة بالبحث. صفحة واحدة، بلا حساب ولا خادم.

**الموقع:** https://m000n-o00o.github.io/index/

### المزايا

- **حفظ الرابط** مع عنوان وتصنيف وملاحظة اختيارية. عند لصق رسالة كاملة فيها رابط، يصبح نصها عنوانًا تلقائيًا.
- **البحث** في العناوين والملاحظات والروابط والتصنيفات والحسابات، مع تمييز الكلمات المطابقة.
- **تحديد المصدر تلقائيًا** لروابط X ولينكدإن وتيليجرام ويوتيوب وGitHub، مع اسم الحساب. أما روابط واتساب فيُحدَّد مصدرها يدويًا.
- **متابعة الحالة** لكل رابط: جديد، قيد المتابعة، مكتمل.
- **تصنيفات خاصة بكل مستخدم.** يبدأ الجميع بتصنيف «عام»، ثم يضيف كلٌّ تصنيفاته.
- **العربية والإنجليزية**، مع وضعين داكن وفاتح، ويُضبطان من الإعدادات.

### طريقة الاستخدام

1. افتح الرابط أعلاه.
2. على الآيفون: اضغط مشاركة، ثم **إضافة إلى الشاشة الرئيسية**، وافتحه من الأيقونة بعد ذلك.
3. اضغط **إضافة رابط**، والصق الرابط، واختر التصنيف، ثم احفظ.

### أين تُحفظ البيانات؟

تُحفظ الروابط افتراضيًا **في متصفح هذا الجهاز فقط**، ولا تُرسل إلى أي جهة، ولا يوجد أي تتبّع.

لذلك:

- الروابط المحفوظة على الجوال لا تظهر على الحاسب، والعكس كذلك.
- مسح بيانات المتصفح يحذفها. يُنصح بتنزيل نسخة احتياطية من **الإعدادات ← النسخ الاحتياطي** من حين لآخر، ويمكن استعادتها على أي جهاز.

### اختياري: المزامنة بين الأجهزة عبر GitHub

لعرض الروابط نفسها على كل الأجهزة، يمكن حفظها في مستودع **خاص** على GitHub:

1. أنشئ مستودعًا **خاصًا** جديدًا، مثل `links-data`.
2. أنشئ رمز وصول من نوع **Fine-grained** من `github.com/settings/personal-access-tokens/new`:
   - **Repository access:** اختر Only select repositories، ثم مستودع البيانات فقط.
   - **Permissions:** اضبط Contents على **Read and write**، ولا شيء غيرها.
   - **Expiration:** تاريخ تتذكر تجديده عنده، مثل سنة.
3. في الصفحة، افتح **الإعدادات ← البيانات ← GitHub**، وأدخل اسم المستخدم واسم المستودع والرمز.
4. اختياري: أضف ملف `categories.txt` إلى المستودع، وفيه تصنيف واحد في كل سطر.

حماية الرمز:

- لا تضعه في كود أو مستودع عام أو صورة شاشة أو محادثة.
- يُحفظ الرمز في متصفح الجهاز الذي أُدخل فيه فقط.
- إذا انكشف، احذفه فورًا من إعدادات GitHub وأنشئ رمزًا جديدًا. والرمز المضبوط بالطريقة أعلاه لا يصل إلا إلى ذلك المستودع وحده.

### استضافة نسختك الخاصة

التطبيق كله ملف `index.html` واحد مع أيقوناته، بلا خطوات بناء ولا مكتبات.

1. اعمل Fork لهذا المستودع.
2. من **Settings ← Pages**، اختر **Deploy from a branch**، ثم `main` و`/ (root)`.
3. ستكون نسختك على `https://<your-username>.github.io/<repository>/`.

</div>
