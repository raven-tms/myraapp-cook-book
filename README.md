# 📖 Recipe Notebook

تطبيق دفتر الوصفات — Android WebView App

## البناء

1. افتح المشروع في **Android Studio**
2. اضغط **Build → Build APK** أو **Run**

## المتطلبات

- Android Studio Hedgehog أو أحدث
- JDK 17+
- Android SDK 34
- minSdk 21 (Android 5.0+)

## الملفات المهمة

| الملف | الوصف |
|-------|-------|
| `app/src/main/assets/index.html` | كود التطبيق كامل (HTML/CSS/JS) |
| `app/src/main/java/.../MainActivity.kt` | WebView wrapper بـ Kotlin |
| `app/src/main/res/mipmap-*/ic_launcher.png` | أيقونات التطبيق |

## المميزات

- 🎨 13 ثيم لوني مع وضع فاتح/داكن
- 🔥 Firebase Auth (Google Sign-In)
- ☁️ Firestore sync
- 🎙️ تسجيل صوتي + Speech-to-Text
- 📤 مشاركة الوصفات
- 🗂️ Collections
- 🌐 دعم العربية / الفرنسية / الإنجليزية
