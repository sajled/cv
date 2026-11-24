# CV w LaTeXu

Moje CV na jedną stronę A4, napisane w LaTeXu (zadanie 3 z listy 7, Podstawowy warsztat informatyka).

## Skąd co pochodzi

- **Układ graficzny** (nazwa i tytuł na górze, sekcje z nazwą po lewej i treścią po prawej, poziome linie) jest wzorowany na szablonie z Canvy:
  https://www.canva.com/templates/EAGQUnFrIZI-science-and-engineering-resume-in-white-black-simple-style/
  Nie kopiowałem niczego z tego szablonu poza ogólnym wyglądem. Canva to szablon graficzny, a tu jest kod LaTeX napisany od nowa.
- **Początek preambuły** (pakiety do polskich znaków i języka) pochodzi z przykładowego pliku z repozytorium z listy 7 (https://github.com/iiuni/LaTeX).
- **Pomoc Claude'a (Anthropic):** pomógł mi napisać makra `\cvsection` i `\wpis`, ustawić marginesy i listy oraz poprawić błędy przy kompilacji. Tłumaczył też, jak to działa.

## Mój wkład

- cała treść CV: dane, wykształcenie, doświadczenie, projekty, umiejętności, kwalifikacje
- wybór układu i sekcji
- sklejenie wszystkiego, kompilowanie i poprawianie

## Jak skompilować

    pdflatex cv.tex

W repozytorium trzymam tylko pliki źródłowe. Plik `cv.pdf` i pliki pomocnicze (`.aux`, `.log`, `.out`) są w `.gitignore`.

