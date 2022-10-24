# AAU-LaTeX-Report-template
En omstrukturering af AAUs officielle LaTeX-skabelon, med fokus på brugervenlighed, overskuelighed, strømlining og især at nye brugere af LaTeX ikke overvældes af alle mulige filer som ikke bruges af selve PDF-rapporten.
Original/official template = https://github.com/jkjaer/aauLatexTemplates

Instructions:
1. Download hele repo'et som ZIP-fil (Tryk på den grønne knap 'Code', tryk på 'Download ZIP')

2. Indlæs filen i din LaTeX-klient (jeg bruger Overleaf, her trykker man fra hovedsiden på 'New Project > Add Project' og vælger ZIP-mappen)

3. Vælg om du vil have en forside med billede eller uden billede:
Dette vælges under setup/1-documentSetup.tex med variablen \def\myForsideMedBillede{} i linje 10
\def\myForsideMedBillede[0] = Forside uden billede
\def\myForsideMedBillede[1] = Forside med billede

4. Udfyld de resterende felter i documentSetup-filen for at fylde forside, colophon, titlepages og preface med navne, uddannelse, år osv.

5. Udfyld Abstract(resumé) på dansk og engelsk i filen setup/2-documentAbstracts.tex

6. Skriv rapporten ind i sektionerne. (:
Kig, hvordan sektionerne kaldes i master.tex, hvis du skal fjerne nogle eller tilføje nye.
I sektionen 'Introduction' kan du se nogle eksempler på formatering og indsættelse af billeder/tabeller.
Sidst i dokumentet, i Appendix B er der eksempler på hvordan man laver avanceret formatering med billeder eller codeblocks.

--

I media-mappen har jeg efterladt danske logoer etc. som ikke bruges i min skabelon til rapporten, men som man kan skifte over til, hvis det ønskes.

I mappen "guides til forfatter" har jeg lagt IDAs Cheatsheet til formatering/kommandoer i LaTeX samt SDU's guide til at skrive akademiske rapporter.
