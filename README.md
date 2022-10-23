# CoronaSystem

-זהו פרויקט לניהול נתוני מגיפת קורונה עבור קופת חולים.

המערכת מחזיקה בנתוני הפציינטים של קופת החולים ומאפשרת עריכה, מחיקה חיפוש וצפייה בנתונים.

מסך הבית יראה כך:


![צילום מסך_20221023_150845](https://user-images.githubusercontent.com/116342618/197391334-4e0f5008-60af-471c-8b36-7d107e21ecb8.png)

ניתן להוסיף חבר חדש לקופה בלחיצה על ADD NEW PATIENT.

כך זה יראה:

![צילום מסך_20221023_150936](https://user-images.githubusercontent.com/116342618/197391442-63f8df0a-7afe-4d14-b498-f4fd5f5302d4.png)

עבור כל פציינט ניתן לצפות בנתונים אודותיו, לערוך את פרטיו או למחוק אותו מהמאגר.
כך זה יראה בהתאמה

![צילום מסך_20221023_150959](https://user-images.githubusercontent.com/116342618/197391479-505c6cbd-6a64-44af-baac-0d594043fc72.png)
![צילום מסך_20221023_151012](https://user-images.githubusercontent.com/116342618/197391481-043171c4-df9f-438c-9839-46460666a8a3.png)
![צילום מסך_20221023_151027](https://user-images.githubusercontent.com/116342618/197391483-6319480a-eaaf-4e4b-8d54-b710f2ca4e22.png)

כמו כן ניתן לחפש פציינט ספציפי עם סינון לפי מפתח של תעודת זהות

כך זה יראה:

![צילום מסך_20221023_151045](https://user-images.githubusercontent.com/116342618/197391528-b44a7f0f-2f4e-4a1d-802b-5bee3a18bdb3.png)


השתמשתי בסביבת עבודה (שהייתה חדשה לי) VISUAL-STUDIO 
יצרתי פרויקט מסוגasp.net core שעושה שימוש בMVC 

זה מה שכתוב documents של Microsoft על הפרויקט:

ASP.NET Core MVC is a rich framework for building web apps and APIs using the Model-View-Controller design 
pattern

הנה קישור-

https://learn.microsoft.com/en-us/aspnet/core/mvc/overview

 חיברתי לפרויקט database מסוג sqlserver.
 
על מנת לחבר את הdatabase הייתי צריכה להוריד כמה packages להוסיף בנאי וליצור תקיעה של Data

מכיון שתחום זה הינו חדש לי לא הספקתי לבדוק בשלמות את תקינות הקלטים שמוזנים למערכת.

תודה רבה ובדיקה נעימה!😃
