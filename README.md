#!/bin/bash

echo "Dziendobry!"
echo "Oto kalkulator."
echo "Wybierz opcje:"

echo "1-dodawanie"
echo "2-odejmowanie"
echo "3-mnozenie"
echo "4-dzielenie"

read kal


echo "Podaj 1 liczbe"
read a

echo "Podaj 2 liczbe"
read b


if [ $kal = "1" ] 
    then 
        w=`expr $a + $b`
        echo "$w"
    elif [ $kal = "2" ] 
    then 
        w=`expr $a - $b`
        echo "$w"
    elif [ $kal = "4" ] 
    then 
        w=`expr $a / $b`
        echo "$w"
    elif [ $kal = "3" ] 
    then 
        w=`expr $a \* $b`
        echo "$w"
fi 
