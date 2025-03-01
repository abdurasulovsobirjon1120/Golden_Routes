# **Business Requirements Document (BRD)**

## **1\. Project Overview**

**Project Name:** Golden Routes  
 **Prepared By:** Ilhomjon Begboyev Sharof o'g'li  
 **Date:** 24.02.2025  
 **Version:** 1.0

Golden Routes \- bu Oʻzbekiston va Markaziy Osiyoning eng yaxshi turistik marshrutlarini taqdim etuvchi mobil ilova bo‘lib, sayohatchilar uchun qulay rejalashtirish va yo‘nalishlarni topish imkoniyatini beradi.

## **2\. Business Objectives**

Golden Routes ilovasi quyidagi maqsadlarni ko‘zlaydi:

* Turistlarga shaxsiylashtirilgan marshrutlarni taklif qilish.  
* Mahalliy ekskursiyalar va gid xizmatlarini bir platformada jamlash.  
* Sayohat tajribalarini optimallashtirish va qulay rejalashtirish imkoniyatini taqdim etish.  
* Turizm sohasi tadbirkorlarini raqamli ekotizimga kiritish va ularga mijozlar oqimini oshirishga yordam berish.

## **3\. Business Scope**

Golden Routes ilovasi quyidagi imkoniyatlarni taqdim etadi:

* **Marshrut yaratish:** Foydalanuvchilar o‘z qiziqishlari asosida shaxsiy sayohat rejalarini yaratishlari mumkin.  
* **Oflayn xaritalar:** Internet ulanishsiz yo‘nalishlarni ko‘rish imkoniyati.  
* **Ekskursiyalar va tadbirlar:** Mahalliy ekskursiyalar va sayyohlik tadbirlarini bron qilish.  
* **Gidlar bilan bog‘lanish:** Mahalliy gidlar va sayohat tashkilotchilarining xizmatlarini izlash va ularga buyurtma berish.  
* **Foydalanuvchi tajribasi:** Sharhlar va reytinglar orqali xizmatlar haqida fikr bildirish.

## **4\. Stakeholders**

| Role | Description |
| :---- | :---- |
| **Project Owner** | Abdurasulov Sobirjon |
| **Developers** | Backend va mobil dasturchilar |
| **Design Team** | UX/UI dizaynerlar |
| **Tour Providers** | Ekskursiyalar, gidlar, sayohat agentliklari |
| **End Users** | Mahalliy va xorijiy sayohatchilar |

## **5\. Functional Requirements**

Foydalanuvchilar ro‘yxatdan o‘tishi va profilingizni yaratishi mumkin bo‘lishi kerak.

Geolokatsiya asosida turistik joylarni taklif qilish.

Sayohat marshrutlarini rejalashtirish va ularni saqlash.

Foydalanuvchi sharhlari va reytinglar tizimini qo‘llab-quvvatlash.

Mahalliy gidlar va ekskursiyalarni bron qilish imkoniyati.

To‘lov tizimlarini integratsiya qilish (Payme, Click, Visa, MasterCard).

Ko‘p tilli qo‘llab-quvvatlash (o‘zbek, ingliz, rus va boshqalar).

### **Funktsional Talablar**

| ID | Nomi | Tavsif | Ustuvorlik | Turi | Bog‘liqlik |
| :---- | :---- | :---- | :---- | :---- | :---- |
| FR1 | User Registration & Authentication | Foydalanuvchilar platformaga ro‘yxatdan o‘tishi va autentifikatsiya qilinishi kerak. | High | Functional | No dependencies |
| FR2 | Personal Profile Management | Foydalanuvchilar profil yaratishi va tahrirlashi mumkin. | Medium | Functional | FR1 |
| FR3 | Route Planning & Customization | Foydalanuvchilar sayohat marshrutlarini yaratishi va moslashtirishi kerak. | High | Functional | FR1, FR2 |
| FR4 | QR Code for Tourist Spots | Har bir turistik joy uchun QR kod orqali ma’lumot olish mumkin bo‘lishi kerak. | Medium | Functional | FR3 |
| FR5 | Offline Map Support | Oldindan yuklab olingan xaritalar orqali internetga ulanmasdan foydalanish mumkin. | High | Functional | FR3 |
| FR6 | Tour Guide Booking System | Mahalliy gidlar bilan bog‘lanish va ekskursiyalarni bron qilish imkoniyati. | High | Functional | FR1, FR3 |
| FR7 | Secure Payment System | Xizmatlar uchun xavfsiz to‘lov tizimi (Payme, Click, Visa, MasterCard). | High | Functional | FR6 |
| FR8 | Review & Rating System | Foydalanuvchilar xizmatlarni baholashi va sharh qoldirishi mumkin. | Medium | Functional | FR6 |
| FR9 | Multi-Language Support | Ilova bir nechta tilda ishlashi kerak. | High | Functional | No dependencies |
| FR10 | Push Notifications | Yangiliklar va maxsus takliflar haqida bildirishnomalar yuborish. | Medium | Functional | FR1 |
| FR11 | Emergency Assistance Feature | Favqulodda holatlarda yordam chaqirish imkoniyati. | High | Functional | No dependencies |
| FR12 | Social Media Sharing | Sayohat tajribalarini ijtimoiy tarmoqlarda ulashish. | Low | Functional | FR1 |
| FR13 | AI-based Personalized Recommendations | Foydalanuvchi qiziqishlari asosida tavsiyalar. | Medium | Functional | FR1, FR3 |
| FR14 | Data Analytics Dashboard | Adminlar uchun foydalanuvchi faolligi bo‘yicha analitik panel. | High | Functional | No dependencies |

## **6\. Non-Functional Requirements**

Ilovaning tezkor ishlashi va minimal kechikishlar bilan yuklanishi.

Data security va maxfiylikni ta’minlash.

Ilova oflayn rejimda ham ishlashini qo‘llab-quvvatlash.

Moslashuvchan va skalabil tizim arxitekturasi.

Platformalararo qo‘llab-quvvatlash (iOS, Android).

## **Nofunksional Talablar**

| ID | Kategoriya | Nomi | Tavsif | Ustuvorlik | Bog‘liqk |
| :---- | :---- | :---- | :---- | :---- | :---- |
| NFR1 | Ishlash unumdorligi | **Yuklama boshqaruvi** | Ilova kamida 10,000 faol foydalanuvchini qo‘llab-quvvatlashi kerak. | High | No dependencies |
| NFR2 | Xavfsizlik | **Ma’lumotlarning maxfiyligi** | GDPR, CCPA va boshqa xalqaro maxfiylik standartlariga mos kelishi kerak. | High | No dependencies |
| NFR3 | Ishonchlilik | **Tizimning barqarorligi** | Ilova uzluksiz ishlashi uchun 99.9% uptime kafolatlanishi kerak. | High | No dependencies |
| NFR4 | Texnik xizmat | **Tizimni yangilash va texnik qo‘llab-quvvatlash** | Modullarga ajratilgan kod bazasi bo‘lishi va tezkor yangilanishlar o‘rnatish imkoniyati kerak. | Medium | No dependencies |
| NFR5 | Foydalanuvchi tajribasi | **Oddiy va intuitiv interfeys** | Foydalanuvchilar uchun qulay UI/UX dizayni ishlab chiqilishi kerak. | High | No dependencies |
| NFR6 | Moslashuvchanlik | **Ko‘p platformali moslik** | Ilova Android, iOS va veb brauzerlar bilan mos bo‘lishi kerak. | High | No dependencies |
| NFR7 | Zaxira nusxa | **Ma’lumotlarni avtomatik saqlash** | Foydalanuvchilarning ma’lumotlari har kuni zaxira qilinishi kerak. | High | No dependencies |
| NFR8 | Qonunchilikka moslik | **Regulyativ talablar** | O‘zbekiston va xalqaro turizm qonunlariga mos kelishi kerak. | Medium | No dependencies |
| NFR9 | Tillarni qo‘llab-quvvatlash | **Ko‘p tilli qo‘llab-quvvatlash** | O‘zbek, rus, ingliz va boshqa tillarda ishlash imkoniyati bo‘lishi kerak. | Medium | No dependencies |
| NFR10 | Monitoring | **Tizim monitoringi** | Real vaqt rejimida xatolar va tizim ishlash holatini kuzatish imkoniyati kerak. | High | No dependencies |

## **7\. Risk Analysis**

| Risk | Probability | Mitigation Strategy |
| :---- | :---- | :---- |
| Raqobatbardosh bozor | O‘rta | Differensial xizmatlar va innovatsion funksiyalar qo‘shish |
| Foydalanuvchilar kamligi | Yuqori | Marketing strategiyasi va SEO optimizatsiyasi |
| Texnik nosozliklar | Past | Doimiy texnik monitoring va testlash |
| Ma’lumotlar xavfsizligi | O‘rta | Kuchli autentifikatsiya va shifrlash tizimlari |

## **8\. Success Metrics**

Golden Routes muvaffaqiyatini o‘lchash uchun quyidagi mezonlar ishlatiladi:

* Ilovani yuklab olgan foydalanuvchilar soni.  
* Foydalanuvchilar faolligi va ulanish davomiyligi.  
* Bron qilingan ekskursiyalar va yo‘nalishlar soni.  
* Foydalanuvchilar sharhlari va reytinglari.  
* Platformaga qo‘shilgan mahalliy hamkorlar soni.

## **9\. Timeline**

| Task | Duration | Status |
| :---- | :---- | :---- |
| BRD tayyorlash | 1 hafta | Done |
| UI/UX dizayn yaratish | 2-3 hafta | Pending |
| Backend va mobil dasturlash | 2-3 oy | Pending |
| Testlash va debugging | 1 oy | Pending |
| Beta versiya ishga tushirish | 2 hafta | Pending |
| Rasmiy versiya chiqarish | 3 oy | Pending |

---

## **10\. Conclusion**

Golden Routes O‘zbekistonda va Markaziy Osiyoda sayohat qilishni qulaylashtirish uchun mo‘ljallangan innovatsion platforma bo‘lib, turizm industriyasini raqamli ekotizim bilan bog‘lashga xizmat qiladi. Ushbu BRD loyiha rivojlanishi uchun asosiy yo‘nalishlarni belgilab beradi va keyingi bosqichlarga tayyorgarlik ko‘rish imkonini beradi.

## **Texnik Talablar**

| ID | Kategoriya | Nomi | Tavsif | Ustuvorlik | Bog‘liqlik |
| :---- | :---- | :---- | :---- | :---- | :---- |
| TR1 | Arxitektura | **Microservices arxitekturasi** | Ilova modullarga bo‘lingan microservices arxitekturasi asosida ishlashi kerak. | High | No dependencies |
| TR2 | Backend | **Dastur server qismi** | Backend **Django (Python)** asosida ishlab chiqilishi kerak. | High | No dependencies |
| TR3 | Frontend | **Dastur old qismi** | Ilova interfeysi **Flutter** orqali ishlab chiqilishi kerak. | High | No dependencies |
| TR4 | Ma’lumotlar bazasi | **Ma’lumotlarni saqlash tizimi** | PostgreSQL ma’lumotlar bazasi ishlatilishi kerak. | High | No dependencies |
| TR5 | API | **RESTful API aloqasi** | Frontend va backend RESTful API orqali bog‘lanishi kerak. | High | TR2, TR3 |
| TR6 | Bulutli xizmatlar | **Ilovani joylashtirish** | Ilova **AWS yoki Google Cloud** serverlarida joylashtirilishi kerak. | High | No dependencies |
| TR7 | Xavfsizlik | **Foydalanuvchi autentifikatsiyasi** | JWT yoki OAuth2 yordamida foydalanuvchi autentifikatsiyasi amalga oshirilishi kerak. | High | TR2 |
| TR8 | Xavfsizlik | **Ma’lumotlarni shifrlash** | Foydalanuvchi ma’lumotlari shifrlangan formatda saqlanishi kerak. | High | TR2, NFR2 |
| TR9 | Ishlash unumdorligi | **Ma’lumotlar kechiktirilishini optimizatsiya qilish** | So‘rovlarni kechiktirmasdan (≤200ms) qayta ishlash uchun **Redis yoki Memcached** ishlatilishi kerak. | Medium | TR4 |
| TR10 | Analitika | **Ma’lumotlar tahlili paneli** | Administratorlar uchun foydalanuvchi faolligi bo‘yicha analitik vositalar qo‘shilishi kerak. | High | No dependencies |
| TR11 | Bildirishnomalar | **Push xabarlarni jo‘natish** | Firebase yoki boshqa servis orqali push bildirishnomalar yuborish imkoniyati bo‘lishi kerak. | Medium | TR5 |
| TR12 | Ulanish | **GPS va xarita integratsiyasi** | Google Maps yoki OpenStreetMap bilan bog‘lanish kerak. | High | No dependencies |
| TR13 | Moslik | **Ko‘p qurilmali moslik** | Ilova **mobil, planshet va veb** versiyalarida to‘g‘ri ishlashi kerak. | High | No dependencies |

### **Work Breakdown Structure**

### **1\. Loyiha boshqaruvi (Project Management)**

1.1. Loyiha rejasini tuzish  
1.2. Risklarni aniqlash va boshqarish  
1.3. Resurslarni taqsimlash  
1.4. Jamoani shakllantirish  
1.5. Moliya va byudjet nazorati

### **2\. Dasturiy ta’minotni ishlab chiqish (Software Development)**

**2.1. Tizim arxitekturasi va dizayni**

2.1.1. UML diagrammalarni yaratish

2.1.2. Ma’lumotlar bazasi tuzilishini ishlab chiqish

2.1.3. API va backend strukturasini belgilash

**2.2. Frontend ishlab chiqish**

2.2.1. UI/UX dizayni

2.2.2. Mobil ilova yaratish (Flutter)

2.2.3. Veb sayt yaratish (React yoki Next.js)

**2.3. Backend ishlab chiqish**

2.3.1. Django yordamida server qismini yaratish

2.3.2. API-larni ishlab chiqish

2.3.3. Ma’lumotlar bazasini optimallashtirish

**2.4. Integratsiyalar**

2.4.1. To‘lov tizimi (Payme, Click, Stripe)

2.4.2. Google Maps API qo‘shish

2.4.3. Telegram bot va notifikatsiyalar

### **3\. Test va sifat nazorati (Testing & QA)**

3.1. Unit testlar yozish  
3.2. Funksional testlarni o‘tkazish  
3.3. Xatolarni aniqlash va tuzatish  
3.4. Yaxshilashlar va optimizatsiya

### **4\. Ishga tushirish va ekspluatatsiya (Deployment & Maintenance)**

4.1. Server va hosting sozlash  
4.2. Ilovani Play Store va App Store’ga joylash  
4.3. Veb sayti va mobil ilovalarni monitoring qilish  
4.4. Mijozlarning fikr-mulohazalarini yig‘ish  
4.5. Yangilanishlarni chiqarish va qo‘llab-quvvatlash

