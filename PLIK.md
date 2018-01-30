#!/bin/bash
echo "Podaj pierwsza liczbe"
read a
echo "Podaj druga liczbe"
read b
c=$(expr $a + $b)
echo "Suma tych liczb to: "$c
if test $c%2 == 0; then
echo "Jest to liczba parzysta"
else 
echo "Jest to liczba nieparzysta"
