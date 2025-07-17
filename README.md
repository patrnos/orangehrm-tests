# OrangeHRM Tests – Struktura Repozytorium

Repozytorium zawiera pełną dokumentację oraz dowody realizacji testów manualnych systemu OrangeHRM. Struktura katalogów została zaprojektowana tak, aby od razu po wejściu do repozytorium było jasne, do czego służy każdy folder i co można w nim znaleźć.

---

## Struktura Katalogów i Ich Opis

| Katalog/Filer    | Opis                                                                                                                |
|------------------|---------------------------------------------------------------------------------------------------------------------|
| **bugs/**        | **Defekty (błędy)** – główny katalog na zgłoszenia defektów. Każdy błąd rejestrowany jest jako osobny podkatalog.    |
| **BUG-.../**     | Folder defektu, np. `BUG-UX-01`. Zawiera materiały i opis pojedynczego zgłoszenia.                                   |
| screenshots/     | Podfolder w obrębie błędu – przechowuje zrzuty ekranu ilustrujące wystąpienie defektu.                               |
| video/           | Podfolder w obrębie błędu – zawiera nagrania (MP4, GIF) pokazujące przebieg błędu lub sposób odtworzenia.            |
| TC-....md        | Plik Markdown z opisem błędu: kroki do odtworzenia, rezultat oczekiwany i rzeczywisty, priorytet.                    |
| **test_cases/**  | **Przypadki testowe** – szczegółowe opisy przypadków testowych (manualne pozytywne i negatywne).     |
| **README.md**    | Plik z głównym opisem repozytorium, cyklem pracy, zasadami zgłaszania oraz opisem struktury folderów.                |

---

## Opis katalogów – nawigacja

- **`bugs/`** – katalog przechowujący WSZYSTKIE RAPORTY błędów. Dla każdego zgłoszenia powstaje podfolder typu `BUG-...` .
    - Każdy taki folder zawiera:
        - **screenshots/**: zrzuty ekranu (wizualna dokumentacja defektu)
        - **video/**: krótkie nagrania pokazujące sposób odtworzenia błędu (jeśli dotyczy)
        - **TC-...zgłoszenie.md**: plik Markdown z opisem kroku po kroku, skutków i oczekiwanym rezultatem

- **`test_cases/`** – uporządkowane przypadki testowe wykorzystywane podczas manualnego i automatycznego testowania.
    - Sekcja podzielona na rodzaje testów (pozytywne/negatywne).

- **`README.md`** – najważniejszy plik repozytorium. Po wejściu do repo od razu zobaczysz:
    - krótki opis projektu,
    - strukturę katalogów,
    - instrukcję, jak zgłaszać defekt i jak powinien wyglądać poprawny raport,
    - podstawowe dobre praktyki QA.

---

## Szybki start – jak korzystać ze struktury

1. **Chcesz sprawdzić zarejestrowane defekty?**
    - Wejdź do katalogu `bugs/`. Każdy podfolder odpowiada jednemu błędowi.
    - W każdym folderze znajdziesz zrzuty ekranu, nagrania oraz szczegółowy opis błędu.

2. **Chcesz przejrzeć przypadki testowe?**
    - Zajrzyj do `test_cases/`. Znajdziesz tam odpowiednio otagowane pliki z pełnymi przypadkami testowymi.

3. **Chcesz zgłosić nowy błąd?**
    - Utwórz nowy folder `BUG-...` w `bugs/`, wrzuć dowody (obraz, wideo) do odpowiednich podfolderów i uzupełnij plik markdown z opisem według wzoru.

---

## Najważniejsze zasady

- **Jasność i jednoznaczność** – każde zgłoszenie i test ma swój plik i folder, pełną dokumentację
- **Przejrzystość** – cała struktura widoczna jest z poziomu głównego katalogu repozytorium, a opisy są dostępne już w README.
- **Łatwość nawigacji** – 



