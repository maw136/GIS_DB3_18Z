# Konspekt
## Założenia dotyczące sieci
Lorem

## Definicje
Ipsum

### itp
Dolor

##TEMP



	1. Zadanie:
	Obliczanie maksymalnej i minimalnej przepustowości pomiędzy węzłami grafu skierowanego G w którym wagi krawędzi V(E) oznaczają przepustowości krawędzi.
	2. Kontekst:
	Zadanie przybliża problem zarządzania przepustowością sieci (komputerowych, wodociagowych, elektrycznych, kolejowych). Rozwiązanie tak postawionego problemu może być wykorzystane m. in. w następujący sposób:
		a. Różnego rodzaju heurystyki,
		b. Eliminacja połączeń o niewielkim znaczeniu,
		c. Planowanie rozbudowy sieci o dodatkowe węzły,
		d. Przewidywanie awarii
	3. Założenia 
		○ Nieujemne wagi w grafie,
		○ Maksymalnie 1 krawędź pomiędzy parą wierzchołków.
		○ Grafy badawcze zostaną wygenerowane w ramach zadania.
	4. Specyfikacja:
		a. Wejście: 2 wierzchołki z zadanego grafu
		b. Wyjście: 2 listy wierzchołków składających się na ścieżki o największej i najmniejszej przepustowości, razem z
			i. sumarycznymi przepustowościami,
			ii. wskazaniem gorącej krawędzi.
	5. Analiza:
	Algorytm musi być przetestowany na szeregu grafów o różnych proporcjach krawędzi do wierzchołków oraz różnych rozkładach wag.
	Wymagane jest prawidłowe działanie (detekcja błędu) dla  nieznalezienia ścieżki łączącej wierzchołki.
		○ Przypadek taki może wystąpić w wyniku specyficznego układu kierunków krawędzi.
	
	Zbadana zostanie również złożoność obliczeniowa i pamięciowa algorytmu w oparciu o projekt i eksperyment.
	Wyznaczone zostaną ograniczenia na parametry grafu (liczba wierzchołków, krawędzi, skierowań) ze względu na wydajność.
	
