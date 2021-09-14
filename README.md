# Sannsynlighetsregning og statistikk med anvendelser (Lillestøl)

Kildekode (LaTeX) til en videreutvikling av Jostein Lillestøls lærebok fra 1997
med samme navn. [Lisensfilen](LICENSE.md) regulerer  
hvordan boken kan modifiseres og brukes i undervisning.
Endringsforslag, i form av korreksjoner eller tillegg til boken, kan sendes
inn som en *pull request* i github. Hovedfilen er `lillestol.tex` slik at du 
kompilerer opp boken feks.\ med kommandoen `latex lillestol.tex`.


## Kompilerte pdf-utgaver

Her er en pdf-versjon av hele boken:

<a id="raw-url" href="https://github.com/nsfnost/Lillestol/blob/main/lillestol_1997.pdf">Lillestøl (1997) original</a>


## Kommentarer
* Referanser til Oppgaver og Eksempler er hardkodet, men for oppgaver er kapittelnummer automatisert. Det skal derfor være mulig å legge til eller fjerne hele kapitler. Men, dersom man fjerner deler av et kapittel kan det bli problemer.
* Følgende strukturer har fullt automatisert nummerering: figurer, tabeller, kapitler og delkapitler.

## Ting som bør gjøres (på sikt)
* En automatisk indeks kan lages med utgangspunkt i den manuelt genererte indeksen `ikke_i_bruk\index.tex`
