# dolev2/.github

טפסי ה-issues (`task.yml`, `bug.yml`, `config.yml`) של כל הריפואים של dolev2, במקום אחד.

GitHub מציג את הטפסים מכאן בכל ריפו של החשבון שאין לו תיקיית `.github/ISSUE_TEMPLATE` משלו, גם בריפו פרטי.
ריפו עם תיקייה כזו מאבד את כל הטפסים מכאן, לא רק את הקובץ שהוא דורס.

הכותרות בטפסים הן חוזה של צינור העבודה: שלב התכנון כותב לסעיף Plan, ושער השאלות קורא את "שאלות פתוחות".
לכן שינוי בכותרת מחייב עדכון של הסקילים ב-[dolev2/claude-config](https://github.com/dolev2/claude-config) (`dev-setup/reference/pipeline.md`).

**כל תווית שטופס מוסיף חייבת להיות קיימת גם כאן**, ולא רק בריפו שבו נפתח ה-issue. כרגע: `task`, `bug`, `owner:claude`, `status:explore`, `status:ready-to-execute`. תווית חדשה בטופס נוצרת כאן באותו commit (`gh label create <name> -R dolev2/.github`).

**הריפו חייב להישאר ציבורי.** GitHub משתמש בברירות המחדל רק מריפו `.github` ציבורי.
