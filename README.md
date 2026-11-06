# موقع Codex

## الملفات (ارفعها كلها في نفس المكان على GitHub)

`index.html` · `favicon.ico` · `favicon.svg` · `favicon-48.png` · `favicon-96.png` · `icon-192.png` · `icon-512.png` · `apple-touch-icon.png` · `og-image.png` · `robots.txt` · `sitemap.xml`

## 1) النشر
Settings → Pages → Deploy from a branch → `main` / root.
الرابط هيبقى: `https://USERNAME.github.io/REPO/` (أو `https://USERNAME.github.io/` لو اسم الريبو `USERNAME.github.io`).

## 2) استبدل الرابط (مهم جداً لـ Google)
بعد ما تعرف رابطك، استبدل `YOUR-SITE-URL` في ملفات `index.html` و`robots.txt` و`sitemap.xml` برابطك بدون `https://` وبدون `/` في الآخر.
مثال لو الرابط `https://tomas.github.io/codex/` يبقى `tomas.github.io/codex`.

## 3) ظهور الموقع في جوجل
1. ادخل https://search.google.com/search-console وسجّل بحساب Google.
2. اضغط **Add property** → **URL prefix** وحط رابط موقعك.
3. التحقق: اختار **HTML tag**، وانسخ سطر `<meta name="google-site-verification" ...>` وحطه داخل `<head>` في `index.html`، وارفع الملف، واضغط Verify.
4. من **Sitemaps** أضف `sitemap.xml`.
5. من **URL Inspection** حط رابط الصفحة واضغط **Request indexing**.
6. الفهرسة بتاخد من أيام لأسابيع، وده طبيعي.

## 4) أيقونة الموقع في نتائج البحث
الأيقونة معمولة ومربوطة في `index.html`. جوجل بتظهرها بعد الفهرسة (ممكن تاخد أسابيع). شرطها إن الأيقونة تكون متاحة لجوجل وبمقاس مضاعفات 48px، وده متحقق.

## 5) علشان الناس يلاقوك لما يبحثوا
- **Codex** اسم منتج معروف لشركة كبيرة، فصعب جداً تظهر في أول نتايج لكلمة `codex` لوحدها. الأفضل تستهدف: `Codex تصميم تطبيقات` أو `كودكس لتطوير التطبيقات`، والموقع متظبط على كده.
- اعمل صفحة **Google Business Profile** باسم "Codex لتطوير التطبيقات" علشان تظهر في الخرائط والبحث المحلي.
- اعمل حسابات بنفس الاسم (فيسبوك، لينكدإن، إنستجرام، GitHub) وحط رابط الموقع في كل واحد، لأن الروابط دي بتقوّي ترتيبك.
- انشر شغلك الحقيقي (مشاريع، صور، تقييمات عملاء).
- لو حبيت تضمن ظهور اسمك، فكّر في دومين خاص زي `codex-apps.com`.

## بيانات التواصل
في آخر `index.html` ابحث عن `CONFIG` (رقم واتساب وبريد Gmail).
