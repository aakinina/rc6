# RC6-new-

## Домашняя работа №2 по "Программирование алгоритмов защиты информации"

### Реализовать алгоритм симметричного блочного шифрования RC6

RC6 — полностью параметризированная семья алгоритмов шифрования. Для спецификации алгоритма с конкретными параметрами, принято обозначение RC6-w/r/b, где

w — длина машинного слова в битах.
r — число раундов.
b — длина ключа в байтах. 

Используются четыре 32-битных регистра. Число раундов по умолчанию равно 20. Ключ 16, 24 или 32 байт.

Соответственно, реализованы RC6-32/20/16, RC6-32/20/24, RC6-32/20/32

![](https://github.com/aakinina/RC6-new-/blob/main/rc6_encryption.PNG)

### Сборка

cmake CMakeLists.txt
make
./RC6

### Результаты

![](https://github.com/aakinina/RC6-new-/blob/main/results.PNG)

### Источники

1) http://people.csail.mit.edu/rivest/pubs/RRSY98.pdf
2) Сергей Петрович Панасенко "Алгоритмы шифрования. Специальный справочник", 2015
3) https://tools.ietf.org/id/draft-krovetz-rc6-rc5-vectors-00.html
