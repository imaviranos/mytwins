# 👶 Twin Feeder UI

מערכת מעקב האכלות חכמה לתאומים – פשוטה, נוחה, ועם ממשק בעברית 💡

---

## 🧭 מה זה עושה?

- מאפשר לבחור בין "תינוק 1" ו־"תינוק 2"
- מזינים כמות האכלה (במיליליטרים)
- הנתונים נשמרים אוטומטית בגיליון Google Sheets
- מוצגות 2 האכלות אחרונות לכל תינוק

---

## 🚀 איך זה עובד?

📦 פרויקט React שמתחבר ל־Google Apps Script דרך API פרוקסי ב־Vercel:

```
React (UI) → /api/feed (Vercel Proxy) → Google Apps Script → Google Sheets
```

---

## 🗂 מבנה תיקיות

```
twin-feeder-ui/
├── src/
│   └── App.js           # ממשק המשתמש
└── pages/
    └── api/
        └── feed.js      # API פרוקסי ל־Google Apps Script
```

---

## 🛠 טכנולוגיות

- React
- Google Sheets + Apps Script
- Vercel (פריסה חינמית בענן)
- Next.js API Routes (לשימוש פרוקסי)

---

## 🧪 דוגמה

<img src="https://i.imgur.com/FmSKtFB.png" width="500"/>

---

## 🤝 קרדיטים

פיתוח: [@aviran](mailto:aviran@bringg.com)  
סיוע טכני: ChatGPT 🚀

---

## 📄 רישיון

פרויקט זה פתוח לציבור – אפשר לשתף, לשכפל ולהשתמש חופשי 🧡