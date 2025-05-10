# Networking z NAvirem

Networking z NAvirem to aplikacja internetowa, która umożliwia uczestnikom poznawanie się poprzez rozmowy w małych grupach. Aplikacja została zaprojektowana z myślą o wydarzeniach, takich jak spotkania networkingowe, warsztaty czy konferencje, gdzie celem jest integracja i wymiana doświadczeń uczestników.

<img src="/image.png" alt="Ikonka aplikacji" className="w-24 h-24 mb-4" />

## Funkcjonalności

- **Rejestracja uczestników**:
  - Uczestnicy podają swoje imię i zainteresowania.
- **Tworzenie grup**:
  - Algorytm grupowania unika powtórzeń interakcji między uczestnikami.
  - Grupy są oznaczone kolorami i ikonami.
- **Zarządzanie sesją**:
  - Timer rundy (domyślnie 10 minut).
  - Możliwość remiksowania grup przez administratora.
- **Panel administratora**:
  - Monitorowanie uczestników i grup.
  - Historia rund.
  - Resetowanie sesji.

## Widoki aplikacji

1. **Widok powitalny**:
   - Wybór roli uczestnika lub administratora.
2. **Formularz rejestracji**:
   - Uczestnicy wprowadzają swoje dane i zainteresowania.
3. **Widok oczekiwania**:
   - Ekran oczekiwania na rozpoczęcie sesji.
4. **Widok grupy**:
   - Informacje o grupach i timer rundy.
5. **Panel administratora**:
   - Zarządzanie uczestnikami, grupami i sesją.

## Instalacja

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/navir8/networking-app.git
   cd networking-app
   ```

2. Zainstaluj zależności:
   ```bash
   npm install
   ```

3. Uruchom aplikację lokalnie:
   ```bash
   npm start
   ```

4. Otwórz aplikację w przeglądarce pod adresem:
   ```
   http://localhost:3000
   ```

## Struktura projektu

- **`src/`**: Główne źródła aplikacji.
  - **`components/`**: Komponenty React.
  - **`assets/`**: Obrazy i ikony.
- **`public/`**: Zasoby publiczne, m.in. ikona aplikacji.

## Jak używać

1. Otwórz aplikację i wybierz swoją rolę:
   - Uczestnik: Podaj imię i zainteresowania, a następnie dołącz do sesji.
   - Administrator: Wprowadź kod administratora, aby zarządzać sesją.
2. Rozpocznij sesję jako administrator.
3. Utwórz grupy i rozpocznij networking!

## Technologie

- **React** - Biblioteka do budowania interfejsów użytkownika.
- **JavaScript** - Język programowania.
- **CSS** - Stylowanie interfejsu.

## Dalszy rozwój

- **Możliwość czatu w grupach**.
- **Integracja z kalendarzem wydarzeń**.
- **Analityka interakcji uczestników**.

## Wkład w projekt

Zapraszamy do zgłaszania problemów i propozycji zmian poprzez zakładkę [Issues](https://github.com/navir8/networking-app/issues).

## Licencja

Projekt jest dostępny na licencji MIT. Szczegóły znajdziesz w pliku [LICENSE](./LICENSE).