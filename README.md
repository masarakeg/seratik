# سيرتك | SERATIK 🚀

> موقع احترافي لخدمات تصميم وتحسين السيرة الذاتية – مُحسَّن للسيو وجاهز للنشر على GitHub Pages

---

## 📁 هيكل الملفات

```
seratik/
├── index.html              ← الصفحة الرئيسية (SEO كامل + Schema)
├── 404.html                ← صفحة الخطأ المخصصة
├── robots.txt              ← تعليمات محركات البحث
├── sitemap.xml             ← خريطة الموقع لجوجل
├── manifest.json           ← PWA manifest
├── .htaccess               ← Apache: HTTPS + Gzip + Cache headers
├── css/
│   └── style.css           ← كل ستايلات الموقع
├── js/
│   └── main.js             ← JavaScript المُحسَّن
├── images/                 ← الصور (أضفها يدويًا)
│   ├── og-image.jpg        ← 1200×630 لمشاركة السوشيال
│   ├── favicon.png         ← 32×32
│   └── apple-touch-icon.png← 180×180
└── .github/
    └── workflows/
        └── deploy.yml      ← CI/CD GitHub Actions
```

---

## 🚀 خطوات الرفع على GitHub

### 1. أنشئ Repository جديد
```bash
# على GitHub.com: New Repository
# الاسم: seratik  (أو seratik.github.io إذا أردت GitHub Pages مجاني)
# Public ✅
```

### 2. ارفع الملفات
```bash
git init
git add .
git commit -m "feat: launch SERATIK website 2026"
git branch -M main
git remote add origin https://github.com/USERNAME/seratik.git
git push -u origin main
```

### 3. فعّل GitHub Pages
```
GitHub Repo → Settings → Pages
Source: Deploy from a branch
Branch: main / root
Save ✅
```

> سيكون الموقع على: `https://USERNAME.github.io/seratik`

### 4. ربط دومين مخصص (اختياري)
```
Settings → Pages → Custom domain → seratik.com
أضف في DNS:
  A Record     @     185.199.108.153
  A Record     @     185.199.109.153
  A Record     @     185.199.110.153
  A Record     @     185.199.111.153
  CNAME        www   USERNAME.github.io
```

---

## 🔍 خطوات Google Search Console

### الخطوة 1: أضف الموقع
1. افتح [Google Search Console](https://search.google.com/search-console)
2. اضغط **Add Property**
3. اختر **URL prefix**
4. أدخل: `https://seratik.com/`

### الخطوة 2: Verify الموقع (اختر طريقة)

**الأسهل – HTML Tag:**
```html
<!-- ضع هذا في <head> في index.html -->
<meta name="google-site-verification" content="YOUR_CODE_HERE" />
```

**أو DNS Record:**
```
TXT Record @ → google-site-verification=YOUR_CODE
```

### الخطوة 3: أرسل Sitemap
```
Search Console → Sitemaps → أضف:
https://seratik.com/sitemap.xml
```

### الخطوة 4: Request Indexing
```
Search Console → URL Inspection
أدخل: https://seratik.com/
اضغط: Request Indexing
```

---

## 📊 Google Analytics 4 (اختياري)

أضف قبل `</head>` في index.html:
```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

---

## ⚡ ملاحظات مهمة للأداء

- استخدم صور **WebP** بدلاً من PNG/JPG
- ضغط الصور قبل الرفع (أداة: [Squoosh](https://squoosh.app))
- الـ CSS/JS يُضغط تلقائيًا عبر GitHub Actions
- الموقع محسّن لـ Core Web Vitals

---

## 🔑 الكلمات المفتاحية المستهدفة

| الكلمة | نوعها |
|--------|-------|
| تصميم سيرة ذاتية احترافية | رئيسية |
| CV احترافي مصر | محلية |
| CV ATS | تقنية |
| كتابة سيرة ذاتية | خدمة |
| Resume Design Egypt | إنجليزية |
| سيرة ذاتية للخريجين 2026 | long-tail |

---

## 📱 التواصل والدعم

WhatsApp: [01068204700](https://wa.me/201068204700)

---

© 2026 سيرتك | SERATIK – جميع الحقوق محفوظة
