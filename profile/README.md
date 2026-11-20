<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="logo.svg">
    <img src="logo.svg" alt="Fastsite" width="72">
  </picture>
</p>

<h2 align="center">
  Website hosting.<br>
  AI Agentic infrastructure.<br>
  Locally in Saudi Arabia.
</h2>

Your AI builds your website. Fastsite keeps it online, fast and secure.

**[Website](https://fastsite.sa)** · **[Pricing](https://fastsite.sa/pricing/)** · **[Docs](https://fastsite.sa/docs/)** · **[info@fast.sa](mailto:info@fast.sa)**

## What Fastsite is

Fastsite hosts websites on servers in Saudi Arabia. Sign up, add a site, publish it, and it answers on its own `name.fastsite.cloud` address.

Fastsite is for people who build with AI coding agents (Claude Code, ChatGPT) and for the agents themselves.

Fastsite serves the files your site is made of: HTML, CSS, JavaScript, images, fonts and documents. Builds run on Fastsite's servers in Riyadh once Fastsite turns them on: then turn on a site's build settings and Fastsite installs the packages, runs your build command and publishes the output folder; with them off (the default), what you upload or push is published as it is. Fastsite does not run your own server code: `/api/*` can go to the functions of your linked Fastbase project. For sign-ins, data and server functions, [connect Fastbase](https://fastsite.sa/docs/integrations/).

## Quick start

1. **Create your account.** Open [fastsite.sa](https://fastsite.sa) and choose **Start building**. Continue with Google or GitHub, or use an email address and a password.
2. **Add a site.** Give the site a name. The name becomes its free address: a site called `asas` answers on `asas.fastsite.cloud`.
3. **Publish it.** Pick the way that suits you. All three end the same: your site live on servers in Saudi Arabia.

| Way | How |
|---|---|
| [Upload](https://fastsite.sa/docs/deployments-and-undo/) | Drop a folder or a .zip in the dashboard. |
| [GitHub](https://fastsite.sa/docs/github/) | Import a repository once. Every push gets its own preview, with the link posted on the pull request, and your production branch is the live site. |
| [Chat](https://fastsite.sa/docs/deploy-by-chat/) | Ask your own Claude Code. |

Every new version is a new deployment, and an earlier one comes back in one click.

## Deploy by chat

Connect your own Claude Code to Fastsite, then ask it in plain words to create a site, put your files on it, show the deployments, go back to the one before, or set a variable.

Make a token in the dashboard, under **Account**, then **Tokens**. Then run this line in your terminal, with your token in place of `<token>`:

```text
claude mcp add --transport http fastsite https://fastsite.sa/api/mcp --header "Authorization: Bearer <token>"
```

Try: «Create a site called my-shop in my organization, with a home page that says hello, and deploy it.» Then: «Go back to the previous deployment.»

Facts for agents are at [fastsite.sa/llms.txt](https://fastsite.sa/llms.txt).

## What you get

- **Deployments and undo.** Every version of your site is a deployment. Deployments are kept, so going back is one click.
- **A preview for every change.** Each change gets its own link, so you can check it before it goes live.
- **A free address and HTTPS.** `name.fastsite.cloud` is your free address, ready the moment you create your site. Every address gets a certificate at no cost.
- **Your own domain.** Add your own domain when you want, and the certificate is taken care of.
- **Password protection.** Put a site behind a password, for example while it is still being built.
- **Environment variables.** Keep a site's settings and keys out of its files.
- **Logs and usage.** Each site's request logs and deployment logs, and its requests and traffic over the last day, week or month.
- **Team and roles.** An owner manages billing and members; a member publishes and manages sites.
- **Authenticator app.** Add a second step to your sign-in: a code from an authenticator app.
- **API and tokens.** The Fastsite API is what the dashboard itself uses. You can call it from your own scripts.

## Pricing

**Free for one site. Pro for SAR 95 a month per organization.**

Free: 1 site on `name.fastsite.cloud` and 100 GB of traffic a month. Pro: 3 sites and 1 TB a month, SAR 29 a month for each extra site, your own domains and password protection. A preview for every change is part of the Pro plan.

[See pricing](https://fastsite.sa/pricing/)

## Hosting in Saudi Arabia

Servers in Saudi Arabia, open to visitors anywhere. What hosting here gives you depends on what your site does. We say which case you are in before you move.

- **Your site's own code handles personal data.** Sign-ins, forms that collect details, and server functions. Here residency matters: your site's files and the hosting logs stay in Saudi Arabia.
- **Your site only shows pages.** Portfolios, landing pages, menus, docs, blogs. You gain speed for visitors in Saudi Arabia, because the pages load from servers close to them. That is a speed gain. We do not sell it as compliance.
- **The access log keeps no visitor IP address.** It is rolled daily and entries are deleted after 28 days. One log keeps an address: the shield's log of **refused** requests, so an attack can be traced and the address blocked. It is kept 7 days.
- **Under attack.** The shield has a stricter profile for a site under attack: its limits are five times lower.

Hosting in Saudi Arabia keeps servers, files and logs in the Kingdom. What the law asks of your site depends on what it does with personal data, and Fastsite does not give legal advice.

## Docs

[Quickstart](https://fastsite.sa/docs/getting-started/) · [Deployments and undo](https://fastsite.sa/docs/deployments-and-undo/) · [Deploy from GitHub](https://fastsite.sa/docs/github/) · [Deploy by chat](https://fastsite.sa/docs/deploy-by-chat/) · [Domains and HTTPS](https://fastsite.sa/docs/domains-and-https/) · [Environment variables](https://fastsite.sa/docs/environment-variables/) · [Integrations](https://fastsite.sa/docs/integrations/) · [API reference](https://fastsite.sa/docs/api/) · [Limits](https://fastsite.sa/docs/limits/) · [Hosting in Saudi Arabia](https://fastsite.sa/docs/hosting-in-saudi-arabia/) · [Pricing and billing](https://fastsite.sa/docs/pricing-and-billing/) · [Support](https://fastsite.sa/docs/support/)

## The Fast family

Fastsite works with the rest of the Fast family. Connect once, and the keys are filled in for you.

**Fastbase:** database · **Fastsend:** email · **Fastsite:** hosting

Hosted on Fastsite: Fastbase · Fastsend · Fast Source.

## Support

Write to [info@fast.sa](mailto:info@fast.sa). Say which site you mean and what you saw.

[Legal pages](https://fastsite.sa/legal/): [Terms](https://fastsite.sa/legal/terms) · [Privacy](https://fastsite.sa/legal/privacy) · [Acceptable use](https://fastsite.sa/legal/acceptable-use) · [Cookies](https://fastsite.sa/legal/cookies) · [Refunds](https://fastsite.sa/legal/refunds) · [Open-source notices](https://fastsite.sa/legal/open-source)

<p align="center">A Fast Solutions product</p>

---

<div dir="rtl">

<h2 align="center">
  استضافة المواقع.<br>
  بنية تحتية لوكلاء الذكاء الاصطناعي.<br>
  محلياً في السعودية.
</h2>

مساعدك الذكي يبني موقعك، و Fastsite يبقيه على الإنترنت، سريعا وآمنا.

**[الموقع](https://fastsite.sa/ar/)** · **[الأسعار](https://fastsite.sa/ar/pricing/)** · **[الوثائق](https://fastsite.sa/ar/docs/)** · **[info@fast.sa](mailto:info@fast.sa)**

## ما هو Fastsite؟

يستضيف Fastsite المواقع على خوادم في السعودية. أنشئ حسابا، وأضف موقعا، وانشره، فيعمل على عنوانه `name.fastsite.cloud`.

وهو موجه لمن يبني مواقعه مع وكلاء الذكاء الاصطناعي (Claude Code و ChatGPT) وللوكلاء أنفسهم.

يخدم Fastsite الملفات التي يتكون منها موقعك: HTML و CSS و JavaScript والصور والخطوط والمستندات. وعمليات البناء تجري على خوادم Fastsite في الرياض حين يشغلها Fastsite: بعدها فعل إعدادات البناء للموقع، فيثبت Fastsite الحزم ويشغل أمر البناء وينشر مجلد الإخراج؛ وإذا كانت مطفأة (وهو الافتراضي) ينشر ما ترفعه من ملفات أو تحديثات كما هو. ولا يشغل Fastsite كود خادم خاصا بك. ولتسجيل الدخول والبيانات ودوال الخادم، [اربط Fastbase](https://fastsite.sa/ar/docs/integrations/).

## البداية السريعة

1. **أنشئ حسابك.** افتح [fastsite.sa](https://fastsite.sa/ar/) واختر **ابدأ البناء**. أكمل بحساب Google أو GitHub، أو استخدم بريدك الإلكتروني وكلمة مرور.
2. **أضف موقعا.** اختر اسما للموقع. الاسم يصير عنوانه المجاني: موقع اسمه `asas` يعمل على `asas.fastsite.cloud`.
3. **انشره.** اختر الطريقة التي تناسبك. والنتيجة واحدة: موقعك منشور على خوادم في السعودية.

| الطريقة | كيف |
|---|---|
| [الرفع](https://fastsite.sa/ar/docs/deployments-and-undo/) | ارفع مجلدا أو ملف zip من لوحة التحكم. |
| [GitHub](https://fastsite.sa/ar/docs/github/) | تربط المستودع مرة واحدة. ولكل تحديث ترفعه معاينة خاصة به يصلك رابطها في طلب الدمج، وفرع الإنتاج هو الموقع المنشور. |
| [المحادثة](https://fastsite.sa/ar/docs/deploy-by-chat/) | اطلب من Claude Code الخاص بك. |

كل نسخة جديدة نسخة منشورة مستقلة، وأي نسخة سابقة تعود بضغطة واحدة.

## النشر بالمحادثة

اربط Claude Code الخاص بك بـ Fastsite، ثم اطلب منه بكلام عادي أن ينشئ موقعا، ويضع ملفاتك عليه، ويعرض النسخ المنشورة، ويرجع إلى التي قبلها، أو يضبط متغيرا.

أنشئ رمزا من لوحة التحكم: **الحساب** ثم **الرموز**. ثم شغل هذا السطر في الطرفية، وضع رمزك مكان `<token>`:

<pre dir="ltr"><code>claude mcp add --transport http fastsite https://fastsite.sa/api/mcp --header "Authorization: Bearer &lt;token&gt;"</code></pre>

جرب: «أنشئ موقعا اسمه my-shop في منظمتي، بصفحة رئيسية تقول مرحبا، وانشره.» وبعد ذلك: «ارجع إلى النسخة المنشورة السابقة.»

المعلومات المكتوبة للوكلاء على [fastsite.sa/llms.txt](https://fastsite.sa/llms.txt).

## ما تحصل عليه

- **عمليات النشر والتراجع.** كل نسخة من موقعك نسخة منشورة مستقلة. وكل نسخة منشورة محفوظة، فالرجوع ضغطة واحدة.
- **معاينة لكل تعديل.** لكل تعديل رابط خاص به، فتراجعه قبل نشره.
- **عنوان مجاني وشهادة HTTPS.** لكل موقع عنوان مجاني بصيغة `name.fastsite.cloud`، يكون جاهزا لحظة إنشاء الموقع. ولكل موقع شهادة بلا تكلفة.
- **نطاقك الخاص.** أضف نطاقك الخاص متى شئت، والشهادة علينا.
- **الحماية بكلمة مرور.** ضع موقعك خلف كلمة مرور، مثلا وهو ما زال قيد التجهيز.
- **متغيرات البيئة.** أبق إعدادات موقعك ومفاتيحه خارج ملفاته.
- **السجلات والاستهلاك.** سجلات الطلبات وسجلات النشر لكل موقع، وعدد طلباته وحركة بياناته خلال آخر يوم أو أسبوع أو شهر.
- **الفريق والأدوار.** المالك يدير الفوترة والأعضاء، والعضو ينشر المواقع ويديرها.
- **تطبيق المصادقة.** أضف خطوة ثانية عند تسجيل الدخول: رمز من تطبيق المصادقة.
- **الواجهة البرمجية والرموز.** الواجهة البرمجية لـ Fastsite هي ما تستخدمه لوحة التحكم نفسها. يمكنك استدعاؤها من سكربتاتك.

## الأسعار

**مجانا لموقع واحد. وخطة Pro بـ 95 ريالا شهريا لكل منظمة.**

المجانية: موقع واحد على `name.fastsite.cloud` و100 جيجابايت من حركة البيانات شهريا. Pro: 3 مواقع و1 تيرابايت شهريا، و29 ريالا شهريا لكل موقع إضافي، ونطاقاتك الخاصة والحماية بكلمة مرور. خطة Pro تشمل معاينة لكل تعديل.

[اطلع على الأسعار](https://fastsite.sa/ar/pricing/)

## الاستضافة في السعودية

خوادم في السعودية، مفتوحة للزوار من أي مكان. ما تكسبه من الاستضافة هنا يعتمد على ما يفعله موقعك، ونخبرك بحالتك قبل أن تنتقل.

- **كود موقعك نفسه يتعامل مع بيانات شخصية.** تسجيل الدخول، ونماذج تجمع بيانات، ودوال الخادم. هنا يهم أن تبقى البيانات داخل المملكة: ملفات موقعك وسجلات الاستضافة تبقى في السعودية.
- **موقعك يعرض صفحات فقط.** معارض أعمال وصفحات هبوط وقوائم ووثائق ومدونات. تكسب سرعة لزوارك في السعودية، لأن الصفحات تحمل من خوادم قريبة منهم. هذا مكسب سرعة، ولا نبيعه على أنه امتثال.
- **سجل الوصول لا يحفظ عنوان IP لأي زائر.** يبدأ سجل جديد كل يوم وتحذف السجلات بعد 28 يوما. سجل واحد يحفظ عنوانا: سجل الدرع للطلبات **المرفوضة**، ليمكن تتبع الهجوم وحجب العنوان. ويحفظ 7 أيام.
- **عند التعرض لهجوم.** للدرع وضع أكثر تشددا للموقع الذي يتعرض لهجوم: تصير حدوده أقل بخمس مرات.

الاستضافة في السعودية تبقي الخوادم والملفات والسجلات داخل المملكة. أما ما يطلبه النظام من موقعك فيعتمد على ما يفعله ببيانات الأشخاص، و Fastsite لا يقدم استشارة قانونية.

## الوثائق

[البداية السريعة](https://fastsite.sa/ar/docs/getting-started/) · [عمليات النشر والتراجع](https://fastsite.sa/ar/docs/deployments-and-undo/) · [النشر من GitHub](https://fastsite.sa/ar/docs/github/) · [النشر بالمحادثة](https://fastsite.sa/ar/docs/deploy-by-chat/) · [النطاقات و HTTPS](https://fastsite.sa/ar/docs/domains-and-https/) · [متغيرات البيئة](https://fastsite.sa/ar/docs/environment-variables/) · [التكاملات](https://fastsite.sa/ar/docs/integrations/) · [مرجع الواجهة البرمجية](https://fastsite.sa/ar/docs/api/) · [الحدود](https://fastsite.sa/ar/docs/limits/) · [الاستضافة في السعودية](https://fastsite.sa/ar/docs/hosting-in-saudi-arabia/) · [الأسعار والفوترة](https://fastsite.sa/ar/docs/pricing-and-billing/) · [الدعم](https://fastsite.sa/ar/docs/support/)

## عائلة Fast

يعمل Fastsite مع بقية عائلة Fast. اربط مرة واحدة، والمفاتيح تضاف لك تلقائيا.

**قواعد البيانات:** Fastbase · **البريد:** Fastsend · **الاستضافة:** Fastsite

مستضافة على Fastsite: Fastbase · Fastsend · Fast Source

## الدعم

راسلنا على [info@fast.sa](mailto:info@fast.sa) وحدد أي موقع تقصد وما الذي رأيته.

[الصفحات القانونية](https://fastsite.sa/ar/legal/): [الشروط](https://fastsite.sa/ar/legal/terms) · [الخصوصية](https://fastsite.sa/ar/legal/privacy) · [الاستخدام المقبول](https://fastsite.sa/ar/legal/acceptable-use) · [ملفات الكوكيز](https://fastsite.sa/ar/legal/cookies) · [الاسترداد](https://fastsite.sa/ar/legal/refunds) · [إشعارات المصادر المفتوحة](https://fastsite.sa/ar/legal/open-source)

<p align="center">من منتجات Fast Solutions</p>

</div>
