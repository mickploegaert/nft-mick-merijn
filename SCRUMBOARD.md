# Hoe maak ik een Scrum Board aan voor dit project?

## Inhoudsopgave
1. [Wat is een Scrum Board?](#wat-is-een-scrum-board)
2. [GitHub Projects gebruiken](#github-projects-gebruiken)
3. [Stap-voor-stap handleiding](#stap-voor-stap-handleiding)
4. [Best Practices](#best-practices)
5. [Kolommen en workflow](#kolommen-en-workflow)

## Wat is een Scrum Board?

Een Scrum Board is een visueel hulpmiddel voor het beheren van werk in een Agile/Scrum project. Het helpt teams om:
- Werk te visualiseren
- Voortgang bij te houden
- Knelpunten te identificeren
- Samenwerking te verbeteren

## GitHub Projects gebruiken

GitHub biedt een ingebouwde functionaliteit voor het maken van project boards. Dit is ideaal voor het beheren van je NFT project.

## Stap-voor-stap handleiding

### 1. Ga naar de GitHub repository
Navigeer naar: `https://github.com/mickploegaert/nft-mick-merijn`

### 2. Open het Projects tabblad
- Klik op het **"Projects"** tabblad bovenaan de repository pagina
- Als je geen Projects tabblad ziet, ga dan naar **Settings** en zorg ervoor dat Projects is ingeschakeld onder "Features"

### 3. Maak een nieuw project aan
- Klik op **"New project"** (groene knop)
- Of klik op **"Link a project"** > **"New project"**

### 4. Kies een template
GitHub biedt verschillende templates:
- **Board** - Eenvoudig kanban bord (aanbevolen voor beginners)
- **Table** - Tabelweergave met meer velden
- **Roadmap** - Tijdlijnweergave

**Aanbeveling**: Kies **"Board"** voor een klassiek Scrum Board

### 5. Geef je project een naam
Voorbeelden:
- "NFT Project Sprint Board"
- "Mick & Merijn NFT Development"
- "Sprint Planning Board"

### 6. Kies de zichtbaarheid
- **Public** - Iedereen kan het board zien
- **Private** - Alleen jij en collaborators kunnen het zien

### 7. Klik op "Create project"

## Kolommen en workflow

### Standaard kolommen instellen

Een typisch Scrum Board heeft de volgende kolommen:

#### Optie 1: Basis Setup
1. **Backlog** - Alle taken die gedaan moeten worden
2. **To Do** - Taken voor de huidige sprint
3. **In Progress** - Taken waar momenteel aan gewerkt wordt
4. **Review** - Taken die klaar zijn voor review
5. **Done** - Voltooide taken

#### Optie 2: Uitgebreid
1. **Backlog** - Alle ideeën en taken
2. **Ready** - Taken die klaar zijn om op te pakken
3. **In Progress** - Actieve taken
4. **Testing** - Taken in de test fase
5. **Review** - Code review/peer review
6. **Done** - Afgerond

### Kolommen aanpassen

1. **Kolom toevoegen:**
   - Klik op **"+"** aan de rechterkant van het board
   - Geef de kolom een naam
   - Klik op "Create column"

2. **Kolom verwijderen:**
   - Klik op de **"..."** in de kolomkop
   - Selecteer **"Delete column"**

3. **Kolom hernoemen:**
   - Klik op de **"..."** in de kolomkop
   - Selecteer **"Rename"**

## Issues toevoegen aan je Scrum Board

### Nieuwe issue maken
1. Ga naar het **"Issues"** tabblad in je repository
2. Klik op **"New issue"**
3. Vul de titel en beschrijving in
4. Wijs het toe aan het project (rechterkant onder "Projects")
5. Klik op **"Submit new issue"**

### Bestaande issues toevoegen
1. Open je project board
2. Klik op **"+ Add item"** in een kolom
3. Zoek en selecteer de issue die je wilt toevoegen
4. Of typ **#** gevolgd door het issue nummer

### Issues verplaatsen
Sleep en drop issues tussen kolommen om de status bij te werken.

## Best Practices

### 1. Labels gebruiken
Gebruik GitHub labels om issues te categoriseren:
- `bug` - Voor bugs
- `feature` - Voor nieuwe features
- `enhancement` - Voor verbeteringen
- `documentation` - Voor documentatie taken
- `design` - Voor design taken
- `frontend` - Voor frontend werk
- `backend` - Voor backend werk

### 2. Prioriteiten aangeven
- Gebruik labels zoals `priority: high`, `priority: medium`, `priority: low`
- Of gebruik nummers in de issue titel: `[P1]`, `[P2]`, `[P3]`

### 3. Sprints organiseren
- Maak gebruik van **Milestones** voor sprints
- Bijvoorbeeld: "Sprint 1 - December 2024"
- Wijs issues toe aan de juiste milestone

### 4. Daily Standup
Gebruik het board tijdens daily standups:
- Wat heb je gisteren gedaan? (Verplaats naar Review/Done)
- Waar werk je vandaag aan? (Controleer In Progress)
- Zijn er blockers? (Markeer met label `blocked`)

### 5. Automation
GitHub Projects ondersteunt automation:
- Auto-move naar Done wanneer een issue wordt gesloten
- Auto-add nieuwe issues aan je project
- Instellingen: Klik op **"..."** bovenaan het project > **"Workflows"**

### 6. Regelmatig opschonen
- Verplaats oude Done items naar een Archive kolom
- Of sluit oude issues en houd het board overzichtelijk

## Voor dit NFT Project

### Aanbevolen kolommen voor NFT Development:
1. **Backlog** - Alle ideeën en features
2. **Design** - UI/UX ontwerp taken
3. **Development** - Coding taken
4. **Testing** - QA en testing
5. **Deployment** - Klaar voor productie
6. **Done** - Live en afgerond

### Voorbeeld issues voor NFT project:
- "Implementeer NFT gallery component"
- "Voeg wallet connectie toe"
- "Maak responsive design voor mobile"
- "Optimaliseer afbeeldingen voor snelheid"
- "Schrijf documentatie voor deployment"

## Extra Tips

### Keyboard Shortcuts
- `c` - Maak nieuwe issue
- `e` - Edit issue
- `/` - Focus op search

### Mobile App
Download de GitHub mobile app om je board onderweg te beheren.

### Integraties
Koppel je board aan:
- Slack voor notificaties
- Discord voor team updates
- Andere tools via GitHub Actions

## Hulp nodig?

- [GitHub Projects Documentatie](https://docs.github.com/en/issues/planning-and-tracking-with-projects)
- [Scrum Guide](https://scrumguides.org/)
- [Agile Best Practices](https://www.atlassian.com/agile/scrum)

---

**Veel succes met je NFT project! 🚀**
