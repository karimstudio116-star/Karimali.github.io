# Karim Ali Portfolio

موقع بورتفوليو كريم علي: جرافيك ديزاينر، ومونتير، ومصوّر فيديو. بلغتين (إنجليزي وعربي).

## الملفات
- `index.html`: الموقع كله
- `karim.webp`: صورتك
- `kphysio-01` لحد `kphysio-12`: تصميمات K-Physio
- `og.jpg`: الصورة اللي بتظهر لما تبعت اللينك على واتساب

## رفع الموقع على GitHub Pages
1. ادخل github.com واعمل حساب، أو سجّل دخول لو عندك حساب.
2. اضغط **+** فوق على اليمين واختار **New repository**.
3. سمّي الريبو `USERNAME.github.io` (حط اسم المستخدم بتاعك مكان USERNAME)، واختار **Public**، واضغط **Create repository**.
4. في صفحة الريبو اضغط **uploading an existing file**.
5. فك ضغط ملف الـ zip، وحدد **كل الملفات** (Ctrl+A) واسحبها لصفحة الرفع. كلها ملفات، مفيش فولدرات، واضغط **Commit changes**.
6. ادخل **Settings ← Pages**، ومن **Source** اختار **Deploy from a branch**، واختار `main` و `/ (root)`، واضغط **Save**.
7. استنى من دقيقة لدقيقتين، وموقعك هيشتغل على: `https://USERNAME.github.io`

## بعد الرفع: صورة المعاينة على واتساب
افتح `index.html` على GitHub (أيقونة القلم) وغيّر السطر ده:
`<meta property="og:image" content="og.jpg">`
لـ:
`<meta property="og:image" content="https://USERNAME.github.io/og.jpg">`

## إضافة ريل جديد
في `index.html` دوّر على `var REELS=[` وزوّد الـ ID بتاع الفيديو.
الـ ID هو الجزء اللي بعد `shorts/` في اللينك، مثلًا من `youtube.com/shorts/7wxwt3_kwnA` الـ ID هو `7wxwt3_kwnA`.

## إضافة تصميم جديد
ارفع الصورة في الريبو جنب باقي الملفات، وبعدين زوّد سطر في `var WORK=[` بنفس شكل السطور اللي فيها:
مسار الصورة، والاسم بالإنجليزي، والاسم بالعربي.
