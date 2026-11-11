# Weryfikacja

Data: 2026-11-11.

## Wykonane sprawdzenia

Przed pierwszą instalacją wykonano oficjalny quick_validate.py, sprawdzenie odsyłaczy, metadanych i braku niedokończonych TODO oraz potwierdzono zapis całej paczki w koncie ChatGPT. Repo RybCode wykorzystano wyłącznie do odczytu.

W kopii GitHub zachowano instrukcje i szablony, a z metadanych pominięto automatyczną ikonę platformy. Sprawdzono kompletność plików i cele odsyłaczy.

## Przegląd reguł według scenariuszy

Tabela dokumentuje analizę instrukcji, nie niezależny test zachowania modelu.

| Scenariusz | Reguła |
|---|---|
| Mały eksperyment bez repo | PM i potrzebny etap, bez wymuszania pełnego zespołu |
| Gra edukacyjna | Role dobrane do gry; brak odziedziczonej specyfikacji witryny i zgody na kontakt z marką |
| Niepodane repo | Zebranie brakującego repo/materiałów i ustalenie praw przed zapisem |
| Odpowiedź „A” | Akceptacja przedstawionego wyboru w jego granicach |
| Wznowienie specjalisty | Celowany odczyt i własny istniejący dokument |
| Zadanie Codexa | Jeden prompt, krótki status w PM, brak TASK |
| Częściowe dowody lub nowy head PR | Odbiór dokładnej wersji z jawnymi ograniczeniami |
| Merge uruchamia pierwszą publikację | Zgoda na wynik i sprawdzenie skutku przed merge |
| Zmiana kierunku | Tylko dotknięty zakres; docs/ aktualizuje zespół, dokumenty główne Codex |
| Local → Cloud | Weryfikacja zachowania bajtów i dostępności materiałów |
| Równoległość | Podział plików, baza i kolejność integracji, bez podagentów |
| Błąd GitHub | Zatrzymanie operacji i dokładny komunikat bez sekretów |
| Diagnoza bez nowych informacji | Fakty, sprawdzenia i opcje zamiast zapętlenia |
| Odrzucona propozycja | Brak powrotu jako zadanie lub zastępcza kampania testów |

## Ograniczenia

Nie wykonano niezależnego testu w nowych rozmowach modelu, pełnego projektu z tym skillem ani testu na drugim komputerze i telefonie. Pierwsze użycie pozwoli ocenić potrzebne korekty.
