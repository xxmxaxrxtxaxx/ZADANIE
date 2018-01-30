#!/bin/bash

echo "Podaj jaki masz dzis humor w skali od 1 do 3"
read humor

if test $humor  == 1 ; then
echo "Masz zły humor"

elif test  $humor == 2 ; then
echo "Masz średni humor"

else 
echo "jesteś szczęśliwy"

fi


