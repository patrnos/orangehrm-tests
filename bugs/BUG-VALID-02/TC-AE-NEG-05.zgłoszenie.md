# TC-AE-NEG-05 – Brak walidacji znaków specjalnych w polu "Last Name"

**Moduł:** PIM / Add Employee  
**Kroki do odtworzenia:**
1. Wejdź na stronę: https://opensource-demo.orangehrmlive.com/
2. Zaloguj się do aplikacji z użyciem domyślnych danych administratora (Admin / admin123).
3. Przejdź do modułu PIM i wybierz opcję Add Employee.
2. W polu "First Name" wpisz: `Anna`.
3. W polu "Last Name" wpisz dowolną poprawną wartość, np. `Testowy122`.
4. Kliknij przycisk "Save".

**Oczekiwany rezultat:**  
System wyświetla czytelny komunikat walidacyjny (np. "Only alphabetic and basic special characters are allowed") i uniemożliwia zapisanie imienia zawierającego cyfry.

**Rzeczywisty rezultat:**  
System pozwala na zapisanie nazwiska „Kowalski!@#$%” bez ostrzeżenia.

**Priorytet:** Wysoki
