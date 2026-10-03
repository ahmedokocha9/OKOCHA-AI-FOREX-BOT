OKOCHA AI FOREX BOT — مشروع Android Studio

المحتويات:
- تطبيق Android بسيط يعرض واجهة عربية داخل WebView.
- يجلب سلسلة أسعار صرف يومية من Frankfurter API عند توفر الإنترنت.
- يحسب EMA 20 وEMA 50 وRSI 14 ويعرض إشارة تعليمية.
- لا يحتوي على تداول فعلي أو اتصال بوسيط أو RoboTrader.

مهم بشأن البيانات:
Frankfurter يعرض أسعار صرف مرجعية يومية، وليست أسعار فوركس لحظية أو أسعار تنفيذ. قد تكون أحدث نقطة متاحة من يوم عمل سابق بسبب توقيت تحديث المصدر والعطلات.

إنشاء APK:
1. نزّل Android Studio على كمبيوتر.
2. افتح مجلد AhmedAIForex كمشروع.
3. انتظر مزامنة Gradle وتنزيل Android SDK المطلوبة (compileSdk 35).
4. اختر Build > Build Bundle(s) / APK(s) > Build APK(s).
5. ستجد الملف غالباً في app/build/outputs/apk/debug/app-debug.apk.

هذا المرفق هو مشروع المصدر، وليس ملف APK جاهزاً. بيئة الإنشاء الحالية لا تحتوي على Android SDK أو Gradle مثبتين، لذلك لم يتم إنتاج APK هنا.
