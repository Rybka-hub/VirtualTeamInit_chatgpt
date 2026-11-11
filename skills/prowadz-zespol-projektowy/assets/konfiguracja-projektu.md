# Konfiguracja projektu — szablon

Użyj po uzgodnieniu potrzebnego zakresu. W nowym repo może to być `docs/README.md`, łączący konfigurację i mapę. Usuń niepotrzebne pola. Brak uzgodnienia oznacz jawnie; nie wypełniaj go domyślną zgodą.

## Tożsamość i punkt startowy

- Projekt, cel, odbiorcy i pierwszy wynik: {przyjęte ustalenia}.
- Granice i najważniejsze ograniczenia: {ustalenia}.
- Repo i wspólna gałąź: {właściwy adres i gałąź albo brak repo}.
- Stan, następny krok i źródło: {dokument PM lub przyjęte podsumowanie}.
- Zespół: Work Cloud w Projects; wykonanie: Codex Local/Cloud, po sprawdzeniu dostępu.

## Mapa dokumentów

| Dokument lub obszar | Właściciel | Status i zastosowanie |
|---|---|---|
| {konfiguracja/mapa} | PM | {istnieje / do utworzenia} |
| {dokument PM} | PM | Bieżący stan, kolejność i krótkie statusy zleceń |
| {rejestr decyzji produktu} | PM | Wybory, granice, źródła i zastąpienia |
| {plik powołanej roli} | {rola} | {istnieje / oczekiwana ścieżka; bieżący zakres} |
| Dokumenty główne | Codex | Stan wykonania i obsługa; aktualizacje według potrzeby |
| `implementation/`, jeżeli potrzebne | Codex | Raporty i dowody wykonawcze |

Nie twórz plików dla wszystkich możliwych ról. Mapa nie jest potwierdzeniem istnienia oczekiwanego dokumentu.

## Uprawnienia i integracja

| Operacja | Przyjęty zakres albo status „do uzgodnienia” | Źródło |
|---|---|---|
| Pracownik: własne pliki, gałąź, commit, push i PR | {zakres} | {jawna zgoda} |
| PM: wspólne dokumenty i PR | {zakres} | {zgoda} |
| PM: merge dokumentacji i kodu po przeglądzie | {zakres} | {zgoda} |
| Codex: commit, push i PR | Według konkretnego promptu | Prompt przekazany przez właściciela |
| Usuwanie gałęzi lub plików | {zakres lub brak zgody} | {źródło} |
| Pierwsza publikacja | Zgoda na konkretny wynik | {źródło, gdy udzielona} |
| Kolejne publikacje i faktyczny skutek merge | {ręcznie / automatycznie / jeszcze nie ustalono} | {źródło} |
| Płatne zasoby i publiczny dostęp | {konkretny zakres lub brak zgody} | {źródło} |

Nie zamieniaj propozycji z szablonu w przyjęte decyzje. Niewymagane jeszcze wybory można pozostawić nieustalone; nie wolno wykonywać zależnej operacji, zanim zostaną rozstrzygnięte. Konieczne dla zamknięcia etapu odłożenie uzgodnij z rolą i momentem powrotu.
