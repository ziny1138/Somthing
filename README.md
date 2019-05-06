# Somthing
Trying to figure out how to use git :) PART one, more to come. 

def pobierz_dane(liczba_cyfr):
    lista=[]
    for i in range(liczba_cyfr):
        lista.append(input("Podaj liczbe:"))
    return lista

d=int(input("Podaj liczbę cyfr:"))
print(pobierz_dane(d))


def srodkowy(lista):
    if len(lista)==1 or len(lista)==2:
        return lista
    else:
        return srodkowy(lista[1:-1])




xd=srodkowy(ziemniak)

print(xd)
