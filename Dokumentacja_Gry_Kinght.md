# Dokumentacja Projektowa Gry "Kinght"

Niniejszy dokument stanowi oficjalną specyfikację techniczną i opis założeń projektowych niezależnej gry platformowej 2D o nazwie **"Kinght"**. Projekt łączy w sobie klasyczną mechanikę gier zręcznościowych z nowoczesnym podejściem do rozgrywek typu *time attack* (wyścigi z czasem).

---

## 1. Główne Założenia Projektowe i Inspiracje

Projekt został zapoczątkowany z myślą o stworzeniu minimalistycznej, ale wysoce grywalnej produkcji retro. Główne filary gry to:

* **Prostota mechaniki:** Gra unika skomplikowanych systemów RPG czy rozbudowanego ekwipunku. Skupia się na czystej zręczności i precyzji gracza, wzorem klasycznych produkcji z lat 80. i 90.
* **Dynamika i Grywalność na Czas:** Główną osią rozgrywki jest ukończenie poziomów w jak najkrótszym czasie. Projekt jest bezpośrednio targetowany pod społeczność zainteresowaną tzw. *speedrunningiem*. Każdy element poziomu ma wymuszać na graczu optymalizację jego ścieżki ruchu.
* **Inspiracja "Mario Bros":** Pod względem fizyki skoku, konstrukcji kafelkowej świata (tile-based) oraz ogólnego klimatu, gra mocno nawiązuje do kultowej serii firmy Nintendo. Stanowi ona swoisty hołd dla tamtej ery gamingu, zaadaptowany do współczesnych realiów niezależnego gamedevu.

---

## 2. Rdzeń Rozgrywki (Core Gameplay) i Analiza Wizualna

Na podstawie obecnego prototypu gry zaimplementowano pętlę rozgrywki opartą na eksploracji i zbieractwie.

* **Główny Bohater:** Postać gracza to tajemniczy bohater w szacie z kapturem (zaprojektowany w estetyce *pixel art*). Jego unikalny wygląd wyróżnia się na tle otoczenia i zapewnia dobrą widoczność podczas dynamicznych manewrów.
* **Płytki Świata (Tileset):** Świat gry zbudowany jest z bloków z wyraźną, zieloną krawędzią trawy i fioletowym wypełnieniem strukturalnym. Zapewnia to wysoki kontrast wizualny, kluczowy dla gier wymagających szybkiej reakcji.
* **Energy Cells (Ogniwa Energii):** Rozmieszczone w przestrzeni poziomu, świecące na niebiesko kapsuły. Stanowią one główny cel na każdej mapie. Gracz musi zebrać określoną liczbę (lub wszystkie) ogniw, aby aktywować mechanizm wyjścia i odblokować kolejny etap.

---

## 3. Plan Rozwoju i Kamienie Milowe (To-Do List)

Projekt znajduje się obecnie w fazie aktywnego prototypowania. Aby gra osiągnęła status pełnoprawnej produkcji, zdefiniowano następujące kamienie milowe do zaimplementowania w najbliższych cyklach produkcyjnych:

| Kategoria | Zadanie | Szczegółowy Opis Funkcjonalności | Priorytet |
| :--- | :--- | :--- | :--- |
| **Interfejs (UI)** | Licznik czasu | Wdrożenie precyzyjnego stopera (HUD) odmierzającego milisekundy, wyświetlanego w rogu ekranu podczas rozgrywki. | WYSOKI |
| **Zawartość** | Projektowanie poziomów | Stworzenie pakietu co najmniej 10-15 unikalnych map o rosnącej krzywej trudności, wprowadzających ruchome platformy i pułapki. | WYSOKI |
| **Mechanika** | Zaawansowany ruch | Rozbudowanie kodu kontrolera postaci o mechaniki takie jak: bieg (sprint), zryw w powietrzu (dash) oraz odbijanie się od ścian (wall jump). | WYSOKI |
| **Grafika** | Tło gry (Background) | Zastąpienie jednolitego szarego tła wielowarstwową grafiką z efektem paralaksy (np. zamglone góry, pikselowe chmury przesuwające się z różną prędkością). | ŚREDNI |
| **Struktura** | Architektura Menu | Projekt i implementacja Menu Głównego (Start, Opcje, Wyjście) oraz Menu Zakończenia Poziomu wyświetlającego statystyki i końcowy czas. | ŚREDNI |
| **Kosmetyka** | Personalizacja wizualna | Wprowadzenie prostego systemu cząsteczek (efekt kurzu przy skoku/lądowaniu) oraz alternatywnych palet kolorystycznych dla szaty bohatera. | NISKI |

---

## 4. Przebieg Procesu Produkcyjnego

Prace nad grą "Kinght" trwają intensywnie od kilku miesięcy. Deweloper skupił się na dostarczeniu tzw. *Vertical Slice* – czyli małego, ale w pełni grywalnego fragmentu gry prezentującego styl graficzny i fizykę ruchu.

W procesie tworzenia kluczową rolę odegrały:
1.  **Analiza materiałów edukacyjnych:** Korzystanie z branżowych tutoriali dotyczących programowania fizyki platformowej 2D, obsługi kolizji maszyn stanów postaci.
2.  **Wykorzystanie narzędzi AI:** W ograniczonym, pomocniczym zakresie sztuczna inteligencja została zaangażowana do refaktoryzacji struktur kodu, wykrywania drobnych błędów (bug-fixing) oraz generowania pomysłów na optymalizację algorytmów odpowiedzialnych za ruch.

---

## 5. Podsumowanie i Status Projektu

Gra w obecnej fazie posiada już w pełni funkcjonalny rdzeń (ruch postaci, kolizje, zbieranie obiektów), co udowadnia słuszność przyjętej koncepcji projektowej. Choć przed autorem jeszcze długa droga związana z dodaniem zaplanowanej zawartości (Contentu), gra na tym etapie wykazuje wysoki potencjał grywalnościowy. Wszystkie założone cele produkcyjne są sukcesywnie realizowane, co pozwala z optymizmem patrzeć na finalną wersję tytułu.
