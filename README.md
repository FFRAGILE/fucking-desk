# ⚡ EnigMano Pro — Unified Cloud Instance (Windows & Linux)

[English](#english-documentation) | [راهنمای فارسی](#راهنمای-فارسی-farsi-guide)

---

## راهنمای فارسی (Farsi Guide)

پروژه **EnigMano Pro** یک ابزار خودکارسازی امن برای راه‌اندازی سرورهای مجازی رایگان ویندوز ۱۰ و لینوکس اوبونتو با منابع سخت‌افزاری قدرتمند (۱۶ گیگابایت رم و پردازنده چند هسته‌ای) از طریق سرویس **GitHub Actions** و دسترسی گرافیکی **Google Chrome Remote Desktop (GCRD)** است.

### 🌟 ویژگی‌های برجسته نسخه جدید:
* **سرعت شبکه فوق‌سریع:** دسترسی به پهنای باند گیگابیتی دیتاسنتر ابری مایکروسافت.
* **کارت صدای فعال بومی (VB-Audio):** فعال‌سازی و راه‌اندازی کامل درایورهای صوتی پیش از اولین ورود شما به ویندوز.
* **آزادسازی هارد دیسک (+۴۰ گیگابایت):** پاک‌سازی پکیج‌های سنگین و بدون استفاده پیش‌فرض برای مهیا ساختن فضای ذخیره‌سازی بزرگ‌تر.
* **دور زدن محدودیت‌ها (Cloudflare WARP):** نصب و اتصال خودکار کلودفلر وارپ برای تغییر آی‌پی سرور و عبور از فیلترینگ یا محدودیت‌های سایت‌هایی مانند Spotify.
* **ابزار دانلودر اختصاصی روی دسکتاپ:** قرارگیری ابزار اختصاصی `EnigMano_Downloader` روی دسکتاپ برای دانلود بی‌نهایت فایل با سرعت گیگابیتی بدون نیاز به مرورگر.
* **قابلیت دانلود پیش‌فرض:** امکان وارد کردن لینک دانلود مستقیم در پنل گیت‌هاب جهت بارگذاری فایل روی دسکتاپ پیش از ورود شما.

---

### 🛠️ مراحل راه‌اندازی و استفاده:

#### ۱. کپی کردن پروژه (Fork)
در بالای همین صفحه روی دکمه **Fork** کلیک کنید تا یک نسخه از پروژه روی اکانت شما کپی شود.

#### ۲. دریافت کد اتصال از گوگل کروم
1. به سایت [remotedesktop.google.com/headless](https://remotedesktop.google.com/headless) بروید و وارد اکانت گوگل خود شوید.
2. مراحل را تا انتها رفته و دستور طولانی مربوط به بخش **Windows (PowerShell)** را کپی کنید.

#### ۳. اجرای ورک‌فلو در گیت‌هاب
1. در ریپازیتوری فورک‌شده خود، به تب **Actions** بروید و آن را فعال کنید.
2. ورک‌فلو به نام **`⚡ Pro Unified Cloud — Windows & Linux`** را انتخاب کرده و دکمه **Run workflow** را بزنید.
3. در فرم باز شده:
   * سیستم‌عامل مورد نظر خود را انتخاب کنید (Windows یا Linux).
   * دستور پاورشلی که از گوگل کپی کردید را در کادر **CODE** قرار دهید.
   * یک پین کد ۶ رقمی دلخواه (مثلاً `123456`) برای رمز اتصال تعیین کنید.
   * در صورت تمایل، لینک دانلودی را در بخش **DOWNLOAD_URL** قرار دهید.
   * نام کامپیوتر دلخواه خود را تایپ کرده و تیک اتصال کلودفلر وارپ را بزنید.
4. روی دکمه سبز رنگ **Run workflow** کلیک کنید.

#### ۴. اتصال نهایی
* حدود ۳ دقیقه منتظر بمانید تا نصب و بهینه‌سازی به پایان برسد.
* به سایت [remotedesktop.google.com/access](https://remotedesktop.google.com/access) بروید و به سیستم جدید آنلاین شده متصل شوید.

---

### ⚠️ نکات مهم و محدودیت‌ها:
* هر سشن حداکثر **۳۴۰ دقیقه (حدود ۵.۶ ساعت)** فعال خواهد بود و پس از پایان کار، تمامی فایل‌ها به دلایل امنیتی پاک می‌شوند.
* به دلیل مغایرت اجرای مداوم سیستم‌عامل با برخی قوانین گیت‌هاب اکشنز، اکیداً توصیه می‌شود از **یک اکانت فرعی گیت‌هاب** برای این کار استفاده کنید.

---

## English Documentation

**EnigMano Pro** automates the deployment of free, high-performance cloud instances running Windows 10 or Ubuntu Linux on GitHub Actions runners, using **Google Chrome Remote Desktop** for lag-free graphical remote access.

### 🌟 Key Features:
* **High Bandwidth Network:** Leverage Microsoft's Gigabit cloud data center speeds.
* **Pre-activated Sound:** VB-Audio virtual cable is configured and loaded before you log in.
* **Storage Optimizer (+40GB Free space):** Cleans up heavy default developer SDKs to maximize your C: drive storage.
* **Cloudflare WARP Integration:** Automatically bypasses geo-restrictions and DC blocks (e.g., Spotify, OpenAI).
* **Pre-downloader Input:** Specify a direct URL during workflow configuration to pre-load a file directly to your Desktop.
* **Desktop Multi-Downloader:** Includes an interactive tool `EnigMano_Downloader.bat` on your Desktop to download multiple large files consecutively at extreme speeds.

---

### 🛠️ Getting Started:

#### 1. Fork this Repository
Click **Fork** in the top-right corner to create a copy of this repository in your personal GitHub account.

#### 2. Obtain Google CRD Credentials
1. Go to [remotedesktop.google.com/headless](https://remotedesktop.google.com/headless) and sign in.
2. Complete the authentication steps and copy the PowerShell command.

#### 3. Run the Workflow
1. In your forked repository, go to the **Actions** tab and enable workflows.
2. Select **`⚡ Pro Unified Cloud — Windows & Linux`** and click **Run workflow**.
3. Fill out the configuration inputs:
   * Select your **OS** (Windows or Linux).
   * Paste the copied PowerShell command into the **CODE** field.
   * Set a 6-digit **PIN** for secure access.
   * Optionally, paste a direct download URL in the **DOWNLOAD_URL** field.
   * Choose a custom computer name and toggle the **WARP** option.
4. Click **Run workflow**.

#### 4. Connect to your Cloud PC
* Wait 3–4 minutes for the setup to complete.
* Go to [remotedesktop.google.com/access](https://remotedesktop.google.com/access) to connect to your online machine using your configured PIN.

---

### ⚠️ Disclaimer & Usage Policies:
* GitHub Action runners have a maximum run limit of **340 minutes (approx. 5.6 hours)**. All local data will be permanently wiped when the session terminates.
* Constant execution on primary accounts might violate GitHub Actions' terms of service. It is highly recommended to run this on **secondary/temporary GitHub accounts** to prevent restrictions.
