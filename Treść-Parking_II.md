### Parking (II)
Parking składa się z 16 stanowisk postojowych. Czujniki monitorują zajętość miejsc i przesyłają do systemu informatycznego skompresowaną informację w postaci 16-bitowej liczby w kodzie U2 przy założeniu, że 1 oznacza miejsce zajęte, a 0 miejsce wolne (zapis identyczny jak w zadaniu Parking (I)). Napisz program, który poda informację o ilości wolnych miejsc na parkingu.
## Wejście
Liczba całkowita (16-bitowa w kodzie U2) w systemie dziesiętnym oznaczająca informację na temat zajętości miejsc.
## Wyjście
Liczba całkowita z przedziału <0; 16> - ilość wolnych miejsc na parkingu.
## Przykład
### Wejście:
```
-19415
```
### Wyjście:
```
9
```
Wyjaśnienie do przykładu: Zajęte i wolne stanowiska zapisane w postaci liczby -19415 odpowiadają ciągowi bitów 1011010000101001, w którym jest 9 zer (czyli wolnych miejsc).
