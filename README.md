# محفظتي اليومية - walet

- `www/`: ملفات الواجهة (index.html وmanifest.json وsw.js والأيقونات). هذا هو مجلد الويب الذي يُنسخ إلى التطبيق.
- `capacitor.config.json`: webDir يشير إلى `www`.
- `.github/workflows/main.yml`: يبني APK تلقائيًا عند كل push إلى main.

بعد نجاح الـ workflow ستجد ملف `vocab-wallet-debug-apk` في تبويب Actions داخل قسم Artifacts.
