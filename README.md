Zdale repozytorium

   1. Wklejacie w przeglądarkę adres https://github.com/perlaaaaaa/2LO.git, a następnie na wyświetlonej stronie logujecie się
      na swoje konto GITHUB
   2. Klikacie przycisk Fork, w prawym górnym rogu
   ----------------------------------------------------------------------------------------------------------------------------
   3. Wracamy na witrynę cs50.io. Klonujecie moje repozytorium 2LO: git clone https://github.com/perlaaaaaa/2LO.git
   4. Wchodzimy do folderu 2LO : cd 2LO
   5. Tworzycie folder imię_nazwisko bez polskich znaków : mkdir imię_nazwisko
   6. Wchodzimy do folderu : cd imię_nazwisko
   7. Tworzymy plik Hello.java: touch Hello.java (Tworzymy program wyświetlający napis Hello World)
   8. Zapisujemy plik (ctrl+s), kompilujemy (javac Hello.java), uruchamiamy (java Hello)
   9. Dodajmy nasz folder do lokalnej wersji repozytorium: git add Hello.java      (jesteśmy w folderze 2LO, a nie imię_nazwisko)
   10. Zatwierdzamy zmiany w lokalnej wersji repozytorium : git commit -m "add Hello" 
   11. Wysyłamy zmiany do zdalnego repozytorium: git push origin master, zostaniemy poproszeni o podanie swojej nazwy użytkownika
        i hasła
   ----------------------------------------------------------------------------------------------------------------------------
   12. Wracamy do GitHUB, odświeżamy stronę. Nasze zmiany powiiny być widoczne


Przy następnym uruchomieniu cs50.io będąc w folderze github wpisujemy git pull,
aby zaktualizować lokalne pliki z tymi w zdalnym repozytorium.

Po dokonaniu jakiś zmian wykonujemy punkty od 6(dodajemy zmienione pliki) -9.
