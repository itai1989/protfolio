# 🚀 Full-Stack & DevOps Portfolio Project | Itai Turgeman

ברוכים הבאים לפרויקט הסיכום שלי במסגרת לימודי הנדסת תוכנה ב**מכללת כנרת**. פרויקט זה מציג תשתית DevOps מלאה המארחת מספר אפליקציות בסביבת ענן מנוהלת.

---

## 🌐 קישורים חיים (Live Demo)
* **פורטפוליו אישי:** [http://130.110.238.128:3001](http://130.110.238.128:3001)
* **חנות תחפושות (React):** [http://130.110.238.128:3002](http://130.110.238.128:3002)
* **מעקב לחץ דם (Node.js & MySQL):** [http://130.110.238.128:3003](http://130.110.238.128:3003)

---

## 🏗️ ארכיטקטורת המערכת
הפרויקט מבוסס על ארכיטקטורת Microservices המנוהלת באמצעות **Docker Compose** ומורכבת מהרכיבים הבאים:

1.  **Portfolio Hub:** שרת Nginx המגיש את דף הנחיתה המרכזי.
2.  **Costume Store (Frontend):** אפליקציית React המוגשת בתוך קונטיינר Nginx ייעודי.
3.  **Health Tracker (Backend):** שרת Node.js (Express) המנהל API מול מסד נתונים.
4.  **Database:** מסד נתונים MySQL עם Persistence מבוסס Docker Volumes לשמירת מידע קבועה.

---

## 🛠️ סט טכנולוגי (Tech Stack)
* **Infrastructure:** Oracle Cloud (OCI) - Ubuntu Instance.
* **Containerization:** Docker, Docker Compose.
* **CI/CD Pipeline:** GitHub Actions.
* **Frontend:** React.js, HTML5, CSS3.
* **Backend:** Node.js, Express.
* **Database:** MySQL.
* **Web Server:** Nginx.

---

## 🔄 תהליך ה-CI/CD
בפרויקט זה הוטמע תהליך אוטומציה מלא (Continuous Integration & Deployment):
1.  **Code Push:** שליחת קוד ל-GitHub.
2.  **Build & Push:** GitHub Actions בונה Image חדש לכל שירות.
3.  **Docker Hub:** האימג'ים נדחפים למאגר המרכזי ב-Docker Hub.
4.  **Auto Deploy:** ה-Actions מתחבר לשרת ה-Oracle Cloud באמצעות SSH, מושך את האימג'ים המעודכנים ומריץ אותם מחדש.



---

## 👤 אודותיי
**איתי תורג'מן**
סטודנט שנה אחרונה להנדסאי תוכנה במכללת כנרת.
מתמחה בפיתוח Full-Stack עם תשוקה לעולמות ה-DevOps והאוטומציה.

---
*פרויקט זה הוגש כחלק מדרישות הקורס במכללת כנרת, פברואר 2026.*