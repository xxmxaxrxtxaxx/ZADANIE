#!/bin/bash

echo "Podaj jaki masz dzis humor w skali od 1 do 3"
read a

if test $a == 1; then
echo "Masz zły humor"

elif test $a == 2; then
echo "Masz średni humor"

elif test $a == 3; then  
echo "jesteś szczęśliwy"

else 
echo "Twoj humor jest poza skala" 

fi

