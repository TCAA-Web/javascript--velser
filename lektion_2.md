## Lektion 2 Øvelsesopgaver - Numbers og regex

1. Lav en funktion der kan tjekke om en værdi (argumentet) er en string eller et tal og vise det i DOM´en.
   Det skal gerne ende ud i at der eks. står: 123 er af typen: number, i DOM´en.

2. Lav en funktion der kan tjekke om en email er korrekt (indeholder @ og slutter på .com/.dk/osv.)

3. Lav en funktion der kan tjekke om længden på en string er længere end eller lig med 2 bogstaver

4. Lav en funktion der kan give os et tilfældigt tal, mellem to input argumenter, eks. mellem 4 og 32. Tilføj en button til HTML´en og lav en onclick der kalder din funktion. Til slut skal følgende besked vises for brugeren: Vores tilfældige tal mellem _startværdi_ og _slutværdi_ er: _randomværdi_ `;

5. Lav en funktion der returnerer en tilfældig RGB farve værdi og tildel denne til et element du opretter, når brugeren klikker på en knap.

# Bonus opgaver

6. Udbyg din funktion fra opgave 5, så den kan tage imod en string. Hvis der er en string som argument, skal funktionen kunne "læse" hvad der står i stringen og sætte farven på dit element til enten:
   Red, Green, Blue, Yellow, Purple eller Random.
   Hvis man ikke kalder funktionen med et argument skal den altid "defaulte" til at bruge Math.random()

7. Udbyg nu din funktion fra tidligere der kunne indsætte et element i DOM´en til at kunne tage imod resultatet fra din anden funktion. Det vil sige at man kan sætte BG-color på det nye element, ved blot at kalde din farve funktion.

8. Lav en funktion der kan danne en tilfældig sætning. En sætning er opbygget af;
   et navneord, et tillægsord og et udsagnsord. Lav derfor tre arrays af ord,
   eks: ["jeg", "han", "hun", "dem", "de"] og ["kaster", "tegner", "giver", "henter"] og ["vand", "maling", "fyrværkeri"] osv... Brug nu det du har lært om Math.random til at lade tilfældighed vælge tre ord og sammensæt dem til en string. Vis til sidst stringen i DOM´en.
