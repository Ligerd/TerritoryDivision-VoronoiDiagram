# Podzial-teretorii-na-obszary-Voronoi-diagram-
## Programu umożliwia:

a.) wczytanie konturu analizowanego terenu wraz z umiejscowieniem punktów kluczowych (banki, parabanki, kasy oszczędnościowo-kredytowe);

b.) narysowanie optymalnych granic obszarów (na danym obszarze mieści się tylko jeden punkt kluczowy);

c.) naniesienie na wczytany teren (mapę) obiektów, które podlegają analizie ;

d.) definiowanie typów obiektów / budynków, które mogą podlegać analizie w trakcie działania programu;

e.) dodawanie / usuwanie elementów konturu terenu;

f.) dodawanie / usuwanie punktów kluczowych;

g.) nakładanie (podkładanie) grafiki pod wyznaczone kontury, aby można było w sposób bardziej wiarygodny wizualizować analizowany obszar;

h.) wyświetlenie listy obiektów należących do danego obszaru;

i.) wyświetlenie zbiorcze (grupujące po ich typie) listę obiektów należących do danego obszaru;

j.) wyświetlenie (zbiorcze) liczby mieszkańców danego terenu (na podstawie informacji o budynkach mieszkalnych).

## Przykładowy plik wejściowy ma następującą strukturę:

Kontury terenu (wymienione w kolejności łączenia): Lp. x y
1. 0 0
2. 0 20
3. 20 30.5
4. 40 20
5. 40 0

Punkty kluczowe: Lp. x y Nazwa
1. 1 1 KOK Krawczyka
2. 1 19 KOK Kaczmarskiego
3. 30 10 KOK Łazarewicza

Definicje obiektów: Lp. Typ_obiektu (Nazwa_zmiennej Typ_zmiennej)*
1. SZKOŁA Nazwa String X double Y double
2. DOM X double Y double L_MIESZKAŃCÓW int
3. NIEDŹWIEDŹ X double Y double

Obiekty: Typ_obiektu (zgodnie z definicją)
1. SZKOŁA "Szkoła robienia dużych pieniędzy" 4 1
2. DOM 4 3 100
3. DOM 4 17 120
4. DOM 4 18 80
5. NIEDŹWIEDŹ 20 20
6. NIEDŹWIEDŹ 40 1
7. NIEDŹWIEDŹ 39 1
8. NIEDŹWIEDŹ 39 2

Dokładną informację o projekcie można przeczytać w specyfikacjach projektu.
