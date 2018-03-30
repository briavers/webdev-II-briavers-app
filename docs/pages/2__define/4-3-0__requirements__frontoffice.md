---
layout   : default
permalink: define/requirements/frontoffice/
# Custom Page Variables
# ─────────────────────
title: Frontoffice
---

Functional Requirements
-----------------------
- Rollen:
  - Een niet-aangemelde gebruiker is een **bezoeker**.
  - Een aangemelde gebruiker is een **klant**.

- Registratie van klanten:
  - Een bezoeker kan zich registreren als klant.
  - De klant krijgt een activatie-e-mail met code.
  - De klant de account activeren.

- Authenticatie van klanten:
  - De bezoeker die klant is kan zich aanmelden.
  - Een bezoeker die geen klant is kan zich niet aanmelden.
  - De aangemelde klant kan zich afmelden.
  - Een bezoeker kan een e-mailadres opgeven voor een wachtwoordreset.

- Beheer van klanten:
  - De klant kan de eigen gegevens wijzigen _(update)_.
  - De klant kan zich deactiveren _(soft delete)_.
  - De klant kan zich na deactivatie pas na een sperperiode opnieuw activeren _()_.
  - De klant kan zich verwijderen _(hard delete)_, maar enkel de persoonlijke gegevens worden permanent gewist.

- Beheer van producten/diensten:
  - De klant kan een eigen product/dienst toevoegen _(create)_.
  - De klant kan een eigen product/dienst publiceren _(update: publish)_.
  - De klant kan een eigen product/dienst intrekken _(update: unpublish)_.
  - De klant kan een eigen product/dienst wijzigen _(update: unpublish)_ tot vlak voor de veilingperiode.
  - De klant kan foto’s uploaden en koppelen aan een eigen product/dienst.
  - De klant kan bestaande categorieën en bestaande subcategorieën koppelen aan een eigen product/dienst.
  - De klant kan een eigen product/dienst hoger in de ranking laten plaatsen.

- Veilen van producten/diensten:
  - De klant kan de veilingperiode voor een eigen product/dienst instellen tot vlak voor de veilingperiode.
  - De klant kan de veilingperiode voor een eigen product/dienst wijzigen tot vlak voor de veilingperiode.
  - De klant kan een minimumprijs _(Eng.: reserve price)_ instellen voor een eigen product/dienst.
  - De klant kan de afstand van de eigen locatie tot locatie van het/de product/dienst aflezen.
  - De klant (koper) kan een bod uitbrengen op het/de product/dienst van een andere klant (verkoper) tijdens de veilingperiode van dat/die product/dienst.
  - De bezoeker kan een aftelklok van de veilingperiode aflezen.
  - De gebruiker kan de kenmerken van een product/dienst aflezen.
  - De gebruiker kan de categorie(ën) en subcategorie(ën) van een product/dienst aflezen.

- Starten en stoppen van veilingen:
  - Het systeem systeem start een veiling autonoom.
  - Het systeem systeem stopt een veiling autonoom.
  - Het systeem synchroniseert tijd tussen back- en frontend.

- Sorteren van producten/diensten:
  - Een gebruiker kan de lijst van producten/diensten oplopend alfabetisch sorteren op kenmerken.
  - Een gebruiker kan de lijst van producten/diensten aflopend alfabetisch sorteren op kenmerken.
  - Een gebruiker kan de lijst van producten/diensten oplopend sorteren op prijs.
  - Een gebruiker kan de lijst van producten/diensten aflopend sorteren op prijs.

- Filteren van producten/diensten:
  - Een gebruiker kan de lijst van producten/diensten filteren op kenmerken.
  - De klant (koper) kan de lijst van producten/diensten filteren op locatieafstand.

- Metrics:
  - De klant (verkoper) kan statistieken over het/de product/dienst zien.

- Juridische informatie:
  - De app toont de nodige juridische informatie (disclaimer, cookiepolicy, privacy, GDPR).

Non-Functional Requirements
---------------------------

### Beveiligingseisen

- De app is afgeschermd voor niet-bevoegden.
- De app voldoet aan de normale eisen voor beveiliging.

### Technische Eisen

- [Angular](https://angular.io/) 5 of hoger
- [Node.js](https://nodejs.org) 8 of hoger
- [Yarn](https://yarnpkg.com)

### UX-eisen

- De app is gebruiksvriendelijk.
- De app is geoptimaliseerd om vlot te werken.
- De app stimuleert _customer engagement_.
- De app stimuleert interactie tussen klanten.
- De app straalt professionele credibiliteit uit.
- De IA en IxD van de app is logisch opgebouwd.
- De vormgeving van de app is esthetisch verantwoord.




# Personal Requirements

## Functional Requirements
- de ingelogde gebruiker kan een bij een veiling een extra optie kiezen 'onmiddellijk verkocht' en hierbij sluit de veiling dan eveneens spontaan, deze knop verdwijnt in het geval dat door biedingen deze prijs bereikt word. 
- de ingelogde gebruiker kan tijdens een veiling gebruik maken van een snelbied knop waardoor de prijs met 5-10-15 stijgt. 
- de ingelogde gebruiker kan bij het bieden kiezen voor een auto bied functie deze zorgt dat je tot een bepaald bedrag de hoogste bieder bent. deze kan gekozen worden in stappen van 5€, 10€ en 15€ 
- de ingelogde gebruiker kan een chat/mail bericht aangaan met de verkoper. 
- de ingelogde gebruiker kan artikelen/personen rapporteren voor evaluatie indien deze in strijd zijn met de community richtlijnen 