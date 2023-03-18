<style>
  body {
    font-size: 11px;
  }
  h1,
  h2,
  h3,
  h4 {
    border-bottom: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 0;
    font-weight: bold;
  }
  p{
    font-size: 1.5em;
    margin-bottom: 0;
  }
  img {
    align-self: center;
  }
  .center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}

</style>

<h1>SPRAWOZDANIE</h1>
<p align="center">Zajęcia: Grafika komputerowa</p>
<p align="center">Prowadzący: prof. dr hab. Vasyl Martsenyuk</p>

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<p align="center"><b>Laboratorium: </b>2</p>
<p align="center"><b>Data: </b>07.03.2023</p>
<p align="center"><b>Temat: </b>Grafika 2D z użyciem HTML Canvas</p>
<p align="center"><b>Wariant: </b>4</p>

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<p align="end">Igor Gawłowicz,</p>
<p align="end">Informatyka I stopień,</p>
<p align="end">4 semestr,</p>
<p align="end">Gr. 2b</p>

<div style="page-break-after: always;"></div>

1.  **Polecenie nr.1:** \
    Narysować obraz zgodnie z wariantem zadania (patrz Fig. 1) (używając
    zarówno standardowe jak i niestandardowe funkcje rysowania).
2.  **Sposób rozwiązania zadania nr.1:** \
    [<Kod zadanie 1. github>](https://github.com/Zciwolvo/GrafikaKomputerowa/blob/main/Lab2/Lab2Ex1.html) \
     Za pomocą standardowaych funkcji rysowania narysowałem krzyżujące się czerwone prostokąty, następnie oczy składające się z 3 malejących kół, a na końcu usta składające się z dwóch nachodzących na siebie owali, dwóch białych prostokątów stworzonych w odpowiedniej kolejności żeby na siebie dobrze nachodziły, oraz 2 poligonów służących za kąciki ust.

    &nbsp;

      <img class="center" src="z1.png" align="center">

3.  **Polecenie nr.2:** \
    W pliku Lab2Ex2.html program domyślnie rysuje szereg kwadratów. Stworzyć narzędzia pozwalające na wykonywanie czynności

    - Czyszczenie
    - Dodanie nowego koloru
    - Narzędzie rysowania wielokątów(ośmiokąt).

4.  **Sposób rozwiązania zadania nr.1:** \
    [<Kod zadanie 2. github>](https://github.com/Zciwolvo/GrafikaKomputerowa/blob/main/Lab2/Lab2Ex2.html) \
    Dodanie funkcji czyszczącej plansze było bardzo proste wystarczyło dodać przycisk **Clear**, który przywołuje funkcję inicjalizującą czyli taką która aktywuje się po wczytaniu strony i przywraca wszystko do wartości podstawowych. \
    Nowy kolor dodałem poprzez zmianę dropdown selecta oraz dodanie nowego warunku do bloku if/else \
    Aby dodać nowe narzędzie pędzla w kształcie ośmiokątu, dodałem nową zmienną **shape**, w zależności od której używany jest pędzel kwadratowy lub nowy ośmiokątny, a następnie standardowymi kształtami utworzyłem ośmiokąt z dwóch prostokątów oraz 4 polygonów w kształcie trójkata równobocznego.

    &nbsp;

       <img class="center" src="z2.png" align="center"/>

5.  **Wnioski:**

    Funkcje graficzne w języku skryptowym javascript mają bardzo podobnych możliwości do języka Java, jednak przez to że java jest ograniczona do programowania objektowego javascript wydaje się nieco przyjaźniejsza dla początkującego programisty.
