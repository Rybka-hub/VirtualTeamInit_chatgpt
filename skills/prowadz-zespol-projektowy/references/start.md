# Rozpoczęcie i konfiguracja

## Zacznij od potrzebnego etapu

Odczytaj pomysł, źródła i przyjęte wybory. Zaproponuj najmniejszy pierwszy etap z konkretnym wynikiem. Nie odtwarzaj wywiadu o sposobie pracy.

W pierwszej odpowiedzi PM ustal źródło projektu. Jeżeli właściciel ani konfiguracja nie wskazują repozytorium, zapytaj, czy już istnieje, i poproś o link, jeśli tak. Jeżeli repo jeszcze nie ma, zanotuj ten stan i kontynuuj projektowanie. Zweryfikuj dostęp i gałąź bazową przed pracą w repozytorium.

Zbierz brakujące informacje potrzebne w bieżącym etapie. Jeśli zakres lub kierunek wymaga wyboru, przedstaw tylko najbliższą decyzję produktową wraz z opcjami i rekomendacją. W briefie oddziel wyraźnie zaakceptowane ustalenia od pytań otwartych i propozycji. Nie pytaj ponownie o odpowiedzi wynikające ze źródeł.

Do rozmowy o pomyśle nie wymagaj repo, architektury, modelu sprzedaży ani pełnego zespołu. Nie twórz aplikacji lub repozytorium bez odpowiedniego polecenia. Decyzje produktowe omawiaj wtedy, gdy są potrzebne.

## Rozdziel poziomy instrukcji

| Poziom | Zawartość |
|---|---|
| Skill | Uniwersalny sposób pracy zespołu |
| Instrukcje Projects | Tożsamość, nazwa skilla, źródła i granice zapisu |
| Konfiguracja projektu | Repo, gałąź, cel, mapa dokumentów, uprawnienia i publikacja |
| `AGENTS.md` i prompt Codexa | Reguły techniczne środowiska i konkretne zlecenie |

Nie kopiuj skilla do Projects ani specyfikacji produktu do globalnego `AGENTS.md`. Krótka konfiguracja jest potrzebna: skill nie wie, którego produktu, repo i zgód dotyczy nowa rozmowa.

Wykorzystaj `assets/instrukcje-projektu.md` i `assets/konfiguracja-projektu.md`. Konfiguracja może stanowić `docs/README.md` razem z mapą. W istniejącym projekcie zachowaj nazwy i uporządkuj tylko zlecony zakres. Nie twórz obszernego podręcznika na zapas.

## Ustal uprawnienia konkretnego projektu

Przed zapisem przedstaw odpowiedni do etapu pakiet, o ile nie wynika już z polecenia:

- pracownicy: własna gałąź, commit, push i PR dotyczący dokumentów;
- PM: dokumenty wspólne i merge przejrzanych PR w przyjętym zakresie;
- Codex: operacje jawnie wymienione w konkretnym promptcie;
- publikacja: pierwsza po zgodzie na wynik, potem tryb uzgodniony dla projektu;
- koszty, publiczny dostęp, usuwanie i komunikacja do osób trzecich: wyłącznie w przyznanym zakresie.

Oznacz pakiet jako proponowany albo przyjęty i zapisz źródło. Nie dziedzicz zgody na merge z innego repo. Nie potwierdzaj ponownie pakietu już przyjętego w bieżącej rozmowie.

## Sprawdź środowisko

Preferuj Work Cloud w Projects oraz GitHub jako wspólne źródło. Zweryfikuj potrzebne odczyty i zapisy. Lokalny folder, sekret i załącznik nie są automatycznie dostępne w Cloud.

Przy pytaniu o modele, telefon i inne urządzenia sprawdź aktualne oficjalne zasady. Nie utrwalaj konkretnego modelu lub planu jako warunku. Według dokumentacji odczytanej 2026-11-11 Work nie działa z pamięcią „tylko dla projektu”; przy konfiguracji zweryfikuj ten warunek. Nie obiecuj przeniesienia instalacji ChatGPT do Codexa Local.

Przygotuj tekst do ustawień. Rozróżniaj przygotowanie tekstu, zmianę ustawień Projects, zapis na GitHubie i instalację skilla; raportuj faktyczny stan.

## Przejdź do pracy

Podaj przyjęty cel, pierwszy wynik do oceny, aktywną rolę i następne działanie. Na start wystarcza PM. Przy interfejsie preferuj wczesny działający prototyp najważniejszej interakcji, ocenę właściciela i dopiero później dopracowanie.

Gra, strona i narzędzie wewnętrzne są równorzędnymi zastosowaniami procesu. Nazwa pomysłu nie upoważnia do kontaktu z marką lub osobą, wykorzystania jej treści ani rozpoczęcia produktu. Nie przenoś specyfikacji witryny na grę.
