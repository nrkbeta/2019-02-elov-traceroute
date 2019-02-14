# 2019-02-elov-traceroute
Data og kode for analyse av trafikkhopp blant 1343 norske domener.

## Metode og kode
Vi har hentet ned en liste over de 1343 største norske domenene (sammenstilling av data fra Alexa, Umbrella, Majestic og Quantcast), og kjørt disse gjennom traceroute for å finne alle IP-ene man går gjennom for å kommunisere med dem.
Disse IPene har vi så sjekket opp mot to ulike GeoIP-databaser, og deretter kartlagt hvor mange som har trafikk som går utenfor Norge.

Koden ligger i en Jupyter Notebook i dette repoet. Repoet har også to CSV-filer: Den ene er totallisten over domener, den andre er kjøringen vi har gjort på disse.

Med mindre du har god tid kan det være en god idé å bruke vår ferdiggenererte CSV-fil, da kjøringen av de 1343-domenene fort kan ta 12-15 timer.

## Spørsmål og tilbakemeldinger
Kontakt Henrik Lied (henrik.lied@nrk.no) eller Martin Gundersen (martin.gundersen@nrk.no)


