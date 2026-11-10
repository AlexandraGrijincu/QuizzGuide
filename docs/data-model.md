# Modelul preliminar de date
<img width="1169" height="718" alt="ModelPreliminar" src="https://github.com/user-attachments/assets/128f338f-2380-489c-a9c7-5328adef95de" />

**Utilizator:** Reține datele de autentificare și rolul în sistem.

**Quiz:** Reprezinta un test creat de un profesor.

**Questions și Answer:** Structura de conținut al unui quiz.

**Result:** Înregistrează rezultatele unui elev în completarea quiz-ului.
# Endpoint-urile principale
- **GET:**
  - GET /students/{id_student}/quizzes - preia quiz-urile la care este înscris un student cu id_student
  - GET /teachers/{id_profesor}/quizzes - preia quiz-urile unui profesor cu id_profesor
  - GET /quizzes/{id_quizz} - preia întrebările unui quiz
  - GET /quizzes/csv/{id_quizz} - descarcă csv unui quiz
  - GET /users/{id_utilizator} - preia datele utilizatorului
  - GET /quizzes - preia lista tuturor quiz-urilor
- **POST:**
  - POST /quizzes/{id_profesor}- încarca un quiz
  - POST /quizzes/{id_quizz}/student/{id_student} - încarcă răspunsurile pentru un quiz ale unui elev
  - POST /auth/register - înregistrarea unui utilizator nou
  - POST /auth/login - autentificarea în aplicație
  - POST /quizzes/{id_quizz}/students - înscrie studenți la un quiz
- **DELETE:**
  - DELETE /quizzes/{id_quizz} - șterge un quiz
  - DELETE /quizzes/{id_quizz}/students/{id_student} - șterge un student de la un quiz
- **PUT:**
  - PUT /quizzes/{id_quizz} - Modifică un qiuz existent
