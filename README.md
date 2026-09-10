# Secure Login with EmailJS 🚀 | نظام تسجيل دخول آمن

An interactive login system built from scratch using HTML, CSS, JavaScript, and EmailJS. It features a modern UI, basic route protection, and automated email confirmation upon successful login.

نظام تسجيل دخول تفاعلي مبني من الصفر باستخدام HTML، CSS، JavaScript، و EmailJS. يتميز بواجهة مستخدم عصرية، حماية أساسية للصفحات، وإرسال بريد إلكتروني تلقائي للتأكيد عند تسجيل الدخول بنجاح.

---

## 🌟 Features (المميزات)

### 🇬🇧 English:
- **Modern UI/UX:** Clean, responsive design with CSS gradients and hover effects.
- **Interactive Feedback:** Loading spinners and status messages during the authentication process.
- **Email Confirmation:** Integrates with EmailJS to send automated welcome emails to users upon login.
- **Route Protection:** Uses `localStorage` to protect `dashboard.html`, ensuring only logged-in users can access it.
- **Instant Redirection:** Automatically redirects users to the dashboard upon successful email delivery.

### 🇸🇦 Arabic:
- **واجهة مستخدم عصرية:** تصميم نظيف ومتجاوب مع تدرجات لونية وتأثيرات بصرية.
- **تفاعل مباشر:** مؤشر تحميل ورسائل حالة تظهر أثناء عملية التحقق.
- **تأكيد عبر البريد:** دمج مكتبة EmailJS لإرسال رسائل ترحيب تلقائية للمستخدمين فور الدخول.
- **حماية الصفحات (Route Protection):** استخدام `localStorage` لحماية صفحة لوحة التحكم `dashboard.html`، ومنع الدخول إليها بدون تسجيل.
- **توجيه تلقائي:** نقل المستخدم تلقائياً إلى الصفحة الرئيسية بمجرد نجاح الإرسال.

---

## 🛠️ Technologies Used (التقنيات المستخدمة)
- **HTML5:** For the structure of the pages. (لبناء هيكل الصفحات)
- **CSS3:** For styling, gradients, and animations. (للتصميم، الألوان، والمؤثرات الحركية)
- **Vanilla JavaScript:** For form validation, API calls, and logic. (للتحقق من البيانات وبرمجة العمليات)
- **EmailJS API:** To send automated confirmation emails without a backend server. (لإرسال رسائل البريد الإلكتروني دون الحاجة لخادم خلفي)

---

## 🚀 How to Run (كيفية التشغيل)

### 🇬🇧 English:
1. Clone the repository or download the files (`index.html` and `dashboard.html`).
2. Open `index.html` in any modern web browser.
3. Enter an email address and a password (minimum 6 characters).
4. Click "تسجيل الدخول" (Login). You will see a loading state, receive an email confirmation, and be redirected to the dashboard.
5. In the dashboard, click "تسجيل الخروج" (Logout) to clear the session and return to the login screen.

### 🇸🇦 Arabic:
1. قم بتحميل ملفات المشروع (`index.html` و `dashboard.html`).
2. افتح ملف `index.html` في أي متصفح ويب.
3. أدخل بريداً إلكترونياً وكلمة مرور (لا تقل عن 6 أحرف).
4. اضغط على زر "تسجيل الدخول". ستلاحظ ظهور مؤشر التحميل، وستصلك رسالة تأكيد على البريد الذي أدخلته، ثم سيتم توجيهك إلى لوحة التحكم.
5. في لوحة التحكم، يمكنك الضغط على "تسجيل الخروج" لمسح الجلسة والعودة لصفحة الدخول.

---

## ⚙️ Configuration (الإعدادات والتخصيص)
If you want to use your own EmailJS account:
إذا كنت ترغب في استخدام حساب EmailJS الخاص بك:

1. Create an account on [EmailJS](https://www.emailjs.com/).
2. Create an Email Service and get your **Service ID**.
3. Create an Email Template and get your **Template ID**.
4. Get your **Public Key** from the Account settings.
5. Replace the IDs in the `index.html` script:
   - `emailjs.init("YOUR_PUBLIC_KEY")`
   - `emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams)`
   # App-for-all
