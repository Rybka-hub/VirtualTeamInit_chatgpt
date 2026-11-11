# VirtualTeamInit — Zespół projektowy

Skill do prowadzenia projektu przez PM i potrzebnych specjalistów w osobnych rozmowach ChatGPT Work w Projects. Codex Local lub Cloud wykonuje uzgodnione zadania techniczne. Właściciel przenosi prompty i wraca do PM z numerem PR.

## Wywołanie i start

Nazwa w katalogu Skills: **Zespół projektowy**. Identyfikator: `prowadz-zespol-projektowy`.

1. Utwórz projekt ChatGPT i rozmowę Work Cloud, jeżeli funkcja jest dostępna w Twoim środowisku.
2. Wybierz skill lub napisz: „Użyj skilla Zespół projektowy. Pełnij rolę PM nowego projektu. Mój pomysł to…”.
3. PM ustala pierwszy spójny etap i zbiera tylko brakujące informacje. Jeśli nie podałeś repo i nie wskazuje go konfiguracja, pyta o właściwy link `owner/repo` oraz zakres dostępu. Nie wybiera repo na podstawie innego projektu.
4. Gdy repo jeszcze nie istnieje, możecie omawiać pomysł bez zapisu. Utworzenie repo i jego widoczność wymagają właściwego polecenia.
5. PM przygotowuje krótki tekst do ustawień Projects: cel, źródła, repo i uprawnienia. Nie trzeba przepisywać procedur skilla.
6. Potrzebne rozmowy specjalistów uruchamiasz gotowymi promptami PM. Zadania wykonawcze wklejasz do Codexa Local albo Cloud po sprawdzeniu dostępu do materiałów.

## Zawartość

- [SKILL.md](skills/prowadz-zespol-projektowy/SKILL.md): zasady wspólne i wybór trybu.
- `references/`: start, PM, specjalista oraz kontrakt wykonawcy i przekazanie Local ↔ Cloud.
- `assets/`: instrukcje Projects, konfiguracja, opracowanie roli i prompty.
- [VERIFICATION.md](VERIFICATION.md): zakres sprawdzeń i ograniczenia.

## Reguły

- Zespół i formalności rosną według potrzeby; na start może wystarczyć PM z Codexem.
- Zespół utrzymuje `docs/`, Codex dokumentację wykonawczą w katalogu głównym oraz potrzebne raporty w `implementation/`.
- Pełne zadanie pozostaje w promptcie, bez osobnych plików TASK i kopii w dokumencie PM.
- PM organizuje niezależne zadania równoległe; nie uruchamia automatycznych podagentów ani komunikacji między rozmowami.
- Decyzje mają źródło i granice. Merge nie zatwierdza propozycji; jego skutek publikacyjny sprawdza się przed scaleniem.
- Zgody dotyczą konkretnego projektu i nie przechodzą automatycznie z wcześniejszego repo.

## Instalacja i aktualność

Samo zapisanie lub pobranie repo nie instaluje skilla. Instalacja w koncie ChatGPT i lokalne pliki Codexa to osobne mechanizmy. Dostępność oraz synchronizacja zależą od produktu i środowiska; sprawdzaj właściwą listę Skills. Zapis tej kopii nie aktualizuje automatycznie skilla na koncie.

Instrukcje merytoryczne odpowiadają pierwszej zainstalowanej wersji. Metadane UI zawierają nazwę, opis i prompt; pominięto ikonę dodaną automatycznie przez platformę.

Oficjalne materiały do sprawdzenia przy konfiguracji:

- [Skills in ChatGPT](https://help.openai.com/en/articles/20001066-skills-in-chatgpt)
- [Projects in ChatGPT](https://help.openai.com/en/articles/10169521-projects-in-chatgpt)

Skill nie narzuca modelu, abonamentu ani stosu technologii. Nie zawiera specyfikacji i uprawnień repo RybCode.
