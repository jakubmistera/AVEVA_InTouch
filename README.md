# 🏭 System SCADA i IIoT - AVEVA InTouch, Historian & Insight

Wizualne portfolio projektu akademickiego realizowanego w zespole dwuosobowym. Celem projektu było stworzenie od podstaw aplikacji wizualizacyjnej SCADA, konfiguracja przemysłowej bazy danych oraz integracja lokalnego systemu z chmurą (Przemysł 4.0 / IIoT).

> **O repozytorium:** Ze względu na ogromny rozmiar plików projektowych środowiska AVEVA oraz wymogi licencyjne uniemożliwiające uruchomienie projektu bez płatnego oprogramowania, to repozytorium ma formę **portfolio analityczno-wizualnego**. Poniższy opis oraz zrzuty ekranu prezentują pełną architekturę i możliwości stworzonego systemu.

## 🎯 Architektura i cel wdrożenia
Zaprojektowanie kompletnego interfejsu HMI/SCADA dla symulowanego procesu przemysłowego, polegające na akwizycji danych, bieżącym sterowaniu, archiwizacji zmiennych procesowych oraz wyprowadzeniu danych na zewnątrz do środowiska chmurowego w celu ich zdalnego monitorowania i analizy.

## 🛠 Wykorzystane technologie
* **AVEVA InTouch (Wonderware):** Tworzenie głównej aplikacji SCADA (synoptyka, animacje, skrypty, obsługa alarmów).
* **Wonderware Historian:** Przemysłowa baza danych szeregów czasowych – konfiguracja logowania danych z poziomu aplikacji InTouch.
* **AVEVA Insight:** Rozwiązanie chmurowe (IIoT) – publikacja tagów (zmiennych procesowych) do chmury i budowa zdalnych dashboardów analitycznych.

## ⚙️ Wdrożone funkcjonalności
* **Wizualizacja procesu:** Stworzenie ergonomicznych ekranów operatorskich, przypisanie tagów, konfiguracja animacji obiektów oraz skryptów sterujących logiką działania instalacji.
* **Zarządzanie alarmami:** Konfiguracja limitów alarmowych dla zmiennych analogowych i dyskretnych oraz stworzenie czytelnych okien alarmów bieżących i historycznych.
* **Archiwizacja i trendy:** Rejestracja kluczowych parametrów w bazie Historian i wizualizacja ich w postaci trendów historycznych (wykresów) dla operatora, pozwalających na analizę pracy w czasie.
* **Integracja chmurowa (Cloud Computing):** Bezpieczne połączenie lokalnego systemu SCADA z chmurą AVEVA Insight. Umożliwiło to zdalny podgląd pracy instalacji, śledzenie wskaźników KPI i analizę danych z poziomu dowolnej przeglądarki internetowej.

## 📁 Zawartość repozytorium
* `README.md` - szczegółowy opis wdrożonego systemu i zrealizowanych funkcji.
* `images/` - galeria zrzutów ekranu potwierdzająca działanie poszczególnych modułów systemu.

## 📷 Galeria Projektu

### Główny ekran wizualizacji (AVEVA InTouch)
<img width="700" height="368" alt="image" src="https://github.com/user-attachments/assets/b72ebac0-cf19-4483-9557-1ee1e9e95355" />

### Okno trendów i statystyk (AVEVA InTouch)
<img width="796" height="389" alt="image" src="https://github.com/user-attachments/assets/e4d835cb-d525-4672-aa1d-c3a8a9cf0da4" />

### Panel analizy trendów (AVEVA InTouch)
<img width="647" height="375" alt="image" src="https://github.com/user-attachments/assets/c1abd439-ccf6-4514-a977-13684925034f" />

### Analiza danych i monitoring w chmurze (AVEVA Insight)
![AVEVA Insight Dashboard](images/insight_dashboard.jpg)

### Trendy historyczne (Wonderware Historian)
![Wykresy Historian](images/historian_trends.jpg)

### Zarządzanie alarmami
![Zarządzanie alarmami](images/alarms_window.jpg)

---
*Projekt zrealizowany w ramach zajęć laboratoryjnych na Politechnice Warszawskiej (Kierunek: Automatyzacja i Robotyzacja Procesów Produkcyjnych). Projekt zespołowy.*
