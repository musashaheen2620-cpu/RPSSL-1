Readme:

- Det er et spil hvor det er brugeren mod computeren

- Der er flere kombinationer som er 1.Rock, 2.Paper, 3.Scissors, 4.Spock og 5. Lizzard

- Jeg bruger "arreys" for at samle hhv. "1.Rock, 2.Paper, 3.Scissors, 4.Spock og 5. Lizzard"
"string[] valg = { "Rock", "Paper", "Scissors", "Spock", "Lizard" };"


- Det altid spilleren som starter med at indtaste et tal mellem 1-15
dvs: "Vælg et tal: 1=Rock, 2=Paper, 3=Scissors, 4=Spock, 5=Lizard"

- Computeren vælger et tilfældigt tal mellem 1-5 med "random"
"Random rnd = new Random();" - den her kode bruges til at vælge et tilfældigt tal mellem 1-5


- Hvis både brugeren og computeren vælger samme tal så er det ufagjort :

  if (spiller == computer)
            {
                Console.WriteLine("Uafgjort!");
            }

- Hvis computeren vinder så siger den "computer vandt!" og hvis brugeren vinder så siger den "Du vandt!"

- Og sådan bliver man ved med et nyt spil efter både computere og brugeren har valgt et tal 

- Hvis man vælger et tal udover 1-5 så siger den fejl fordi vi har kun valget mellem 1-5

- Der blive rogså brugt "while" som referer til løkke
