مشروع تطبيق الجزيرة - حاسبة مبيعات كروت الإنترنت

المشروع يحتوي على تطبيق Android بواجهة عربية محلية، مع حفظ الفئات والفواتير على الجهاز.

إنشاء APK تلقائياً عبر GitHub Actions:
1) ارفع محتويات هذا المجلد إلى مستودع GitHub جديد.
2) افتح تبويب Actions في المستودع.
3) اختر Build Aljazeera APK ثم Run workflow (أو انتظر البناء بعد push).
4) بعد نجاح البناء افتح نتيجة التشغيل (workflow run) ونزّل Artifact باسم AljazeeraSales-debug-apk.
5) فك ضغط Artifact لتحصل على app-debug.apk وثبّته على هاتف Android.

البناء المحلي باستخدام Android Studio:
افتح المجلد في Android Studio وانتظر Gradle Sync، ثم اختر Build > Build APK(s).

المتطلبات: Android SDK Platform 35 وBuild Tools 35.0.0 وGradle 8.9 وJDK 17.
