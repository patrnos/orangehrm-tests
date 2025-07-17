# TC-AE-NEG-16 – Brak zabezpieczenia przed wielokrotnym wysłaniem formularza ("Save")

**Moduł:** PIM / Add Employee  
**Kroki do odtworzenia:**

1. Wejdź na stronę: https://opensource-demo.orangehrmlive.com/
2. Zaloguj się do aplikacji z użyciem domyślnych danych administratora (Admin / admin123).
3. Przejdź do modułu PIM i wybierz opcję Add Employee.
4. Wypełnij wszystkie wymagane pola formularza prawidłowymi danymi (np. First Name, Last Name, Employee Id).
5. Bardzo szybko (kilkukrotnie) kliknij przycisk Save przed zakończeniem pierwszej operacji zapisu

**Oczekiwany rezultat:**  
Pracownik zostaje dodany jeden raz, a przycisk "Save" jest zablokowany po pierwszym kliknięciu do czasu zakończenia operacji.

**Rzeczywisty rezultat:**  
Pojawia się seria popupów z błędami, a w konsoli przeglądarki odnotowywany jest błąd HTTP 422.


Załaczniki

/screenshots
/video

**Priorytet:** Średni
