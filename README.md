Event propagation — bu DOM elementda hodisa yuz berganda, u qanday tartibda boshqa elementlarga tarqalishini anglatadi.

Capturing (yoki capture phase) — hodisa DOM daraxtining yuqorisidan pastga qarab harakat qiladi, ya’ni documentdan boshlanib, hodisa yuz bergan elementga yetib boradi.

Target phase — bu bosqichda hodisa aynan o‘sha elementda bajariladi (ya’ni target bo‘lgan elementda).

Bubbling (yoki bubble phase) — hodisa yuz bergan elementdan boshlanib, DOM daraxtining yuqorisiga qarab ota-elementlarga tarqaladi.

Agar addEventListener funksiyasida uchinchi argument sifatida true berilsa, listener capturing bosqichida ishlaydi.

Agar false yoki hech narsa berilmasa, listener bubbling bosqichida ishlaydi.

stopPropagation() metodi yordamida hodisaning keyingi ota-elementlarga tarqalishi to‘xtatiladi.



Git and Github
Netlify
✅ Deploy website with Drag & Drop 👍🏻
✅ Deploy website with Github link


🧩 Git nima?
Git — bu versiyalarni boshqarish tizimi (Version Control System, VCS). Asosan dasturchilar tomonidan kod o'zgarishlarini kuzatish, hamkorlikda ishlash va oldingi versiyalarni saqlash uchun ishlatiladi.
 
Git'ning asosiy imkoniyatlari:
Kodingizning har bir versiyasi saqlanadi.

Har qanday vaqtda oldingi holatga qaytish mumkin.

Jamoaviy ishlashda qulaylik yaratadi.

Branch (shoxcha) yaratib, yangi funksiyalar ustida mustaqil ishlash mumkin.

☁️ GitHub nima?
GitHub — bu Git repozitoriylarini onlayn saqlash va hamkorlik qilish uchun platforma. U Git tizimiga asoslangan va dunyodagi eng mashhur kod host xizmatlaridan biri.

GitHub orqali:
Git repozitoriyangizni onlayn saqlaysiz.

Boshqa dasturchilar bilan hamkorlikda ishlaysiz.

Pull Request (PR) orqali o'zgarishlarni muhokama qilasiz.

Issues bo'limida muammolarni kuzatishingiz mumkin.

GitHub Actions orqali Continuous Integration/Deployment (CI/CD) qilish mumkin.

