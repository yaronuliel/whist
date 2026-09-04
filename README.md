# וויסט — ברושור וחוקי המשחק

עמוד HTML יחיד (ללא תלויות חיצוניות) המרכז את חוקי משחק הקלפים וויסט בעברית.

## הפעלה מקומית

פתחו את `index.html` בדפדפן, או:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## פרסום ב־GitHub Pages

הפרסום אוטומטי דרך GitHub Actions — ראו [.github/workflows/deploy.yml](.github/workflows/deploy.yml).

1. צרו ריפו ב־GitHub ודחפו את הענף `main`.
2. ה־workflow ירוץ, יבנה את ענף `gh-pages` וידחוף אליו את תוכן הריפו.
3. ב־**Settings → Pages** בחרו **Source: Deploy from a branch**, ענף `gh-pages`, תיקייה `/ (root)`.
   (הענף נוצר רק אחרי ההרצה הראשונה — אם הוא לא מופיע ברשימה, המתינו שה־workflow יסתיים.)
4. האתר יעלה בכתובת `https://<user>.github.io/<repo>/`.

כל דחיפה ל־`main` מפרסמת מחדש. אפשר גם להריץ ידנית מלשונית **Actions** (`Run workflow`).

הקובץ `.nojekyll` מונע מ־Jekyll לעבד את התוכן, כך שהקובץ מוגש כפי שהוא.

## הדפסה

העמוד כולל עיצוב הדפסה ל־A4 (`@media print`) — הדפיסו מהדפדפן או שמרו כ־PDF.
