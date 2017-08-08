**Webpack Test
-Installing webpack-dev-server for Hot Reload och Hot Module Replacement
- Hot Reload verkar funka out-of-the-box. Man lägger till ett script i package.json
som anropar webpack-dev-server. När man ändrar i nån modul så byggs den och visas direkt i browsern.
Hela sidan laddas om.
- För att få till den mer avancerade laddningen som bara laddar delar och som behåller status på sidan krävs det lite mer konfiguration.
-Skapar dev-server-js och konfar webpack.config.js och app.js för Hot Module Replacement

Ska testa att göra en vanlig commit i master-branchen och sen lägga master-branch i github som en annan
branch genom att skriva "git push origin annan"