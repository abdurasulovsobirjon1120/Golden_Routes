# **Golden Routes \- Functional Requirements**

## **1\. User Registration and Authentication**

**Title:** User Registration and Authentication  
**Description:** Foydalanuvchilar mobil ilovaga ro‘yxatdan o‘tishi, login qilish va profilinga kirish imkoniyatiga ega bo‘lishi kerak. Google, Apple ID va email orqali autentifikatsiya qo‘llab-quvvatlanadi.  
**Priority:** High  
**Requirement Acceptance Test (RAT):**

* Foydalanuvchi email yoki ijtimoiy tarmoq orqali ro‘yxatdan o‘tishi mumkin.  
* Email orqali tasdiqlash xati yuboriladi.  
* Parolni unutgan foydalanuvchilar tiklash funksiyasidan foydalanishi mumkin.

---

## **2\. Personalized Route Planning**

**Title:** Personalized Route Planning  
**Description:** Foydalanuvchilar o‘zining qiziqishlari va manzillari asosida shaxsiy sayohat marshrutlarini yaratish imkoniyatiga ega bo‘lishi kerak.  
**Priority:** High  
**Requirement Acceptance Test (RAT):**

* Foydalanuvchi turistik joylar, restoranlar va tadbirlarni marshrutiga qo‘shishi mumkin.  
* Ilova avtomatik ravishda optimal yo‘nalish yaratadi.  
* Foydalanuvchilar marshrutni saqlash va keyinchalik tahrirlash imkoniyatiga ega bo‘ladi.

---

## **3\. Offline Maps**

**Title:** Offline Maps Support  
**Description:** Foydalanuvchilar internetga ulanmagan holda ham xaritalardan foydalanish imkoniyatiga ega bo‘lishi kerak.  
**Priority:** Medium  
**Requirement Acceptance Test (RAT):**

* Foydalanuvchi xaritani oldindan yuklab olib, oflayn foydalanishi mumkin.  
* Joylashuv aniqligi saqlanadi va navigatsiya imkoniyati mavjud bo‘ladi.  
* Oflayn rejimda ham marshrutga o‘zgartirish kiritish mumkin.

---

## **4\. Tour Booking System**

**Title:** Tour Booking System  
**Description:** Foydalanuvchilar mahalliy gidlar va ekskursiyalarni bron qilish imkoniyatiga ega bo‘lishi kerak.  
**Priority:** High  
**Requirement Acceptance Test (RAT):**

* Foydalanuvchi turli ekskursiyalarni ko‘rib chiqishi va narxlarni solishtirishi mumkin.  
* Bronlash tugmachasi orqali ekskursiyalarni tasdiqlash va to‘lov qilish mumkin.  
* Foydalanuvchiga bron tasdiqlash xabarnomasi yuboriladi.

---

## **5\. User Reviews and Ratings**

**Title:** User Reviews and Ratings  
**Description:** Foydalanuvchilar ekskursiyalar, gidlar va turistik joylar haqida sharh qoldirish va reyting berish imkoniyatiga ega bo‘lishi kerak.  
**Priority:** Medium  
**Requirement Acceptance Test (RAT):**

* Har bir ekskursiya yoki xizmat uchun sharh yozish funksiyasi mavjud bo‘lishi kerak.  
* Foydalanuvchilar 1 dan 5 gacha baho qo‘yishi mumkin.  
* Moderatorlar nomaqbul sharhlarni o‘chirish imkoniyatiga ega bo‘lishi kerak.

---

## **6\. Multi-language Support**

**Title:** Multi-language Support  
**Description:** Ilova foydalanuvchilar turli tillarda foydalanishlari uchun tilni o‘zgartirish imkoniyatini qo‘llab-quvvatlashi kerak. **Priority:** Medium  
**Requirement Acceptance Test (RAT):**

* Ilova o‘zbek, ingliz, rus va boshqa tillarni qo‘llab-quvvatlashi kerak.  
* Foydalanuvchi interfeys tilini o‘z xohishiga ko‘ra o‘zgartira olishi kerak.

---

## **7\. Secure Payment System**

**Title:** Secure Payment System  
**Description:** Foydalanuvchilar ekskursiyalar yoki xizmatlar uchun xavfsiz to‘lovlarni amalga oshirish imkoniyatiga ega bo‘lishi kerak.  
**Priority:** High  
**Requirement Acceptance Test (RAT):**

* Ilova Visa, MasterCard, Payme va Click kabi to‘lov tizimlarini qo‘llab-quvvatlashi kerak.  
* Har bir tranzaksiya shifrlangan bo‘lishi kerak.  
* To‘lov muvaffaqiyatli amalga oshirilganda, foydalanuvchi kvitansiya olishi kerak.

---

## **8\. Real-time Customer Support**

**Title:** Real-time Customer Support  
**Description:** Foydalanuvchilarga real vaqtda mijozlarni qo‘llab-quvvatlash xizmati taqdim etilishi kerak.  
**Priority:** Medium  
**Requirement Acceptance Test (RAT):**

* Foydalanuvchilar chat yoki telefon orqali qo‘llab-quvvatlash xizmatiga bog‘lanish imkoniyatiga ega bo‘lishi kerak.  
* Chatbot yordamida tez-tez beriladigan savollarga avtomatik javob berish tizimi mavjud bo‘lishi kerak.  
* Xizmat ko‘rsatuvchi jamoa 24/7 ishlash imkoniyatiga ega bo‘lishi kerak.

---

## **9\. Push Notifications**

**Title:** Push Notifications  
 **Description:** Ilova foydalanuvchilarga muhim bildirishnomalarni yuborish imkoniyatiga ega bo‘lishi kerak.  
 **Priority:** Medium  
 **Requirement Acceptance Test (RAT):**

* Foydalanuvchilar bron qilingan xizmatlar haqida eslatmalar olishi kerak.  
* Yangi ekskursiyalar va chegirmalar haqida avtomatik xabarnomalar kelishi kerak.  
* Foydalanuvchilar bildirishnomalarni yoqish yoki o‘chirish imkoniyatiga ega bo‘lishi kerak.

---

## **10\. Social Media Integration**

**Title:** Social Media Integration  
 **Description:** Foydalanuvchilar o‘z sayohat tajribalarini ijtimoiy tarmoqlarda ulashish imkoniyatiga ega bo‘lishi kerak.  
 **Priority:** Low  
 **Requirement Acceptance Test (RAT):**

* Ilova Facebook, Instagram va Telegram bilan integratsiyalashgan bo‘lishi kerak.  
* Foydalanuvchilar o‘z marshrutlarini ijtimoiy tarmoqlarda ulashishi mumkin bo‘lishi kerak.  
* Ilova ijtimoiy tarmoqlarga avtomatik ravishda reklama e’lon qilish imkoniyatiga ega bo‘lishi kerak.

# **Golden Routes \- Functional Requirements**

## **1\. User Registration & Authentication**

**ID:** FR1  
 **TITLE:** User Registration & Authentication  
 **DESC:** Foydalanuvchilar platformaga ro‘yxatdan o‘tishi va autentifikatsiya qilinishi kerak. Ilovaga elektron pochta, telefon raqami yoki ijtimoiy tarmoqlar orqali kirish mumkin bo‘lishi lozim.  
 **PRIORITY:** High  
 **RAT:** Functional  
 **DEP:** No dependencies

## **2\. Personal Profile Management**

**ID:** FR2  
**TITLE:** Personal Profile Management  
**DESC:** Foydalanuvchilar o‘z profilini yaratishi, tahrirlashi va sayohat afzalliklarini belgilashi mumkin bo‘lishi kerak.  
**PRIORITY:** Medium  
**RAT:** Functional  
**DEP:** FR1

## **3\. Route Planning & Customization**

**ID:** FR3  
**TITLE:** Route Planning & Customization  
**DESC:** Foydalanuvchilar o‘zlarining sayohat yo‘nalishlarini rejalashtirishi, marshrutlarni qo‘shishi va o‘ziga moslashtira olishi kerak.  
**PRIORITY:** High  
**RAT:** Functional  
**DEP:** FR1, FR2

## **4\. QR Code Integration**

**ID:** FR4  
**TITLE:** QR Code for Tourist Spots  
**DESC:** Har bir turistik joy uchun QR kod mavjud bo‘lishi va u orqali batafsil ma’lumot olish imkoniyati yaratilishi kerak.  
**PRIORITY:** Medium  
**RAT:** Functional  
**DEP:** FR3

## **5\. Offline Map Support**

**ID:** FR5  
 **TITLE:** Offline Map Support  
 **DESC:** Foydalanuvchilar oldindan yuklab olingan xaritalar orqali internetga ulanmasdan turib joylarni topa olishlari kerak.  
 **PRIORITY:** High  
 **RAT:** Functional  
 **DEP:** FR3

## **6\. Tour Guide Booking**

**ID:** FR6  
 **TITLE:** Tour Guide Booking System  
 **DESC:** Foydalanuvchilar mahalliy gidlar bilan bog‘lanib, ekskursiyalarni oldindan bron qila olishlari kerak.  
 **PRIORITY:** High  
 **RAT:** Functional  
 **DEP:** FR1, FR3

## **7\. Payment Integration**

**ID:** FR7  
 **TITLE:** Secure Payment System  
 **DESC:** Foydalanuvchilar ekskursiyalar yoki xizmatlar uchun ilova orqali xavfsiz to‘lovlarni amalga oshira olishlari kerak (Payme, Click, Visa, MasterCard).  
 **PRIORITY:** High  
 **RAT:** Functional  
 **DEP:** FR6

## **8\. Review & Rating System**

**ID:** FR8  
 **TITLE:** Review & Rating System  
 **DESC:** Foydalanuvchilar xizmatlarni baholashi va sharh qoldirishi mumkin bo‘lishi kerak.  
 **PRIORITY:** Medium  
 **RAT:** Functional  
 **DEP:** FR6

## **9\. Multi-Language Support**

**ID:** FR9  
 **TITLE:** Multi-Language Support  
 **DESC:** Ilova bir nechta tilda (o‘zbek, ingliz, rus va boshqalar) ishlashi kerak.  
 **PRIORITY:** High  
 **RAT:** Functional  
 **DEP:** No dependencies

## **10\. Push Notifications**

**ID:** FR10  
 **TITLE:** Push Notifications  
 **DESC:** Foydalanuvchilarga yangiliklar, eslatmalar va maxsus takliflar haqida push xabarnomalar yuborilishi kerak.  
 **PRIORITY:** Medium  
 **RAT:** Functional  
 **DEP:** FR1

## **11\. Emergency Assistance Feature**

**ID:** FR11  
 **TITLE:** Emergency Assistance Feature  
 **DESC:** Foydalanuvchilar favqulodda holatlarda yordam chaqirish imkoniyatiga ega bo‘lishlari kerak.  
 **PRIORITY:** High  
 **RAT:** Functional  
 **DEP:** No dependencies

## **12\. Social Media Sharing**

**ID:** FR12  
 **TITLE:** Social Media Sharing  
 **DESC:** Foydalanuvchilar o‘z marshrutlarini va sayohat tajribalarini ijtimoiy tarmoqlarda o‘rtoqlashishi mumkin bo‘lishi kerak.  
 **PRIORITY:** Low  
 **RAT:** Functional  
 **DEP:** FR1

## **13\. AI-based Recommendation System**

**ID:** FR13  
**TITLE:** AI-based Personalized Recommendations  
**DESC:** Ilova foydalanuvchilarning qiziqishlari va oldingi tajribalariga asoslangan tavsiyalar berishi kerak.  
**PRIORITY:** Medium  
**RAT:** Functional  
**DEP:** FR1, FR3

## **14\. Data Analytics Dashboard**

**ID:** FR14  
**TITLE:** Data Analytics Dashboard  
**DESC:** Administratorlar foydalanuvchi faolligi va xizmatlardan foydalanish statistikalarini kuzata olishi uchun analitik panel bo‘lishi kerak.  
**PRIORITY:** High  
**RAT:** Functional  
**DEP:** No dependencies

