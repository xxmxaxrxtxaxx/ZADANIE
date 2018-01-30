#!/bin/bash

echo "Podaj jaki masz dzis humor w skali od 1 do 3"
read a

if test $a == 1; then
echo "Masz zły humor"

elif test $a == 2; then
echo "Masz średni humor"

else 
echo "jesteś szczęśliwy"

fi

