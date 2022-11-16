# Dynamisk minnesallokering i C (del I)
Demonstration av funktioner malloc, realloc samt free för dynamisk minnesallokering i C.

Filen "main.c" demonstrerar användning av dynamisk minnesallokering för en dynamisk array för lagring av heltal. 
Först allokeras utrymme för 20 heltal, vilket sedan tilldelas och skrivs ut. 

Sedan omallokeras arrayen till att rymma 40 heltal, där tidigare innehåll bibehålls, medan de 20 nya adresserna tilldelas nya heltal. 
Därefter skrivs arrayens innehåll ut igen, både i terminalen samt till en textfil döpt "numbers.txt".

Innan programmet avslutas frigörs minnet allokerat för arrayen.

Se video tutorial här: https://youtu.be/KLoAY-KJUeI

