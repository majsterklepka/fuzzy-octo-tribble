# fuzzy-octo-tribble
ac 3-pin socket tester

Hi, Jak się macie?

Zaprezentuje Wam dziś projekt testera gniazd sieciowych 230-240V. Projekt zaczerpnięty z [instructables.com](https://www.instructables.com "Instructables.com").

Z uwagi na fakt, że projekt dotyczy kontaktu z siecią prądu przemiennego 230V(Europa), wykonanie go wymaga ogromnego doświadczenia i pewnej, dość dużej wprawy w pracach z napięciem sieciowym.

Do wykonania, potrzeba:
- trzy rezystory 2W, 47k
- trzy diody LED,
- trzy zwykłe diody prostownicze, o napięciu wstecznym min. 1000V i prądzie min. 1A
- płytka drukowana według dokumentacji zawartej w katalogu [KiCad](/KiCad "Dokumentacja")
- obudowa, wykonana na drukarce 3D, [Dokumentacja, obudowa](/3dhousing "3Dhousing")
- mocowania kabla testowego, [Dokumentacja, blaszka](/mechanical "mechanical")
- kabel sieciowy, zalewany, trzy-żyłowy, z wtyczką, z uziemieniem

## Krótka instrukcja obsługi

| LED1  |LED2 | LED3 | opis |
| --- | --- | --- | --- | 
| X | X | | wszystko OK |
| X | | | niepodłączona ziemia(E) |
| | X | X | sieć(L) - ziemia(E) odwrócone |
| X | | X | sieć(L) - zero(N) odwrócone |
| | X | | brak zero(N) |
| | | | brak sieci(L)/brak zero(N) i brak ziemi(E) | 
  

##Credits

Jak zwykle i ten projekt jest dostępny na zasadach Wolnych Licencji:
- [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/ "license")

- - - 

Baw się dobrze, czuj się wolny i pamiętaj o Autorze(ach)! Podziel się tym projektem ze swoimi przyjaciółmi.

>Uwaga!!!  
>W układzie występuje niebezpieczne dla życia napięcie sieciowe!  
>Po montażu, płytkę drukowaną należy zaizolować lakierem poliuretanowym!  
>a elementy obudowy, wieku z puszką obudowy skleić!  
>przepust należy wypełnić silikonem!  

_Msc. Paweł Sobótka (SQ7EQE)_ 

