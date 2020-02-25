
Git är bra för att ha koll på versioner, historik när man kodar själv och
framförallt när man kodar tillsammans med andra. Dels för att man kan jobba 
i samma projekt men också för att kolla vad som ändrats sen man kollade sist
eller att gå tillbaka och titta på tidigare versioner om något gått fel.

I git jobbar vi med olika projekt som är huvudmappar som kallas för 
Repositories. Dessa huvudmappar blir python projekt med undermappar som
kallas Packages. En Package måste innehålla en tom fil som heter
__init__.py för att hittas av pythons projektstruktur. I dessa undermappar
lägger vi vanliga py scripts som kallas modules. Vi kommer med tiden
jobba fram en bra mappstruktur men kör pä så här till en början.

Absolut enklaste sättet att få ordning på git är att ladda ner 
GitHub Desktop. Den gör så att man slipper krångla med att skriva in
lösenord eller skaffa SSH nycklar. När man laddat ner den och loggat in på 
sitt git konto så lägger den automatiskt in gitlösenordet.

Dags att komma igång
1.	Se till så att jag har invitat er git till Repositoriet

2.	Logga in på GitHub Desktop alternativt se till så att användarnamn
	och email finns i gits globala inställningar på datorn. 
 
3.	Klona repositoriet i en passande mapp i datorn, antingen genom
	GitHub Desktop eller via terminalen gå in i mappen där ni vill att 
	mappen ska hamna och skriva:
	git clone https://github.com/DataClub-Bioinformatics/GettingStartedGit.git

4.	Antingen öppna upp mappen som Project i spyder menyn.
	Projects. Om det inte funkar att ladda in den genom Open Project så gör
	New Project > Existing Directory > __Hitta där ni clona__ > Create
	
	to be continued .... 
