**Komma igång med GIT** :trollface:

Git är bra för att ha koll på versioner, historik när man kodar själv och
framförallt när man kodar tillsammans med andra. Dels för att man kan jobba 
i samma projekt men också för att kolla vad som ändrats sen man kollade sist
eller att gå tillbaka och titta på tidigare versioner om något gått fel.

I git jobbar vi med olika projekt som är huvudmappar som kallas för 
__Repositories__. Dessa huvudmappar blir python projekt med undermappar som
kallas __Packages__. En Package måste innehålla en tom fil som heter
```
__init__.py 
```
för att hittas av pythons projektstruktur. I dessa undermappar
lägger vi vanliga py scripts som kallas modules. Vi kommer med tiden
jobba fram en bra mappstruktur men kör pä så här till en början.

Absolut enklaste sättet att få ordning på git är att ladda ner 
GitHub Desktop. Den gör så att man slipper krångla med att skriva in
lösenord eller skaffa SSH nycklar. När man laddat ner den och loggat in på 
sitt git konto så lägger den automatiskt in gitlösenordet.

_Dags att komma igång_
1. Se till så att jag har invitat er git till Repositoriet

2. Logga in på GitHub Desktop alternativt se till så att användarnamn
   och email finns i gits globala inställningar på datorn. 
 
3. Klona repositoriet i en passande mapp i datorn, antingen genom
   GitHub Desktop eller via terminalen gå in i mappen där ni vill att 
   mappen ska hamna och skriva:
```
git clone https://github.com/DataClub-Bioinformatics/GettingStartedGit.git
```

4. Gå till klonade mappen och skapa upp en map sen skriv i terminalen:
```
mkdir {din mapp med valfritt namn}
cd {din mapp}
touch __init__.py
```
5. skapa upp en .py fil med valfritt namn och skriv något i denna fil.

6. Skriv i terminalen:
```
cd ..

git status (kolla status om det finns något att checka in)

git add . (lägg till de filerna som skapats upp, "add . lägger till alla filer 
så använd lite försiktigt)

git commit -m ”något meddelande” (Här skriver man in något meddelande som kortfattat
beskriver ändringen som skett)

git push (skicka koden till git) 
```

:clap:

