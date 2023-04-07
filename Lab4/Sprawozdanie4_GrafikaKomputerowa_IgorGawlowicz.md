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

<p align="center"><b>Laboratorium: </b>4</p>
<p align="center"><b>Data: </b>21.03.2023</p>
<p align="center"><b>Temat: </b>Język opisu sceny SVG</p>
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

1. **Polecenie nr. 1:**

- Opracować scenę hierarchiczną zgodnie z obrazem używając zamiast kół wielokąty obracające się (animacja!) według wariantu. Opracowanie powinno być w języku SVG.
- **Sposób rozwiązania:** \
  Utworzyłem nowy plik SVG zdefiniowałem rozmiary obszaru, który zostanie wygenerowany.
  Następnie utworzyłem nowy obiekt graficzny o identyfikatorze Octagon gdyż moim wariantem zadania był ośmiokąt utworzyłem go poprzez wypunktowanie następnych wierzchołków naszej figury w taki sposób żeby spójnie składały się w ścieżkę tworzącą ośmiokąt foremny.
  Kolejnym krokiem było stworzenie 8 linii od środką figury do każdego z jej wierzchołków za pomocą wbudowanej w język SVG linii. \
  Po utworzeniu całej figury następnym krokiem było ustawienie transormacji animującej **animateTransform** \
  Później musiałem już tylko stworzyć proste kształty takie jak trójkąt budujący podstawę oraz prostokąt przysłowiowo nazwany "huśtawką" \
  Ostatnim już krokiem było wywołanie naszych kształtów na ekranie i odpowiednie dopasowanie ich metodą prób i błędów.

2. **Wnioski:** \
   Język SVG jest powszechnie używany w logach i prostych symbolach ze względu na swoją bezstratną skalowalność do ekranu gdyż jest on zapisany za pomocą funkcji matematycznych w odróżnieniu od formatów zapisu grafiki rastrowej jakość obrazu nigdy nie wytraca na rozdzielczość, jednak pisanie czegoś bardziej skomplikowanego może okazać się kłopotliwe i kontr produktywne w takiej sytuacji należy skorzystać z przeznaczonych do tego programów obróbki graficznej.
