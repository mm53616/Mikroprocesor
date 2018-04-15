# Mikroprocesor

Aplikacja okienkowa napisana w C# będąca modelem programowego symulatora mikroprocesora; UI sworzone przy użyciu XAMLa (projekt grupowy).
Zgodnie z narzuconymi poleceniami zrealizowano symulację zbudowaną z trzech rozkazów 
do wyboru przy pojedynczym poleceniu: ADD – służące dodawaniu, SUB – służące odejmowaniu 
i MOV – służące przesłaniu oraz z 8-bitowych rejestrów AX, BX, CX, DX oraz dodatkowo wprowadzana 
liczba zewnętrzna. Wartości rejestrów miały być przydzielane w programie od razu po jego uruchomieniu,
z możliwością zmian ich wartości i przypisaniu rejestrowi wybranej przez siebie powyżej 
przedstawionej liczby. Dodatkowo należało dodać możliwość zapisu w postaci binarnej oraz dziesiętnej oraz 
funkcję zapisu historii rozkazów do pliku, z którego również można ją wczytać i ponownie wywołać. 
Program jest też rozwinięcty o 10 funkcji przerwań procesora oferowanych
przez moduł BIOS. Miały one być w widoczny sposób wywoływane i prezentowane. 
Projekt nie skończony w 100%, ze względu na nieprawidłowe działanie kolejki.
