# Somthing
Trying to figure out how to use git :) PART one, more to come. 

def pobierz_dane(liczba_cyfr):
    lista=[]
    for i in range(liczba_cyfr):
        lista.append(input("Podaj liczbe:"))
    return lista

d=int(input("Podaj liczbę cyfr:"))
print(pobierz_dane(d))



def parzysto(liczba):
    for i in range(liczba):
        if liczba%2 == 0:
            return ("prawda")
        else:
            return ("fałsz")

for i in ziemniak:
    print(parzysto(i))
