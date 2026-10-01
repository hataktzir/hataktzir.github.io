# התקציר - hataktzir.github.io

האתר של **התקציר**: מערכת AI שמקצרת תוכן ארוך לקליפים מוכנים לפרסום, בלי עריכה ידנית בשום שלב.
המערכת מתמללת את הוידאו, מודל שפה בוחר את הרגעים ששווה לראות, והיא חותכת, כותבת כותרת ותיאור, בונה תמנייל, נותנת קרדיט ליוצר ומעלה.
התחלנו בלייבים של סטרימרים ישראלים ביוטיוב. הכיוון: הרצאות, פודקאסטים, אימוני כושר, וכל וידאו ארוך.

- **האתר:** https://hataktzir.github.io
- **הערוץ:** https://www.youtube.com/@hataktzir
- **הקוד של המערכת:** https://github.com/lironobel/hataktzir
- **יצירת קשר:** lironn217@gmail.com

## מה יש בריפו הזה

| קובץ | מה הוא |
|---|---|
| `index.html` | דף המוצר. כולל ריצה אמיתית של הצינור על לייב של 11.7 שעות (29.9.2026), עם גרף לחיץ ויומן ריצה. |
| `demo/` | התמניילים שהמערכת בנתה באותה ריצה, ו-`og.png` לתצוגה בשיתוף ברשתות. |
| `privacy.html` | מדיניות הפרטיות של "hataktzir uploader", הכלי הפרטי שמעלה קליפים לערוץ דרך YouTube Data API. **גוגל דורש את הדף הזה להרשאת היוטיוב, ואין לשנות או למחוק אותו.** |

האתר הוא HTML סטטי, בלי build, ומתפרסם דרך GitHub Pages מהענף `main`.

---

## In English

Website for **Hataktzir**, an AI system that shortens long-form video into ready-to-publish clips with no manual editing: transcription, LLM moment selection, cutting, titles, thumbnails, creator credit and upload. It started with Israeli livestreamers on YouTube; lectures, podcasts and fitness content are next.

- `index.html`: product page with a real, interactive pipeline run.
- `privacy.html`: privacy policy for "hataktzir uploader", the private tool that uploads clips to the channel via the YouTube Data API. Required by Google for the OAuth app; do not remove.
- Source code: https://github.com/lironobel/hataktzir
