# QuizzGuide

### **Direcție tematică:**

P7. Învățare și evaluare educațională. Quiz-uri, planuri de studiu, bănci de exerciții, feedback formativ, analiză de progres și asistență pentru organizarea învățării.

**Problema:** Procesul educațional este afectat de lipsa de personalizare a învățării, de feedback-ul întârziat și de dificultatea cu care profesorii reușesc să centralizeze rapid progresul pe termen scurt al elevilor.

**Scopul:** Ușurarea muncii profesorilor și sprijinirea elevilor în a avea un proces de învățare mai personalizat cu feedback formativ.

**Utilizatorii vizați:** Elevii și profesorii

### **Obiective:**
- Permiterea profesorilor să creeze, editeze și șteargă quiz-uri pentru elevii de gimnaziu și liceu
- Oferirea către elevi a unui feedback formativ imediat după rezolvarea unui quiz
- Protejarea intimității elevilor prin opțiunea de a rezolva quiz-urile anonim
- Implementarea unui control al accesului, astfel încât fiecare quiz să fie vizibil doar persoanelor alese de profesor
- Permiterea importului și exportului de quiz-uri în format CSV, pentru reutilizarea lor

### **Membrii echipei și responsabilități:** 
- Hutopila Gianina-Brîndusa (gianina.hutopila05@e-uvt.ro)
  - Leader
  - Backend developer
- Grijincu Alexandra-Ștefania (alexandra.grijincu05@e-uvt.ro)
  - Frontend developer

### **Funcționalități principale propuse:**
 - **Obligatorii:**
   - Crearea și publicarea quiz-urilor. Profesorul creează un quiz cu mai multe întrebări, alege elevii care îl pot vedea și îl publică. Rezultat: elevii selectați văd quiz-ul în lista lor.
   - Feedback formativ automat. Elevul rezolvă un quiz și îl trimite. Rezultat: vede imediat scorul și explicația pentru fiecare răspuns greșit.
   - Gestionarea accesului. Profesorul adaugă sau scoate elevi dintr-un quiz. Rezultat: doar persoanele alese pot vedea și rezolva quiz-ul.
 - _Opționale:_
   - Anonimat. Elevul bifează opțiunea de anonimat înainte de a rezolva un quiz. Rezultat: profesorul vede rezultatul, dar nu și numele elevului.
   - Feedback ulterior. Profesorul vede rezultatele unui elev și adaugă un comentariu. Rezultat: elevul vede comentariul la quiz-ul respectiv.

### **Tehnologii propuse:**

Backend: Spring Boot

Frontend: HTML, CSS, JavaScript

Bază de date: PostgreSQL
