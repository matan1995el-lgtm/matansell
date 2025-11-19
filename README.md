# מערכת ניהול שעות חודשיות - פיל ומתן

מערכת מלאה לניהול שעות עבודה חודשיות עבור שני עובדים (פיל ומתן), כולל חישובי שעות, סטטוס התאמה, סיכום שבועי, סטטיסטיקות חודשיות, ייבוא/ייצוא, שמירה וטעינה מקומית, והגדרות עיצוב ולוגיקה.

## 🚀 פריסה ב־Vercel

1. צור ריפו חדש ב־GitHub והעלה אליו את הקבצים הבאים:
   - `index.html`
   - תיקייה `public/` עם שלושת הקבצים:
     - `xlsx.full.min.js`
     - `jspdf.umd.min.js`
     - `jspdf.plugin.autotable.min.js`

2. ודא שהקובץ `index.html` נמצא **בשורש הריפו** – כלומר לא בתוך תיקייה כמו `src/` או `pages/`.

3. התחבר ל־[Vercel](https://vercel.com), בחר את הריפו שלך → לחץ Deploy.

4. סיים! האתר שלך מוכן לשימוש.

## 📁 מבנה תיקיות
your-repo/ ├── index.html └── public/ ├── xlsx.full.min.js ├── jspdf.umd.min.js └── jspdf.plugin.autotable.min.js


## 📦 פיצ'רים עיקריים

- יצירת טבלה חודשית לפי חודש ושנה
- הזנת שעות כניסה/יציאה לפיל ומתן
- חישוב סה״כ שעות וסטטוס התאמה
- סיכום שבועי וסטטיסטיקות חודשיות
- ייבוא מקובץ Excel
- ייצוא ל־Excel ו־PDF
- שמירה וטעינה מקומית
- הגדרות עיצוב ולוגיקה
- תמיכה מלאה בעברית ו־RTL
- רספונסיביות מלאה

## 📥 הורדת קבצי ספריות לתיקיית `public`

1. **xlsx.full.min.js**  
   - [הורדה ישירה](https://cdn.sheetjs.com/xlsx-latest/package/dist/xlsx.full.min.js)

2. **jspdf.umd.min.js**  
   - [הורדה ישירה](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js)

3. **jspdf.plugin.autotable.min.js**  
   - [הורדה ישירה](https://cdnjs.cloudflare.com/ajax/libs/jspdf-autotable/3.5.25/jspdf.plugin.autotable.min.js)

📌 לאחר ההורדה, שים את שלושת הקבצים בתיקייה בשם `public` בתוך הריפו שלך.


