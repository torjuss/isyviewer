# isyviewer

BIM viewer.

## Beskrivelse

Basert på følgende [tutorial](https://github.com/Autodesk-Forge/data.management-nodejs-integration.box).

## Installasjon

### Krav
- Autodesk developer credentials
- [NodeJS](https://nodejs.org/en/) (vi bruker siste versjon 7.2.0)
- npm - Node Package Manager (vi bruker siste versjon 4.0.2)
- Editor/utviklermiljø: Så langt har vi brukt kommandolinjeverktøy i form av [Git Bash for Winwdows](https://git-for-windows.github.io/)
- Github-konto

### Installasjon
- Lag Autodesk-konto og få credentials
- Installer NodeJS
- Installer Git Bash
- åpne Git Bash som administrator og kjør kommandoen <b>node -v</b> for å sjekke versjonsnummeret til NodeJS. Kjør deretter <b>npm -v</b> for å sjekke versjonsnummeret til package manageren. Dersom den er mindre enn 4.0.2 kan du kjøre <b>npm install npm@latest -g</b> for å få siste versjon.

### Kjøre prosjektet lokalt
- Åpne Git Bash og naviger til ditt ønskede lokale workspace, for eks: C:\Workspace\
- Kjør kommandoen under for å lage lokal kopi av Github-repositoryet: 

  git clone https://github.com/torjuss/isyviewer.git

- Naviger inn i prosjektet: <b>cd isyviewer</b>
- Kjør kommandoen: <b>npm install</b> for å installere alle eksterne biblioteker som trengs. Disse bibliotekene er listet opp under "dependencies" i fila <b>package.json</b>.
- Dersom alt gikk greit kan du nå starte prosjektet og teste vha:

  export FORGE_CLIENT_ID=<<YOUR CLIENT ID FROM FORGE DEVELOPER PORTAL>>
  export FORGE_CLIENT_SECRET=<<YOUR FORGE CLIENT SECRET>>
  npm run dev
