# Creatine Experiment Tracker

Dansksproget, mobiloptimeret PWA til daglig registrering af kreatineksperimentet.

## Privatliv og lagring
- Registreringer gemmes i browserens `localStorage` på den enhed, hvor appen bruges.
- Ingen backend, konto, analyseværktøjer eller datasynkronisering.
- GitHub-repository'et indeholder kun kildekode – aldrig personlige trackingdata.
- Eksportér jævnligt JSON-backup. Rydning af browserens webstedsdata kan slette registreringerne.

## Funktioner
- Daglige 1–10-målinger: fokus, mental udholdenhed, hukommelse, mental klarhed og mental træthed.
- Søvnlængde, koffein, samlet kreatindosis, antal doser og noter.
- Én registrering pr. dato; gem igen for at redigere.
- Historik, gennemsnit baseret på faktiske værdier, CSV-eksport samt JSON-backup/import.
- Den eneste forudindlæste registrering er den konkret oplyste registrering fra 18. november 2026. Ikke-registrerede dage opfindes ikke.

## Kørsel og installation
Appen skal serveres fra en webserver. For installation som PWA på Android skal den publiceres via HTTPS, eksempelvis GitHub Pages. Åbn adressen i Chrome, og vælg installer/føj til startskærm.

## GitHub Pages og adgang
At repository'et er privat betyder ikke automatisk, at den publicerede Pages-side også er privat. Tilgængeligheden afhænger af GitHub-plan og Pages-indstillinger. Kontrollér sidens adgangsindstillinger, før den publiceres.

## Backup
Brug Historik → Backup (JSON) regelmæssigt. Import af en backup erstatter eksisterende registreringer på de datoer, der findes i backupfilen.
