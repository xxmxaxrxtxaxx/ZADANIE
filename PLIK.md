#!/bin/bash
echo "Podaj pierwsza liczbe"
read a
echo "Podaj druga liczbe"
read b
c=$(expr $a + $b)
echo "Suma tych liczb to: "$c
