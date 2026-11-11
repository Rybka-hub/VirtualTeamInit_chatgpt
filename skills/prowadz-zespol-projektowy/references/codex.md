# Kontrakt wykonawcy Local i Cloud

## Przygotuj pełny prompt

Umieść wyłącznie w rozmowie: repo, bazę i środowisko; cel, zakres i wyłączenia; przyjęte wymagania i źródła; materiały i zależności; wynik i kryteria odbioru; potrzebne punkty oceny; zgodę na operacje Git i warunki publikacji; aktualizację dotkniętych dokumentów; obsługę blokad i przekazanie wyniku.

Nie wymagaj wszystkich dokumentów przy drobnej zmianie. Respektuj aktualny `AGENTS.md` właściwy środowisku. Nie kopiuj globalnego pliku właściciela do skilla i nie zakładaj, że Cloud czyta plik z komputera.

| Dokument główny | Funkcja |
|---|---|
| `README.md` | Obsługa, środowisko, konfiguracja, uruchomienie i sprawdzenia |
| `README_SHORT.md` | 2–4 proste zdania o rzeczywistym działaniu |
| `PROJECT_CONTEXT.md` | Cel, odbiorcy, granice i kryteria sukcesu |
| `HANDOFF.md` | Aktualny stan do wznowienia, wyniki, data i stan Git |
| `PLANS.md` | Plan większego zadania, postęp i zależności |
| `ARCHITECTURE.md` | Komponenty, dane, integracje i konfiguracja |
| `DECISIONS.md` | Istotne decyzje techniczne z uzasadnieniem |

W istniejącym repo zachowaj odpowiedniki. Produktowe `docs/DECISIONS.md` i techniczny `DECISIONS.md` łącz odsyłaczami zamiast kopiować całe decyzje. Nie zmieniaj istniejących ID bez potrzeby.

## Pozostaw samodzielność wykonawcy

Codex sam planuje, dobiera szczegóły i naprawia problemy w przyjętym zakresie. Przy krokach ręcznych podaje krótką instrukcję, czeka na wykonanie, sprawdza wynik i kontynuuje. Nie odsyła każdego logowania lub wpisu konfiguracji do PM.

Przy zmianie zakresu, kosztach, istotnym kompromisie lub nierozstrzygniętej sprzeczności przedstawia potrzebną decyzję. Informację do PM przygotowuje dla właściciela; sam nie kontaktuje się z tą rozmową.

Przy blokadzie podejmuje uzasadnione próby, dopóki dają postęp lub nową informację. Gdy przestają ją dawać, opisuje fakty, sprawdzenia, wpływ i realne opcje. Nie narzucaj sztywnego limitu czasu lub prób bez uzgodnienia.

## Odbierz i udokumentuj wynik

Wynik obejmuje PR, faktyczne zmiany, właściwe sprawdzenia i jawne pominięcia. Jeśli prompt jawnie obejmuje commit, push i PR, jego przekazanie stanowi zgodę w tym zakresie. Merge pozostaje PM; publikacja wymaga właściwej zgody lub przyjętego trybu projektu.

Po zmianie produktu poleć synchronizację dotkniętych dokumentów głównych z aktualnym `docs/`. `PLANS.md` jest planem wykonawcy, a `HANDOFF.md` stanem wznowienia; nie mają powtarzać pełnego promptu.

## Wznów to samo zadanie, również Local ↔ Cloud

Dotychczasowy Codex aktualizuje `HANDOFF.md` i przygotowuje prompt wznowienia. Zapisuje cel i ograniczenia, wykonany zakres, pozostałe kroki, wyniki i stan Git: repo, gałąź, bazę, SHA i niezacommitowane pliki wymagające zachowania.

Sprawdza, czy potrzebne zmiany są na zdalnej gałęzi i czy nowe środowisko ma zasoby, zależności i konfigurację. Pliki ignorowane i lokalne sekrety nie przechodzą przez samo logowanie. Nie ujawniaj wartości sekretów.

Nie porzucaj niezacommitowanej pracy i nie obiecuj, że `HANDOFF.md` przenosi jej bajty. Zachowaj pracę w autoryzowany sposób i sprawdź dostępność przed wznowieniem zależnych działań. Nowy wykonawca najpierw weryfikuje stan.

Przeniesienie tego samego zadania nie wymaga rundy przez PM. Nowe cele, rozszerzenie uprawnień i odbiór etapu wracają do właściwej rozmowy.
