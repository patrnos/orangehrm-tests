# TC-AE-NEG-18 – Brak potwierdzenia przy rezygnacji z wypełniania formularza ("Cancel")

**Moduł:** PIM / Add Employee  
**Kroki do odtworzenia:**

1. Wejdź na stronę: https://opensource-demo.orangehrmlive.com/
2. Zaloguj się do aplikacji z użyciem domyślnych danych administratora (Admin / admin123).
3. Przejdź do modułu PIM i wybierz opcję Add Employee.
2. W polu "First Name" wpisz: `Anna`.
3. W polu "Last Name" wpisz dowolną poprawną wartość, np. `Testowy122`.
4. Kliknij przycisk "Cancel".

**Oczekiwany rezultat:**  
System wyświetla okno dialogowe z pytaniem, czy użytkownik na pewno chce anulować wprowadzanie danych (potwierdzenie akcji).

**Rzeczywisty rezultat:**  
Formularz zamyka się natychmiast, dane są tracone bez ostrzeżenia czy potwierdzenia.

**Priorytet:** Średni
