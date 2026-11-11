# Szablony promptów

Uzupełnij potrzebne pola rzeczywistymi danymi, usuń zbędne i podaj właścicielowi gotowe polecenie. Sam szablon niczego nie zleca. Pełnego zlecenia wykonawczego nie kopiuj później do dokumentacji.

## Start projektu — przykład dla właściciela

```text
Użyj skilla Zespół projektowy (prowadz-zespol-projektowy).
Pełnij rolę 00 — PM nowego projektu. Pomysł: {opis}.
Materiały i repo, jeśli istnieją: {źródła}.
Pomóż ustalić pierwszy spójny etap. Zacznij od tego,
co już wiadomo, i najwyżej trzech potrzebnych pytań.
```

## Powołanie lub wznowienie specjalisty

```text
Użyj skilla Zespół projektowy w roli {nazwa} projektu {nazwa}.
Koordynatorem jest rozmowa {PM}; wyniki przenosi właściciel.
Repo i baza: {repo, gałąź}. Konfiguracja: {ścieżka}.
Celowany odczyt: {punkt startowy, bieżące podsumowanie PM,
właściwe decyzje, własny istniejący dokument i zależności}.
Twój wynik: {konkretny zakres i kryteria zakończenia}.
Przyjęte granice: {istotne decyzje i wyłączenia}.
Przeprowadź potrzebne wybory z właścicielem. Aktualizuj {plik}
po rozmowie, opisując aktualny stan i podstawy ustaleń.
Uprawnienia: {faktycznie przyznany zakres zapisu/Git}.
Przekaż właścicielowi PR i krótki wynik do przeglądu PM.
```

## Pełne zadanie dla Codexa Local albo Cloud

```text
Projekt/repo: {repo}. Baza: {gałąź}. Środowisko: {Local/Cloud}.
Wykonaj jeden spójny etap: {konkretny wynik}.
Sprawdź stan Git i właściwe AGENTS.md. Przy wznowieniu odczytaj
PROJECT_CONTEXT.md i HANDOFF.md lub projektowe odpowiedniki.
Źródła wymagań i przyjęte decyzje: {dokładne odsyłacze}.
Zakres: {zaakceptowane zachowania i zmiany}.
Poza zakresem: {istotne wyłączenia}.
Materiały, dostęp i równoległe zadania: {faktyczny stan}.
Kryteria odbioru: {sprawdzalne wyniki}.
Sprawdzenia: {adekwatne do zmiany; wymagane dowody i ograniczenia}.
Punkty oceny właściciela: {jeżeli potrzebne}.
Dobierz szczegóły wykonania w tych granicach. Prowadź potrzebne
kroki ręczne bez odsyłania każdej czynności do PM. Przy blokadzie
kontynuuj uzasadnione próby, dopóki dają postęp lub nowe informacje;
potem przedstaw właścicielowi fakty, sprawdzenia i dostępne opcje.
Zaktualizuj tylko dotknięte dokumenty główne. docs/ pozostaje
pod odpowiedzialnością PM i specjalistów, poza {jawne wyjątki}.
Nie twórz pliku TASK ani kopii tego zlecenia. PLANS.md opisuje
Twój plan, a HANDOFF.md aktualny stan wznowienia.
Uprawnienia: {dokładny zakres, w tym commit, push i utworzenie PR,
jeśli objęte poleceniem}. Merge: {PM / przyznany wyjątek}.
Publikacja i skutek PR/merge: {faktyczne warunki}.
Przy błędzie GitHub zatrzymaj dalsze operacje GitHub i zgłoś
dokładny komunikat bez sekretów oraz rzeczywisty stan.
Na koniec podaj PR, wykonany zakres, wyniki i pominięte sprawdzenia
oraz ewentualną konkretną blokadę do przekazania PM przez właściciela.
```

## Przejęcie rozmowy PM lub specjalisty

```text
Użyj skilla Zespół projektowy. Przejmij rolę {rola} w {projekt}.
Repo i wspólna baza: {dane}; konfiguracja i mapa: {źródło}.
Odczytaj {bieżący punkt startowy, własny dokument, właściwe decyzje
i potrzebne zależności}. Aktualny etap: {krótko, stan i wynik/PR}.
Obowiązujące granice i uprawnienia: {źródła i istotne ograniczenia}.
Zastąpione/odrzucone kierunki: {tylko istotne dla następnego kroku}.
Następny krok: {konkret}. Nie powtarzaj rozstrzygniętych pytań
ani nie odtwarzaj kolejki z archiwum. Sprawdź aktualny stan źródeł.
```

## Przekazanie tego samego zadania Codexa

Dotychczasowy wykonawca przygotowuje poniższy prompt po aktualizacji stanu i sprawdzeniu zachowania pracy:

```text
Wznów istniejące zadanie w {Local/Cloud}, bez rozszerzania zakresu.
Repo: {repo}; gałąź: {branch}; ostatni sprawdzony SHA: {sha}.
Odczytaj właściwe AGENTS.md, PROJECT_CONTEXT.md i HANDOFF.md.
Cel i istotne granice oryginalnego zlecenia: {krótko}.
Wykonano: {stan}; pozostało: {kroki i kryteria zakończenia}.
Materiały i stan zmian: {co faktycznie wysłano, co lokalne,
gdzie zachowano niezacommitowaną pracę i jak ją udostępniono}.
Sprawdź dostępność zasobów i konfiguracji bez ujawniania sekretów.
Zachowaj uprawnienia: {dokładny zakres pozostałych operacji}.
Zweryfikuj rzeczywisty stan Git przed zmianami. Nie porzuć cudzej
pracy i nie zakładaj, że lokalne pliki pojawiły się w Cloud.
Nowy cel lub zmiana zakresu wymagają decyzji właściciela/PM.
```
