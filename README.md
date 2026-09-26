# Pull Requests op Github

## Voorbereiding

- De docent tekent op het bord het verschil tussen lokale en remote branches, en tussen de `main` branch en een feature branch. 
- Laat zien: waar wordt de PR aangemaakt?

## Stappen voor studenten (1)

### Code wijzigen en PR aanmaken

1. Clone deze repo.
2. Maak een feature branch op basis van de `main` branch, noem hem bijvoorbeeld `feature-naam`.
3. Wijzig in `index.html` de card waar jouw naam op staat: voeg een beschrijving toe over jezelf.
4. Push de feature branch naar Github.
5. Maak een Pull Request aan. Assign de docent als reviewer.

### Styling wijzigen

6. Ga terug naar de `main` branch en maak een __nieuwe__ feature branch aan. Nu ga je iets in de CSS aanpassen wat __alleen__ geldt voor jouw card. Gebruik bijv. de `nth-child`-selector.
7. Maak een tweede PR aan. Assign de docent.

## Docent aan zet

- Als de studenten klaar zijn met stap 5. reviewt en merget de docent alle PR's.
- Ondertussen druppelen de nieuwe PR's binnen. Deze worden nog niet gemerged.

## Studenten (2)

### Tweede PR's updaten

1. De docent heeft de eerste PR's gemerged. Dat betekent dat je lokale `main` branch en je lokale feature branche niet meer up-to-date zijn. Pull de `main` branch, zodat jouw lokale omgeving weer up-to-date is met de remote `main` branch.
2. Merge de `main` branch nu in jouw feature branch. Lokaal heeft jouw branch nu alle wijzigingen binnen, maar je tweede PR loopt nog achter. Daarom moet je je feature branch opnieuw pushen.
3. Als de docent alle PR's heeft gemerged, kun je je lokale `main` weer updaten met `git pull`.

