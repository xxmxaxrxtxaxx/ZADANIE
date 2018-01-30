#!/bin/bash

echo "Dziendobry! wpisz liczbe od 1 do 3 a dowiesz sie czegos ciekawego."
read a

if test $a == 1; then
echo "2 + 2 to 4"

elif test $a == 2; then
echo "Magdalena Roszak to Geniusz!"

elif test $a == 3; then 
echo "zdalem grafike"

else 
echo "Nie wiesz jakie liczby znajduja sie w przedziale 1 do 3" 

fi

