#!/bin/bash
echo "Podaj pierwsza liczbe"
read a
echo "Podaj druga liczbe"
read b
c=$(expr $a + $b)
d=$(expr $c % 2)
echo "Suma tych liczb to: "$c
