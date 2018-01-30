#!/bin/bash
echo "Podaj pierwsza liczbe"
read a
echo "Podaj druga liczbe"
read b
c=$(expr $a + $b)
echo "Suma tych liczb to: "$c
echo "Podaj kolejna liczbe"
read d
e=$(expr $c + $d)
echo "Teraz suma wynosi:"$e 
