# Topologie Sieci

## 1. Topologia Sieci Fizycznej

### a. Magistrala (Bus)
- **Opis**: Topologia magistrali polega na tym, że wszystkie urządzenia w sieci są podłączone do jednego wspólnego kabla (szyny), który przesyła dane.
- **Zalety**:
  - Niskie koszty instalacji.
  - Prosta w konfiguracji.
  - Mniejsze zapotrzebowanie na okablowanie.
- **Wady**:
  - Awaria na jednym kablu może wyłączyć całą sieć.
  - Trudności w diagnozowaniu problemów.
  - Ograniczona wydajność przy większej liczbie urządzeń.
- **Zastosowanie**: Stosowana w małych sieciach lokalnych, takich jak w biurach lub w budynkach mieszkalnych.

### b. Pierścień (Ring)
- **Opis**: W topologii pierścienia urządzenia są połączone w zamknięty krąg, a dane krążą w jednym kierunku od urządzenia do urządzenia.
- **Zalety**:
  - Wydajność w przypadku małych sieci.
  - Prosta instalacja.
  - Mniejsza liczba kabli.
- **Wady**:
  - Awaria jednego urządzenia lub kabla może zakłócić działanie całej sieci.
  - Trudności w rozbudowie sieci.
  - Trudniejsze diagnozowanie i naprawa problemów.
- **Zastosowanie**: Często używana w sieciach metropolitalnych lub w bardziej kontrolowanych środowiskach, np. w firmach.

### c. Gwiazda (Star)
- **Opis**: W topologii gwiazdy każde urządzenie jest podłączone do centralnego punktu (np. koncentratora lub switcha), który zarządza komunikacją.
- **Zalety**:
  - Łatwość w rozbudowie sieci.
  - Łatwiejsza diagnoza awarii – problem z jednym urządzeniem nie wpływa na całą sieć.
  - Dobra skalowalność.
- **Wady**:
  - Wymaga dużej ilości kabli.
  - Awaria centralnego urządzenia (np. switcha) wyłącza całą sieć.
- **Zastosowanie**: Powszechnie używana w biurach, szkołach, dużych firmach, wszędzie tam, gdzie potrzebna jest duża niezawodność.

---

## 2. Topologia Sieci Logicznej

### a. Punkt-punkt (Point-to-Point)
- **Opis**: Topologia punkt-punkt łączy dwa urządzenia bezpośrednio, bez żadnych pośredników.
- **Zastosowanie**: Używana w połączeniach między dwoma urządzeniami, np. połączenie dwóch routerów.

### b. Przekazywanie żetonu (Token Passing)
- **Opis**: W tej topologii "żeton" (token) krąży po sieci i daje uprawnienia do wysyłania danych. Tylko urządzenie, które posiada żeton, może wysłać dane.
- **Zastosowanie**: Wykorzystywana w topologii pierścienia, np. w starszych sieciach Token Ring.

### c. Wielodostępowa (Multiple Access)
- **Opis**: Urządzenia w tej topologii mają równy dostęp do medium transmisyjnego i mogą nadawać dane w dowolnym momencie, korzystając z protokołów kontroli dostępu.
- **Zastosowanie**: Stosowana w sieciach Ethernet, np. w sieciach lokalnych.
