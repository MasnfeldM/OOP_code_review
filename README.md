# Code review úkolu Queue

Autor: Matěj Mansfeld

## Základní info

Úkolem bylo napsat metody pro třídu Queue tak, aby se chovala stejně jako implementace z importu queue.

Třída obsahuje následující metody:

put(self,data): vloží data na začátek

    data se ukládají jako instance třídy Node, která poskytuje ukazatele na okolní instance ve stejné Queue

get(self): vyjme a vrátí první člen

empty(self): zkontroluje zda je objekt prázdný, vrací bool

full(self): zkontroluje zda je objekt plný, vrací bool

size(self): vrátí velikost objektu

## Úpravy

Zlepšení čistelnosti (hlavně lepší segmentace)

Nahrazení zbytečné while smyčky v metodě put

V metodách empty a full se místo vlastní while smyčky používá metoda size