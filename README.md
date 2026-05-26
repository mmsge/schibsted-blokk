# schibsted-blokk

Adblock-liste for å blokkere alle Schibsted sine media-sidar, slik at du slepp å ta stilling til «Pay or Consent»-ordninga deira.

## Kva er dette?

Schibsted har innført ei såkalla «Pay or Consent»-ordning (òg marknadsført som «Schibsted ad choice») på dei fleste av media-merka sine. Det vil seie at du anten må:

- godta sporing og personifisert reklame, eller
- betale ein månadleg sum for å sleppe sporing.

Eit tredje val — å bruke nettstaden utan sporing og utan å betale — finst ikkje.

Dette repoet inneheld ei adblock-liste som blokkerer alle desse sidene heilt, så du slepp å hamne i klemma. Tanken er å bryte musklminnet som dreg oss tilbake til vg.no og aftenposten.no kvar dag, og heller finne andre kjelder til nyhende.

## Korleis bruke lista

1. Installer ein nettlesarutvidelse som støttar Adblock Plus-filter, til dømes [uBlock Origin](https://ublockorigin.com/) eller [Adblock Plus](https://adblockplus.org/).
2. Legg til ein ny filterliste med URL:
   ```
   https://raw.githubusercontent.com/mmsge/schibsted-blokk/hovud/schibsted-blokk.txt
   ```
   eller last ned fila `schibsted-blokk.txt` og importer ho manuelt.
3. Oppdater filtra, og nettlesaren vil no nekte å gå inn på Schibsted-sidene.

I uBlock Origin gjer du dette under **Dashbord → Filterlister → Importer**.

## Kva blir blokkert?

Sjå [`schibsted-blokk.txt`](./schibsted-blokk.txt) for full liste. Ho dekkjer mellom anna:

- **Noreg:** Aftenposten, VG, Vektklubb, Bergens Tidende, Stavanger Aftenblad, E24, Tek.no, Godt.no, Minmote, Shifter, TVGuide, Podme
- **Sverige:** Aftonbladet, Svenska Dagbladet, Omni, Omni Ekonomi, Klart.se

## Bidrag

Manglar det ein Schibsted-eigd nettstad med «Pay or Consent» som du meiner bør med på lista? Opprett ein issue eller send ein pull request.
