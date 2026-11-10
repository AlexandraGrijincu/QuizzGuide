# Diagrama de arhitectura
<img width="1310" height="731" alt="Diagrama" src="https://github.com/user-attachments/assets/59e163c1-ead5-4878-ac79-eda22261ddff" />

### Descrierea arhitecturii

Această diagramă este arhitectura aplicației QuizzGuide. Aplicația este structurată în două medii principale.
#### Frontend
Tehnologiile folosite pentru Frontend sunt HTMLL, CSS și JavaScript. 

Utilizatorul mai întâi interacționează cu autentificarea. În funcție de rolul utilizatorului, fie profesor sau elev, fluxul redirecționează utilizatorul către Pagina profesor sau Pagina elev.
Acțiunile efectuate în aceste pagini sunt trimise către backedn prin API Service, care funcționează ca legătura dintre Frontend și Backend.
#### Backend
Tehnologiile folosite pentru Backend sunt Spring Boot.

AuthController gestionează cererile de autentificare ale utilizatorilor. QuizzController primește cererile HTTP de tip JSON. 

QuizzService încorporează funcționalitățile principale ale aplicației. Aceste funcționalități sunt adăugare quiz, rezolvare quiz, adăugare elevi, vizualizare note, vizualizare quiz, adăugare feedback. ImportExportCSVService este serviciul prin care se pot importă sau exportă fișiere CSV.
#### Persistența datelor
Baza de date stochează datele aplicației cum ar fi utilizatorii, quiz-urile, notele și feedback-ul.

Fișierele CSV sunt utilizate ca resursă externă pentru operațiunile de import și export de date.
