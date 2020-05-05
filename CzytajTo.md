# Informacje o Knowledge Universe Advanced
##  Cel
Główna idea **Knowledge Universe Advanced** to stworzenie zbioru skondensowanej wiedzy w celu szybszego poszerzania horyzontów. Osiągane to jest dzięki współpracy, dzieleniu się wiedzą z innymi. Cccemy dzielić się wiedzá i umiejętnościami szybciej.
Pomyśl o tym jak o zdecentralizowanej i skompresowanej wikipedii bez cenzury i z mniejszą ilością stron (tworzymy nową stronę dla nowej kategorii a nie dla każdego pojęcia) 

## Historia i przeznaczenie
Oczywiste jest, że wszystko czego się nie powtarza to się zapomina. Dlatego zwykle po przeczytaniu mądrej książki stosujemy kilka zasad a reszta idzie w zapomnienie. Zdecydowana większość. Rzadko kiedy możemy nawet całą naraz wykorzystać.
Dobre notatki są zbawienne ale zajmują dużo miejsca, i jest ich za dużo aby je czytać. Nie ma także motywacji. Ich stworzenie zajmuje wiele czasu i energii. A wiedza się powtarza. Czasami dwie różne książki mogą się pokrywać w 80%.
Po co więc robić te same notatki 2 razy?
Tutaj zaczyna się Knowledge Universe.
Otwarte centrum notatek z różnych dziedzin życia w którym wiele osób tworzy i aktualizuje różne notatki. **Dołącz i Ty!**

## Jak zacząć?

1. Opanuj podstawy użycia githuba, tak abyś wiedział(a) co to commit, push, pop, pull request, merge.
	- githuba można używać w przeglądarce, w aplikacji internetowej lub programie pobranym na komputer/smartfona
2. Opanuj podstawy *języka* markdown. To naprawdę tylko kilka trików, np. aby pogrubić tekst wystarczy napisać: **\*\*tekst\*\***

## Workflow
Jak to wygląda w praktyce:

1. Masz jakiś **jeden (naraz)** materiał, jak książka, artykuł, filmik, film dokumentalny itp...
2. Tworzysz nowy "branch" w repozytorium z odpowiednią nazwą: **"(TYP_MATERIAŁU)(JĘZYK_MATERIAŁU)(AUTOR)-NAZWA\-MATERIAŁU"**
	1. Typy materiałów: **KSIĄŻKA, ARTYKUŁ, STRONA WWW, WIDEO, FILM, AUDIOBOOK, PODKAST**
	2. Gdy nie ma jasno podanego autora to nazwa serwisu, kanału lub strony.
	3. Przykład użycia: **(STRONA WWW)(PL)(VISMAYA-MAITREYA)-BPA-NIEBEZPIECZNA-TOKSYNA**
3. Zaktualizuj "Źródła.md" podając źródło materiału
4. Zrób notatki w odpowiednim pliku/plikach (jeśli materiał jest z kilku dziedzin).
5. Ewentualne załączniki dodaj w folderze o nazwie notatki który jest w folderze z daną notatką .md.
	1. Pliki nazywają się w formie **"0047\_Bpa-przyklad-pierwszy.jpg"**
	2. Przykład: notatka "Zdrowie.md" ma załączniki w folderze "Zdrowie" obok tej notatki. Zał. numerujemy od 0001.
	3. Należy dodać odwołanie do każdego załącznika w tekście. I do każdego odwołania ma być 1 plik. Odwołanie to napisać w formie **"Zobacz przykład @0047"** i jest już wtedy jednoznaczne gdzie go szukać.
6. "Commituj" zmiany na swój "branch".
7. Gdy już skończysz, utwórz "pull request"
8. Twoje zmiany, twój branch, zostanie przyłączony do brancha "master" przez administratora.
9. Każdy branch to materiał z 1 źródła. Branch ze informacjami z kilku źródeł naraz będą **odrzucane**.

Oczywiście aby zapisać i podzielić się tekstem przed ukończeniem dzieła, warto robić commity i pushować co jakiś czas.

## Zasady
- **Każdy branch to materiały z 1 źródła **
- Zbieramy całą możliwą wiedzę i dajemy tutaj w ORYGINALNEJ ale *skompresowanej* formie. Sama esencja, ale bezstratna. Tak, że można wyrzucić tą np. książkę i całą ważną wiedzę odtworzyć stąd. Nigdy nie wracać do materiału źródłowego.
- Jeśli wiedza jest bardziej podatna do zawarcia w formie graficznej, wtedy dodać załączniki, ale raczej unikać tego
- Unikać pisania opinii, ale jeśli już jest to coś bardzo istotnego, to *upewnij się, że jest to dobrze zaznaczone pisząc kursywą.*
- Cenzura jest ŚCIŚLE ZABRONIONA. Nie oceniamy wiedzy. Mamy listę autorów i źródeł więc wiemy skąd każda informacja pochodzi. Każdy osądza odpowiednie **źródło** wg. siebie samego. Zasada nie tyczy się ewidentnego trollowania itp.
- Jeśli jest mnóstwo szczegółowej wiedzy, lepiej jest przechowywać ją w oddzielnym pliku
- Zbieramy wiedzę ze wszystkich dostępnych źródeł ale proszę napisać jaki był język źródła (w tytule brancha i w Źródła.md)
- notatki i foldery na załączniki są w folderze "Knowledge", w folderze głównym nic nie dodawać!

## Sekcje TODO
Jeśli zostawisz coś nieukończonego, napisz **"TODO"**. Będzie wtedy ławo to znaleźć i ukończyć.
Takie fragmenty powinny, jeśli w ogóle taka powstanie, być ukończone w branchu materiału przed pull requestem.
W trakcie tworzenia notatek dopuszczalne jednak jest ich tymczasowe istnienie.

## Styl
Używamy *języka* markdown do pisania. Dzięki temu tekst wygląda **dobrze** podczas gdy jest kompatybilny z *repozytorium*.

Zasady formatowania tekstu:

- dbać o ładne formatowanie tekstu
- nagłówki dla struktury tekstu (hierarchiczna budowa tekstu)
- Tekst normalny
- Tekst **pogrubiony** dla szczególnie ważnych fragmentów
- Tekst *pochyły* jest apropo subiektywnych opini i doświadczeń

Można używać linki.

## Źródła

Zawsze pisać źródło materiału w pliku "Źródła.md" w głównym katalogu i w nazwie brancha.

Używać wszystko co jest dostępne, np:

- książki
- filmy, wideo, itp.
- youtube, bitchute itp.
- artykuły
- audiobooku, podkasty itp.
- strony internetowe

## Autor

**Pomysł i realizacja przez M4S13R, Maj 2020. Kopiowanie fragmentów Knowledge Universe Advanced jest dozwolone, ale tylko i wyłącznie bez modyfikacji, z odpowiednim kontekstem i z odsyłaczem do repozytorium.** 