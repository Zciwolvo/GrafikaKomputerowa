<style>
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
</style>

<h1>SPRAWOZDANIE</h1>
<p align="center">Zajęcia: Grafika komputerowa</p>
<p align="center">Prowadzący: prof. dr hab. Vasyl Martsenyuk</p>

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<p align="center"><b>Laboratorium: </b>6</p>
<p align="center"><b>Data: </b>11.04.2023</p>
<p align="center"><b>Temat: </b>Światło i materiały</p>
<p align="center"><b>Wariant: 8</b></p>

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

1.  **Polecenie nr. 1.:** \
     Obiekt 1. Korkociąg wokół osi {x | y | z} zawierający N obrotów. Punkty są stopniowo powiększane. Ustalić aktualny kolor rysujący na {zielony | niebieski | brązowy | … }. \
    [<Kod zadanie 1. i 2. github>](https://github.com/Zciwolvo/GrafikaKomputerowa/blob/main/Lab4/lab4.svg)

    &nbsp;

    Korkociąg został stworzony poprzez jedną dość prostą funkcję matematyczną, która w pętli rysuje punkty oddalone od siebie o niewielką przestrzeń tworząc koła w każdej iteracji przy czym wysokość każdego z punktów stale wzrasta sprawiając wrażenie struktury podobnej do sprężyny

       <div align="center">
       <img src="z1.png" />
       </div>

2.  **Polecenie nr. 2.:** \
    Obiekt 2: Pyramida, wykorzystując dwa wachlarze trójkątów oraz modelowanie hierarchiczne (najpierw tworzymy podprogramę rysowania jednego trójkonta; dalej wykorzystując przekształcenia geometryczne tworzymy pyramidę). Podstawą pyramidy jest wielokąt o **n** wierzchołkach.

    &nbsp;
    Zaczynamy przez utworzenie funkcji piramida, która za parametry przyjmuje nasz silnik graficzny oraz liczba wierzchołków **n**, następnie iterując przez naszą liczbę wierchołków będziemy potrzebować nowej funkcji, która na podstawie położenia danego wierchołka oraz jego poprzednika utworzy trójkąt za pomocą funkcji matematycznych.

       <div align="center">
       <img src="z21.png" />
       </div>
     Podstawa przykładowej piramidy o 8 kątach
       <div align="center">
       <img src="zad22.png" />
       </div>

3.  **Pozostałe figury:** \
    Dodatkowo stworzyłem sześcian, ze względu na to że nie można go napisać w algorytmiczny sposób ze względu na brak zależności między jego wierchołkami musiałem wypisać współrzędne na osi x,y,z każdego z jego wierchołków. Następnie narysowałem każdą z jego sześciu ścian i otrzymałem kompletny sześcian.

      <div align="center">
       <img src="z31.png" />
       </div>

4.  **Wnioski** \
    Biblioteka OpenGL służąca do tworzenia trój wymiarowych obiektów w języku java jest niesamowitym narzędziem z bardzo wieloma możliwościami wliczając w to funkcje wielu obiektów geometrycznych. Jednak moim zdaniem budowanie złożonych tworów za pomocą tych technologii może dla wielu okazać się zbyt zagmatwane przez co prędzej skorzystałbym z silników graficznych jak na przykład unity.
