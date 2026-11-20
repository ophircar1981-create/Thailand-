פרויקט Android לאפליקציית "תאילנד – הספירה לאחור"

מה כלול:
- קובץ ה-HTML המקורי שחולץ מהקובץ שהועלה, בתוך app/src/main/assets/index.html
- אפליקציית Android מבוססת WebView
- JavaScript ו-DOM Storage מופעלים כדי שהספירה לאחור והצ'קליסט יעבדו וישמרו נתונים

איך לבנות APK:
1. פתחו את התיקייה ThailandCountdown ב-Android Studio.
2. המתינו ל-Gradle Sync והתקינו SDK 35 אם Android Studio מבקש.
3. בחרו Build > Build Bundle(s) / APK(s) > Build APK(s).
4. קובץ ה-APK יופיע בדרך כלל ב-app/build/outputs/apk/debug/app-debug.apk

הערות:
- הוסר טעינת Tailwind מה-CDN כי קובץ ה-HTML כבר מכיל CSS שנוצר מראש.
- גופן Rubik נטען מ-Google Fonts ולכן דורש אינטרנט; אם אין חיבור, יוצג גופן מערכת חלופי.
- קישורים חיצוניים נפתחים בדפדפן.
- זהו פרויקט מקור מוכן לבנייה, לא קובץ APK חתום/מותקן.
