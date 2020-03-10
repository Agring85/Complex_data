I zip-filen ligger min kode som besvarelse til den sidste opgave i kurset "How to Code: Complex Data"
Koden er skrevet i sproget Racket og programmet DrRacket.

Den sidste del af multiple-choice opgaven lyder:
Q3: Can you fill all 12 slots with the TAs above?
yes or no

Q4: Suppose you add a 10th TA, Alex who is only available to work shift 7.
Can you fill every shift to make a schdule using the 9 TAs above plus Alex?
yes or no

Q5: Suppose instead of Alex, you add a 10th TA, Erin who is only available to work shift 4.
Can you fill every shift to make a schdule using the 9 TAs above plus Erin?
yes or no

For at besvare spørgsmålet via koden, brug "interactions window" og skriv:
(schedule-tas Add_list (list 1 2 3 4 5 6 7 8 9 10 11 12))

Add_list:
for Q3 = 12-slot
for Q4 = add-david
for Q5 = add-erin

Eftertanke: I sin nuværende form er det vigtigt at listen af ta's står i den rigtige rækkefølge, ellers melder den #false, til trods
for at der godt kan lægges et skema.
For at løse buggen, skal der i koden enten tilføjes en måde at sortere listen, eller koden skal gennemgå alle de muligheder den pågældende liste kan sættes
sammen på.

Hent DrRacket: https://download.racket-lang.org/