# TC-AE-NEG-17 – Brak ostrzeżenia o utracie danych przy odświeżeniu strony

**Moduł:** PIM / Add Employee  
**Kroki do odtworzenia:**

1. Wejdź na stronę: https://opensource-demo.orangehrmlive.com/
2. Zaloguj się do aplikacji z użyciem domyślnych danych administratora (Admin / admin123).
3. Przejdź do modułu PIM i wybierz opcję Add Employee.
4. Rozpocznij wypełnianie formularza dodawania pracownika.
5. Naciśnij F5 (odświeżenie strony), bez wcześniejszego zapisywania danych.

**Oczekiwany rezultat:**  
System wyświetla okno ostrzegawcze przeglądarki o niezapisanych zmianach (możliwa utrata danych).

**Rzeczywisty rezultat:**  
Strona odświeża się natychmiast bez żadnego ostrzeżenia, dane są tracone.

**Priorytet:** Średni
