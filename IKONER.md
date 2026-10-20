# App-ikoner (du legger dem inn selv)

Appen bygger uten ikoner (får da Androids standardikon). Når du har dine egne:

Legg dem i `app/src/main/res/` på GitHub (Add file > Upload files):

    app/src/main/res/mipmap-mdpi/ic_launcher.png      48x48
    app/src/main/res/mipmap-hdpi/ic_launcher.png      72x72
    app/src/main/res/mipmap-xhdpi/ic_launcher.png     96x96
    app/src/main/res/mipmap-xxhdpi/ic_launcher.png    144x144
    app/src/main/res/mipmap-xxxhdpi/ic_launcher.png   192x192

Valgfritt, samme størrelser, for runde ikoner: `ic_launcher_round.png`.

Eller et adaptivt ikon: `mipmap-anydpi-v26/ic_launcher.xml` (+ `ic_launcher_round.xml`).

Byggingen oppdager filene av seg selv; ingen annen endring trengs.
Hvis du har mipmap-mappene fra Android Studio / Image Asset Studio, slipp hele
`mipmap-*`-mappene rett inn i `app/src/main/res/`.
