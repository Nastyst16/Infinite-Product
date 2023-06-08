# Infinite-Product
##### Exercise 1 - Homework PCLP 1

##### Copyright 2022
##### Nastase Cristian-Gabriel Grupa 315CA
##### PCLP


## Problema 1 - Un produs infinit

      Modularizam problema cu ajutorul headerului intitulat "function1.h"

            Incepem prin citirea primei valori din cei doi vectori
      deoarece avem nevoie sa stocam aceste doua numere in variabilele maxa si maxb,
      ca ulterior sa ne ajute in determinarea celui de al doilea maxim.

    Folosim un "for" care ne calculeaza simultan cerintele problemei:
      a) produsul scalar in variabila "ps"
      b) al doilea maxim din fiecare vector in variabilele "a_max" si "b_max"
      c) norma 2 pentru fiecare vector (utilizand formula atasata)

            Prin acest "for" evitam folosirea vectorilor care presupun o optimizare 
      deficitara din punct de vedere al memoriei utilizate si al timpului de executare.

            Am avut grija sa observ daca al doilea maxim nu exista, iar variabilele 
      a1_ok si b1_ok imi comunica acest lucru.

      La final tratam separat cazul in care n == 0 si afisam cerintele cerute.
