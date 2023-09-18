# Eiga:

Nuomojame airbnb.

- install:
  - client
  - server
  - foler
  - npm scripts

- server:
  - cors
  - helmet
  - nodemon
  - express:
    - error midleware
    - api

- client:
  - react
    - layout:
      - header
      - outlet
      - footer
        - pages:
          - pagrindinis
          - 404

- register:
  - react page
  - form + validacija + fetch
  - server api + validacija
  - DB: user table
  - redirect -> login page

- login:
  - react page
  - form + validacija + fetch
  - server api + validacija
  - cookies + token
  - DB: user table + token table
  - redirect -> user dashboard page (priklausomai ar admin, ar selleris)

- admin: namu tipu CRUD
  - add form: pavadinimas
  - table + button: edit, delete
  - edit form

- admin: pardaveju CRUD
  - table + button: ban, unban

- pardavejas: automobiliu CRUD
  - add form: pavadinimas, dydis, tipas, kaina ir t.t.
  - table + button: edit, delete
  - edit form

- public namu list page:
  - empty list state
  - korteliu stiliuje atvaizduoti visus galimus airbnb

- public home page:
  - empty list state
  - korteliu stiliuje atvaizduoti max 6 naujausius airbnb

- patinka/nepatinka (sirdute):
  - fronte reikia sirdutes 
  - sirdutes API
  - DB: sirdutes table
  - atskiras puslapis, kur atvaizduojami visi siuo metu palaikinti userio airbnb
  - pas pardaveja jo namu skelbimu lenteleje rodyti total sirduciu kieki



