# CryptCesar

# Лабораторна робота №1

Криптосистема на основі шифру цезаря.


Базові відомості :
Шифр Цезаря - один з найдавніших шифрів, названий на честь римського імператора Гая Юлія Цезаря, який використовував його для секретного листування. При шифруванні кожен символ замінюється іншим, віддаленим від нього в алфавіті на фіксоване число позицій. 

Якщо зіставити кожному символу алфавіту його порядковий номер, то шифрування і розшифрування можна виразити формулами модульної арифметики: 
y=(x+k) mod n 
x=(y+n−(k mod n)) mod n, 
де x - символ відкритого тексту, y - символ шифрованого тексту, n - потужність алфавіту, а k - ключ. 

### Посилання

З прикладами використання шифру Цезаря можна ознайомитись на чисельних сайтах відповідної тематики, наприклад: 


* [Ciox.ru](https://ciox.ru/caesar-cipher)- Ciox шифр цезаря!
* [Questhint.ru](http://questhint.ru/shifr-tsezarya/ ) - Questhint шифр цезаря
* [Hostcity.ru](http://hostciti.net/calc/it/cipher-ceaser.html ) - Hostcity шифр цезаря

## Переглянути онлайн
[`https://vitalikprac.github.io/cryptCesar/`](https://vitalikprac.github.io/cryptCesar/)


Ліцензія
----

MIT
