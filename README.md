# 💖 Interaktywny Prezent "Dla Mojej Kochanej"

Witaj w repozytorium mojego osobistego, interaktywnego projektu! Został on stworzony z myślą o mojej dziewczynie, jako cyfrowy, romantyczny prezent, który ma za zadanie wywoływać uśmiech na jej twarzy, przypominać o moich uczuciach i dawać poczucie bezpieczeństwa.

Projekt składa się z trzech spójnych wizualnie podstron (utrzymanych w uroczej, pastelowej stylistyce *glassmorphism*), które pełnią różne funkcje: od generatora komplementów, przez mini-grę, aż po wirtualną walentynkę. Głównym motywem przewodnim i maskotką projektu jest słodka rybka Rozdymka 🐡.

---

## 🚀 Funkcjonalności i Podstrony

### 1. 💌 Strona Główna (Generator Komplementów)
**Plik:** `index.html`
Serce całego prezentu. Znajduje się tu:
*   **Licznik czasu:** Precyzyjnie odliczający czas (w latach, miesiącach, dniach, godzinach, minutach i sekundach) naszego związku.
*   **Generator słów:** Baza kilkudziesięciu spersonalizowanych komplementów i romantycznych obietnic, które losują się na ekranie.
*   **Pływające tło:** Generowane w JavaScript animowane cząsteczki (serca, kwiaty, urocze symbole).

### 2. 🎮 Mini-gra: Zadbaj o Rozdymkę
**Plik:** `Gra_Zadbaj_o_Rozdymke.html`
Prosta gra w stylu Tamagotchi, w której główną bohaterką jest nasza urocza maskotka.
*   Gracz za pomocą przycisków akcji (karmienie, głaskanie, opowiadanie żartów, wysyłanie buziaków) zwiększa "Pasek Szczęścia" Rozdymki.
*   Każda akcja wyzwala zabawną wypowiedź rybki w dymku oraz responsywną animację wystrzeliwujących emotikonów.
*   Po osiągnięciu 100% szczęścia pojawia się specjalny ekran wygranej z dedykacją.

### 3. 🌹 Pytanie Walentynkowe
**Plik:** `walentynki-index.html`
Interaktywna, wirtualna walentynka.
*   Zadaje najważniejsze pytanie z pulą losowo mieszanych, pozytywnych odpowiedzi.
*   Po kliknięciu przycisku pojawia się dedykowany ekran z wyznaniem miłości oraz uroczą grafiką.

---

## 🎨 Zasoby Graficzne

W folderze głównym znajdują się dedykowane grafiki, które ożywiają cały projekt i nadają mu unikalny charakter:
*   `Dwie_Rybki.png` - Grafika koncepcyjna/tło.
*   `Rozowe_Serce.png` - Wykorzystywane jako element dekoracyjny.
*   `Usmiechnieta_Rozdymka.png` - Urocza grafika maskotki z tłem, używana na ekranach finałowych.
*   `Usmiechnieta_Rozdymka_Bez_Tla.png` - Sprite używany bezpośrednio w mini-grze do animacji lewitowania i podskoków.

---

## 🛠️ Technologie i Ciekawe Rozwiązania

Projekt opiera się na czystym **HTML, CSS oraz Vanilla JavaScript**. Nie wymaga żadnych zewnętrznych bibliotek ani frameworków, co gwarantuje błyskawiczne ładowanie.

*   **Powiadomienia w czasie rzeczywistym (Discord Webhooks):** Projekt jest zintegrowany z prywatnym serwerem Discord. Skrypt wysyła powiadomienia za każdym razem, gdy strona zostaje otwarta, gdy losowany jest komplement lub gdy podejmowana jest akcja w grze.
*   **Obejście "Sleeping Tabs":** Wykorzystanie `Page Visibility API` pozwala na wykrycie powrotu do zminimalizowanej karty przeglądarki na smartfonie, co wyzwala powiadomienie bez konieczności odświeżania strony.
*   **Pełna Responsywność (RWD):** Elementy interfejsu korzystają z nowoczesnych funkcji CSS, takich jak `clamp()`, `vmin` i `dvh`, dzięki czemu projekt skaluje się idealnie na każdym urządzeniu mobilnym i nie powoduje problemów z uciętym interfejsem przy wysuniętej klawiaturze telefonu.

---

## 💡 Jak uruchomić?

Projekt jest statyczną stroną internetową (Frontend). 
Aby go uruchomić, wystarczy pobrać repozytorium i otworzyć dowolny z plików `.html` w nowoczesnej przeglądarce internetowej. Docelowo projekt jest hostowany w [GitHub Pages](https://pientaszek0.github.io/Prezent/), dzięki czemu działa na każdym urządzeniu z dostępem do internetu.

---
*Stworzone z miłością ❤️*