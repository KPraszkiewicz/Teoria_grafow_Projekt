# Algorytm Dijkstry
Aby uruchomić program, należy skompilować plik main.cpp, a następnie włączyć plik wykonywalny.
Plik dijkstra_dane.txt musi się znajdować w tym samym katalogu co plik wykonywalny programu.

### Struktura pliku dijkstra_dane.txt
```
liczba_wierzchołków liczba_krawędzi
od do waga
od do waga
od do waga
```

### jakie problemy rozwiązuje?
- Algorytm znajduje najkrótszą ścieżkę w grafie skierowanym o dodatnich wagach.
- Może sprawdzić, czy graf jest spójny.

### przykłady wykorzystania
- Jest często używany w sieciach komputerowych, np. przy trasowaniu (przykładowo w protokole OSPF).
- Może być wykorzystany w nawigacji.
- Wyszukiwanie ścieżki w grach.

### z jakich metod korzysta się obecnie do rozwiązywania tych problemów?
- Zwykle korzysta się z usprawnionego algorytmu dijkstry, który wykorzystuje kopiec fibonacciego.
- W grach zwykle stosuje się szybsze i prostrze algorytmy wyszukiwania ścieżki, które są mniej dokładne, ale pozwalają zaoszczędzić trochę zasobów.