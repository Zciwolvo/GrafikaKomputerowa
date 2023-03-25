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

<p align="center"><b>Laboratorium: </b>3</p>
<p align="center"><b>Data: </b>14.03.2023</p>
<p align="center"><b>Temat: </b>Modelowanie hierarchiczne w grafice 2D</p>
<p align="center"><b>Wariant: </b>8</p>

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
    Opracować scenę hierarchiczną zgodnie z obrazem używając zamiast kół wielokąty obracające się (animacja!) według wariantu. Opracowanie powinno być w jednym z języków: Java lub JavaScript,
    na dwa sposoby: \
    a) używając hierarchiję funkcje (sposób subroutinowy) \
    b) tworząc graf sceny (sposób obiektowy). W tym celu proponuję do pobrania odpowiedni pliki

    &nbsp;

2.  **Sposób rozwiązania zadania 1a:** \
     [<Kod zadanie 1a. github>](https://github.com/Zciwolvo/GrafikaKomputerowa/blob/main/Lab3/SubroutineHierarchy.html) \
     Zacząłem od stworzenia funkcji tworzącej kształt według wariantu na kole za pomocą funkcji matematycznych. Następnie zauważyłem że figura na obrazku składa się z trzech część: trójkąta jako podstawy, lini łączącej dwa ośmiokąty (w moim przypadku) oraz wspomnianych wcześniej w zdaniu ośmiokątów. Do każdej z figur stworzyłem funkcje przyjmujące odpowiednie parametry po czym podsumowałem wszystko tworząc funkcje łączącom ze sobą podstawę z belką. gdy miałem już wszystkie potrzebne funkcję wykorzystałem wbudowane funkcje canvy aby umieścić struktury na ekranie w odpowiednich miejscach zgodnie z referencją.

3.  **Sposób rozwiązania zadania 1b:** \
     [<Kod zadanie 1b. github>](https://github.com/Zciwolvo/GrafikaKomputerowa/blob/main/Lab3/SceneGraph.html) \
    Tym razem w podejściu obiektowym, utworzyłem obiekt **shape**, który w bardzo podobny sposób z wykorzystaniem funkcji matematycznych buduje nam ośmiokąt. Po dodaniu do naszego obiektu shape metody rysującej zamierzony kształt przechodzimy do funkcji generującej plansze. Tworzymy wszystkie potrzebne obiekty w nieco pododbny sposób ale tym razem nieco bardziej odosobniony od siebie gdyż każdy z fragmentów struktur stworzyłem jako osobny obiekt. Po ułożeniu wszystkiego w pozycjach zgodnych z referencją dodałem do funkcji aktualizującej klatki obrót każdego z ośmiokątów.
4.  **Wnioski:**
    Metody graficzne języka Javascript posiadają bardzo wiele przydatnych funkcji, które z odrobiną wprawy pozwolą nam utworzyć niemalże wszystko, a różnica pomiędzy podejściem obiektowym a subrutynowym jest mimo wszystko dość spora jednak dla różnych rozwiązań jedno podejście zazwyczaj będzie lepsze od drugiego jednak to wszystko zależy od rodzaju problemu, z którym się mierzymy.
