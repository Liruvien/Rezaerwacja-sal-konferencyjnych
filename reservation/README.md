# Aplikacja przegladarkowa do rezaerwacji sal konferencyjnych

Aplikacja umożliwia zarządzanie salami konferencyjnymi, w tym dodawanie, edytowanie, usuwanie sal oraz rezerwowanie ich na określone dni. System umożliwia również wyszukiwanie sali na podstawie różnych kryteriów.

## Funkcje aplikacji

### Strona główna

Po wejściu na stronę główną użytkownik widzi listę wszystkich sal konferencyjnych. Przy każdej sali znajdują się informacje o jej statusie (zajęta lub wolna danego dnia) oraz linki do modyfikacji danych sali i jej usunięcia.

### Szczegółowy widok sali

Po kliknięciu w nazwę sali użytkownik zostaje przeniesiony do szczegółowego widoku sali. W tym widoku znajduje się:

- Nazwa sali,
- Pojemność sali,
- Informacja, czy sala posiada rzutnik.

Dodatkowo wyświetlana jest lista dni, w których sala będzie zajęta (tylko dni przyszłe). Użytkownik może także zarezerwować salę, usunąć ją lub edytować jej dane.

### Dodawanie nowej sali

Użytkownik ma możliwość dodania nowej sali konferencyjnej, podając jej nazwę, pojemność oraz informację o dostępności rzutnika.

### Edycja sali

Po wejściu na stronę edycji sali użytkownik może zaktualizować dane sali: nazwę, pojemność oraz informację o dostępności rzutnika.

### Rezerwacja sali

Na stronie rezerwacji użytkownik widzi listę dni, w których sala będzie zajęta. Można wybrać datę rezerwacji, przy czym system dba o to, aby nie było dublujących się rezerwacji na ten sam dzień i dla tej samej sali. Data rezerwacji nie może dotyczyć przeszłości.

### Wyszukiwanie sali (dla chętnych)

Użytkownik może wyszukiwać sale na podstawie różnych kryteriów, takich jak:

- Nazwa sali,
- Pojemność sali,
- Dostępność rzutnika.

## Wskazówki dotyczące kodu

- Używaj czytelnych nazw zmiennych i plików.
- Twórz funkcje, które rozwiązują jeden problem, unikaj dużych funkcji.
- Pamiętaj o częstych commitach w systemie kontroli wersji (np. Git), aby prześledzić historię zmian.
- Przede wszystkim, koduj w sposób zrozumiały i prosty. Po napisaniu rozwiązania spróbuj je uprościć, jeśli to możliwe.
- Dokumentuj kod. Każda funkcja powinna zawierać przynajmniej krótki opis.
- Pisz kod w języku angielskim.

## Instalacja i uruchomienie

1. Skopiuj repozytorium na swoją maszynę

## Technologie

Aplikacja została stworzona przy użyciu następujących technologii:

- Django (do tworzenia aplikacji webowej)
- Python (język programowania)
- Postgresql (baza danych)