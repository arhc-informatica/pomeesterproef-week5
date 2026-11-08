# PO Meesterproef — Week 5 (Usability-, Taal-Test & Testscript)

Dit is de **week 5**-versie. Er is **geen nieuwe code** in deze week: je gebruikt je bestaande app (week 4) om te testen.

Je mag een eigen onderwerp kiezen.

## Wat zit erin?

Deze week bevat **geen nieuwe code**. Je werkt verder in je eigen project (week 4) en test die.

## Wat is een testscript?

Een **testscript** is een eenvoudig overzicht (bijv. in een Google Spreadsheet of op papier) met **testcases**: korte stappen die een tester uitvoert om te controleren of je website goed werkt en begrijpelijk is.

Een testscript heeft meestal deze kolommen:

| # | Testcase (wat doe je?) | Verwacht resultaat | Resultaat (OK/Fout) | Opmerking |
|---|---|---|---|---|
| 1 | Open de homepage | Titel en tekst zijn zichtbaar | | |
| 2 | Klik op "Toevoegen" | Formulier verschijnt | | |
| 3 | Vul naam + beschrijving in en klik Opslaan | Nieuwe rij staat in de lijst | | |
| 4 | Laat naam leeg en klik Opslaan | Foutmelding of niets opgeslagen | | |

### Hoe maak je een testscript?

1. Open Google Spreadsheets (of Excel/papier).
2. Maak een tabblad "Testcases" met de kolommen hierboven.
3. Schrijf per belangrijke functie van je site 1 of meer testcases.
4. Voeg een tabblad "Bevindingen" toe voor opmerkingen en prioriteiten.

### Hoe gebruik je een testscript?

1. Laat een tester (klasgenoot, vriend of familielid) je site gebruiken.
2. De tester voert de testcases uit en vult "Resultaat" en "Opmerking" in.
3. Bespreek de bevindingen en noteer wat je wilt fixen.

> **Werken in je eigen project:** test je eigen app (week 4) en noteer bevindingen in je testscript. Commit en push daarna in je eigen repo.

## Usability & Taaltoets (zie de reader)

Lees de reader **"Reader Usability en User Experience - V2.pdf"** in deze map. Kies **één usability-onderwerp** (bijv. Consistentie, Zichtbaarheid, Status & Feedback, Fouten voorkomen, Doelgroep of Gewoonte) en bedenk **3 testcases** om dit onderwerp op jouw app te testen.

### Taaltoets (checklist)

Controleer de teksten op je website (met een klasgenoot):

- [ ] Geen spelfouten (gebruik een spellingscontrole).
- [ ] Korte, duidelijke zinnen die passen bij je doelgroep.
- [ ] Duidelijke koppen en knopteksten (actief, bijv. "Sla op").
- [ ] Toon past bij je doelgroep (formeel/informeel).
- [ ] Teksten zijn begrijpelijk zonder uitleg.

Voorbeeld (onderwerp: Status & Feedback):
| # | Testcase | Verwacht resultaat |
|---|---|---|
| 1 | Klik op "Opslaan" in het formulier | Direct feedback (bijv. redirect of melding) |
| 2 | Laat een verplicht veld leeg en klik Opslaan | Duidelijke foutmelding |
| 3 | Open de lijst na opslaan | Nieuwe rij is zichtbaar |

## Opdrachten (week 5)

- Kies één usability-onderwerp uit de reader en bedenk 3 testcases (zie boven).
- Doe een **taaltoets** met de checklist hierboven en pas teksten aan.
- Maak een testscript met testcases op basis van je ontwerp en je idee (bijv. in Google Spreadsheets).
- Laat familie of vrienden de testcases uitvoeren en noteer hun bevindingen.
- Neem de bevindingen op in je to-do-lijst (Taakbord) en geef prioriteiten (hoog/midden/laag).
- Overleg welke zaken je nog wilt fixen en plan ze in voor week 6.
- Zorg dat al je definitieve code en bestanden op GitHub staan.
- **AI-Check:** verantwoord je AI-gebruik in het evaluatieformulier (heb je AI gebruikt? Zo ja: welke prompts/vragen en wat heb je ervan geleerd?).
- Vul het Evaluatieformulier in (zie hoofdstuk 4).

## Hulp

### Testen

- **Testscript:** een simpel overzicht van stappen + verwacht resultaat; geen code nodig.
- **Testers:** kies mensen die lijken op je doelgroep; geef korte instructies.
- **Bevindingen:** noteer wat fout ging, wat onduidelijk was en wat goed werkte.
- **Prioriteren:** fix eerst blokkades (showstoppers), daarna cosmetische punten.

### W3Schools

- **HTML Forms:** https://www.w3schools.com/html/html_forms.asp
- **CSS:** https://www.w3schools.com/css/
- **Python/Flask:** https://www.w3schools.com/python/python_flask.asp

### Hulp

- **App starten:** `python app.py` en open http://127.0.0.1:5000.
- **Database resetten:** verwijder `data.db` en start de app opnieuw.
- **GitHub:** commit en push regelmatig (`git add .`, `git commit -m "..."`, `git push`).