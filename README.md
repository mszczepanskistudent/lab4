# lab4

## Kroki:

1. **Konfiguracja użytkownika w Git:**
   - Ustawienie nazwy użytkownika: `git config --global user.name "Mateusz Szczepański"`.
   - Ustawienie adresu e-mail użytkownika: `git config --global user.email "m.szczepanski@student.po.edu.pl"`.

2. **Inicjalizacja nowego repozytorium:**
   - Utworzenie nowego katalogu: `git init RepoNaZajecia`.
   - Przejście do nowego katalogu: `cd RepoNaZajecia`.

3. **Tworzenie plików:**
   - Stworzenie plików `plik1.txt` i `plik2.txt`: `wsl touch plik1.txt plik2.txt`.

4. **Dodanie i zatwierdzenie plików:**
   - Dodanie wszystkich plików: `git add *`.
   - Zatwierdzenie zmian z opisem: `git commit -m "Added all the files"`.

5. **Tworzenie pliku `nowy_plik2.txt`:**
   - Stworzenie pliku `nowy_plik2.txt`: `wsl touch nowy_plik2.txt`.
   - Dodanie pliku `plik2.txt` do śledzenia: `git add plik2.txt`.
   - Zatwierdzenie zmian z opisem: `git commit -m "New file nowy_plik2.txt creation"`.

6. **Usuwanie pliku `plik1.txt`:**
   - Usunięcie pliku `plik1.txt`: `git rm .\plik1.txt`.
   - Zatwierdzenie zmian z opisem: `git commit -m "File plik1.txt deleted"`.

7. **Dodanie i zatwierdzenie pliku `nowy_plik2.txt`:**
   - Dodanie pliku `nowy_plik2.txt` do śledzenia: `git add nowy_plik2.txt`.
   - Zatwierdzenie zmian z opisem: `git commit -m "New file nowy_plik2.txt creation"`.

8. **Zmiana nazwy pliku `plik2.txt` na `nowy_plik1.txt`:**
   - Zmiana nazwy pliku: `git mv plik2.txt nowy_plik1.txt.txt`.
   - Zatwierdzenie zmian z opisem: `git commit -m "Filename change"`.

9. **Zmiana nazwy pliku `plik1.txt.txt` na `plik1.txt`:**
   - Zmiana nazwy pliku: `git mv plik1.txt.txt plik1.txt`.
   - Zatwierdzenie zmian z opisem: `git commit -m "Filename change"`.

10. **Dodanie zawartości do pliku `nowy_plik1.txt`:**
    - Dodanie tekstu do pliku: `echo "tekst do pliku nowy_plik1" >> .\nowy_plik1.txt`.
    - Wyświetlenie zawartości pliku: `cat .\nowy_plik1.txt`.
    - Zatwierdzenie zmian z opisem: `git commit -m "Added content to nowy_plik1.txt"`.

11. **Dodanie zawartości do pliku `nowy_plik2.txt`:**
    - Dodanie tekstu do pliku: `echo "tekst do pliku nowy_plik2" >> .\nowy_plik2.txt`.
    - Zatwierdzenie zmian z opisem: `git commit -m "Added content to nowy_plik2.txt"`.

12. **Dodanie pliku `.gitignore` i użycie go:**
    - Dodanie `.gitignore` do śledzenia: `echo '.\nowy_plik1.txt' >> .gitignore`.
    - Wyświetlenie zawartości pliku `.gitignore`: `cat .gitignore`.

13. **Wyświetlenie logów:**
    - Wyświetlenie logu komitów w formacie skróconym: `git log --oneline`.
    - Wyświetlenie logu komitów z grafem w formacie skróconym: `git log --graph --oneline`.

14. **Tworzenie i przełączanie gałęzi:**
    - Utworzenie nowej gałęzi: `git branch nowy_branch`.
    - Przełączenie się na nową gałąź: `git checkout nowy_branch`.
    - Przełączenie się z powrotem na gałąź główną (master): `git checkout master`.

15. **Scalanie gałęzi:**
    - Scalenie zmian z nowej gałęzi do gałęzi głównej (master): `git merge nowy_branch`.

To są kroki opisujące wszystkie zmiany w repozytorium Git spowodowane wykonaniem skryptu Bash.
