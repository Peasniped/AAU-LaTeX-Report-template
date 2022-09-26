# AAU-LateX-Report-template
En omstrukturering af AAUs officielle LaTeX-skabelon, med fokus på brugervenlighed, overskuelighed, strømlining og især at nye brugere af LaTeX ikke overvældes af alle mulige filer som ikke bruges af selve PDF-rapporten.
Original/official template = https://github.com/jkjaer/aauLatexTemplates

Instructions:
1. Download hele repo'et som ZIP-fil (Tryk på den grønne knap 'Code', tryk på 'Download ZIP')

2. I din LaTeX-klient (jeg bruger Overleaf) uploader du ZIP-mappen

!!! Bemærk, når filen uploades starter du i Preamble.tex, når rapporten compiles vil du få en fejl, du skal stå i filen master.tex !!!

3. Vælg om du vil have en forside med billede eller uden billede:
Dette vælges under setup/1-documentSetup.tex med variablen \def\myForsideMedBillede{} i linje 5
\def\myForsideMedBillede[0] = Forside uden billede
\def\myForsideMedBillede[1] = Forside med billede

4. Udfyld alle felterne i filen for at fylde forside, colophon, titlepages og preface

5. Udfyld Abstract(resumé) på dansk og engelsk i filen setup/2-documentAbstracts.tex

6. Skriv rapporten ind i sektionerne. (:
Kig, hvordan sektionerne kaldes i master.tex, hvis du skal fjerne nogle eller tilføje nye.
I sektionen 'Introduction' kan du se nogle eksempler på formatering og indsættelse af billeder/tabeller.

I media-mappen har jeg efterladt danske logoer etc. som ikke bruges i rapporten, men som man kan skifte over til, hvis det ønskes.

I media-mappen har jeg desuden lagt IDAs Cheatsheet til formatering/kommandoer i LaTeX:
Guide / Cheatsheet udarbejdet af IDA: media/IDA LaTeX Cheatsheet.pdf
