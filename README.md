# Aplikacja Webowa do rejestracji pacjentów i umawiania wizyt lekarskich.

System został stworzony w oparciu o **WordPress** i zestaw wtyczek, w tym **KiviCare**, umożliwiający rezerwację wizyt medycznych oraz zarządzanie pacjentami i lekarzami. Projekt działa lokalnie na serwerze XAMPP.

## Funkcjonalności
- **Rejestracja i logowanie użytkowników:**
  - Pacjent może założyć konto, zalogować się, rezerwować wizyty oraz przeglądać swoje dane.
  - Lekarz może przeglądać wizyty swoich pacjentów, edytować ich dane oraz dodawać notatki do wizyt.
  - Lekarz może zobaczyć swoje wizyty przeszłe i przyszłe, ale tylko takich co zarezerwowali tylko u niego
  - Role: Administrator, Lekarz, Pacjent.
- **Zarządzanie wizytami:**
  - Zarządzanie godzinami pracy lekarzy:
  - Brak możliwości nakładania się wizyt.
    
- **Personalizacja i bezpieczeństwo:**
  - Ukrywanie domyślnego adresu logowania WordPress dzięki wtyczce **WPS Hide Login**.

## Wykorzystane technologie i wtyczki
- **WordPress 6.0+**
- **XAMPP**: Lokalny serwer PHP i MySQL.
- **Wtyczki:**
  - **KiviCare** - Zarządzanie wizytami i pacjentami.
  - **Elementor** - Kreator wizualny do budowy strony.
  - **Qi Addons for Elementor** - Dodatkowe komponenty dla Elementora.
  - **Redux Framework** - Framework do zarządzania opcjami wtyczek i motywów.
  - **User Menus** - Dynamiczne menu nawigacyjne w zależności od roli użytkownika.
  - **User Registration** - Rejestracja użytkowników.
  - **WPS Hide Login** - Ukrycie domyślnej strony logowania.
  - **Colorlib Login Customizer** - Personalizacja strony logowania.
  - **Contact Form 7** - Tworzenie formularzy kontaktowych.

## Wymagania systemowe
- **Serwer lokalny lub hosting** z PHP 7.4+ i MySQL 5.7+. 
- **WordPress:** Wersja 6.0 lub nowsza.
- **Wtyczki:** Wszystkie wymienione powyżej.

## Instalacja
### 1. **Pobierz pliki WordPress**

- Pobierz WordPress.zip z repozytorium.
https://github.com/kubeusz04/Aplikacja-do-rejestracji-pacjent-w/releases/download/Wordpress/wordpress.zip
- Skopiuj folder WordPress do folderu htdocs w XAMPP.

### 2. **Utwórz bazę danych**

- Zaloguj się do phpMyAdmin (http://localhost/phpmyadmin).
- Utwórz nową bazę danych o nazwie "wordpress"

### 3. **Zaimportuj bazę danych**

- W phpMyAdmin zaimportuj plik `.sql` z repozytorium do nowo utworzonej bazy danych. 
https://github.com/kubeusz04/Aplikacja-do-rejestracji-pacjent-w/releases/download/Wordpress/wordpress.sql

### 4. **Zainstaluj wtyczki**

- Zaloguj się do panelu administracyjnego WordPressa (http://localhost/nazwa_strony/wp-admin).
- Zainstaluj wszystkie wtyczki wymienione w repozytorium (np. Elementor, KiviCare, Contact Form 7).


## Możliwe przyszłe plany rozwoju
- Dodanie systemu Powiadomień e-mail dla pacjentów i lekarzy.
- Oddtwarzanie na urządzeniach mobilnych.
- Optymalizacja wydajności dla obsługi większej liczby użytkowników.
- Rozliczenia wizyt i generowanie faktur.
- Tłumaczenie strony na inne języki (np. angielski, niemiecki) za pomocą wtyczki Polylang lub WPML.
- Synchronizacja wizyt z Google Calendar dla lekarzy i pacjentów.

## Autorzy
Kuba Zawadzki, Oskar Fonder, Szymon Kamiński, Albert Falęcki.



