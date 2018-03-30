---
layout   : default
permalink: define/requirements/backoffice/
# Custom Page Variables
# ─────────────────────
title: Backoffice
---



# Minimal Requirements

## Functional Requirements

- Rollen:
    
    - Een niet-aangemelde gebruiker is een **bezoeker**.
    - Een aangemelde gebruiker kan **hoofdbeheerder** zijn.
    - Een aangemelde gebruiker kan **beheerder** zijn.

- Authenticatie van beheerders:
    
    - De bezoeker die (hoofd)beheerder is kan zich aanmelden.
    - De bezoeker die geen (hoofd)beheerder is kan zich niet aanmelden.
    - De aangemelde (hoofd)beheerder kan zich afmelden.

- Beheer van beheerders:
    
    - De eerste beheerder is automatisch een hoofdbeheerder.
    - De hoofdbeheerder kan een nieuwe beheerder toevoegen _(create)_.
    - De hoofdbeheerder kan een beheerder activeren _(update)_.
    - De hoofdbeheerder kan een beheerder deactiveren _(soft delete)_.
    - De hoofdbeheerder kan een beheerder verwijderen _(hard delete)_.
    - De hoofdbeheerder kan de gegevens van een beheerder aanpassen _(update)_.
    - De hoofdbeheerder kan een beheerder een hoofdbeheerder maken _(update)_.
    - De hoofdbeheerder kan een hoofdbeheerder een beheerder maken _(update)_.
    - De (hoofd)beheerder kan de eigen gegevens wijzigen _(update)_.

- Beheer van klanten:
    
    - De (hoofd)beheerder kan een nieuwe klant toevoegen _(create)_.
    - De (hoofd)beheerder kan een klant activeren _(update)_.
    - De (hoofd)beheerder kan een klant deactiveren _(soft delete)_.
    - De (hoofd)beheerder kan de gegevens van een klant wijzigen _(update)_.

- Beheer van product-/dienstcategorieën:
    
    - De hoofdbeheerder kan een nieuw(e) categorie toevoegen _(create)_.
    - De hoofdbeheerder kan een categorie verwijderen _(hard delete)_.
    - De hoofdbeheerder kan de details van een categorie wijzigen _(update)_.
    - De (hoofd)beheerder kan een nieuw(e) subcategorie toevoegen _(create)_.
    - De (hoofd)beheerder kan een subcategorie verwijderen _(hard delete)_.
    - De (hoofd)beheerder kan de details van een subcategorie wijzigen _(update)_.

- Beheer van producten/diensten:
    
    - De (hoofd)beheerder kan een nieuw(e) product/dienst toevoegen _(create)_.
    - De (hoofd)beheerder kan een product/dienst verwijderen _(soft delete)_.
    - De (hoofd)beheerder kan de gegevens van een product/dienst wijzigen _(update)_.

- Metrics:
    
    - De (hoofd)beheerder kan gedetailleerde statistieken zien over klanten.
    - De (hoofd)beheerder kan gedetailleerde statistieken zien over producten/diensten.


## Non-Functional Requirements
### Beveiligingseisen

- De app is afgeschermd voor
     niet-bevoegden.
- De app voldoet aan de normale
     eisen voor beveiliging.

### Technische Eisen

- [PHP](https://secure.php.net)
     7.2 of hoger 
  - [Composer](https://getcomposer.org)
  - [Laravel](https://laravel.com) 5.6 of hoger

- [MySQL](https://www.mysql.com/products/community/) 5.7 of hoger
- [Node.js](https://nodejs.org) 8 of hoger 
  - [Yarn](https://yarnpkg.com)
  - [Laravel Mix][]
  - [Vue](https://vuejs.org) toepassen voor de frontend. (Niet-verplicht, maar voor bonuspunten)
- [Bootstrap](http://getbootstrap.com) 4 of hoger

### UX-eisen

- De app is gebruiksvriendelijk.
- De app is geoptimaliseerd om vlot te werken.
- De app straalt professionele credibiliteit uit.
- De IA en IxD van de app is logisch opgebouwd.
- De vormgeving van de app is esthetisch verantwoord.



# Personal Requirements

## Functional Requirements
- de beheerder kan gebruikers een tijdelijke ban geven waneer ze tegen de community richtlijnen gaan
- de beheerder kan statestieken aanmaken en deze onthouden zodat er snel een bepaalde set gegevens kan worden gekozen
## Non-Functional Requirements