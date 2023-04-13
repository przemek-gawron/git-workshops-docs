---
sidebar_position: 5
---

# Komendy w konsoli

Wewnątrz konsoli będziemy uzywać komendy ```cd``` (change directory) <br/> ```cd ..``` -> przeniesie nas do katalogu wyzej<br/> ```cd katalog``` -> przeniesie nas do folderu katalog

## Komendy w git 

```git config user.name Przemek``` - skonfigurowanie nazwy użytkownika 

```git config user.email Przemek@test.pl``` - konfiguracja maila

```git add .``` - dodanie wszystkich zmian do indeksu (stage). Zmiany w plikach jak i nowe pliki

```git commit -m „komentarz„``` - komenda, która wszystkie zmiany z indeksu (stage) zbiera razem i robi z nich pojedynczy commit. Parametr -m służy do pisania komentarza do commit-a

```git init``` - komenda do uruchomienia w katalogu z projektem aby zainicjować repozytorium git

```git status``` - pokazuje aktualny status repozytorium, ile commit-ów jesteśmy do tyłu w porównaniu ze zdalnym repozytorium, jakie pliki są śledzone a jakie nie itd.

```git checkout nazwa_gałęzi``` - komenda ta daje możliwość przełączenia się na inna gałąź

```git checkout commit_hash``` - komenda ta daje możliwość przełączenia się kodu do dowolnego commit-a

```git checkout -b nazwa_gałęzi``` - komenda ta umożliwia stworzenie nowej gałęzi o nazwie nazwa_gałęzi. Po jej utworzeniu git automatycznie się na nią przełączy.

```git branch -D nazwa_gałęzi``` - komenda ta daje możliwość skasowania lokalnej gałęzi 

```git branch -a``` - wyświetla listę wszystkich gałęzi, w tym tych ze zdalnego repozytorium.

```git cherry-pick commit_hash``` - pozwala na zastosowanie zmian w całości z jednego commit-a (commit_hash) do aktualnej gałęzi. Jest to takie wybieranie pojedynczych commitów z dowolnych(czyli innych gałęzi) innych miejsc w repozytorium

```git merge nazwa_gałęzi``` - komenda podstawowa, która pozwala scalić zmiany z innej gałęzi na tą na, której jesteśmy

```git log``` - wyświetla historię commitów

```git clone adres_do_repozytorium``` - podstawowa komenda, która pozwala pobrać repozytorium na dysk lokalny

```git push``` - komenda wysyła commity do zdalnego repozytorium

```git remote add nazwa_repozytorium url_do_repozytorium``` - komenda pozwalająca dodać zdalne repozytorium do którego będziemy mogli robić komendy push i pull

```git pull``` - aktualizuje historię oraz nasz kod do ostatniego wysłanego do zdalnego repozytorium commita. Zanim zaczniemy prace w repozytorium to komanda ta sprawi, że będziemy mieć aktualne lokalne repozytorium
