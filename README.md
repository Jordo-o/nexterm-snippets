# Corpobit-snippets voor Nexterm

Deze bron bevat 772 snippets uit https://github.com/corpobit/nexterm-snippets.
De namen hebben een categorieprefix. De bestanden bevatten de oorspronkelijke
opdrachten, de beschrijving en eventuele invulvelden met hun standaardwaarden.

## Toevoegen aan Nexterm

1. Zet `NTINDEX` en de map `snippets/` samen in de hoofdmap
   van een Git-repository of op een HTTPS-webserver die Nexterm kan bereiken.
2. Bij een openbare GitHub-repository met branch `main` is de bron-URL
   `https://raw.githubusercontent.com/<eigenaar>/<repository>/main`.
   Gebruik bij een webserver de HTTPS-URL van de map met `NTINDEX`.
   Open in beide gevallen eerst `<bron-URL>/NTINDEX` om de locatie te controleren.
3. Kies in Nexterm **Settings → Sources → Add**, geef de bron de naam
   **Corpobit Snippets** en plak de bron-URL uit stap 2. Kies de bron vervolgens
   in de lijst bij **Snippets**.

### Publiceren met Git

Maak desgewenst op GitHub een lege openbare repository. Open een terminal in
de uitgepakte map en vervang EIGENAAR en REPOSITORY door je eigen gegevens.

```sh
git init -b main
git add .gitattributes LICENSE README.md NTINDEX snippets
git commit -m "Add converted Nexterm snippets"
git remote add origin https://github.com/EIGENAAR/REPOSITORY.git
git push -u origin main
```

## Invulvelden

In 531 snippets staan velden zoals `{container_name}`. Nexterm vult die velden
niet in en kan een gekozen snippet direct uitvoeren. Kopieer voor deze
snippets de opdracht uit het `.snippet`-bestand, vervang de velden en voer de
ingevulde opdracht uit in de bedoelde shell of client. De beschrijving bij
elke template vermeldt de velden en eventuele standaardwaarden.

Zie LICENSE voor de oorspronkelijke licentie.
