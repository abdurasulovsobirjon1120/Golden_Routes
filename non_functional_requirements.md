# **Golden Routes \- Non-Functional Requirements**

## **1\. Performance and Scalability**

## **Description:** Ilova yuqori yuklamalarda ham samarali ishlashi va kelajakda foydalanuvchilar soni oshganida muammosiz kengaytirilishi kerak.  **Priority:** High  **Requirement Acceptance Test (RAT):**

Ilova 10,000+ faol foydalanuvchiga xizmat ko‘rsatishi kerak.

Sahifalar yuklanish vaqti 2 soniyadan oshmasligi kerak.

Backend serverlar avtomatik miqyoslana olishi kerak.

## **2\. Security and Data Privacy**

## **Description:** Foydalanuvchilarning shaxsiy ma’lumotlari xavfsiz saqlanishi va uchinchi shaxslarga oshkor qilinmasligi kerak.  **Priority:** High  **Requirement Acceptance Test (RAT):**

Ilova foydalanuvchi ma’lumotlarini shifrlangan holda saqlashi kerak.

HTTPS protokoli orqali barcha ma’lumot almashinuvi amalga oshirilishi kerak.

Kirish va autentifikatsiya uchun ikki faktorli himoya qo‘llanilishi kerak.

## **3\. Usability and User Experience**

## **Description:** Ilova intuitiv interfeys va qulay navigatsiyaga ega bo‘lishi, turli yoshdagi foydalanuvchilar uchun tushunarli bo‘lishi kerak.  **Priority:** High  **Requirement Acceptance Test (RAT):**

Foydalanuvchilar kamida 90% hollarda asosiy funksiyalarni oson topa olishi kerak.

Minimal UI dizayn qoidalariga rioya qilinishi kerak.

Mobil ilovada bir qo‘l bilan foydalanish imkoniyati ta’minlanishi kerak.

## **4\. Availability and Reliability**

## **Description:** Ilova doimiy ravishda ishlashi va minimal uzilishlarga ega bo‘lishi kerak.  **Priority:** High  **Requirement Acceptance Test (RAT):**

Ilova 99.9% uptime kafolati bilan ishlashi kerak.

Server nosozligi yuzaga kelganda avtomatik tiklanish mexanizmi bo‘lishi kerak.

Asosiy xizmatlar 24/7 monitoring qilinishi kerak.

## **5\. Compatibility**  

## **Description:** Ilova turli operatsion tizimlar va qurilmalarda ishlashi kerak.  **Priority:** Medium  **Requirement Acceptance Test (RAT):**

Ilova Android va iOS platformalarida to‘g‘ri ishlashi kerak.

Ekran o‘lchamlarining moslashuvchanligini ta’minlash kerak.

Ilova eski va yangi qurilmalarda muammosiz ishlashi lozim.

## **6\. Maintainability and Code Quality**

**Description:** Ilova kod bazasi yaxshi hujjatlashtirilgan, tushunarli va kengaytirishga mos bo‘lishi kerak.  
 **Priority:** Medium  
 **Requirement Acceptance Test (RAT):**

Kod 80% dan ortiq qismi unit-testlar bilan qamrab olingan bo‘lishi kerak.

Kod Google va Airbnb kod yozish standartlariga mos bo‘lishi kerak.

Yangi xususiyatlar qo‘shish jarayoni minimal qiyinchilik bilan amalga oshirilishi kerak.

## **7\. Legal and Compliance**

**Description:** Ilova O‘zbekiston va xalqaro qonunchilikka muvofiq ishlab chiqilishi kerak.  
 **Priority:** High  
 **Requirement Acceptance Test (RAT):**

Ilova GDPR va O‘zbekiston shaxsiy ma’lumotlarni himoya qilish qonunlariga mos bo‘lishi kerak.

Foydalanuvchilar maxfiylik siyosati bilan rozi bo‘lishi kerak.

Ma’lumotlar uchinchi shaxslarga ruxsatsiz taqdim etilmasligi kerak.

## **8\. Localization and Multilingual Support**

**Description:** Ilova turli tillarda ishlashi va foydalanuvchilarning madaniy o‘ziga xosliklariga moslashishi kerak.  
 **Priority:** Medium  
 **Requirement Acceptance Test (RAT):**

Ilova o‘zbek, rus, ingliz va boshqa tillarda ishlashi kerak.

Har bir til uchun to‘g‘ri tarjima va formatlash ta’minlanishi kerak.

Foydalanuvchi istalgan vaqtda tilni almashtirish imkoniyatiga ega bo‘lishi kerak.

## **9\. Backup and Disaster Recovery**

**Description:** Ilova nosozliklar yoki tizim ishdan chiqishiga qarshi xavfsiz tiklanish mexanizmlariga ega bo‘lishi kerak.  
 **Priority:** High  
 **Requirement Acceptance Test (RAT):**

Ma’lumotlar avtomatik ravishda kunlik backup qilinishi kerak.

Nosozlik yuzaga kelganda ma’lumotlarni tiklash jarayoni 30 daqiqadan oshmasligi kerak.

Favqulodda holatlar uchun avtomatik rezerv tizimi ishlashi kerak.

## **10\. Logging and Monitoring**

**Description:** Ilova ishlashini kuzatish va muammolarni tezkor aniqlash uchun monitoring va loglash tizimiga ega bo‘lishi kerak.  
 **Priority:** Medium  
 **Requirement Acceptance Test (RAT):**

Har qanday tizim xatosi logga yozilishi kerak.

Tizim real vaqt monitoring vositalari bilan kuzatilishi kerak.

Administrativ panel orqali barcha tizim ishlash ko‘rsatkichlari kuzatilishi kerak.

# **Golden Routes \- Non-Functional Requirements**

## **1\. Performance & Scalability**

**ID:** NFR1  
 **TITLE:** System Performance  
 **DESC:** Ilova bir vaqtning o‘zida kamida 10,000 faol foydalanuvchini qo‘llab-quvvatlashi va muammosiz ishlashi kerak.  
 **PRIORITY:** High  
 **RAT:** Non-Functional  
 **DEP:** No dependencies

## **2\. Security & Data Privacy**

**ID:** NFR2  
 **TITLE:** Secure User Data  
 **DESC:** Foydalanuvchilarning shaxsiy ma’lumotlari himoyalangan bo‘lishi va GDPR, CCPA kabi xalqaro maxfiylik standartlariga mos kelishi kerak.  
 **PRIORITY:** High  
 **RAT:** Non-Functional  
 **DEP:** No dependencies

## **3\. Availability & Reliability**

**ID:** NFR3  
 **TITLE:** System Uptime  
 **DESC:** Ilova 99.9% uptime bilan uzluksiz ishlashi va server nosozliklari oldindan bartaraf qilinishi kerak.  
 **PRIORITY:** High  
 **RAT:** Non-Functional  
 **DEP:** No dependencies

## **4\. Maintainability & Support**

**ID:** NFR4  
 **TITLE:** System Maintainability  
 **DESC:** Ilova kod bazasi modullarga ajratilgan bo‘lishi va tezkor yangilanishlar kiritish imkoniyatiga ega bo‘lishi kerak.  
 **PRIORITY:** Medium  
 **RAT:** Non-Functional  
 **DEP:** No dependencies

## **5\. Usability & Accessibility**

**ID:** NFR5

**TITLE:** User-Friendly Interface  
**DESC:** Ilova oddiy va intuitiv dizaynga ega bo‘lib, barcha yoshdagi foydalanuvchilar uchun qulay bo‘lishi kerak.  
 **PRIORITY:** High  
 **RAT:** Non-Functional  
 **DEP:** No dependencies

## **6\. Compatibility & Cross-Platform Support**

**ID:** NFR6  
 **TITLE:** Multi-Device Compatibility  
 **DESC:** Ilova iOS, Android va veb-platformalar bilan to‘liq mos kelishi kerak.  
 **PRIORITY:** High  
 **RAT:** Non-Functional  
 **DEP:** No dependencies

## **7\. Data Backup & Recovery**

**ID:** NFR7  
 **TITLE:** Automatic Data Backup  
 **DESC:** Ma’lumotlar har kuni avtomatik tarzda zaxira qilinishi va tizim buzilganda tezkor tiklanish imkoniyati bo‘lishi kerak.  
 **PRIORITY:** High  
 **RAT:** Non-Functional  
 **DEP:** No dependencies

## **8\. Legal & Compliance**

**ID:** NFR8  
 **TITLE:** Regulatory Compliance  
 **DESC:** Ilova O‘zbekiston qonunchiligi hamda xalqaro turizm qonunlariga mos ravishda ishlab chiqilishi kerak.  
 **PRIORITY:** Medium  
 **RAT:** Non-Functional  
 **DEP:** No dependencies

## **9\. Localization & Multi-Language Support**

**ID:** NFR9  
 **TITLE:** Multi-Language Support  
 **DESC:** Ilova o‘zbek, ingliz, rus va boshqa tillarni qo‘llab-quvvatlashi kerak.  
 **PRIORITY:** Medium  
 **RAT:** Non-Functional  
 **DEP:** No dependencies

## **10\. Logging & Monitoring**

**ID:** NFR10  
 **TITLE:** System Monitoring  
 **DESC:** Tizimda real vaqt rejimida monitoring qilish va xatolarni aniqlash imkoniyati bo‘lishi kerak.  
 **PRIORITY:** High  
 **RAT:** Non-Functional  
 **DEP:** No dependencies

